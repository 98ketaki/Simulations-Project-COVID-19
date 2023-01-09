# SEIR and SEIRV model for simulation of the COVID-19 data
## Simulations-Project-COVID-19

## Background
The COVID-19 pandemic continues with an unknown course of disease making it difficult for policymakers to
plan for public health. Mathematical models can be used to predict and understand how an infectious
disease spreads and how various factors affect the dynamics. We therefore aim to use mathematical modeling and simulation to study the behavior of COVID-19 delta wave in India.

## Methods

<img width="842" alt="SEIR" src="https://user-images.githubusercontent.com/52592007/211352945-cd3026f3-d9e1-4fb5-ada4-6b52a67678e7.png">
<img width="1151" alt="SEIRV (1)" src="https://user-images.githubusercontent.com/52592007/211352950-e2bd5cb4-8e07-470e-9667-d8015c228277.png">

We formed ordinary differential equations for SEIR and SEIRV models and solved them using the Forward
Euler numerical integration methods. The models were then evaluated for various initial parameters and compared for vaccinated versus unvaccinated populations. We validated the model by simulating the COVID data on the Indian population statistics.


## Results
We successfully solved the proposed SEIR and SEIRV models, using
a numerical integration scheme. Furthermore, we used a nonlinear least square
optimizer to fit the model to the Indian Covid Delta wave numbers
