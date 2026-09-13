# Excel con IA — Control de Gastos Personales

Proyecto final: **Domina Excel con IA**

## Objetivo
Analizar los gastos personales de un hogar usando funciones predictivas y de análisis
automático en Excel, respondiendo la pregunta:

> **¿En qué mes se concentran los mayores gastos, qué categoría los impulsa y cómo se
> proyecta el gasto del próximo mes?**

## Contenido del archivo `Control_Gastos_IA.xlsx`

| Hoja | Contenido |
|---|---|
| `Datos` | 89 transacciones simuladas (enero–junio 2026) con Fecha, Categoría, Descripción, Monto y Mes |
| `Resumen_IA` | Tabla dinámica por mes/categoría, proyección de julio 2026 con `FORECAST`, análisis automático de insights (mes de mayor gasto, categoría dominante, tendencia) e interpretación generada con fórmulas dinámicas de texto, más 2 gráficos |
| `Documentación` | Tema, fuente de datos, funciones de IA usadas y conclusiones |

## Funciones utilizadas
- **`FORECAST`**: función predictiva (regresión lineal) para proyectar el gasto de julio 2026 por categoría y total.
- **`SLOPE`**: calcula la tendencia (pendiente) del gasto mensual.
- **`SUMIFS` / `INDEX` / `MATCH`**: agregación dinámica e identificación automática de insights (mes pico, categoría dominante).
- **Fórmulas de texto dinámicas** (`&`, `TEXT`, `IF`): generan una interpretación automática del análisis, similar a "Ideas de Excel".
- Gráfico de barras apiladas y gráfico de línea de tendencia/proyección.

## Resultado principal
El análisis muestra que **Marzo 2026** fue el mes de mayor gasto (~$2.8M COP), con
**Vivienda** como categoría dominante. Para julio de 2026 se proyecta un gasto total de
aproximadamente $2.46M COP.


## Autora:
Mariana Silva Borda

