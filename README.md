# Lithium-Ion_Battery_Ageing_PINN_Demo
Demonstration of Physics Informed Neural Networks to Model Lithium-ion cell degradation. 

# Lithium-Ion Battery Calendar-Ageing Modelling Using iPINNs

This repository demonstrates the use of an **Inverse Physics-Informed Neural Network (iPINN)** to identify calendar-ageing parameters of a lithium-ion battery from sparse experimental observations.

## Objectives

- Model lithium-ion battery calendar ageing
- Incorporate a governing degradation equation into neural-network training
- Estimate physically interpretable ageing parameters
- Compare iPINN predictions with experimental capacity data
- Investigate the effect of storage temperature on degradation

## Physics Model

The normalized capacity loss is represented using the semi-empirical model

$$
\operatorname{Loss}(t)=a\sqrt{t}+bt,
$$

where:

- $a$ represents the diffusion-limited ageing contribution
- $b$ represents the effective long-term linear-ageing contribution
- $t$ represents storage time

The normalized remaining capacity is

$$
Q(t)=1-\operatorname{Loss}(t).
$$

## Repository Structure

```text
Lithium-Ion_Battery_Ageing_PINN_Demo/
├── README.md
├── LICENSE
├── requirements.txt
├── data/
├── images/
├── notebooks/
└── src/
``
