Titulo: NumPy: analisis numerico eficiente con Phyton

# Numpy_1
Crear arrays con secuencias numéricas.
Cargar archivos.
Verificar las dimensiones de un array.
Realizar la transposición de un array.
Matrices

# Numpy_2
Al igual que los vectores, las matrices son estructuras de datos que representan múltiples valores relacionados. Una tabla de datos se puede representar mediante una matriz. 
 Las matrices 3D tienen aplicaciones más avanzadas, como el procesamiento de imágenes, el trabajo con animaciones y la modelización matemática.
 Siempre escribimos primero el número de filas y luego el número de columnas. Estos números son importantes porque para operaciones como la suma y la multiplicación, las dimensiones de las matrices deben ser compatibles. Solo podemos sumar matrices con el mismo número de filas y columnas. Para que la multiplicación sea posible, el número de columnas de la primera matriz debe ser igual al número de filas de la segunda.
 Aprendi: Realizar selecciones dentro de arrays, Construir gráficos utilizando Matplotlib, Comparar arrays., Verificar la existencia de NaNs.

# Numpy 3 Operaciones entre arrays
## Diferencia entre arrays
📌 Cálculo de la suma de errores cuadráticos
  Se utiliza la expresión np.sum(np.power(Moscu - y, 2)) para calcular la suma de los errores al cuadrado entre dos arreglos numéricos:
  Moscu: valores reales (observados).
  y: valores estimados por un modelo.
  Este cálculo consiste en:
  Obtener la diferencia entre los valores reales y estimados.
  Elevar al cuadrado cada diferencia (para evitar cancelaciones entre errores positivos y negativos).
  Sumar todos los errores al cuadrado.
  Este valor se conoce como suma de errores cuadráticos (o residuos al cuadrado) y es un indicador clave para evaluar la calidad de un modelo, especialmente en regresión. Cuanto menor sea, mejor es el ajuste del modelo a los datos reales.
En Numpy 3 aprendimos: Realizar operaciones entre arrays.Calcular la norma entre dos arrays. Implementar la regresión lineal.
# Numpy 4
Generar secuencias de números aleatorios.
Garantizar la reproducibilidad de resultados.
Agrupar arrays.
Guardar archivos.
