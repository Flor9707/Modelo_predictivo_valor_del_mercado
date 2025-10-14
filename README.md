# Modelo_predictivo_valor_del_mercado
# 🚗 Predicción del Valor de Mercado de Autos Usados – Rusty Bargain

Rusty Bargain está desarrollando una aplicación para atraer nuevos clientes interesados en vender o comprar autos usados. Esta herramienta permite estimar rápidamente el valor de mercado de un vehículo, basándose en su historial técnico, versiones de equipamiento y precios anteriores.

## 🧠 Enfoque del Proyecto

El objetivo principal fue construir un modelo de regresión que prediga con precisión el valor de mercado de un coche, optimizando tres factores clave:

- Calidad de la predicción  
- Velocidad de la predicción  
- Tiempo requerido para el entrenamiento

## 🔍 Proceso y Hallazgos

Se probaron múltiples enfoques de modelado, priorizando el balance entre precisión y eficiencia computacional. El modelo más efectivo fue **CatBoostRegressor**, que logró una excelente predicción incluso con codificación one-hot para variables categóricas.

Aunque se ajustaron hiperparámetros para mejorar el rendimiento, se evitó un sobreentrenamiento excesivo que pudiera comprometer el tiempo de entrenamiento. Se concluyó que el modelo podría seguir mejorando con más iteraciones, pero a costa de mayor gasto computacional.

## 📊 Resultados

- Alta precisión en la estimación del valor de mercado  
- Modelo robusto y rápido, ideal para aplicaciones en tiempo real  
- Codificación eficiente de variables categóricas  
- Equilibrio entre rendimiento y costo computacional

## 👤 Autora

Flor María Borja Luna
