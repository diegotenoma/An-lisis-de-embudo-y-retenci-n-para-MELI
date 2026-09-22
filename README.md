# 🛒 Análisis de Embudo y Retención — MercadoLibre LATAM

Análisis del comportamiento de usuarios en el funnel de compra y retención por cohortes para MercadoLibre, cubriendo 10 países de América Latina durante el periodo enero–agosto 2025. El objetivo es identificar los puntos de mayor fricción en el proceso de compra y los patrones de abandono a lo largo del tiempo.

🎯 Preguntas de Negocio
¿Cuál es la tasa de conversión entre cada etapa del embudo de compra y en qué paso se observa la mayor caída?
¿Cómo varía esa pérdida por país?
¿Qué tan bien se retiene a los usuarios en D7, D14, D21 y D28 desde su registro?
¿Qué países muestran mejor o peor retención y qué implica para la estrategia?
📂 Estructura del Archivo
Hoja	Contenido
Informe Ejecutivo	Resumen de hallazgos, implicaciones y reflexión analítica
Embudo General	Tasas de conversión globales por etapa del funnel
Embudo General x País	Conversión desglosada por los 10 países de LATAM
Retención x País	Tasas de retención D7, D14, D21 y D28 por país
Retención x Cohort	Retención mensual por cohortes de enero a agosto 2025

Periodo de análisis: 01/01/2025 – 31/08/2025
Cobertura geográfica: Argentina, Bolivia, Brasil, Chile, Colombia, Ecuador, México, Paraguay, Perú, Uruguay

🔍 Hallazgos Principales
Embudo de Conversión General
Etapa	Tasa de Conversión
Select Item	76.89%
Add to Cart	11.01%
Begin Checkout	4.00%
Add Shipping Info	2.41%
Add Payment Info	2.09%
Purchase	1.25%

Caída crítica: La mayor pérdida ocurre entre Select Item y Add to Cart — una reducción del ~85%. Esto sugiere desalineación entre el interés inicial y la intención real de compra: problemas de precio, confianza o relevancia del producto.

Conversión por País
Mejor desempeño (Add to Cart > 13%): Chile (17.5%), Uruguay (22.7%), México (13.2%)
Mayor fricción (Add to Cart < 10%): Paraguay (9.5%), Ecuador (10.2%), Argentina (8.75%)
Conversión final nula: Ecuador, Colombia y Paraguay no registran compras completadas — la fricción ocurre en el flujo de pago o envío
Retención por Cohortes
Periodo	Rango de Retención
D7	70% – 88%
D14	29% – 57%
D21	7.5% – 26.6%
D28	0.2% – 3.0%

La retención cae de forma pronunciada después del día 14 — los usuarios que no generan hábito en las primeras dos semanas prácticamente no regresan.

Retención por País (D28)
Mejor retención: México (3.1%), Perú (3.2%), Bolivia (2.5%), Ecuador (2.5%), Uruguay (2.5%)
Menor retención: Colombia (1.6%), Chile (1.7%), Argentina (1.8%)
💡 Recomendaciones

Prioridad 1 — Add to Cart Es la caída más grande del embudo y el cuello de botella con mayor impacto en revenue potencial. Optimizar la relevancia del producto, mostrar precio final sin cargos sorpresa y mejorar señales de confianza (reseñas, garantías) podría mover esta métrica significativamente.

Prioridad 2 — Checkout en países con conversión nula Ecuador, Colombia y Paraguay pierden usuarios que ya demostraron intención. Las fricciones técnicas en shipping o payment deben resolverse — un usuario que llega al checkout no debería perderse por barreras operativas.

Prioridad 3 — Retención D14 La caída entre D7 y D14 es la más pronunciada en todas las cohortes. Implementar estrategias de re-engagement (notificaciones, ofertas personalizadas) entre el día 7 y 14 podría recuperar una porción significativa de usuarios.

Enfoque local, no global Los patrones varían considerablemente por país — las optimizaciones deben diseñarse por mercado, no como iniciativas regionales únicas.

🛠️ Herramientas Utilizadas
Microsoft Excel / Google Sheets
Análisis de cohortes y embudo de conversión
Tablas por segmento geográfico y temporal
👤 Autor

Diego Tenorio Martínez — Data Analyst
linkedin.com/in/tenoriodiego | github.com/diegotenoma
