# Análisis de Datos y Consultas Estratégicas - Tiendas Irene

Este proyecto contiene el diseño de una base de datos relacional orientada al análisis comercial para **"Tiendas Irene"**, un negocio de retail simulado. El objetivo principal es responder a requerimientos analíticos del negocio mediante la ejecución de scripts estructurados en **SQL Server**.

## 🛠️ Tecnologías Utilizadas
* **Motor de Base de Datos:** Transact-SQL (T-SQL) / SQL Server
* **Herramienta:** SQL Server Management Studio (SSMS)

## 📊 Estructura de los Datos
Se diseñó una tabla maestra optimizada para análisis rápido llamada `Ventas_Diarias`, la cual centraliza información clave sobre:
* **Dimensiones de Negocio:** Clientes, Ubicación (Ciudades), Vendedores y Proveedores.
* **Métricas Transaccionales:** Precios unitarios, cantidades vendidas, cálculo automático de ingresos (`Total_Pagar`) e indicadores logísticos como el estado de stock.

## 🔍 Requerimientos de Negocio Resueltos
El script incluye consultas avanzadas desarrolladas para extraer *insights* estratégicos, respondiendo a las siguientes necesidades:
1. **Métricas de Control Financiero:** Cálculo del Gran Total de ingresos recaudados y proyecciones de impuestos fiscales (Cálculo automatizado del 18% de IGV).
2. **Evaluación de la Fuerza de Ventas:** Conteo preciso de transacciones y operaciones realizadas por asesores específicos (ej. Jorge Soto).
3. **Análisis de Clientes y Geografía:** Segmentación de mercados y filtrado de consumidores específicos en regiones clave como Lima y Callao.
4. **Análisis de Inventarios y Logística:** Identificación de alertas de quiebre de stock (`Estado_Stock = 'Bajo'`) en categorías críticas como Abarrotes.
5. **Análisis Avanzado de Precios y Productos:** Aplicación de operadores lógicos y funciones de rango (`BETWEEN`, `IN`, `LIKE`) para auditar la oferta de productos comerciales.

---
*Proyecto desarrollado por **Andy Manuel Trujillo Perez** como parte de mi portafolio para posiciones de Data Analyst Junior.*
