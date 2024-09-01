# AgenteViajero
metaheuristica:colonia de hormigas
Proyecto Agente Viajero - Metaheurística de Colonia de Hormigas
Este proyecto fue desarrollado como parte del curso de Análisis de Algoritmos durante el semestre 2019-02 del programa de Ingeniería de Sistemas. El objetivo principal del proyecto es implementar una solución al Problema del Viajero (TSP, por sus siglas en inglés) utilizando la Metaheurística de la Colonia de Hormigas (ACO).

Descripción del Proyecto
El Problema del Viajero es un problema de optimización combinatoria que busca encontrar el camino más corto que permite a un viajero visitar una serie de ciudades exactamente una vez y regresar a la ciudad de origen. Dado que el problema es NP-difícil, se utilizan técnicas metaheurísticas, como la Colonia de Hormigas, para encontrar soluciones aproximadas en un tiempo razonable.

Metaheurística de la Colonia de Hormigas (ACO)
El algoritmo ACO simula el comportamiento de las hormigas en la naturaleza, donde las hormigas encuentran el camino más corto entre su colonia y una fuente de alimento mediante el uso de feromonas. En este proyecto, se simula este comportamiento para resolver el TSP, donde cada hormiga construye una solución parcial y se depositan feromonas en las rutas más prometedoras, guiando a las hormigas futuras hacia soluciones óptimas.

Características del Proyecto
Entrada de Datos: El usuario ingresa el número de ciudades (vértices) y las distancias entre ellas (aristas) para generar la matriz de adyacencia del grafo.
Simulación ACO: Se configura el número de hormigas, parámetros alfa y beta que influyen en la importancia de las feromonas y la visibilidad, y la tasa de evaporación de feromonas.
Resultados: Se imprime la matriz de distancias, y se calcula el recorrido más corto aproximado encontrado por el algoritmo.
Ejecución del Proyecto
Para ejecutar el proyecto, simplemente clona el repositorio y compila los archivos Java en un entorno de desarrollo compatible (como NetBeans o Eclipse). Asegúrate de que la entrada de datos sea consistente y de ingresar valores válidos para las distancias entre las ciudades.

bash
Copiar código
# Clonar el repositorio
git clone https://github.com/tu_usuario/AgenteViajero_Metaheuristica.git

# Compilar y ejecutar el proyecto
javac AgenteViajero__Metaheuristica.java
java AgenteViajero__Metaheuristica
Requisitos
Java JDK 8 o superior
Entorno de desarrollo (NetBeans, Eclipse, IntelliJ IDEA)
Autor
Este proyecto fue desarrollado por Lightday Carrillo como parte del curso de Análisis de Algoritmos.

