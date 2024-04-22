# objetos_js
## intervalos de tiempo 
### Principales propiedades y métodos de los intervalos de tiempo en JavaScript:

Un intervalo de tiempo en JavaScript es una función que se ejecuta repetidamente después de un intervalo de tiempo especificado. Se utiliza principalmente con el método setInterval(), que toma una función y un tiempo en milisegundos como argumentos, y la función se ejecuta continuamente a ese intervalo hasta que se detiene explícitamente con clearInterval(). Esto es útil para realizar tareas repetitivas, como actualizaciones periódicas de contenido o temporizadores.

1. `intervalID`: Es el identificador devuelto por la función setInterval(). Este identificador se utiliza más tarde para detener el intervalo de tiempo usando clearInterval().

2. `setInterval`(función, tiempo): Este método se utiliza para ejecutar una función de manera repetitiva cada cierto intervalo de tiempo especificado en milisegundos.

3. `clearInterval`(id): Se utiliza para detener la ejecución de un intervalo de tiempo específico identificado por su ID. Es importante detener los intervalos de tiempo una vez que ya no son necesarios para evitar fugas de memoria y un uso ineficiente de recursos.

4. `Precisión`: Los intervalos de tiempo en JavaScript no son precisos debido al modelo de ejecución asíncrona del lenguaje. Por lo tanto, no se debe depender de ellos para tareas críticas que requieran una precisión milimétrica.

5. `Retrasos y superposiciones`: Es importante tener en cuenta que si el tiempo de ejecución de una función en un intervalo es mayor que el intervalo mismo, se pueden producir solapamientos y retrasos en las ejecuciones posteriores.

6. `Uso responsable`: Se recomienda utilizar los intervalos de tiempo con moderación y de manera consciente para no sobrecargar el navegador con múltiples tareas en segundo plano.

7. `Alternativas`: En casos donde se requiera mayor precisión y control sobre el tiempo de ejecución, se pueden utilizar funciones como requestAnimationFrame o setTimeout para lograr resultados más eficientes en términos de rendimiento.

