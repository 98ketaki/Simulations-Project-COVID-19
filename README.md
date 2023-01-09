# SEIR and SEIRV model for simulation of the COVID-19 data
## Simulations-Project-COVID-19

## Background
The COVID-19 pandemic continues with an unknown course of disease making it difficult for policymakers to
plan for public health. Mathematical models can be used to predict and understand how an infectious
disease spreads and how various factors affect the dynamics. We therefore aim to use mathematical modeling and simulation to study the behavior of COVID-19 delta wave in India.

## Methods
<img width="421" alt="Screenshot 2023-01-09 at 1 35 30 PM" src="https://user-images.githubusercontent.com/52592007/211353391-c4e2fa28-5bc7-403d-be39-2844bbf1eb56.png">

We formed ordinary differential equations for SEIR and SEIRV models and solved them using the Forward
Euler numerical integration methods. The models were then evaluated for various initial parameters and compared for vaccinated versus unvaccinated populations. We validated the model by simulating the COVID data on the Indian population statistics.


## Results
We successfully solved the proposed SEIR and SEIRV models, using
a numerical integration scheme. Furthermore, we used a nonlinear least square
optimizer to fit the model to the Indian Covid Delta wave numbers

The data, final code, graphs and slides are available in the repository
