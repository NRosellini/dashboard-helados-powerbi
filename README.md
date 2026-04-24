# 🍦 Dashboard Helados S.A. — Power BI

Dashboard interactivo desarrollado en Power BI para el análisis comercial de una empresa de helados. Permite monitorear ingresos, comparar ejecución vs presupuesto, identificar clientes y productos más rentables, y detectar patrones estacionales.

## 🎯 Objetivo de negocio

Brindar al equipo comercial y de gerencia una herramienta visual para responder preguntas clave:
- ¿Cómo evolucionan los ingresos mes a mes?
- ¿Cuánto nos estamos desviando del presupuesto anual?
- ¿Cuáles son nuestros clientes y sabores más rentables?
- ¿Qué tan marcada es la estacionalidad del negocio?

## 📊 Páginas del dashboard

### Página 1 — Resumen ejecutivo por cliente
KPIs principales (Ingreso Bruto, Desvío vs Presupuesto, Venta por Cliente), evolución mensual y filtro interactivo por cliente.

### Página 2 — Análisis por sabor de helado
Ranking de sabores por ingresos y cantidad en kilogramos. Permite identificar productos estrella vs productos de baja rotación.

### Página 3 — Tendencia y promedio móvil
Serie temporal con **promedio móvil** para suavizar la estacionalidad y visualizar la tendencia real del negocio, independientemente de los picos mensuales.

## 🔍 Principales insights

- **Ingreso bruto anual:** $10.08 millones
- **Desvío vs presupuesto:** -5.48% (ejecución por debajo del objetivo)
- **Estacionalidad marcada:** pico en enero-febrero (verano), caída fuerte de junio a septiembre (invierno), recuperación en noviembre-diciembre
- **Concentración de ingresos:** los 8 sabores top representan más del 60% de la facturación

## 🛠️ Tecnologías y técnicas aplicadas

- **Power BI Desktop** — modelado de datos, medidas DAX, dashboard interactivo
- **DAX** — medidas calculadas para KPIs, comparación vs presupuesto, promedio móvil
- **Modelado de datos** — relaciones entre tablas de ventas, clientes, productos y presupuesto
- **Storytelling visual** — navegación entre páginas, slicers interactivos, formato condicional por color (rojo/verde según cumplimiento)

## 📁 Archivos

- `Helados S.A..pbix` — archivo del dashboard en Power BI
- `Helados.xlsx` — dataset fuente
- `01 - TP6 FINAL.pdf` — exportación en PDF del dashboard completo

## 🎓 Contexto

Trabajo práctico final desarrollado durante el curso avanzado de Power BI en la Universidad Nacional de Córdoba (UNC).

## 👤 Autor

Nicolás Rosellini — [LinkedIn](https://www.linkedin.com/in/nicolas-rosellini/)
