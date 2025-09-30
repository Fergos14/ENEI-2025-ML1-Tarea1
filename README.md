# Assignment: Linear Models, Regularization, and Model Selection on Real Data

**Environment:** Python, `numpy`, `pandas`, `matplotlib`, `scikit-learn`.

**Group Member:** Rodrigo Fernando Caballero Chocano

## Differences observed between OLS, Ridge, and Lasso
 Respecto a métricas:
El modelo cerrado (OLS) mostró mejor rendimiento a comparación de los demás modelos. Ridge mantuvo todas las variables, mientras que Lasso realizó selección de variables.

## Effect of learning rate on gradient descent
Se mostró en todos los casos que a medida que la tasa de aprendizaje aumentaba, el gradiente descendiente convergió con mayor rapidez. Sin embargo, learning ratos muy altos desestabilizaba el modelo.


## How k-fold cross-validation influenced the choice of regularization strength.

El k-fold cross-validation influenció de manera directa la elección de la fuerza del penalizador. De esta manera se optimizó la elección evitando valores demasiado bajos o altos.
