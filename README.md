# TRABAJO FINAL DEL MÁSTER EN CIENCIA DE DATOS

## Predicción de potenciales compradores de un ecommerce

## Autor

IVAN DARIO OVALLE BENAVIDES

## Informacion adicional

* Universidad Oberta de Catalunya [Universitat Oberta of Catalunya.](http://www.uoc.edu/portal/ca/index.html)
* Master en Ciencia de Datos
* Tutor: Santiago Rojo Muñoz

## Resumen

El objetivo principal del proyecto es generar los mejores modelos de clasificación de leads que permitan predecir los posibles compradores de un Ecommerce. Para ello, primero se realizó la unión de 4 bases de datos resumidas ahora solo en 1. Se realizó también el análisis exploratorio de los datos, el análisis descriptivo y los respectivos trabajos de limpieza. Posteriormente, se realizaron estudios estadísticos para determinar la colinealidad de las variables numéricas y luego se redujo la dimensionalidad de estas mediante análisis de componentes principales.  También se revisó la relación de las variables categóricas con el indicativo de cliente. Se ejecutaron varias técnicas de balanceo de datos para que se puedan generar los modelos de clasificación pertinentes con alto grado de precisión y confiabilidad. La técnica ganadora fue Smote. Continuando con el proceso, se generaron varios modelos de aprendizaje supervisado con Smote como técnica de balanceo, para clasificar a los potenciales compradores. De acuerdo con el F2-Score, la exactitud y la validación cruzada K-fold, el modelo que mejor clasificó fue Gradient Boosting, seguido por el Árbol de Decisión. Por debajo de estos quedaron Ada Boosting, Regresión Logística y Random Forest. Luego se decidió generar otro dataset con los datos de los usuarios que no compraron o que compraron después de la fecha de registro. Esto con el fin de que el comercio pueda clasificar a los potenciales compradores que no compran de una, pero que están aún calientes, para poder enviarles campañas publicitarias. Se realizaron los modelos con los dos ganadores previos y con otros tres modelos: Perceptrón, Análisis Discriminante lineal y GaussianNB. Para este dataset, el desempeñó del Árbol de Decisión fue mejor que Gradient Boosting. Le siguen los modelos de Perceptrón y Análisis discriminante lineal que tuvieron buenos desempeños, mientras que GaussianNB clasificó de forma mediocre.

## Código
Iniciar revisando el archivo llamado "1.todoslosclientes.ipynb" de la carpeta: https://github.com/ivanova93/ecommerce-tfm/tree/main/Codigo

## Licencia

El contenido de este proyecto esta licencia de Reconocimiento- No Comercial- Sin Obra Derivada 3.0 España de Creative Commons (https://creativecommons.org/licenses/by-nc-nd/3.0/es/)
El código fuente usado que soporta el informe presentado esta licenciado bajo la [MIT license](http://opensource.org/licenses/mit-license.php).
