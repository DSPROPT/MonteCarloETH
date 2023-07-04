Simulación de Monte Carlo para el precio de Ethereum
Este repositorio contiene un Jupyter notebook que utiliza la simulación de Monte Carlo para prever los posibles precios futuros de Ethereum.

Descripción Teórica
La simulación de Monte Carlo es una técnica computacional que permite modelar situaciones inciertas y comprender la gama de posibles resultados, así como la probabilidad de diferentes resultados. En este proyecto, usamos la simulación de Monte Carlo para modelar los posibles precios futuros de Ethereum.

En términos generales, el proceso consiste en los siguientes pasos:

Recopilamos datos históricos de los precios de Ethereum.
Calculamos los rendimientos logarítmicos diarios, que son una medida de cómo cambia el precio cada día.
Generamos miles de "trayectorias" aleatorias del precio futuro de Ethereum, utilizando los rendimientos logarítmicos diarios para guiar la aleatoriedad.
Visualizamos estas trayectorias para obtener una idea de la gama de posibles precios futuros.
Cómo ejecutar el notebook
Para ejecutar este notebook, necesitarás Jupyter Notebook o Jupyter Lab, así como Python 3 y las siguientes bibliotecas de Python: yfinance, numpy, matplotlib, scipy.

Puedes instalar Jupyter y estas bibliotecas con pip:


pip install notebook yfinance numpy matplotlib scipy

Una vez que tengas Jupyter y las bibliotecas necesarias instaladas, puedes clonar este repositorio y abrir el notebook MonteCarloETH.ipynb en Jupyter.

Guía Paso a Paso del Código

Importación de bibliotecas: Importamos las bibliotecas necesarias de Python.

Descarga de datos: Utilizamos yfinance para descargar los datos históricos de los precios de Ethereum de los últimos 5 años.

Cálculo de rendimientos: Calculamos los rendimientos logarítmicos diarios a partir de los datos de precios.

Simulación de Monte Carlo: Utilizamos los rendimientos logarítmicos diarios para generar miles de trayectorias aleatorias del precio de Ethereum para el próximo año.

Visualización: Creamos gráficos para visualizar las trayectorias simuladas de los precios de Ethereum, así como la distribución final de los posibles precios.

Advertencia
Este notebook está destinado a ser una demostración de cómo utilizar la simulación de Monte Carlo en finanzas y no debe ser utilizado para tomar decisiones de inversión reales. Siempre debes realizar tu propia investigación y/o buscar el consejo de un asesor financiero profesional antes de invertir en criptomonedas u otros instrumentos financieros.
