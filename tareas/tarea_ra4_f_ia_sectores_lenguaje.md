# Práctica IA (RA4 · f)

## 1) Caso de uso
- Tipo de aplicación: Web de recomendación de productos (e-commerce)
- Problema: Los usuarios no encuentran fácilmente productos de su interés, lo que reduce las ventas
- Usuario: Clientes de una tienda online

## 2) Datos
- Datos: Historial de compras, clics en productos, tiempo de navegación, valoraciones
- Tipo minería: Recomendación (filtrado colaborativo) + clasificación

## 3) Pipeline
- Recogida: Logs de navegación y base de datos de compras
- Limpieza: Eliminación de datos duplicados o incompletos
- Transformación: Conversión a matrices usuario-producto
- Entrenamiento: Modelo de recomendación (ej. algoritmo de vecinos o ML)
- Predicción: Generación de productos recomendados
- Uso: Mostrar recomendaciones personalizadas en la web

## 4) Integración
- Backend: API REST que conecta la web con el modelo de IA
- Frontend: Interfaz con sección “Productos recomendados”
- Flujo: Usuario entra → navega → backend envía datos → IA genera recomendación → se muestran productos

## 5) Valor
- Mejora: Personalización de la experiencia del usuario
- Sin IA: Recomendaciones genéricas menos efectivas
- Rentabilidad: Aumento de ventas y fidelización

## 6) Diagrama
```mermaid
flowchart LR
    U[Usuario] --> W[App Web]
    W --> B[Backend (API REST)]
    B --> IA[Modelo de IA]
    IA --> R[Recomendaciones]
    R --> W
    W --> U
```
