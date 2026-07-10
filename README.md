# An-lisis-del-Embudo-de-Conversi-n-y-Experimento-A-A-B-para-una-Aplicaci-n-M-vil-
Desarrollé un proyecto de análisis de datos para una empresa del sector de alimentos con el objetivo de comprender el comportamiento de los usuarios dentro de su aplicación móvil y evaluar el impacto de un cambio en la interfaz mediante un experimento A/A/B.
El proyecto combinó el análisis del embudo de conversión con pruebas estadísticas para identificar las etapas donde los usuarios abandonaban el proceso de compra y determinar si la implementación de una nueva tipografía influía significativamente en la experiencia y conversión de los usuarios.

Objetivos del proyecto:
Analizar el comportamiento de los usuarios a lo largo del embudo de conversión.
Identificar las etapas con mayor abandono durante el proceso de compra.
Evaluar la calidad y consistencia de los datos experimentales.
Validar la correcta distribución de usuarios entre los grupos de control y prueba.
Determinar, mediante pruebas estadísticas, si el cambio de tipografía generaba un impacto significativo en las conversiones.
Proporcionar recomendaciones basadas en evidencia para apoyar decisiones de diseño del producto.
Herramientas utilizadas:
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
Metodología de resolución:
Importación, limpieza y preparación de los registros de eventos generados por los usuarios de la aplicación.
Validación de tipos de datos, tratamiento de valores faltantes y creación de variables de fecha y hora para facilitar el análisis temporal.
Análisis exploratorio de datos (EDA) para determinar el número de eventos, usuarios únicos, promedio de eventos por usuario y periodo efectivo de análisis.
Construcción del embudo de conversión identificando la frecuencia de cada evento, la proporción de usuarios que avanzaban entre etapas y el punto donde se producía la mayor pérdida de usuarios.
Evaluación de la correcta asignación de usuarios en los grupos experimentales (246, 247 y 248).
Formulación y validación de hipótesis mediante pruebas estadísticas para comparar las tasas de conversión entre los grupos de control (A/A) y el grupo experimental (A/B).
Interpretación de los resultados considerando el nivel de significancia y el impacto de múltiples pruebas estadísticas sobre la confiabilidad del experimento.
Resultados obtenidos:

El análisis permitió identificar los principales puntos de abandono dentro del embudo de conversión y cuantificar el porcentaje de usuarios que completaban el proceso de compra. Asimismo, la evaluación del experimento A/A confirmó la consistencia de los grupos de control, garantizando la validez del experimento.

Posteriormente, la comparación entre los grupos de control y el grupo experimental permitió determinar si el cambio de tipografía generaba diferencias estadísticamente significativas en el comportamiento de los usuarios. Los resultados proporcionaron evidencia objetiva para respaldar la decisión de implementar o descartar el nuevo diseño de la aplicación, minimizando el riesgo de tomar decisiones basadas únicamente en percepciones.

Este proyecto demuestra competencias en análisis exploratorio de datos (EDA), análisis del comportamiento de usuarios, embudos de conversión (Funnel Analysis), diseño y validación de experimentos A/A/B, pruebas de hipótesis, estadística inferencial y visualización de datos, aplicadas a la optimización de la experiencia del usuario y la toma de decisiones basada en datos.
