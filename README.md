# CarbonCore

### AI-Powered Carbon-Aware Data Center Optimization

## Overview

CarbonCore is an AI-driven decision support system designed to support more sustainable data center operations by optimizing workloads based on carbon intensity, energy consumption, and operational costs.

The project aims to combine predictive machine learning with intelligent workload scheduling to identify lower-carbon operating windows while respecting workload priorities, deadlines, and service-level agreements (SLAs).

A dashboard prototype has been developed to demonstrate the proposed system. Real-world data integration, AI model implementation, and full system deployment are planned as future development stages.

**Current Status:** Dashboard prototype developed. Predictive models, intelligent scheduling, and real-world data integration remain in development.

## Project Demo

Explore the CarbonCore prototype and interface:

- **[Live Demo](https://carboncore-six.vercel.app/)** — Explore the interactive web prototype.
- **[Figma UI/UX Prototype](YOUR_FIGMA_LINK)** — View the dashboard design and interface.

## Abstract

Data centers face growing energy demands, making carbon-aware computing an important challenge for sustainable digital infrastructure. CarbonCore proposes an AI-powered framework to support workload scheduling decisions by considering carbon emissions and operational efficiency.

The proposed framework combines time-series forecasting of energy demand and carbon intensity with intelligent scheduling to identify suitable workload execution windows. A digital twin environment is also planned to simulate scheduling decisions and evaluate their potential impact before real-world implementation.

The dashboard prototype presents the system concept and its intended decision-support capabilities. Future development will focus on integrating real-world data, implementing and evaluating predictive and scheduling models, and validating the framework under realistic operating conditions.

## Key Objectives

- **Carbon-Aware Optimization:** Identify opportunities to shift workloads toward periods with lower carbon intensity.
- **Predictive Analytics:** Explore forecasting models for energy demand and carbon intensity.
- **Intelligent Scheduling:** Develop scheduling strategies that balance emissions, electricity costs, workload priorities, deadlines, and SLAs.
- **Simulation and Validation:** Evaluate scheduling strategies in a digital twin environment before real-world deployment.
- **Explainable Decision Support:** Provide interpretable insights into scheduling recommendations and their expected impact.

## Proposed System Architecture

The proposed framework consists of six main components:

1. **Data Layer:** Planned integration of energy consumption, carbon intensity, electricity pricing, and relevant environmental data.
2. **Forecasting Module:** Time-series forecasting of energy demand and carbon intensity, with Temporal Fusion Transformer (TFT) as a proposed approach.
3. **Intelligent Scheduling Engine:** A proposed reinforcement learning approach using Deep Q-Networks (DQN) to support workload scheduling decisions.
4. **Digital Twin:** A planned simulation environment for testing scheduling strategies and evaluating potential outcomes.
5. **Explainability Module:** Planned use of SHAP and causal analysis techniques to improve the interpretability of system recommendations.
6. **Decision Support Dashboard:** A developed interface prototype for presenting system insights and optimization recommendations.

## Current Progress

### Completed

- [x] Defined the project concept and system objectives.
- [x] Established the initial system architecture and proposed AI methodology.
- [x] Developed the dashboard prototype.
- [x] Advanced to the AgentX finalist stage.

### Planned Development

- [ ] Develop the business model, revenue strategy, and commercialization plan.
- [ ] Assess market opportunities, target customers, and potential industry partnerships.
- [ ] Integrate real-world energy and carbon intensity data.
- [ ] Implement and evaluate forecasting models.
- [ ] Develop and validate the intelligent scheduling engine.
- [ ] Build and test the digital twin simulation environment.
- [ ] Integrate explainability and decision-validation capabilities.
- [ ] Evaluate the system against relevant baselines.
- [ ] Deploy and validate the complete system.

## Expected Impact

- **Reduced Carbon Emissions:** Support workload scheduling decisions that account for carbon intensity.
- **Energy Cost Optimization:** Identify opportunities to reduce electricity costs.
- **Improved Resource Management:** Balance workload requirements with energy and sustainability objectives.
- **Operational Transparency:** Present interpretable recommendations through a centralized dashboard.
- **Sustainable Computing:** Contribute to more environmentally responsible data center operations.

## Proposed Technology Stack

The following technologies are being considered for implementation:

| Component              | Proposed Technology                                                  |
| ---------------------- | -------------------------------------------------------------------- |
| Programming Language   | Python                                                               |
| Machine Learning       | TensorFlow, PyTorch, Scikit-learn                                    |
| Forecasting            | Temporal Fusion Transformer (TFT) and comparative time-series models |
| Reinforcement Learning | Deep Q-Networks (DQN)                                                |
| Explainable AI         | SHAP and causal analysis                                             |
| Dashboard              | Interactive web prototype                                            |
| Simulation             | Digital twin environment                                             |

*The proposed technology stack may change based on implementation requirements and experimental results.*

## Future Work

Future development will focus on real-world data integration, predictive model implementation, intelligent workload scheduling, and simulation-based evaluation.

The system will be evaluated against relevant baselines to assess its potential impact on carbon emissions, electricity costs, and workload scheduling performance. Further work will address system validation and deployment under realistic operating conditions.

## AgentX Competition

CarbonCore was selected as a finalist in **AgentX**, progressing through a competitive selection process involving more than 500 teams to develop an AI-driven solution for SASREF.

The team was unable to attend the final event due to regional security concerns and unsafe air travel conditions. Nevertheless, reaching the finalist stage marked an important milestone for the project.

**[View the AgentX Solution Deck (Arabic)](docs/CarbonCore-AgentX-Solution-Deck-AR.pdf)**

### AgentX Competition Team

- **Ruyuf Alharbi** 
- **Refan Almfarriji**
- **Hadeel Turki**

## Research Project Team

CarbonCore is a collaborative research project originated and led by Ruyuf Alharbi, with academic guidance from Dr. Amal Alshahrani, Department of Computer Science and Artificial Intelligence, College of Computing.

Ruyuf Alharbi 

Refan Almfarriji 

Hadeel Turki 

Khadijah Mirza 

- **Hadeel Turki**
- **Khadijah Mirza**
