# Customer-Personality-Analysis
Introducción
El proyecto de análisis de personalidad de clientes tiene como objetivo segmentar a los clientes en distintos grupos basados en sus características demográficas y comportamiento de compra. El propósito es entender mejor a los diferentes segmentos de clientes y personalizar las estrategias de marketing y ventas para cada grupo, mejorando así la efectividad de las campañas y aumentando la satisfacción del cliente.

Definición del problema
El problema que se aborda en este proyecto es la falta de conocimiento detallado sobre las características y comportamientos de los diferentes segmentos de clientes. Esto impide la creación de estrategias de marketing personalizadas que podrían mejorar la retención de clientes y aumentar las ventas.

Recopilación de datos
Se utilizó un conjunto de datos ‘Customer Personality Analysis’ que incluye información de los clientes de una empresa y donde se detallan hábitos de compras y características demográficas.

Limpieza y preparación de los datos
Los pasos tomados para limpiar y preparar los datos incluye:

Individuación de valores nulos y sustitución con los valores promedio.
Conversión de formatos de datos a tipos adecuados (por ejemplo, ingresos y gastos a valores numéricos).
Eliminación de columnas que no aportan información útil.
Eliminación de los valores atípicos.
Reemplazo de valores con muchas opciones.
Análisis Exploratorio de Datos
El análisis exploratorio reveló las siguientes conclusiones clave:

Existen diferencias significativas en el gasto total y las visitas al sitio web entre los distintos grupos de edad y estado civil.
Los clientes con mayores ingresos tienden a gastar más en la plataforma, pero no necesariamente visitan el sitio con mayor frecuencia.
Los clientes con estudios de postgrado muestran comportamientos de compra diferentes comparados con aquellos con menor nivel educativo.
Creación de variables
Para mejorar el rendimiento del modelo, se crearon nuevas características tales como:

Gasto total por usuario.
Número de hijos en el hogar.
Edad.
Familia.
Educación.
Correlación
Ingresos (Income)

Correlación fuerte con Total Gastado
Correlación inversa con Visitas en la Web y Compras con descuento
Total Gastado

Correlación positiva con Compras en la Web
Correlación inversa con Visitas en la Web
Recency (Número de días sin comprar)

Correlación inversa con Total Gastado
Construcción y Evaluación del Modelo
Se utilizaron algoritmos de clustering, específicamente K-means, para segmentar a los clientes. El modelo fue entrenado con datos de entrenamiento y evaluado utilizando métricas como la inercia y el coeficiente de silhouette para determinar el número óptimo de clusters.

Visualización de Datos
Se crearon visualizaciones para presentar los resultados del análisis y segmentación de clientes. Estas herramientas permiten a los equipos de marketing y ventas identificar rápidamente los diferentes segmentos y adaptar sus estrategias en consecuencia.

Resultados y Discusión
Los principales hallazgos del proyecto incluyen:

Identificación de cuatro segmentos de clientes distintos con características y comportamientos únicos.
Descubrimiento de patrones clave que pueden informar futuras campañas de marketing.
Mejora potencial en la personalización de ofertas y comunicaciones dirigidas a cada segmento.
Conclusión
El proyecto logró segmentar eficazmente a los clientes en grupos significativos, proporcionando una comprensión más profunda de sus comportamientos y características. Esto permite una mejor personalización de las estrategias de marketing y ventas, con el potencial de aumentar la retención y satisfacción del cliente.

Trabajo Futuro
Las posibles mejoras incluyen:

Implementación de modelos predictivos para anticipar el comportamiento futuro de los clientes.
Integración de datos adicionales, como el comportamiento en redes sociales, para enriquecer el análisis.
Monitoreo continuo y ajuste de las estrategias de segmentación y marketing basado en los resultados y retroalimentación obtenida.
