# Búsqueda

Comparación entre dos algoritmos de búsqueda: 
- Ramificación y acotación.
- Ramificación y acotación con subestimación.

Creamos dos clases nuevas en utils.py partiendo de la clase FIFOQueue():

- babg: Modificamos el método extend añadidiendo la ordenación de la lista por el path_cost.

- babs Modificamos el método extend añadidiendo la ordenación de la lista por la suma del path_cost junto con de la heurística dada en la clase problem.

En el fichero search.py añadimos las funciones:
- bab(problem)
- babs_search(problem)

# Clasificador de Legos

Se ha utilizado el dataset de legos de [Kaggle](https://www.kaggle.com/joosthazelzet/lego-brick-images).

Consiste en ser capaz de diferenciar entre 5 clases distintas de legos:
- 2357 Brick corner 1x2x2
- 3003 Brick 2x2
- 3004 Brick 1x2
- 3005 Brick 1x1
- 3022 Plate 2x2
