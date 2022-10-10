# DOCUMENTACIÓN MP4UF1

## Introducción a Markdown.
En este apartado hos mostrare toda la sintaxis y los conceptos básicos para escribir utilizando este lenguaje de marcas.

### Encabezados:
Para crear un encabezado en Markdown basta con que comiences la línea con el carácter #, deberá estar situado delante de la frase/palabra que quieres que tenga el formato de encabezado.

Ejemplos:
```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```
Vista:

![encabezados](https://cloud.google.com/static/looker/docs/images/markdown-headers-text-tiles-718.png?hl=es-419)

### Estilos de letra:
Markdown utiliza asteriscos o guiones bajos para enfatizar.

Simplemente tendrás que envolver palabras o textos en éstos símbolos para conseguir cursivas o negritas.

| Markdown | Resultado |
| ---- | ---- |
| ```*cursiva*``` | *cursiva* |
| ```_cursiva_``` | _cursiva_ |
| ```**negrita**``` | **negrita** |
| ```__negrita__``` | __negrita__ |

Por supuesto si quieres utilizar los dos tipos de énfasis no tienes más que combinar la sintaxis, envolviendo la palabra entre tres asteriscos o tres guiones bajos.

| Markdown | Resultado |
| ---- | ---- |
| ```***cursiva***``` | ***cursiva y negrita*** |
| ```___cursiva___``` | ___cursiva y negrita___ |

### Listas:

Hay 2 tipos de listas:

1. Lista Desordenadas:
    - Para crear una lista no ordenada en Markdown, puedes utilizar el signo de más, un guion o un asterisco. Con las tres opciones obtendrás el mismo resultado.
    
    Ejemplos:
    ```
    - Elemento de lista 1
    - Elemento de lista 2
    * Elemento de lista 3
    * Elemento de lista 4
    + Elemento de lista 5
    + Elemento de lista 6
    ```
    Vista:
    - Elemento de lista 1
    - Elemento de lista 2
    * Elemento de lista 3
    * Elemento de lista 4
    + Elemento de lista 5
    + Elemento de lista 6
    
    Da igual qué elemento escojas, incluso puedes intercambiarlos. Todos se verán igual al procesarse.

2. Listas Ordenadas:
    - Si lo que quieres es crear una lista ordenada, deberás introducir un número con un punto directamente después.
    
    Ejemplos:
    ```
    1. Elemento de lista 1
    2. Elemento de lista 2
    3. Elemento de lista 3
    4. Elemento de lista 4
    5. Elemento de lista 5
    6. Elemento de lista 6
    ```
    Vista:
    1. Elemento de lista 1
    2. Elemento de lista 2
    3. Elemento de lista 3
    4. Elemento de lista 4
    5. Elemento de lista 5
    6. Elemento de lista 6

3. Listas anidadas:
    - Las listas anidadas spn listas dentro de otras listas, cada lista tiene su propia numeración independiente de las otras listas, Tanto como la lista ordenadas y desordenadas se pueden anidar y combinar.
    
    Ejemplo:
    ```
    1. Elemento de lista 1
    2.  Elemento de lista 2
        - Elemento de lista 3
        - Elemento de lista 4
            1. Elemento de lista 5
            2. Elemento de lista 6
    ```

### Párrafos saltos de línea:
Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco **(pulsando dos veces intro)**

Para realizar un salto de línea y empezar **una frase en una línea siguiente dentro del mismo párrafo**, tendrás que pulsar **dos veces la barra espaciadora antes de pulsar una vez intro**.

### Códigos de bloque:
Si quieres crear un bloque entero que contenga código. Lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ```~``` o por tres ``` ` ```.

Ejemplos:
```
Puedes añadir tantas líneas y párrafos como quieras.
```

### Enlaces:
Para crear un enlace primero añadiremos el texto del link entre corchetes y posteriormente el link entre paréntesis el “texto opcional del enlace” es el texto alternativo al pasar el ratón por encima.
Ejemplo:
```
[Markdown](https://es.wikipedia.org/wiki/Markdown "Wiki Markdown")
```

Vista:

[Markdown](https://es.wikipedia.org/wiki/Markdown "Wiki Markdown")

### Imágenes
Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar links.

Solo que en este caso, deberás añadir un símbolo de ```!``` **exclamación** al principio y el **enlace** no será otro que **la ubicación de la imagen**, igual que en el link en la imagen tambien se puede poner texto alternativo que servira en caso de que la carga de la imagen fallase

Ejemplo:
```
![markdown](https://geekytheory.com/content/images/2014/03/markdown.png "Markdown")
```
Vista:

![markdown](https://geekytheory.com/content/images/2014/03/markdown.png "Markdown")
### Tablas:
Para especificar los elementos de la cabecera de cada columna deberás encerrarlos entre barras verticales ```|```, es decir:
```
| Primera columna | Segunda columna | Tercera columna |
```
Ahora deberás **crear una línea adicional debajo para especificar que los encabezados terminan**, para crear una línea similar a la anterion pero escribiendo guiones ```---```.
```
| Cont1 | Cont2 | Cont3 |
| --- | --- | --- |
```

Tambien en esta linea se puede especificar por donde va ha empezar el texto:

Ejemplo:
```
| Encabezado1 | Encabezado2 | Encabezado3 |
| :--- | :---: | ---: |
| cont1 | cont2 | cont3 |
```
Vista:
| Encabezado1 | Encabezado2 | Encabezado3 |
| :-- | :---: | --: |
| cont1 | cont2 | cont3 |

Las filas de contenido se crean **exactamente igual que la línea de cabecera**, pero Markdown es capaz de diferenciarlo gracias a la sintaxis que acabas de utilizar en el paso anterior:

Ejemplo:
```
| Primera columna | Segunda columna | Tercera columna |
| --- | --- | --- |
| Contenido 1-1 | Contenido 1-2 | Contenido 1-3 |
| Contenido 2-1 | Contenido 2-2 | Contenido 2-3 |
| Contenido 3-1 | Contenido 3-2 | Contenido 3-3 |
```
Vista
| Primera columna | Segunda columna | Tercera columna |
| --- | --- | --- |
| Contenido 1-1 | Contenido 1-2 | Contenido 1-3 |
| Contenido 2-1 | Contenido 2-2 | Contenido 2-3 |
| Contenido 3-1 | Contenido 3-2 | Contenido 3-3 |

## Introducción a GitHub.
Es una de las principales plataformas para crear proyectos abiertos de herramientas y aplicaciones, github es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador.

### Comandos utilizados en la UF1
#### Git Clone:
Se utiliza para copiar un repositorio Git existente en un nuevo directorio local. El comando de clonación de Git creará un nuevo directorio local para el repositorio, copiará todo el contenido del repositorio especificado.

[Tutorial de como clonar](https://techobservatory.com/how-to-clone-a-github-repository-in-visual-studio-code/)
![Github+git+visual](https://i.ytimg.com/vi/lYiE5lBS13E/maxresdefault.jpg)

#### Git add . y Git commit -m:
El comando git add **añade un cambio del directorio de trabajo en el entorno de ensayo**. De este modo, indica a Git que quieres incluir actualizaciones en un archivo concreto en la próxima confirmación.

El comando git commit captura una instantánea de los cambios realizados actualmente en el proyecto. Las instantáneas comprometidas se pueden considerar como versiones "seguras" de un proyecto: Git nunca las cambiará a menos que se lo solicite explícitamente.

Página web donde explica a fondo todo sobre [Git add . y Git commit -m](https://www.atlassian.com/es/git/tutorials/saving-changes#:~:text=sobre%20git%20ignore%20.-,git%20add,concreto%20en%20la%20pr%C3%B3xima%20confirmaci%C3%B3n.)
![gitAdd](https://code4all.mx/wp-content/uploads/2019/05/git-areas.png)

#### Git push:
El comando **git push** se usa para cargar contenido del repositorio local a un repositorio remoto. El envío es la forma de transferir confirmaciones desde tu repositorio local a un repositorio remoto.

Link para mas informacion sobre [git push](https://www.atlassian.com/es/git/tutorials/syncing/git-push)

![gitPush](https://miro.medium.com/max/1232/1*HJx_4MCxp0ghLWtTIjH9RQ.jpeg)


## Introducción a HTLM.
Es el componente más básico de la Web. Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript).

