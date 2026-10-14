# A4 MARKDOWN

>ENCABEZADOS

2. Encabezados en Markdown

En Markdown, los encabezados se crean utilizando el símbolo #. El número de almohadillas determina el nivel del encabezado, desde # (nivel 1) hasta ###### (nivel 6). 

# Encabezado de nivel 1

## Encabezado de nivel 2

### Encabezado de nivel 3

#### Encabezado de nivel 4

##### Encabezado de nivel 5

###### Encabezado de nivel 6

Por qué utilizar una estructura jerárquica?

Los encabezados deben organizarse según la jerarquía del contenido, y no simplemente según el tamaño visual que queramos obtener. Por ejemplo, # debe utilizarse para el título principal, mientras que ## y ### sirven para dividir el contenido en secciones y subsecciones.

Esta estructura facilita que el documento sea más claro y accesible, y permite que herramientas como los lectores de pantalla y los índices automáticos comprendan correctamente la organización de la información.

>PÁRRAFOS

3. Párrafos En Markdown 

Los párrafos se escriben simplemente como texto normal. Para separar dos párrafos, se debe dejar una línea en blanco entre ellos.


Este es el primer párrafo. Markdown permite escribir
texto de forma sencilla y clara.

Este es el segundo párrafo. Al dejar una línea en blanco
entre ambos, Markdown los interpreta como párrafos diferentes.


Explicación

La línea en blanco es importante porque indica que comienza un nuevo párrafo. Si simplemente hacemos un salto de línea sin dejar una línea vacía, Markdown puede interpretar el texto como parte del mismo párrafo, dependiendo del procesador Markdown utilizado.

>FORMATO DE TEXTO

Markdown permite aplicar diferentes formatos al texto utilizando símbolos sencillos.

.**negrita**

.*cursiva*

.***negrita y cursiva***

.~~tachado~~

>LISTAS

A continuación se muestran los diferentes tipos de listas que se pueden utilizar en Markdown

Lista no ordenada
- Elemento 1
- Elemento 2
- Elemento 3

 Lista ordenada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

Lista anidada
- Frutas
  - Manzana
  - Plátano
- Verduras
  - Zanahoria
  - Tomate

Lista de tareas
- [x] Tarea completada
- [ ] Tarea pendiente
- [x] Revisar el documento
- [ ] Entregar el trabajo

>ENLACES

En Markdown, los enlaces se crean colocando el texto descriptivo entre corchetes [ ] y la URL entre paréntesis ( ). 

[Haz click aqui para ver el futbol](https://www.marca.com/)

>IMÁGENES

Documenta cómo insertar una imagen almacenada dentro del propio proyecto.

Primero debes de guardar la foto dentro de la carpeta o directorio en el cual tengas el trabajo y despues poner este código.

![Captura de la actividad](images/captura.png)

Poniendo el nombre de la foto entre parentesis, pero solo saldra lo que esta entre los corchetes sino pones ninguna foto.

Utiliza una de las capturas realizadas durante esta actividad y guárdala dentro del directorio:

![Captura de la actividad](FOTOGRAO.png)

Texto alternativo: 

Sirve para describir brevemente el contenido de la imagen. Es importante para la accesibilidad, especialmente para personas que utilizan lectores de pantalla, y también se muestra si la imagen no puede cargarse.

>CITAS

Cita sencilla:
> Esta es una cita sencilla.

Cita formada por varias líneas:
> Esta es la primera línea de la cita.
>
> Esta es la segunda línea de la cita.
>
> Y esta es la tercera línea.

>CÓDIGO EN LÍNEA

Para incluir código dentro de una frase en Markdown, se utilizan comillas invertidas simples: `.

Ejecuta el comando `pythonarchivo.py` desde la ruta `/home/usuario/proyecto`.

>BLOQUES DE CÓDIGO

# 10. Bloques de código

Los bloques de código permiten mostrar fragmentos de código conservando
su formato y facilitando su lectura.

## Bash

```bash
#!/bin/bash
echo "Hola mundo"
```

## JavaScript

```javascript
const saludo = "Hola mundo";
console.log(saludo);
```

## Texto sin formato

```
Este es un bloque de texto
sin ningún lenguaje especificado.
No se aplica resaltado de sintaxis.
```

## Efecto de indicar el lenguaje

Al escribir el nombre del lenguaje después de los tres caracteres
` ``` ` iniciales, Markdown puede aplicar resaltado de sintaxis.

Por ejemplo:

```javascript
const nombre = "Ana";
console.log(`Hola, ${nombre}`);
```

![alt text](image.png)


>TABLAS

| Herramienta | Función | Ejemplo de uso |
|---|---|---|
| ChatGPT | Generación de texto | Crear explicaciones |
| Markdown | Formato de texto | Crear tablas y listas |
| Canva | Diseño gráfico | Crear presentaciones |


>LÍNEA HORIZONTAL 

En Markdown se puede crear una línea horizontal utilizando tres o más guiones, asteriscos o guiones bajos.

---

>CARACTERES ESPECIALES

Algunos caracteres tienen un significado especial en Markdown. Para mostrarlos literalmente se puede utilizar una barra invertida delante del carácter. Esto se conoce como escape.

1. Asterisco *
Problema encontrado: *texto* se interpreta como texto en cursiva.

Código utilizado:

\*texto\*

Resultado obtenido: *texto*

2. Guion bajo _
Problema encontrado: _texto_ se interpreta como texto en cursiva.

Código utilizado:

\_texto\_

Resultado obtenido: _texto_

3. Almohadilla #
Problema encontrado: # Título se interpreta como un encabezado.

Código utilizado:

\# Título

Resultado obtenido: # Título

La barra invertida \ permite indicar a Markdown que el carácter que viene después debe mostrarse literalmente y no interpretarse como parte de la sintaxis.


---


![Captura de la actividad](1.png)
![Captura de la actividad](2.png)
![Captura de la actividad](3.png)
![Captura de la actividad](4.png)
![Captura de la actividad](5.png)
![Captura de la actividad](6.png)
