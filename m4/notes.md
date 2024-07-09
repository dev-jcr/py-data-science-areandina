# Unidad 1
Instalación de librerias
    numpy
    pandas
    scikit-learn
Procesamiento de datos con
    numpy
        métodos
            array
                contiene argumentos para crear vector con datos proporcionados
                    soporta indexado
                crear una matriz de datos
                    import numpy as np
                    matriz = np.array([[3,5,8], [2,4,7], [1,3,6]])
            álgebra lineal
                linalg
                    método .inv()
                        importar
                            from numpy import linalg
            números aleatorios
                random
                    random.randint(100)
                        entero aleatorio entre 100
                    randint() para vectores
                        random.randint(10, size=(5))
                            p. ej.
                                [4 4 1 8 3]
                        random.randing(10, size=(3,7))
                            p. ej.
                                [
                                [9 9 8 0 2 4 1]
                                [8 6 5 1 6 3 7]
                                [5 0 3 5 8 6 8]
                                ]
                    .rand()
                        devuelve aleatorio entre 0.0 y 1.0
                

