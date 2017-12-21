## FILTROS AL ng-repeat

1. Crear una tabla en la vista que utilice la directiva `ng-repeat`

2. LLenar la tabla con los datos del arreglo  de objetos `personas`

~~~
Añadir filtro
~~~

3. Añadir una entrada de texto para filtrar el contenido de la tabla

4. Añadir el comando `filter:nombre` a la tabla

5. Añadir otra condicion de busqueda `sexo`

6. Modificar el valor de las opciones `ng-model` : `busqueda.nombre` y `busqueda.sexo`

7. Modificar el comando `filter:busqueda` (filtro por busqueda)

## ORDER BY - EN FILTROS Y ng-repeat

1. Ordenar la tabla de manera ascedente (nombre)
    - `orderBy:'nombre'`

2. Ordenar la tabla de manera descentente (nombre)
    - `orderBy:'-nombre'`

3. Crear una clase dentro de la etiqueta `estilos`

4. Añadir la directiva `ng-click` a la columna `nombre`
    - `reverse = !reverse`

5. Definir si es ascendente o descentente al hacer clic en la cabecera de la columna
    - `orderBy:'nombre':reverse`

6. Definir que columna es en cada cabecera
    - `columna='nombre';`
    - `columna='sexo';`

7. Modificar el filtro (ordernar)
    - `orderBy:columna:reverse`
