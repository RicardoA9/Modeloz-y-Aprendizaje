# Modeloz-y-Aprendizaje
Trabajo Final

El trabajo presente contiene el código para aplicar 4 algoritmos de aprendizaje,Com son Smote (Técnica de Sobremuestreo de Minorías Sintéticas) , Random Forest, K-Nearest Neighbors (KNN) y Artificial Neural Networks (ANN), al conjunto de datos de cáncer de mama de Wisconsin .
El objetivo es predecir si una masa mamaria es maligna o benigna basándose en los datos proporcionados en la muestras, área y textura entre otro componente obtenido para el dataset trabajado.

Conjunto de datos
El conjunto de datos de cáncer de mama contiene 569 instancias con 31 características numéricas. 
Conclusión
Se proporciona un estudio y análisis del cáncer de mama en la región de Wisconsin donde se evalúa y compara mediante diferentes modelos de aprendizaje los falsos positivos y negativos que se encontró y una precisión y predicción de los resultados obtenidos.
1.	Los resultados obtenidos con Random Forest nos da una precisión de 0.9580 el cual es un acierto a los casos de cáncer detectado por área y textura.Mientras tanto en el modelo KNN se procede a ver que el entrenamiento dio como resultado 0.9780 y el test de 0.9649.
2.	KNN se implementa con k=5 mientras que ANN tiene 2 capas ocultas de 16 neuronas cada una. Estas cosas elementales están sujetas a cambios.
3.	Los mismos datos, se dividen en entrenamiento y pruebas, y se generan las puntuaciones correspondientes, matrices de confusión y errores. Se han mostrado algunas de las visualizaciones de datos.
4.	Los datos se han escalado para ambos, y se han normalizado, para obtener resultados óptimos. Se está produciendo un área más alta bajo la curva ROC para ANN.
5.	Por lo tanto, el modelo ANN tiende a funcionar mejor que KNN para conjuntos de datos complejos como el conjunto proporcionado en este trabajo.
