# Ejercicio-practico-semana-3---Grupo-7
Repositorio del trabajo práctico grupal de análisis de datos. Incluye selección de dataset, limpieza, EDA, visualizaciones y documentación de hallazgos. Todo el proceso está centralizado y coordinado en este repositorio como entregable final.

## Descripción del propósito del dataset:
Se seleccionó el dataset "Teen Smartphone Usage and Addiction Impact Dataset" debido a la creciente relevancia del uso de smartphones en la vida cotidiana, especialmente entre los adolescentes. En la actualidad, los dispositivos móviles no solo son una herramienta de comunicación, sino también una fuente de entretenimiento, socialización, educación e incluso dependencia emocional.

Este dataset permite abordar un problema contemporáneo de alto impacto social: la adicción al teléfono móvil en jóvenes. A través del análisis de variables como el tiempo de uso, las actividades más frecuentes, los hábitos relacionados con el sueño y el comportamiento en redes sociales, es posible obtener insights significativos sobre los patrones de uso y su posible relación con factores psicológicos y conductuales.

Además, este conjunto de datos ofrece una base sólida para realizar un análisis exploratorio detallado, construir visualizaciones informativas y, potencialmente, aplicar modelos predictivos. Su riqueza y diversidad de variables lo convierten en una excelente opción para generar argumentos con sustento analítico y reflexionar sobre uno de los fenómenos más relevantes de la era digital.

## Explicación de los pasos de limpieza y transformación:
### Limpieza y Transformación del Dataset

Para asegurar la calidad y consistencia del dataset seleccionado, se llevaron a cabo los siguientes pasos de limpieza y transformación:

1. **Selección de columnas relevantes**  
   Se eliminaron columnas que no aportaban valor al análisis, específicamente `ID` y `Name`, para centrar el estudio en variables de interés como edad, género, horas de uso diario, niveles de ansiedad, rendimiento académico, entre otras.

2. **Estandarización de nombres de columnas**  
   Los nombres de las columnas se transformaron a minúsculas y se reemplazaron espacios por guiones bajos para facilitar su manejo en Python y asegurar consistencia durante el análisis.

3. **Limpieza y filtrado de valores categóricos**  
   La columna `gender` se revisó para detectar inconsistencias. Se estandarizaron los valores a minúsculas y se filtraron las categorías para conservar únicamente los registros correspondientes a los géneros masculino (`male`) y femenino (`female`), eliminando otros valores para focalizar el análisis.

4. **Verificación de valores nulos y duplicados**  
   Se comprobó que no existieran valores nulos ni registros duplicados, garantizando la integridad del dataset.

5. **Validación de rangos y distribución de variables numéricas**  
   Se revisaron los rangos de las variables numéricas para asegurar que fueran coherentes con la población y contexto de estudio (adolescentes). Por ejemplo, edades entre 13 y 19 años, horas de sueño y uso de dispositivos dentro de límites plausibles.

6. **Preparación para análisis exploratorio**  
   Finalmente, el dataset limpio y transformado fue preparado para el análisis exploratorio, manteniendo variables numéricas y categóricas relevantes para la investigación sobre la adicción al teléfono móvil en adolescentes.

## Principales hallazgos del análisis:

## Insight o conclusión relevante:
