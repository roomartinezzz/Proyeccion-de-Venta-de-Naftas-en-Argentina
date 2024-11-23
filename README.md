# PREDICCIÓN DEL CONSUMO TOTAL DE NAFTAS EN ARGENTINA PARA EL AÑO 2024
Este repositorio contiene un proyecto que utiliza datos históricos y modelos de regresión para predecir el consumo total de naftas en Argentina (medido en km³) para el año 2024.

Variables Consideradas
Total km³: Cantidades vendidas históricas.
Inflación anual histórica: Porcentaje anual de inflación en Argentina.
Precio promedio del barril (OPEP): Precio promedio histórico del petróleo Brent en USD.
PBI de Argentina histórico: Producto Bruto Interno anual medido en dólares estadounidenses.


Se utiliza la técnica de Forward Selection para determinar las variables más significativas.
Variables seleccionadas:
PBI USD
Precio promedio del barril USD (OPEP)
Inflación anual (%)

Modelo Regresión Lineal: R²: 0.81, MAE: 541 km³.
Modelo Random Forest: R²: 0.87, MAE: 428 km³.

## Supuestos para 2024:
PBI: Caída del 2.8% (estimación FMI).
Precio del barril: 83 USD (estimación JP Morgan).
Inflación: 219% (estimación Focus Economics).
#### La predicción final estima el consumo total para el año 2024 en función de estos valores: Total km³ proyectado: 9533.98

## Predicción de MIX PREMIUM de Naftas
Una vez obtenida la cantidad total de naftas para el año 2024 , se utiliza como supuesto para intentar calcular el MIX PREMIUM del 2024:

A través de forward selection, se identificaron dos variables clave para el modelo:
Total km³ consumidos.
Delta entre CVS e inflación.


Modelo Lineal:
R² obtenido: 0.221.
Precisión moderada; errores elevados en predicciones atípicas.
Random Forest:
Implementado como modelo alternativo para mejorar la precisión.

Hipótesis 2024:
Total km³ proyectado: 9533.98.
Delta CVS vs. Inflación: -65%.
#### Predicción para el Mix Premium: 21.69%.

