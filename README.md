# MachineLearning
Uso de modelo XGBClassifier para predecir valores de un parámetro relacionado con la memoria. Se utilizó GridSearchCV para encontrar los mejores hiperparámetros.
Dentro del file 'requisitos' están las librerias utilizadas como sus versiones.

## Distribución de cuantiles
Para definir los rangos de manera más uniforme posible se utilizaron cuantiles en lugar de rangos definidos. Despúes de probar distintas combinaciones se obtuvo que el mejor resultado es el establecido en el código. 

## Entrenamiento
Se encontró la mejor semilla para realizar un train split (nota importante) y se mostró una matriz de confusión en la cual se puede observar que no hay ningún dato predecido en el grupo 3. De igual manera, se obtuvo que la precisión del modelo fue del 50%. 

## Resultados
Inclusive teniendo los mejores hiperparámetros, la mejor semilla para la distribución de train split y una precisión del 50% al momento de predecir valores de prueba no se logró predecir ningún dato dentro del grupo 3. Esto se puede apreciar en los últimos dos bloques de código.

## Nota importante
No hace falta correr todo el codigo, ya que, en el bloque 22 se utilizó una busqueda O(n) de la mejor semilla para distribuir los datos la cual toma mucho tiempo. Esta semilla ya se estableció, por lo que, se recomienda no correr esa parte del código.  
