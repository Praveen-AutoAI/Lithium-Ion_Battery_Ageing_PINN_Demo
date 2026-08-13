# Lithium-Ion_Battery_Ageing_PINN_Demo
Demonstration of Physics Informed Neural Networks to Model Lithium-ion cell degradation. 

# Lithium-Ion Battery Calendar-Ageing Modelling Using PINNs

This repository demonstrates the use of an **Inverse Physics-Informed Neural Network (iPINN)** to identify calendar-ageing parameters of a lithium-ion battery from sparse experimental observations.

## Objectives

- Model lithium-ion battery calendar ageing
- Incorporate a governing degradation equation into neural-network training
- Estimate physically interpretable ageing parameters
- Compare iPINN predictions with experimental capacity data
- Investigate the effect of storage temperature on degradation
- Validate the Physics law considered.
- Predict and forecast the ageing trajectory

## Python Demo

- **Discovery of physical system parameters** from the experimental data using the governing law
- Use the discovered parameters to **predict the system behavior** for new environmental conditions
- Use iPINN to **forecast beyond** the training boundary

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
