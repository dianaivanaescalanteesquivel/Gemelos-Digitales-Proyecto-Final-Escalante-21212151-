[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=dianaivanaescalanteesquivel/Gemelos-Digitales-Proyecto-Final-Escalante-21212151-)

# Gemelos Digitales: Proyecto Final [Escalante 21212151]
Proyecto Final: Proceso de inflamación (3 poblaciones)

## Autor
Diana Ivana Escalante Esquivel,
Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Resumen de la práctica
Este proyecto tuvo como finalidad integrar las competencias específicas relacionadas con el modelado, análisis y control de sistemas biológicos, con el propósito de ilustrar y predecir su dinámica a lo largo del tiempo. Para ello, se aplicaron los conocimientos adquiridos en la asignatura de Gemelos Digitales al estudio de un sistema fisiológico compuesto por tres poblaciones celulares. En este caso, se seleccionó el proceso de inflamación, en el que interactuaron las células dañadas, los macrófagos activados y las citoquinas inflamatorias. Se utilizó el software Eureqa para obtener un sistema de tres ecuaciones diferenciales que describieran la dinámica más adecuada con base en los datos experimentales. Posteriormente, se implementó el método de Heun como técnica para desarrollar un algoritmo de regresión no lineal, orientado a resolver ecuaciones diferenciales ordinarias de primer orden a partir de los datos, los cuales fueron previamente suavizados y normalizados. Se calcularon los parámetros estadísticos fundamentales para estimar las tasas de crecimiento del sistema, incluyendo el tamaño de muestra, los grados de libertad, el nivel de significancia, el valor t de Student, el coeficiente de determinación ajustado y el criterio de información de Akaike corregido. Además, se determinó la matriz Jacobiana del sistema, los puntos de equilibrio y los valores propios asociados, lo que permitió analizar la estabilidad del sistema en torno a dichos puntos. Finalmente, se realizó una simulación predictiva del comportamiento del modelo tanto a corto plazo, al tiempo dos veces mayor que el inicial, como a largo plazo, al tiempo mil, con el fin de evaluar la evolución del sistema.

## Objetivos específicos
1. Seleccionar un conjunto de datos experimentales, suavizarlos y normalizarlos para facilitar su análisis y representación.
2. Utilizar el software Eureqa para obtener las ecuaciones que mejor se ajusten a los datos experimentales.
3. Desarrollar algoritmos basados en el método de Heun para resolver ecuaciones diferenciales ordinarias.
4. Graficar las curvas ajustadas con el fin de evaluar la precisión del modelo frente a los datos experimentales.
5. Estimar las tasas de crecimiento asociadas al modelo y calcular sus parámetros estadísticos clave.
6. Determinar la matriz Jacobiana, los puntos de equilibrio y los valores propios para analizar la estabilidad del sistema.
7. Realizar predicciones a 2t y a t=1000 para evaluar el comportamiento del sistema a corto y largo plazo.

## Docente
Dr. Paul Antonio Valle Trujillo,
Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf
[2] X. Filella, R. Molina, y A. M. Ballesta, "Estructura y función de las citocinas," Medicina Integral, vol. 39, no. 2, pp. 63-71, ene. 2002. [En línea]. Disponible en: https://www.elsevier.es/es-revista-medicina-integral-63-articulo-estructura-funcion-las-citocinas-13026682
