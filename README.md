# RetailPro — Proyecto de Análisis Comercial & BI (SQL Server + Power BI)

Proyecto integral de análisis de datos orientado a optimizar la gestión comercial, el control de inventario y el seguimiento de metas de **RetailPro** (ventas tecnológicas en Argentina y Uruguay).

## 🛠️ Stack Tecnológico
* **Motor de Base de Datos:** Microsoft SQL Server (T-SQL) — Base `Ventas_Tech_DB`
* **Modelado y Visualización:** Power BI Desktop (Esquema en Estrella y DAX)
* **Control de Versiones:** GitHub

## 📂 Estructura del Repositorio y Ejecución
Para reproducir el entorno analítico en SQL Server Management Studio (SSMS), ejecutá los scripts en el siguiente orden:
1. `01_schema_y_carga.sql`: Creación de tablas relacionales (`clientes`, `productos`, `ventas`) e inserción de registros iniciales.
2. `02_metricas_ejecutivas.sql`: Consultas de agregación mensual y ranking Top 5 de productos (`TOP`, `SUM`, `AVG`, `GROUP BY`).
3. `03_joins_y_auditoria.sql`: Vista base unificada para Power BI (`INNER JOIN`), detección de clientes/productos sin movimiento (`LEFT JOIN`) y consolidación regional (`UNION ALL`).

## 📊 Principales Indicadores Modelados (DAX)
* **Total Ingresos** y **Margen %**
* **Inteligencia de Tiempo:** `Ingresos YTD`, `Ingresos Año Anterior` y `% Crecimiento YoY`# retailpro-sql-analytics
