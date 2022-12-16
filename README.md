### Red Neuronal Clasificacion Ropa:

##Datos:
- Se usará un dataset facilitado por Zalando en Github con 70000 datos de imagenes cada una clasificada en 10 tipos diferentes de prendas. 

##Red Neuronal:
- Tipo de Red neuronal convolucional para clasificación de imagenes
- Las imagenes las detecta clasificando por la forma que le hace reconocer los colores de los pixeles de las imagenes, descubriendo patrones y similitudes. 
- Para que no sea tan grande la red neuronal y debido a la media complejidad del problema le bajaremos la resolucion a las imagenes y dejaremos con 28*28 pixeles en gama monocromática: blanco y negro. Entre estos dos colores se encuentra una gama entera grises donde a cada pixel en funcion de su color se le asigna un valor entre 0 y 255, siendo 0 el color puramente negro y 255 totalmente blanco, esto hará que la red detecte el patron de la forma de cada tipo de prenda. 
- Input: 784 neuronas de entrada (28x28)
- Output: 10 neuronas de salida: tipos de prenda que existen a clasificar (camiseta, pantalon, abrigo, etc...)
- 2 capas ocultas -> 50 neuronas cada una
- Del dataset de Zalando tendremos 60000 datos / imagenas para entrenar y 10000 para testear los resultados.

##Resutados:
- Una red neuronal con un 90% de precisión
