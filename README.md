# Net Grid Replacement Needs

A quantitative forecasting and investment strategy project analyzing future U.S. electric grid replacement needs over a 20-year horizon.

This project was developed during an AI-focused hackathon challenge and uses research, modeling, and scenario analysis to estimate where new generation capacity may be needed as demand grows and aging power plants retire.

## Project Overview

The U.S. power grid faces two simultaneous pressures: rising electricity demand and the retirement of aging generation assets. This project estimates **net new capacity needs** by combining demand growth assumptions, asset retirement timelines, technology mix analysis, and investment strategy thinking.

The final output connects technical modeling with business decision-making: a forecast of replacement needs, high-potential investment categories, and portfolio strategies for a large institutional investor.

## Problem Statement

Future energy demand can be estimated, but the more strategic question is:

> How much new generation capacity must be built to meet future demand while replacing retiring assets and maintaining grid reliability?

This model considers:

- Regional energy demand growth
- Retirement of aging power plants
- Technology-specific construction timelines
- Reliability reserve needs and downtime assumptions
- Capital deployment opportunities for infrastructure investors

## Methodology

### 1. Demand and Replacement Forecasting

The model evaluates net new capacity needs by combining:

- Historical and projected electricity demand
- Population and industrial demand trends
- Climate adaptation and electrification pressures
- Existing power plant age and expected retirement windows
- Replacement timelines across multiple generation technologies

### 2. Technology Mix Analysis

The project compares several energy categories, including:

- Utility-scale solar and storage
- Onshore and offshore wind
- Natural gas backup generation
- Next-generation nuclear and small modular reactors
- Grid storage and distributed resilience technologies

### 3. Scenario and Risk Analysis

The strategy accounts for risk factors such as:

- Policy and regulatory changes
- Material supply constraints
- Technology obsolescence
- Construction delays
- Regional adoption differences
- Reliability and intermittency challenges

## Key Deliverables

### Quantitative Forecasting Model

Forecasts net new capacity needs across technology, region, and timeline:

- **Years 1–5:** Immediate build-out to replace coal retirements and stabilize grid reliability
- **Years 6–10:** Scaling renewables and storage while maintaining backup capacity
- **Years 11–20:** Long-term growth from nuclear, advanced storage, and next-generation solar/wind

### Asset Retirement Visualization

Interactive visualization showing geographic distribution and retirement patterns of existing power plants.

🔗 Power Plant Retirements Visualization: https://chp36.github.io/power_plant_retirements/

### Investment Strategy

The project identifies high-potential investment categories:

- Utility-scale solar + storage
- Onshore and offshore wind
- Next-generation nuclear and SMRs
- Distributed resilience and behind-the-meter storage

Each category includes capital deployment timing, ROI assumptions, risk factors, and strategic considerations.

### Sample Portfolio Strategies

#### Portfolio A: Transition Backbone Strategy

- **Allocation:** 55%
- **Focus:** Utility-scale generation and storage projects
- **Expected ROI:** 9.5–12.5%
- **Strengths:** Stable returns, core infrastructure focus, scalable deployment
- **Risks:** Technology obsolescence and material supply constraints

#### Portfolio B: Distributed Resilience Strategy

- **Allocation:** 45%
- **Focus:** Distributed resources and customer-level storage
- **Expected ROI:** 11–16%
- **Strengths:** Faster growth, consumer adoption exposure, higher-margin technology providers
- **Risks:** Local regulatory hurdles and uneven regional adoption

### Performance Dashboard

A dashboard prototype was built for real-time portfolio tracking.

Monitored metrics include:

- ROI
- Grid reliability
- Capacity growth
- Retirement coverage
- Portfolio performance

🔗 Grid Performance Lens Dashboard: https://grid-performance-lens.lovable.app/

## Project Structure

```text
├── models/              # Forecasting assumptions and modeling logic
├── visualizations/      # Charts, plots, and interactive visual assets
├── dashboard/           # Dashboard prototype files
├── docs/                # Research notes, references, and hackathon deliverables
└── README.md            # Project documentation
```

## What This Project Demonstrates

This project highlights my ability to combine data analysis, AI-assisted research, forecasting, and strategic business thinking.

It demonstrates experience with:

- Quantitative forecasting
- Scenario analysis
- Infrastructure and energy market research
- Data visualization and dashboard design
- AI-assisted research workflows
- Translating technical analysis into investment recommendations
- Cross-functional collaboration across engineering, analytics, and business strategy

## Role and Contributions

As part of the hackathon team, I contributed to the technical modeling, research synthesis, AI-assisted analysis, and strategic framing of the final recommendation.

The project earned recognition for **AI architecture** and **technical leadership**, reflecting the team's ability to combine AI tools, data modeling, and business insight into a clear investment strategy.

## How to Use

1. Explore the retirement visualization:
   https://chp36.github.io/power_plant_retirements/

2. Review the dashboard prototype:
   https://grid-performance-lens.lovable.app/

3. Adapt model assumptions inside `/models/` for custom scenarios.

## Future Improvements

- Add documented data sources and model assumptions
- Expand regional forecasting granularity
- Add sensitivity analysis for demand growth, retirement timelines, and policy changes
- Build reproducible notebooks for the modeling workflow
- Add automated dashboard refreshes from updated source data
- Compare investment outcomes under multiple market scenarios

## About

Developed during an AI-focused hackathon sprint by a cross-functional team of engineering, analytics, and business students.

This project supports my broader focus on **data engineering, automation, forecasting, infrastructure analytics, and technical decision-support systems**.