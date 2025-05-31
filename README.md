Repositorio del Trabajo de Fin de Grado (TFG): `Machine learning financiero aplicado a la predicción del EUR/USD`

<br>

TFG para el Grado en Economía en la Universidad Internacional de La Rioja (UNIR), Facultad de Economía y Empresa.

Autor: Iñaki Gangutia Arrázola

Director: Javier Martínez Rodríguez

<br>

En este repositorio de GitHub se encuentran todos los archivos necesarios en lo referente al código desarrollado en el TFG. El código posee una complicación en el apartado `1. Data Collection` referente a la obtención de los datos por medio de la API de _Yahoo Finance_, en el caso de este trabajo se ha utilizado JupyterLab, debido a que en otros IDEs devuelve un error. Aún así, al tratarse de una API gratuita su correcto funcionamiento es considerablemente errático, por lo que no funciona en todo momento. 

A modo de solución, se han incluido en este repositorio los archivos con los datos resultantes de las descargas de las APIs, siendo estos `TFG_data_X.csv` y `TFG_data_y.csv`. Estos podrán cargarse directamente al inicio del apartado `2. Data Processing & Cleaning` y seguir con el proceso del programa sin ningún otro problema.

También se han especificado las versiones de Python y de las librerías utilizadas durante la carga inicial de las librerías, con el objetivo de facilitar la reproducción del entorno y ayudar a resolver posibles errores de ejecución del código.
