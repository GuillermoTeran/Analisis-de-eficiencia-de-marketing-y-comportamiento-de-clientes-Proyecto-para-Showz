# Análisis de eficiencia de marketing y comportamiento de clientes — Proyecto para Showz
Descripción del proyecto:

Como parte de mis prácticas en el departamento de analítica de Showz, una empresa de venta de entradas para eventos, realicé un estudio integral para optimizar los gastos de marketing y entender mejor el comportamiento de los usuarios en la plataforma. El objetivo principal fue evaluar el retorno de inversión de diferentes canales de adquisición, mejorar la segmentación de clientes y ofrecer recomendaciones de inversión con base en datos.

## Objetivos del análisis:

Investigar cómo los usuarios interactúan con la plataforma y cuándo se convierten en clientes.

Calcular métricas clave como CAC, LTV, y ROMI por fuente de adquisición.

Evaluar la rentabilidad del gasto en marketing digital en distintos dispositivos y canales.

Establecer una base para decisiones estratégicas de inversión en marketing.

## Preparación de los datos
Se integraron tres datasets principales:

Visitas al sitio (visits_log_us.csv)

Órdenes y compras (orders_log_us.csv)

Gastos de marketing (costs_us.csv)

Las tareas incluyeron:

Conversión de tipos de datos y normalización de fechas.

Cálculo de sesiones por usuario y su duración.

Unión de datasets mediante claves comunes para análisis multifuente.

## Análisis de comportamiento del cliente
Se analizaron métricas clave relacionadas con el uso de la plataforma:

Frecuencia de visitas diaria, semanal y mensual.

Duración promedio de sesión y retorno de usuarios.

Tiempos de conversión desde el primer acceso hasta la primera compra (Conversion 0d, 1d, etc.).

Tamaño promedio del pedido y comportamiento de compra por cohorte.

LTV (Valor del tiempo de vida del cliente) para distintos segmentos.

## Análisis de marketing y rentabilidad
Se calcularon y visualizaron métricas clave:

Costo total y por fuente de adquisición.

CAC (Costo de adquisición de cliente) por canal.

ROMI (Retorno sobre inversión en marketing) por canal y dispositivo.

Comparación del rendimiento de canales como orgánico, redes sociales, publicidad pagada, etc.

## Hallazgos clave:
Las fuentes orgánicas y de referidos presentaron el mejor ROMI gracias a su bajo CAC.

Las plataformas móviles generaron más sesiones, pero las conversiones fueron más altas en escritorio.

El tiempo medio de conversión fue menor en campañas con CTA directas, como email marketing.

Algunos canales tuvieron un alto costo con bajo retorno, lo que permitió sugerir su desinversión.

## Recomendaciones de inversión en marketing:
Concentrar presupuesto en canales con ROMI positivo, como búsqueda orgánica, referidos y campañas específicas de remarketing.

Reducir inversión en canales con bajo LTV y alto CAC, como ciertas campañas de display no segmentadas.

Personalizar campañas por dispositivo, priorizando escritorio para conversiones y móvil para generación de leads.

Implementar análisis de cohortes mensuales para monitorear la eficiencia de campañas nuevas.

## Herramientas utilizadas:

Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook

Análisis cohortes, atribución de canales, KPIs de marketing (LTV, CAC, ROMI)

## Impacto del proyecto:
Este análisis sentó las bases para una asignación de presupuesto basada en datos en el equipo de marketing, ayudando a reducir el CAC promedio y aumentar el ROI general de campañas publicitarias.


