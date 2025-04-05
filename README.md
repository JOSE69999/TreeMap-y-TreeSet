# Proyecto de Ejercicios con TreeMap y TreeSet en Java

## Ejercicio 1: Análisis de Frecuencia de Palabras (TreeMap)

### Descripción:
En este ejercicio se implementa un programa que lee un archivo de texto y cuenta la frecuencia de cada palabra, ordenándolas alfabéticamente.

### Instrucciones:
1. El programa lee un archivo de texto (`texto.txt`).
2. Divide el texto en palabras, ignorando puntuaciones y convirtiéndolas a minúsculas.
3. Almacena las palabras en un `TreeMap<String, Integer>`, donde la clave es la palabra y el valor es su frecuencia.
4. Imprime las palabras en orden alfabético junto con su frecuencia.

### Resultado Esperado:
El programa imprimirá las palabras en orden alfabético junto con la cantidad de veces que aparecen en el archivo de texto.

## Ejercicio 2: Rastreador de Versiones de Código (TreeMap)

### Descripción:
Este ejercicio simula un rastreador de versiones de archivos en un sistema de control de versiones utilizando un `TreeMap<Integer, String>`. La clave representa el número de versión y el valor es el contenido de esa versión del código.

### Instrucciones:
1. Permite agregar una nueva versión con una clave autoincrementada.
2. Obtener una versión específica dada su clave.
3. Obtener la última versión disponible.
4. Eliminar una versión específica si es necesario.

### Resultado Esperado:
El programa debe imprimir la versión más reciente y las versiones anteriores, mostrando el contenido de cada una.

## Ejercicio 3: Sistema de Gestión de Eventos (TreeSet)

### Descripción:
En este ejercicio se implementa un sistema para administrar eventos ordenados cronológicamente usando un `TreeSet<Evento>`. Cada evento contiene: 
- Fecha (LocalDateTime)
- Nombre (String)
- Ubicación (String)

### Instrucciones:
1. Los eventos se agregan al sistema y se ordenan automáticamente por fecha y hora.
2. Permite agregar un nuevo evento.
3. Mostrar la lista de eventos ordenados cronológicamente.
4. Obtener el próximo evento a ocurrir.
5. Eliminar automáticamente los eventos pasados después de una consulta.

### Resultado Esperado:
El programa debe mostrar el próximo evento a ocurrir y la lista de eventos ordenada por fecha y hora. Además, los eventos pasados deben eliminarse automáticamente después de la consulta.


