# Logistic Regression

## Sigmoid (Logistic) Function
Sigmoid: 

$\sigma(z) = \frac{1}{1+e^{-z}}$


For a given feature vector $x$, we compute: 
$z = w^x + b$, 
$\tilde{y} = \sigma(z)$

## Lost function
Average loss: 

$J(w, b) = -\frac{1}{N} \sum^N_{i=1} [y^{(i)}ln(\tilde{y}^{(i)}) + (1-y^{(i)})ln(1-\tilde{y}^{(i)})]$ 

where

$\tilde{y}^{(i)} = \sigma(w^Tx^{(i)} + b)$