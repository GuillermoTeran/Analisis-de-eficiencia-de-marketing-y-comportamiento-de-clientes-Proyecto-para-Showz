# Análisis de eficiencia de marketing y comportamiento de clientes — Proyecto para Showz

## ES Español

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


# Marketing efficiency and customer behavior analysis — Project for Showz

## US English

Project description:

As part of my internship in the analytics department at Showz, an event ticketing company, I conducted a comprehensive study to optimize marketing expenses and better understand user behavior on the platform. The main objective was to evaluate the return on investment of different acquisition channels, improve customer segmentation, and offer data-driven investment recommendations.

## Analysis objectives:

Investigate how users interact with the platform and when they become customers.

Calculate key metrics such as CAC, LTV, and ROMI by acquisition source.

Evaluate the profitability of digital marketing spending across different devices and channels.

Establish a basis for strategic marketing investment decisions.

## Data Preparation
Three main datasets were integrated:

Site visits (visits_log_us.csv)

Orders and purchases (orders_log_us.csv)

Marketing expenses (costs_us.csv)

Tasks included:

Data type conversion and data normalization.

Calculation of sessions per user and their duration.

Joining datasets using common keys for multi-source analysis.

## Customer behavior analysis
Key metrics related to platform usage were analyzed:

Daily, weekly, and monthly visit frequency.

Average session duration and user return.

Conversion times from first access to first purchase (Conversion 0d, 1d, etc.).

Average order size and purchasing behavior by cohort.

LTV (customer lifetime value) for different segments.

## Marketing and profitability analysis
Key metrics were calculated and visualized:

Total cost and cost per acquisition source.

CAC (customer acquisition cost) per channel.

ROMI (return on marketing investment) per channel and device.

Comparison of channel performance such as organic, social media, paid advertising, etc.

## Key findings:
Organic and referral sources had the best ROMI thanks to their low CAC.

Mobile platforms generated more sessions, but conversions were higher on desktops.

The average conversion time was shorter in campaigns with direct CTAs, such as email marketing.

Some channels had a high cost with low return, suggesting divestment.

## Marketing investment recommendations:
Focus budget on channels with positive ROMI, such as organic search, referrals, and specific remarketing campaigns.

Reduce investment in channels with low LTV and high CAC, such as certain non-targeted display campaigns.

Customize campaigns by device, prioritizing desktop for conversions and mobile for lead generation.

Implement monthly cohort analysis to monitor the efficiency of new campaigns.

## Tools used:

Python (pandas, numpy, matplotlib, seaborn)

Jupyter Notebook

Cohort analysis, channel attribution, marketing KPIs (LTV, CAC, ROMI)

## Project impact:
This analysis laid the foundation for data-driven budget allocation within the marketing team, helping to reduce average CAC and increase the overall ROI of advertising campaigns.


