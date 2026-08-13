# Lithium-Ion_Battery_Ageing_PINN_Demo
Demonstration of Physics Informed Neural Networks to Model Lithium-ion cell degradation. 

## **Before jumping directly into these demo, just check out my blog article on PINN loss formulation step-by-step.**
[Lithium-Ion Cell Ageing Modelling Using Inverse PINN](https://praveen-autoai.github.io/machine%20learning/engineering/2026/08/04/Lithium-Ion-Cell-Ageing-Modelling-Using-Inverse-PINN.html)

# Lithium-Ion Battery Calendar-Ageing Modelling Using PINNs

This repository demonstrates the use of an **Inverse Physics-Informed Neural Network (iPINN)** to identify calendar-ageing parameters of a lithium-ion battery from sparse experimental observations.

## Objectives of the Demo:
- **Formulate** a data-driven framework embedding governing calendar ageing kinetics (growth dynamics and Arrhenius temperature dependencies) into neural network loss functions.
- **Discover** unknown physical degradation parameters using inverse neural network optimization (iPINN) on experimental capacity fade data.
- **Quantify** temperature-driven calendar ageing mechanisms across varying thermal storage environments.
- **Validate** the physical consistency and accuracy of the embedded degradation law against experimental benchmarks.
- **Forecast** long-term battery capacity loss and State of Health (SoH) trajectories from partial temporal data.

## 🚀 Project Episodes

* **Episode 1: THE DISCOVERY - Physical Parameter Discovery & Validation**  
  Implement an Inverse Physics-Informed Neural Network (iPINN) framework to identify unknown parameters directly from experimental data and validate the physical inference.

* **Episode 2: THE PREDICTION - Generalization to Unseen Conditions**  
  Utilize the discovered parameters to accurately predict physics-consistent system ageing behavior under new environmental.

* **Episode 3: THE FORECAST - Long-Term Forecasting from Partial Data**  
  Train on partial calendar ageing datasets to extract degradation parameters, extrapolate future degradation trends beyond training boundaries, and evaluate cross-condition performance.


## Dataset

- I have used lithium-ion calendar ageing data from 2 publications in this demo.
- Check the python project files to reach data source.
- I was able to use a small set of ageing data since PINN is not a data hungry approach, the physics used is sufficient enough to satisfy hunger during the training process :)

## Repository Structure

```text
Lithium-Ion_Battery_Ageing_PINN_Demo/
├── README.md
├── LICENSE
├── requirements.txt
├── Lithium-ion_CalendarAgeing_Episode#1_InversePINN-Discovery-Demo.ipynb
├── Lithium-ion_CalendarAgeing_Episode#2_InversePINN-Prediction-Demo.ipynb
├── Lithium-ion_CalendarAgeing_Episode#3_InversePINN-Forecasting-Demo.ipynb
└── src/
``
