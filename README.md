# objetos_js
## intervalos de tiempo 
### Principales propiedades y métodos de los intervalos de tiempo en JavaScript:

1. setInterval(función, tiempo): Este método se utiliza para ejecutar una función de manera repetitiva cada cierto intervalo de tiempo especificado en milisegundos.

2. clearInterval(id): Se utiliza para detener la ejecución de un intervalo de tiempo específico identificado por su ID. Es importante detener los intervalos de tiempo una vez que ya no son necesarios para evitar fugas de memoria y un uso ineficiente de recursos.

3. Precisión: Los intervalos de tiempo en JavaScript no son precisos debido al modelo de ejecución asíncrona del lenguaje. Por lo tanto, no se debe depender de ellos para tareas críticas que requieran una precisión milimétrica.

4. Retrasos y superposiciones: Es importante tener en cuenta que si el tiempo de ejecución de una función en un intervalo es mayor que el intervalo mismo, se pueden producir solapamientos y retrasos en las ejecuciones posteriores.

5. Uso responsable: Se recomienda utilizar los intervalos de tiempo con moderación y de manera consciente para no sobrecargar el navegador con múltiples tareas en segundo plano.

6. Alternativas: En casos donde se requiera mayor precisión y control sobre el tiempo de ejecución, se pueden utilizar funciones como requestAnimationFrame o setTimeout para lograr resultados más eficientes en términos de rendimiento.

