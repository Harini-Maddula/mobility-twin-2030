Mobility Twin 2030

AI-Powered Predictive Mobility Platform for Future Cities

AVIRBHAV 2026 — Round 2 Hackathon
Theme: Transportation & Mobility

"Live Prototype" (https://mobility-twin-2030.lovable.app)

---

Overview

Mobility Twin 2030 is a web-based traffic simulation and decision-support prototype designed to help cities explore possible traffic scenarios before implementing real-world traffic-management changes.

The platform creates a simplified digital representation of a traffic network and allows users to explore "what-if" scenarios such as additional vehicle volume, road closures, accidents, and major events.

The prototype presents simulated traffic impacts, identifies potential congestion hotspots, compares network conditions before and after a scenario, and provides suggested interventions.

«Important: The current hackathon prototype operates using simulated/demo traffic data. It is intended to demonstrate the concept and workflow rather than provide live traffic forecasting or real-world traffic predictions.»

---

Problem Statement

Urban traffic conditions can change rapidly because of peak-hour demand, road closures, accidents, major events, and sudden increases in vehicle volume.

A change on one road can affect connected roads and junctions across the network. This can create difficulties for daily commuters, emergency services, delivery services, local businesses, and transportation planners.

Traffic planners need better ways to explore possible network-level effects before making traffic-management decisions.

The problem in one sentence

Traffic changes faster than plans do.

---

Proposed Solution

Mobility Twin 2030 provides a digital representation of a traffic network where users can explore possible scenarios and observe their simulated impact.

The platform follows four main stages:

1. Problem — Identify changing traffic conditions.
2. Simulation — Run a selected what-if scenario.
3. Prediction — Estimate the simulated network impact.
4. Recommendation — Present a suggested intervention.

This approach demonstrates how digital simulation can support transportation planning and scenario analysis.

---

Key Features

1. Traffic Dashboard

The dashboard provides an overview of the simulated traffic network, including:

- Current traffic volume
- Average network speed
- Congestion level
- Busiest junction
- Network map
- Individual road information
- Road traffic status

---

2. What-If Traffic Simulator

Users can configure a traffic scenario and observe its simulated impact.

Example scenario inputs include:

- Scenario type
- Additional vehicle volume
- Affected road
- Time of the scenario

The current prototype demonstrates an additional-traffic scenario and can be extended to additional scenario types.

---

3. Simulation Results

After running a scenario, the platform presents:

- Traffic before and after the scenario
- Average-speed changes
- Congestion changes
- Predicted hotspot
- Affected roads
- Network impact summary
- Traffic impact visualization

---

4. Before vs After Analysis

The platform compares road conditions before and after the selected scenario.

This makes it easier to understand how additional traffic can change conditions across the simulated network.

---

5. Recommendation Engine

The prototype provides a suggested intervention based on the simulated scenario.

Example recommendations can include:

- Redirecting traffic
- Using an alternate route
- Considering signal-timing changes

The current recommendation mechanism is part of the prototype simulation workflow and should not be interpreted as a validated real-world traffic-control system.

---

6. Insights Dashboard

The Insights section summarizes the latest simulation run and presents:

- Traffic patterns
- Congestion hotspots
- Scenario analysis
- Recommended actions

---

7. Technology Overview

The prototype currently uses technologies and approaches shown in the project's Technology section, including:

- React
- TypeScript
- Tailwind CSS
- Vite / TanStack Start environment
- Browser-based deterministic rule-based simulation
- Synthetic/demo traffic data
- Interactive SVG-based road-network visualization
- Before/after traffic charts

---

System Workflow

Traffic Scenario
       ↓
Scenario Configuration
       ↓
Simulation Engine
       ↓
Traffic Impact Calculation
       ↓
Network Impact Analysis
       ↓
Hotspot Identification
       ↓
Before vs After Comparison
       ↓
Recommended Intervention

---

Example Demonstration

A sample demonstration scenario is:

Scenario: Additional Traffic
Additional Vehicles: 2,000
Affected Road: Road B
Time: 5:30 PM

The prototype then calculates a simulated network response and presents:

- Updated traffic volume
- Average-speed change
- Congestion change
- Potential congestion hotspot
- Affected roads
- Recommended action
- Traffic impact visualization

All values shown in the current demonstration are simulated prototype values.

---

Digital Twin Concept

The project uses a simplified digital representation of a traffic network.

The network contains roads and junctions that can be represented visually and used as the basis for scenario simulation.

The concept is intended to demonstrate how a transportation digital twin could allow planners to test possible changes virtually before considering implementation in the physical traffic network.

---

Data Transparency

Current Prototype

The current prototype uses:

Synthetic / simulated / demo traffic data

The simulation is designed to demonstrate the product concept and interaction flow.

Not currently claimed

The prototype does not claim:

- Live traffic feeds
- Government traffic data
- Real-time city deployment
- Validated real-world traffic forecasting accuracy
- Government partnerships
- Production traffic-control integration

These would require additional datasets, validation, infrastructure, and integration work.

---

Current Implementation vs Future Scope

Area| Current Prototype| Future Development
Traffic data| Synthetic/demo data| Historical + real-time mobility data
Simulation| Deterministic rule-based simulation| Advanced simulation models
Prediction| Prototype scenario estimation| Trained forecasting models
Backend| Browser-based prototype workflow| Python backend/API
Visualization| Interactive network visualization| Larger-scale city digital twin
Recommendations| Rule-based suggestions| ML/optimization-assisted recommendations
Data feeds| Simulated| Real-time mobility feeds
Validation| Prototype demonstration| Historical and real-world validation

---

Future Scope

The platform can be extended in several directions.

Real Traffic Data Integration

Integrate historical traffic datasets and, where available, real-time mobility feeds.

Advanced Machine Learning

Develop forecasting models using historical traffic patterns, weather, events, road conditions, and other relevant features.

Potential future technologies include:

- Python
- Pandas
- NumPy
- Scikit-learn
- FastAPI or Flask

Larger Digital Twin

Expand the prototype from a small network to larger city-level transportation networks.

Advanced Scenario Simulation

Future versions could support scenarios such as:

- Road closures
- Accidents
- Public events
- Weather-related disruptions
- Emergency vehicle movement
- Public transportation changes
- Construction activity

Optimization

Future versions could evaluate multiple interventions and compare their simulated outcomes.

---

Potential Users

The concept is intended to support:

- Traffic planners
- Transportation authorities
- City planners
- Mobility operators
- Emergency-response planners
- Infrastructure planners

Indirectly, better planning could benefit:

- Daily commuters
- Public transport users
- Delivery services
- Local businesses
- Emergency services
- General road users

---

Potential Impact

Mobility Twin 2030 demonstrates a planning-first approach to transportation management.

Instead of responding only after congestion occurs, planners could use simulation to explore possible consequences of proposed changes before implementation.

The long-term objective is to make traffic planning more:

- Scenario-driven
- Data-informed
- Visual
- Predictive
- Adaptable

The current prototype demonstrates the concept rather than claiming measurable real-world impact.

---

Project Architecture

┌──────────────────────────────┐
│        User Interface        │
│  Dashboard / Simulation UI   │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│      Scenario Controls       │
│ Vehicles / Road / Time       │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│      Simulation Engine       │
│ Deterministic Rule-Based     │
│ Traffic Simulation           │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│      Impact Analysis         │
│ Traffic / Speed / Congestion │
│ Hotspots / Affected Roads    │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│ Recommendation & Insights    │
└──────────────────────────────┘

---

Project Screenshots

The repository contains screenshots of the prototype demonstrating:

- Homepage
- Problem and workflow
- Traffic dashboard
- Network map
- What-if simulator
- Simulation results
- Before/after comparison
- Traffic impact chart
- Recommendation output
- Insights dashboard
- Technology section
- About/project section

Screenshots are available in the "screenshots/" directory.

---

Repository Structure

mobility-twin-2030/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── Project-Documentation.pdf
│   └── Round-1-Presentation.pdf
│
├── screenshots/
│   ├── 01-homepage.png
│   ├── 02-problem-and-workflow.png
│   ├── 03-dashboard.png
│   ├── 04-network-map.png
│   ├── 05-simulation-input.png
│   ├── 06-simulation-results.png
│   ├── 07-before-after.png
│   ├── 08-traffic-impact-chart.png
│   ├── 09-ai-recommendation.png
│   ├── 10-insights.png
│   ├── 11-technology.png
│   └── 12-about-project.png
│
└── [actual project source files]

«The source-code structure should reflect the actual project generated and maintained for the prototype. Do not create empty folders only for appearance.»

---

Deployment

The current prototype is deployed as a web application.

Live Prototype

https://mobility-twin-2030.lovable.app

The deployed prototype is currently presented in Demo Mode and uses simulated traffic data.

---

Hackathon

Event: AVIRBHAV 2026
Round: Round 2 — Infinity War
Theme: Transportation & Mobility
Project: Mobility Twin 2030

---

Project Status

Current Status

Functional Hackathon MVP / Prototype

The current version demonstrates the core workflow:

Scenario
   ↓
Simulation
   ↓
Impact Analysis
   ↓
Before/After Comparison
   ↓
Recommendation
   ↓
Insights

---

Limitations

The current prototype has several limitations:

1. Traffic data is simulated rather than sourced from a live mobility feed.
2. The simulation is a deterministic prototype model.
3. Results have not been validated against real-world traffic measurements.
4. The prototype represents a simplified traffic network.
5. Recommendations are intended for demonstration and are not operational traffic-control instructions.
6. Real-world deployment would require additional data, validation, infrastructure, security, and domain expertise.

---

Why Mobility Twin 2030?

Traditional traffic planning can involve evaluating changes after they are proposed or after problems occur.

Mobility Twin 2030 demonstrates a different workflow:

Model → Simulate → Understand → Plan

The goal is to help planners explore possible traffic outcomes before making changes to the real network.

---

Team

Project: Mobility Twin 2030
Hackathon: AVIRBHAV 2026
Domain: Transportation & Mobility

Add the final team-member names here before submission.

---

License

This project is developed as a hackathon prototype for AVIRBHAV 2026.

See the "LICENSE" file for project licensing information.

---

Project Links

Live Prototype

https://mobility-twin-2030.lovable.app

GitHub Repository

Add the final GitHub repository URL here.

Project Documentation

See:

"docs/Project-Documentation.pdf"

Round 1 Presentation

See:

"docs/Round-1-Presentation.pdf"

---

Disclaimer

Mobility Twin 2030 is a hackathon prototype created to demonstrate a predictive mobility simulation concept.

The traffic values, network conditions, predictions, and recommendations shown in the current prototype are simulated/demo outputs and should not be treated as real-world traffic forecasts or operational traffic-management instructions.
