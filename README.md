# Simulación de Monte Carlo para el precio de Ethereum

Este repositorio contiene un Jupyter notebook que utiliza la simulación de Monte Carlo para prever los posibles precios futuros de Ethereum.

## 📖 Descripción Teórica

La simulación de Monte Carlo es una técnica computacional que permite modelar situaciones inciertas y comprender la gama de posibles resultados, así como la probabilidad de diferentes resultados. En este proyecto, usamos la simulación de Monte Carlo para modelar los posibles precios futuros de Ethereum.

En términos generales, el proceso consiste en los siguientes pasos:

1. **Recopilación de datos históricos:** Recopilamos datos históricos de los precios de Ethereum.
2. **Cálculo de rendimientos:** Calculamos los rendimientos logarítmicos diarios, que son una medida de cómo cambia el precio cada día.
3. **Generación de trayectorias aleatorias:** Generamos miles de "trayectorias" aleatorias del precio futuro de Ethereum, utilizando los rendimientos logarítmicos diarios para guiar la aleatoriedad.
4. **Visualización:** Visualizamos estas trayectorias para obtener una idea de la gama de posibles precios futuros.

## 💻 Cómo ejecutar el notebook

Para ejecutar este notebook, necesitarás Jupyter Notebook o Jupyter Lab, así como Python 3 y las siguientes bibliotecas de Python: `yfinance`, `numpy`, `matplotlib`, `scipy`.

Puedes instalar Jupyter y estas bibliotecas con pip:

```bash
pip install notebook yfinance numpy matplotlib scipy

