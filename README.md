# A2.2 LDA y Árboles de Decisión

SC3314 – Inteligencia Artificial Universidad de Monterrey Dr. Antonio Martínez Torteya
A2.2 LDA y Árboles de Decisión
En esta actividad trabajarás con la misma base de datos que trabajaste en el proyecto del primer
parcial y en la actividad A2.1. Si por algún motivo tienes problemas y deseas cambiar de base
de datos, puedes hacerlo, especificando claramente con qué base de datos estás trabajando
ahora y de dónde la obtuviste.
Desarrolla los siguientes puntos en una Jupyter Notebook, tratando, dentro de lo posible, que
cada punto se trabaje en una celda distinta. Los comentarios en el código siempre son
bienvenidos, de preferencia, aprovecha el markdown para generar cuadros de descripción que
ayuden al lector a comprender el trabajo realizado.
1. Importa los datos a tu ambiente de trabajo y separa los datos en entrenamiento y prueba,
con una relación que consideres adecuada, manteniendo un balance de clases.
Demuestra que se cumplió la condición imprimiendo datos relevantes en la consola.
2. Corre una regresión logística simple con la función GLM de statsmodels con todas tus
variables de entrada e imprime el resumen del modelo en consola. Indica cuáles son las
2 variables más relevantes para este estudio y selecciónalas, eliminando todas las demás
variables de tus datos de entrenamiento y prueba.
3. Genera un modelo usando la metodología de linear discriminant analysis. Visualiza la
función discriminante con una gráfica de variable 1 vs variable 2, donde cada observación
tenga algo que la distinga dependiendo de su clase (por ejemplo, distinto color, distinto
marcador, etc.)
4. Genera un modelo usando la metodología de árboles de decisión. Deberás podar el árbol,
habiendo seleccionado primero un valor óptimo de 𝛼𝛼 mediante una metodología de
LOOCV. Visualiza tanto el árbol resultante, como la partición en una gráfica de variable 1
vs variable 2, donde cada observación tenga algo que la distinga dependiendo de su
clase.
5. Calcula, para ambos modelos, todas las métricas revisadas en clase en los datos de
prueba. Indica qué opinas sobre los resultados, especificando si crees que uno de los dos
modelos es mejor para esta tarea específica.

-[HTML](./A2_1-598557.html)

-[Jupyter Notebook](./A2_1-598557.ipynb)

-[Base de Datos](./USA%20Housing%20Dataset.csv)
