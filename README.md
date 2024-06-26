# predicciones-de-ventas-de-alimentos
Proyecto de ciencia de datos, desarrollado en Python para hacer predicciones en la venta de alimentos en diversas tiendas.

# Resumen

El proyecto consiste en llevar a cabo un análisis exploratorio de datos sobre un conjunto de datos relacionados a ventas de alimentos en diversas tiendas, sean éstas de tamaño pequeño, mediano y grande. Luego se detallarán las variables (nombres) de las columnas del conjunto de datos. Después del análisis exploratorio, se procede a generar un Modelo de Regresión Lineal y un Árbol de Regresión (ambos para predecir ventas) y calcular métricas de regresión para poder determinar qué modelo es óptimo para hacer las predicciones de ventas de alimentos.

## Variables
Item_Identifier: Identificador único del alimento o producto.
Item_Weight: Peso del producto expresado en kilogramos (kg).
Item_Fat_Content: Variable categórica o discreta. Definido como Low Fat/Regular como proporción de grasa contenida.
Item_Visibility: Porcentaje de visibilidad de exhibición del producto en una tienda particular expresado en un intervalo de 0.0 a 100.0.
Item_Type: Tipo de item definido en el rango de valores discretos: Fruits and Vegetables, Snack Foods, Household, Frozen Foods, Dairy, Canned, Baking Goods, Health and Hygiene, Soft Drinks, Meat, Breads, Hard Drinks, Others, Starchy Foods, Breakfast, Seafood.
Item_MRP: Precio máximo de venta al público (precio de catálogo) del producto.
Outlet_Identifier: Identificador de tienda.
Outlet_Establishment_Year: Año en que se estableció la tienda.
Outlet_Size: Tamaño de la tienda (Small, Medium, High)
Outlet_Establishment_Year: Año que se instaló la tienda
Outlet_Location_Type: Tipo de ubicación de la tienda.
Oytlet_Type: Tipo de tienda. Los valores permitidos o existentes son: Supermarket Type1, Grocery Store, Supermarket Type3, Supermarket Type2.
Item_Outlet_Sales: Ventas del producto en una tienda particular. Esta la variable objetivo a predecir.

# Objetivos

Los objetivos para este proyecto son los siguientes:
1. Analizar el conjunto de datos para obtener datos estadísticos que proponga mejores propuestas para las tiendas en qué productos debiesen tener mayor porcentaje de exhibición y cuáles no.
2. Tener un modelo de predicción capaz de, valga la redundancia, predecir ventas de estos alimentos considerando el aumento o decremento de los porcentajes del área de exhibición dentro de las tiendas.

# Presentación 

https://drive.google.com/file/d/1JQPdTtb0aGQlofyYEyzWWI0J7wobmuez/view?usp=drivesdk

https://drive.google.com/file/d/1JR3MHBAnI0L8tC_cUuelxIIRaSHB59F3/view?usp=drivesdk
