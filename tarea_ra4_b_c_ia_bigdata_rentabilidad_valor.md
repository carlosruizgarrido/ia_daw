# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Amazon (sector e-commerce)
- Problema a resolver: Maximizar ventas y margen en un entorno altamente competitivo donde los precios cambian constantemente y los clientes esperan recomendaciones personalizadas.
- Objetivo de negocio (rentabilidad): Aumentar ventas y margen bruto mediante pricing dinámico y sistemas de recomendación personalizados.

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad). Se manejan grandes volúmenes de datos generados en tiempo real por millones de usuarios, con múltiples formatos y fuentes heterogéneas (3V: volumen, velocidad y variedad).
- Fuente 1: Datos de comportamiento del usuario (clics, búsquedas, tiempo en página, carrito).
- Fuente 2: Datos transaccionales (compras, devoluciones, métodos de pago).
- Fuente 3: Datos externos (precios de competidores, tendencias de mercado, estacionalidad).
- Volumen/velocidad (estimación): Millones de eventos por hora a nivel global; actualizaciones en tiempo real.
- Formatos (texto, eventos, series temporales, imágenes, etc.): Logs de eventos, series temporales de precios, texto (búsquedas y reseñas), datos estructurados (transacciones).

## 3) Tratamiento/análisis: pipeline de datos
- Ingesta (captura/eventos): Explica el flujo de forma ordenada: Captura automática de clics y transacciones mediante logs y APIs en tiempo real.
- Limpieza/normalización: Eliminación de duplicados, tratamiento de valores nulos, normalización de precios y detección de outliers.
- Almacenamiento (data lake/warehouse): Data Lake en infraestructura cloud distribuida para almacenar datos estructurados y no estructurados.
- Preparación de variables (features): Variables como frecuencia de compra, sensibilidad al precio, historial de navegación, estacionalidad.
- Análisis/BI (opcional): Dashboards para segmentación de clientes y análisis de elasticidad precio-demanda.

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...): Recomendación (filtrado colaborativo + machine learning supervisado). Predicción (modelos de regresión para demanda y elasticidad).
- Entrada del modelo (qué datos usa): Historial de compras, comportamiento de navegación, precios actuales, stock disponible y datos de competencia.
- Salida del modelo (qué produce): Lista personalizada de productos recomendados. Precio óptimo estimado para maximizar margen y probabilidad de compra.
- Decisión que habilita (qué hace la empresa con esa salida): Mostrar recomendaciones personalizadas y ajustar precios dinámicamente en la web en tiempo real.

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 2:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 3:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
