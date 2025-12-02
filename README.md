# Proyecto: Análisis Visual de Medallistas Panamericanos (Centroamérica)

Este proyecto analiza un dataset con información de medallistas panamericanos de Centroamérica. El objetivo fue explorar los datos usando Seaborn, crear varias gráficas y entender patrones sobre los años, deportes, países, sexo de los atletas y tipos de medallas.

Durante el análisis hice diferentes tipos de visualizaciones, probé varios estilos y también guardé todas las gráficas en formato PNG.

# Archivos del repositorio

1. proyecto.ipynb – Notebook con el análisis completo.
2. medallistas_panamericanos_CA.csv – Dataset usado.
3. Imágenes de todas las gráficas. 
4. README.md – Este archivo.

# Análisis Completo del Dataset

Aquí explico de forma sencilla lo que se encontró en cada parte del análisis.

1. Distribución de medallas por año

Al graficar la cantidad de medallas por año, se nota que hay años donde el número de atletas aumenta o disminuye. Esto ayuda a ver cuáles ediciones tuvieron más participación.
En general, los años más recientes tienden a tener más registros, probablemente por un mejor registro de datos.

2. Deportes con mayor número de medallas

Al analizar los deportes, se observa que algunos tienen mucha más presencia que otros.
Hay disciplinas donde aparecen muchos atletas y medallas, lo que refleja una mayor actividad o tradición deportiva en esos países.

Esto también sugiere que ciertos deportes reciben más apoyo o tienen más trayectoria histórica.

3. Participación por sexo

En la comparación entre hombres y mujeres, se ve que hay un ligero predominio de un sexo en algunos deportes.
No es igual en todas las disciplinas, pero sí se nota una diferencia en la cantidad de registros.

Esto permite entender mejor la participación deportiva y cómo ha cambiado con el tiempo.

4. Países más presentes en el dataset

Hay países que tienen más atletas en el dataset, lo que indica que suelen participar más o tienen más medallistas registrados.
No todos los países están representados por igual, por eso este gráfico ayuda a ver cuál tiene más presencia.

5. Relación entre Año y Deporte (violinplot)

El violinplot mostró que ciertos deportes se concentran en algunos periodos específicos.
No todos los deportes aparecen en los mismos años, lo cual tiene sentido porque algunos son más recientes o cambian entre ediciones.

6. Heatmap de correlaciones

La matriz de correlación no tiene mucha variación porque el dataset no tiene muchas columnas numéricas (solo “Año”).
Aun así, se mantiene como parte del análisis visual para completar el conjunto de gráficos solicitados.

# Estilos y colores

Se usaron diferentes paletas de Seaborn como:

- deep
- bright
- muted
- coolwarm
- flare

Además, probé estilos como:
- whitegrid
- darkgrid

Esto hace que los gráficos se vean más variados y completos.

Visualizaciones guardadas

Todas las gráficas se guardaron como imágenes PNG en una carpeta llamada /graficos para que el repositorio quede completo y ordenado.
