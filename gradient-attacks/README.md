# Gradient-Based Attack Exploration
Poking at implementing some existing gradient-based attacks. Gradient-based ML attacks are primarily focused on making perturbations to the input of a model in an attempt to maximize a loss function and lead to a misclassification. 

## Attacks
### *Fast Gradient Sign Method (FGSM)*
Paper: https://arxiv.org/pdf/1412.6572.pdf
Main idea: Neural networks are inherently linear and thus are susceptible to linear perturbation. This means that "cheap analytical perturbations of a linear model should also damage neural networks". This paper focuses on producing adversarial examples perturbed by an imperceptible adjustment that results in image misclassification.

## Setup
```
python -m venv .
source bin/activate
pip install -r requirements.txt
```
