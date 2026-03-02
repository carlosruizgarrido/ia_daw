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
KPI 1 (Tasa de conversión):
- Antes: 2,5%
- Después: 3,5%
- Por qué mejora la rentabilidad: Más visitantes terminan comprando, aumentando ingresos sin incrementar tráfico.

KPI 2 (Ticket medio):
- Antes: 45 €
- Después: 52 €
- Por qué mejora la rentabilidad: Las recomendaciones cruzadas (cross-selling) aumentan el valor por pedido.

KPI 3 (Margen bruto promedio):
- Antes: 22%
- Después: 26%
- Por qué mejora la rentabilidad: El pricing dinámico optimiza precios según demanda y competencia.

## 6) Diagrama del pipeline (ASCII o Mermaid)
```mermaid
flowchart LR
    A[Usuarios y mercado] --> B[Ingesta de datos en tiempo real]
    B --> C[Limpieza y normalización]
    C --> D[Data Lake en la nube]
    D --> E[Feature Engineering]
    E --> F[Modelo IA<br/>Recomendación + Predicción]
    F --> G[Decisión automática<br/>Precio dinámico + Recomendaciones]
    G --> H[Mejora en conversión y margen]
```
## 7) Riesgos y mitigación
Riesgo 1: Sesgo algorítmico
- El sistema puede favorecer ciertos productos o perfiles de clientes.
  Mitigación 1:
    -Auditorías periódicas de equidad, métricas de sesgo y supervisión humana (human-in-the-loop).

Riesgo 2: Data drift (cambio en patrones de consumo)
- Los modelos pueden perder precisión con el tiempo.
  Mitigación 2:
    -Monitorización continua de rendimiento y reentrenamiento periódico automático.

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy): La IA permite a las empresas tomar decisiones basadas en datos masivos, mejorar la personalización, optimizar precios y reducir ineficiencias operativas. Incrementa productividad, precisión en la toma de decisiones y competitividad. En sectores digitales, es ya un factor estratégico clave para diferenciarse.
- Importancia futura (3–5 años): Evolucionará hacia automatización avanzada, integración con IA generativa y sistemas autónomos que optimicen cadenas de suministro y decisiones estratégicas en tiempo real. Aumentará la personalización hipersegmentada y el uso de agentes inteligentes.
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo): Necesidad de datos de calidad, altos costes de infraestructura, cumplimiento normativo (protección de datos), riesgos éticos y posible impacto en el empleo. También es clave la ciberseguridad y la gobernanza del dato.
- Conclusión razonada: La IA es una inversión estratégica imprescindible para mantener competitividad y rentabilidad. No obstante, su adopción debe ser responsable, transparente y supervisada para garantizar sostenibilidad a largo plazo.

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
