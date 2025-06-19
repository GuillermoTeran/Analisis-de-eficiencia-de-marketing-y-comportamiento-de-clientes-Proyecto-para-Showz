# Análisis de eficiencia de marketing y comportamiento de clientes — Proyecto para Showz

## ES Español

**Rol:** Analista de Datos (Prácticas)  
**Herramientas:** Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook

### Descripción del proyecto  
Como parte de mis prácticas en el departamento de analítica de Showz, empresa de venta de entradas para eventos, realicé un estudio integral para optimizar gastos de marketing y entender mejor el comportamiento de usuarios en la plataforma. El objetivo principal fue evaluar el retorno de inversión de distintos canales de adquisición, mejorar la segmentación y ofrecer recomendaciones basadas en datos.

### Objetivos del análisis  
- Investigar interacción de usuarios y momento de conversión a clientes.  
- Calcular métricas clave: CAC, LTV, ROMI por fuente de adquisición.  
- Evaluar rentabilidad del gasto en marketing digital según dispositivos y canales.  
- Establecer base para decisiones estratégicas de inversión en marketing.

### Preparación de los datos  
Se integraron tres datasets principales:  
- visitas al sitio (visits_log_us.csv)  
- órdenes y compras (orders_log_us.csv)  
- gastos de marketing (costs_us.csv)

Tareas realizadas:  
- Conversión de tipos y normalización de fechas.  
- Cálculo de sesiones por usuario y duración promedio.  
- Unión de datasets por claves comunes para análisis multifuente.

### Análisis de comportamiento del cliente  
- Frecuencia de visitas diaria, semanal y mensual.  
- Duración promedio de sesión y tasa de retorno de usuarios.  
- Tiempos de conversión desde primer acceso hasta primera compra (Conversion 0d, 1d, etc.).  
- Tamaño promedio del pedido y comportamiento por cohorte.  
- LTV para distintos segmentos.

### Análisis de marketing y rentabilidad  
- Cálculo y visualización de costos totales y por fuente.  
- CAC por canal.  
- ROMI por canal y dispositivo.  
- Comparación de rendimiento entre canales (orgánico, redes sociales, pago, etc.).

### Hallazgos clave  
- Fuentes orgánicas y referidos mostraron mejor ROMI por bajo CAC.  
- Plataformas móviles generaron más sesiones; conversiones mayores en escritorio.  
- Conversiones más rápidas en campañas con CTA directas (email marketing).  
- Algunos canales con alto costo y bajo retorno, sugiriendo desinversión.

### Recomendaciones de inversión en marketing  
- Concentrar presupuesto en canales con ROMI positivo: búsqueda orgánica, referidos, remarketing.  
- Reducir inversión en canales con bajo LTV y alto CAC, como display no segmentado.  
- Personalizar campañas por dispositivo: escritorio para conversiones, móvil para generación de leads.  
- Implementar análisis de cohortes mensuales para monitorear campañas nuevas.

### Herramientas utilizadas  
- Python (pandas, numpy, matplotlib, seaborn)  
- Jupyter Notebook  
- Análisis de cohortes, atribución de canales, KPIs de marketing (LTV, CAC, ROMI)

### Impacto del proyecto  
Este análisis sentó las bases para una asignación de presupuesto basada en datos, ayudando a reducir CAC promedio y aumentar ROI general de campañas publicitarias.

---

# Marketing efficiency and customer behavior analysis — Project for Showz

## US English

**Role:** Data Analyst Intern  
**Tools:** Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook

### Project description  
As part of my internship in Showz’s analytics department, an event ticketing company, I conducted a comprehensive study to optimize marketing expenses and better understand user behavior on the platform. The main goal was to evaluate ROI of acquisition channels, improve segmentation, and offer data-driven investment recommendations.

### Analysis objectives  
- Investigate how users interact with the platform and when they convert to customers.  
- Calculate key metrics: CAC, LTV, ROMI by acquisition source.  
- Evaluate digital marketing profitability across devices and channels.  
- Establish a basis for strategic marketing investment decisions.

### Data preparation  
Three main datasets integrated:  
- Site visits (visits_log_us.csv)  
- Orders and purchases (orders_log_us.csv)  
- Marketing expenses (costs_us.csv)

Tasks included:  
- Data type conversion and date normalization.  
- Calculation of sessions per user and average session duration.  
- Joining datasets by common keys for multi-source analysis.

### Customer behavior analysis  
- Daily, weekly, and monthly visit frequency.  
- Average session duration and user return rate.  
- Conversion times from first access to first purchase (Conversion 0d, 1d, etc.).  
- Average order size and purchasing behavior by cohort.  
- LTV for different segments.

### Marketing and profitability analysis  
- Calculation and visualization of total and source costs.  
- CAC per channel.  
- ROMI by channel and device.  
- Comparison of channel performance (organic, social media, paid ads, etc.).

### Key findings  
- Organic and referral sources had best ROMI due to low CAC.  
- Mobile platforms generated more sessions, desktop had higher conversions.  
- Faster conversions in campaigns with direct CTAs (email marketing).  
- Some channels had high cost but low return, suggesting divestment.

### Marketing investment recommendations  
- Focus budget on channels with positive ROMI: organic search, referrals, remarketing.  
- Reduce investment in channels with low LTV and high CAC (non-targeted display).  
- Customize campaigns by device: desktop for conversions, mobile for lead generation.  
- Implement monthly cohort analysis to monitor new campaign efficiency.

### Tools used  
- Python (pandas, numpy, matplotlib, seaborn)  
- Jupyter Notebook  
- Cohort analysis, channel attribution, marketing KPIs (LTV, CAC, ROMI)

### Project impact  
This analysis established the foundation for data-driven budget allocation within marketing, helping reduce average CAC and increase overall ROI of advertising campaigns.
