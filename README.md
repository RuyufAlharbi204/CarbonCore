# CarbonCore
### AI-Powered Carbon-Aware Data Center Optimization

## Overview

CarbonCore is an AI-driven decision support system designed to support more sustainable data center operations by optimizing workloads based on carbon intensity, energy consumption, and operational costs.

The project aims to combine predictive machine learning models with intelligent workload scheduling to identify lower-carbon operating windows while respecting workload priorities, deadlines, and service-level agreements (SLAs).

CarbonCore is being developed as a prototype featuring a centralized dashboard for monitoring and decision support, with real-time data integration and deployment planned for future development.


**Current Status:** The dashboard prototype has been developed. Real-world data integration, AI model implementation, and full system deployment remain in progress.

## Dashboard Preview

CarbonCore features an interactive dashboard prototype designed to support carbon-aware data center optimization through predictive insights and intelligent workload scheduling.

- [Live Demo](https://carboncore-six.vercel.app/)
- [Figma UI/UX Prototype](YOUR_FIGMA_LINK)

## Abstract

Data centers are experiencing increasing energy demands, making carbon-aware computing an important challenge for sustainable digital infrastructure. CarbonCore proposes an AI-powered framework that supports workload scheduling decisions by considering both carbon emissions and operational efficiency.

The proposed framework integrates time-series forecasting to predict energy demand and carbon intensity with intelligent scheduling to identify suitable time windows for workload execution. A digital twin environment is planned to simulate scheduling decisions and evaluate their potential impact before implementation.

An interactive dashboard has been developed to present the system concept and support decision-making. Future development will focus on integrating real-world data sources, implementing and evaluating predictive and scheduling models, and validating the framework under realistic operating conditions.

## Key Objectives

- **Carbon-Aware Optimization:** Identify opportunities to shift workloads toward periods with lower carbon intensity.
- **Predictive Analytics:** Explore forecasting models for energy demand and carbon intensity.
- **Intelligent Scheduling:** Develop scheduling strategies that balance carbon emissions, energy costs, workload priorities, deadlines, and SLAs.
- **Simulation & Validation:** Use a digital twin environment to evaluate scheduling strategies before real-world deployment.
- **Explainable Decision Support:** Provide interpretable insights into scheduling recommendations and their expected impact.

## System Architecture

The proposed framework consists of the following components:

- **Data Layer:** Planned integration of energy consumption, carbon intensity, electricity pricing, and relevant environmental data.
- **Forecasting Module:** Time-series forecasting of energy demand and carbon intensity, with Temporal Fusion Transformer (TFT) as a proposed approach.
- **Scheduling Engine:** A proposed reinforcement learning approach using Deep Q-Networks (DQN) to support workload scheduling decisions.
- **Digital Twin:** A planned simulation environment for testing scheduling strategies and evaluating potential outcomes.
- **Explainability Module:** Planned use of SHAP and causal analysis techniques to improve the interpretability of system recommendations.
- **Decision Support Dashboard:** A developed interface prototype for presenting system insights and optimization recommendations.

## Current Progress

- [x] Project concept and system objectives defined.
- [x] Initial system architecture and proposed AI methodology established.
- [x] Dashboard prototype developed.
- [ ] Develop the business model, revenue strategy, and commercialization plan.
- [ ] Assess market opportunities, target customers, and potential industry partnerships.
- [ ] Integrate real-world energy and carbon intensity data.
- [ ] Implement and evaluate forecasting models.
- [ ] Develop and validate the intelligent scheduling engine.
- [ ] Build and test the digital twin simulation environment.
- [ ] Integrate explainability and decision validation capabilities.
- [ ] Deploy and validate the complete system.
## Expected Impact

- **Reduced Carbon Emissions:** Support workload scheduling decisions that account for carbon intensity.
- **Energy Cost Optimization:** Identify opportunities to reduce operational electricity costs.
- **Improved Resource Management:** Balance workload requirements with energy and sustainability objectives.
- **Operational Transparency:** Provide interpretable recommendations through a centralized dashboard.
- **Sustainable Computing:** Contribute to the development of more environmentally responsible data center operations.

## Technology Stack

The proposed and intended technologies include:

- **Programming Language:** Python
- **Machine Learning:** TensorFlow, PyTorch, or Scikit-learn, depending on implementation requirements.
- **Forecasting:** Temporal Fusion Transformer (TFT) and comparative time-series models.
- **Reinforcement Learning:** Deep Q-Networks (DQN).
- **Explainable AI:** SHAP.
- **Interface:** Dashboard prototype.
- **Simulation:** Digital twin environment.

*Technologies listed as proposed are subject to change during implementation.*

## Future Work

Future development will focus on real-world data integration, predictive model implementation, intelligent scheduling, simulation-based evaluation, and deployment. The system will be evaluated against relevant baselines to assess its potential impact on carbon emissions, energy costs, and workload scheduling performance.

## AgentX Competition

CarbonCore was selected as a finalist in **AgentX**, advancing through a competitive selection process involving 500+ teams to develop an AI-driven solution for SASREF.

Although the team was unable to attend the final event due to regional security concerns and unsafe air travel conditions, the project’s selection remains an important milestone in its development.

**[View the AgentX Solution Deck (Arabic)](docs/CarbonCore-AgentX-Solution-Deck-AR.pdf)**

## Project Team

CarbonCore is a collaborative research project developed by a four-member team under the academic guidance of **Dr. Amal Alshahrani**, Department of Computer Science and Artificial Intelligence, College of Computing.

- **Ruyuf Alharbi** — Project Lead & Concept Originator
- **Refan Almfarriji**
- **Hadeel Turki**
- **Khadijah Mirza**


---

*CarbonCore — Toward smarter, more sustainable computing.*
