# Test-A-B-Para-el-Aumento-de-Ingresos
Análisis completo de un test A/B para una tienda online. Incluye priorización de hipótesis con ICE y RICE, visualización de métricas clave, detección de anomalías y pruebas estadísticas.

# Proyecto Final - Sprint 10: Análisis de Test A/B

Este proyecto es parte del curso "Toma de decisiones de negocios basadas en datos" (TripleTen).  
El objetivo es evaluar el impacto de una serie de cambios en una tienda online mediante un test A/B.

##  Objetivo

- Priorizar hipótesis de negocio utilizando los frameworks **ICE** y **RICE**.
- Analizar los resultados de un experimento A/B en términos de:
  - Ingresos acumulados
  - Tamaño promedio de pedido
  - Tasa de conversión diaria
  - Presencia de anomalías
  - Significancia estadística de las diferencias observadas

##  Datos utilizados

- `hypotheses_us.csv`: hipótesis de marketing
- `orders_us.csv`: pedidos realizados durante el experimento
- `visits_us.csv`: visitas diarias por grupo A/B

##  Herramientas y librerías

- Python
- pandas
- matplotlib
- scipy.stats
- Jupyter Notebook

##  Principales hallazgos

- El grupo B presentó una mayor tasa de conversión y tamaño promedio de pedido.
- Las diferencias fueron estadísticamente significativas incluso tras eliminar anomalías.
- Se recomienda implementar los cambios del grupo B.

##  Estructura del proyecto

- Priorización de hipótesis
- Visualización de resultados A/B
- Análisis de valores atípicos
- Pruebas estadísticas
- Toma de decisiones basada en datos

---

> Proyecto desarrollado por @sanchezcsar como parte del programa de Data Analytics de TripleTen.
