Para los encabezados usamos # y un espacio junto al texto que queramos:
# ENCABEZADO DE NIVEL 1
## ENCABEZADO DE NIVEL 2
###### ENCABEZADO DE NIVEL 6

Con tres guiones bajos generamos una separación con una linea continua como la siguiente (también es válido tres asteriscos o tres guiones):
___

## LISTAS
### LISTAS DESORDENADAS
Con los símbolos -, *, ó + generamos listas desordenadas:
- elemento lista 1
* elemento lista 2
+ elemento lista 3

y para anidar únicamente añadimos cuatro espacios en blanco (o tabular) delante de - * ó +
- elemento 4
    - elemento anidado a 4


### LISTAS ORDENADAS
Para crear una lista ordenada es "numero. ":
1. elemento ordenado 1
2. elemento ordenado 2
    + elemento anidado
___
## BLOQUE DE CÓDIGO
Encerrar el código entre ~~~~
~~~~
Aquí va el bloque con el código
~~~~
___
## MARCADO
Para crear un fragmento de texto se usa >

> Esto es un fragmento

>Este es otro fragmento

Estamos fuera

---
## NEGRITAS Y CURSIVAS
Se emplean asteriscos o guiones bajos

*Con un guión bajo o asterisco delante y detrás obtenemos cursiva*

**Con dos guiones bajos o asteriscos delante y detrás obtenemos negrita**

***Con tres guiones bajos o asteriscos delante y detrás obtenemos cursiva y negrita***

___

## ENLACES

El texto del vínculo entre corchetes [] y el link entre paréntesis

> [mi gitHub](https://github.com/JuanJoseSenit?tab=repositories)

Si lo que quieres es mostrar el link directamente se sitúa entre <>

> <https://github.com/JuanJoseSenit?tab=repositories>

___
## IMÁGENES

Sigue una nomenclatura muy similar a los enlaces, sólo que se debe incluir el símbolo de exclamación ! al principio, y lo que va entre paréntesis la ruta a la imagen

> ![Aquí no hay ruta a imagen](/ruta/imagen.jpg)

Lo que va entre corchetes es el mensaje en caso de que la carga de la imagen falle

___
## TABLAS
Para elaborar una tabla:

1. Se emplean \| para separar las columnas y salto de linea para adicionar filas
2. La primera fila es la cabecera, la segunda fila tiene una estructura como:
 | - | - | - | donde en número de guiones son el número de columnas de la tabla y a partir de la tercera fila son los campos de la tabla

| Proyecto | GitHub |
| - | - |
| Cuatro en raya | <https://github.com/JuanJoseSenit/CuatroEnRaya> |
| Landing page | <https://github.com/JuanJoseSenit/Landing-Page-Js> |


___
## ANULAR MARKDOWN
Si quieres usar los símbolos sin que Markdown los interprete basta con emplear \
> *cursiva*

> \*anulo la cursiva usando \ \*






    


