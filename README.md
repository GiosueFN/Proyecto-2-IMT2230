Proyecto 2: PageRank sobre la red de tráfico aéreo de la FAA

Integrante: Giosué Nobizelli

El objetivo del proyecto es aplicar el algoritmo PageRank sobre una red real de tráfico aéreo de Estados Unidos obtenida desde KONECT, construyendo la Matriz de Google a partir de la matriz de hipervínculos de la red, calculando el vector de PageRank mediante iteración de potencias e interpretando los resultados en el contexto de las rutas preferentes de la FAA.

Estructura del Repositorio

* `NoteBook_Proyecto_2.ipynb`: Jupyter Notebook (desarrollado en Google Colab) que contiene todo el código del proyecto: carga de la red, análisis exploratorio, construcción de las matrices H, S y G, cálculo de PageRank mediante iteración de potencias, comparación con el grado de entrada y visualización del subgrafo de nodos más relevantes.
* `Informe proyecto 2 algebra.pdf`: Informe que detalla la elección de la red, la construcción de la Matriz de Google, el cálculo e interpretación del PageRank y las conclusiones obtenidas.
* `out.maayan-faa`: Dataset con la lista de aristas de la red de tráfico aéreo, descargado desde KONECT (http://konect.cc/networks/maayan-faa/).
* `meta.maayan-faa`: Metadatos de la red, descargados desde KONECT.

Requisitos e Instalación

Para ejecutar el código de este proyecto localmente, se necesita Python 3 y las librerías: networkx, numpy, pandas, scipy y matplotlib.

Como el archivo `out.maayan-faa` ya se encuentra en el repositorio, no es necesario descargarlo nuevamente desde KONECT. Basta con subirlo en la celda de "Preparación del archivo de datos" del notebook, o dejarlo en la misma carpeta si se ejecuta localmente, y luego correr el notebook desde la celda de Imports hacia abajo.
