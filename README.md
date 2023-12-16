# Algoritmos Búsqueda

Este proyecto, parte de la Asignatura de Sistemas Inteligentes, se enfoca en la creación de un artefacto de software para procesar archivos GraphML y establecer rutas en una ciudad visitando varios puntos de interés utilizando diferentes estrategias de búsqueda

## Descripción Detallada

El software, desarrollado en Python 3, utiliza la librería SAX para leer archivos GraphML y generar un grafo en memoria. Este grafo representa los nodos y sus aristas (longitudes), estructurándose como una lista de adyacencias para su posterior utilización en la búsqueda de rutas

### Características Principales:

- **Generación de Grafos**: Utiliza GraphML para crear un grafo en memoria, representando nodos y aristas.
- **Estrategias de Búsqueda**: Implementa varias estrategias como anchura, profundidad y costo uniforme para encontrar rutas.
- **Interfaz de Usuario**: Desarrollado con Visual Studio Code y documentado con Overleaf en Latex, facilitando la colaboración y el control de versiones a través de GitHub

## Instalación y Configuración

El código fuente está disponible en el siguiente repositorio de GitHub: [https://github.com/SI-CR/lab-b1-7](https://github.com/SI-CR/lab-b1-7)

## Guía de Uso
### Tarea 1: Generación de un Grafo en Memoria
- **Objetivo**: Nuestro objetivo en esta tarea es crear un grafo en memoria utilizando la librería SAX a partir de un fichero GraphML.
- **Funcionalidad**: Nos enfocamos en almacenar la información de los nodos y sus aristas (longitud) en una lista de adyacencias.
- **Uso de la Librería SAX**: Manejamos eventos generados durante la lectura de un documento XML para procesar el fichero GraphML de manera eficiente.
- **Procedimiento**: Importamos xml.sax en Python 3 y utilizamos distintos métodos para almacenar y posteriormente imprimir el grafo en memoria​​.
### Tarea 2: Definición del Problema
- **Establecimiento del Espacio de Estados**: Definimos variables y dominios relevantes para abordar nuestro problema.
- **Estado Inicial y Función Objetivo**: Establecemos un estado inicial y definimos la función objetivo, que determinará cuándo finaliza la búsqueda.
- **Creación del Problema**: Implementamos una función sucesora para modificar el estado mediante la acción de desplazamiento entre nodos adyacentes​​.
### Tarea 3: Algoritmo de Búsqueda
- **Implementación de Estrategias de Búsqueda**: Optamos por estrategias como la búsqueda en anchura, profundidad y costo uniforme.
- **Desarrollo de Artefactos de Búsqueda**: Creamos una frontera ordenada y un conjunto de estados visitados para nuestra búsqueda.
- **Función de Búsqueda**: Ejecutamos el algoritmo de búsqueda, comprobando si el nodo es el objetivo y si ya ha sido visitado, gestionando los sucesores y la frontera​​.
### Tarea 4: Incorporación de Estrategias Heurísticas
- **Estrategias Voraz y A***: Actualizamos la función calcularValor() para incluir estas estrategias heurísticas avanzadas.
- **Funciones Heurísticas**: Implementamos la heurística euclídea, basada en la posición de los nodos, y la heurística del arco mínimo, ambas enfocadas en estimar el costo necesario para alcanzar un estado objetivo​​.


## Autores

- Esther Camacho Caro
- Isaac González del Pozo
- Jorge Herrero Úbeda



---

Algoritmos Búsqueda - Un proyecto enfocado en la exploración y aplicación de estrategias de búsqueda avanzadas en grafos.
