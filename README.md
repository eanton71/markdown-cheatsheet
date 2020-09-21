 
Titulo 
===
## Indice
## Parrafos
````markdown
Esto es un parrafo. Enter, Enter ...

Otro parrafo. Espacio, Espacio.  
Salto de linea en un parrafo.  
````
Esto es un parrafo.  

Otro parrafo.  
Salto de linea en un parrafo.   


## Encabezados
Para encabezados 1 es valido # o = debajo del texto. Para encabezados 2: ## o - debajo del texto
````markdown

# Header 1  
Header 1
=
## Header 2
Header 2
- 
### Header 3
#### Header 4
##### Header 5 
###### Header 6 
````
# Header 1  
Header 1
=
## Header 2
Header 2
- 
### Header 3
#### Header 4
##### Header 5 
###### Header 6 

# Citas
````markdown
 

> Cita  

> Cita en uno o varios parrafos (blockquote).  Espacio, Espacio, Enter  
segunda linea
>> cita anidada
>>> subcita anidada
>
> retorno 
````
> Cita  

> Cita en uno o varios parrafos (blockquote).  
segunda linea
>> cita anidada
>>> subcita anidada
>
> retorno 
## Listas
### Desordenadas
````markdown
* una 
- otra
+ otra mas
  + subitem. doble espacio o tab
    * subsubitem
* otro 
````
* una 
- otra
+ otra mas
  + subitem  
    * subsubitem
* otro 
### Ordenadas
```markdown
1. Item 1  
2. Item 2  
3. Item 3  
    1. Item 3a  
    2. Item 3b  
        1. item 3ba  
        2. item 3bb  
    3. item 3c 
    4. item 3d  
4. item 4
````
1. Item 1  
1. Item 2  
1. Item 3  
    1. Item 3a  
    1. Item 3b  
        1. item 3ba  
        1. item 3bb  
    1. item 3c 
    1. item 3d  
1. item 4
### Listas de tareas
````
- [x] comprar pan
- [x] ir al supermercado 
  - [x] comprar tomates
  - [ ] comprar pimientos
- [ ] comprar loteria
````
- [x] comprar pan
- [x] ir al supermercado 
  - [x] comprar tomates
  - [ ] comprar pimientos
- [ ] comprar loteria




# Lineas horizontales
````markdown
***
---
___

````
***
---
___


# Enfasis   
````markdown
*cursiva*  
_cursiva_  
**negrita**  
__negrita__  
***cursiva y negrita***  
~~this~~ 
````
*cursiva*  
_cursiva_  
**negrita**  
__negrita__  
***cursiva y negrita***  
~~this~~ 

# Enlaces  
````markdown
http://www.enlace.com  
<http://www.enlace.com>  
[texto que se muestra](http://www.enlace.com)  

````
http://www.enlace.com  
<http://www.enlace.com>  
[texto que se muestra](http://www.enlace.com)  

````markdown
Enlace por referencia [mi enlace][1].Espacio, Espacio  
El mismo enlace [el mismo enlace][1].Espacio, Espacio, Enter

[1]: http://enlace.com
````
Enlace por referencia[enlace] [1].  
[el mismo enlace] [1].  

[1]: http://enlace.com 

 
````
[un enlace a otro lugar][otro lugar].  
[otro enlace más][otro-enlace].  
Y de nuevo regresamos al [primer enlace][otro lugar].  

[otro lugar]: www.github.com  
[otro-enlace]: www.google.com
````
[un enlace a otro lugar][otro lugar].  
[otro enlace más][otro-enlace].  
Y de nuevo regresamos al [primer enlace][otro lugar].  

[otro lugar]: www.github.com  
[otro-enlace]: www.google.com  

 
 
 
## Codigo
Abriendo y cerrando con ````  
````markdown 
bloque de codigo  
otra linea 
````  
Mostrar una linea de codigo en un texto: `System.out.println("Hola Facundo")`  
Se puede indicar el lenguaje: \````javascript, \````python, etc...

```javascript
function alerta(arg) {
  if(arg) {
    document.getElementById("id1").innerHTML = "Hola!";
  }
}
```
```python
def negativo(arg):
    if arg < 0 :
      return True
```
 
## Tablas
````
*cabecera  izquierda*   | cab. derecha
------------ | -------------
celda 1,1    | celda 2,1 
celda 1,2    | celda 2,2
````

**cabecera  izquierda**   | cab. derecha
------------ | -------------
celda 1,1    | celda 2,1 
celda 1,2    | celda 2,2

## Imagenes   

````
![Texto alternativo](https://github.com/eanton71/markdown-cheatsheet/blob/master/IMG_20200224_161708.jpg)
````
 
![Texto alternativo](https://github.com/eanton71/markdown-cheatsheet/blob/master/IMG_20200224_161708.jpg)


 


## HTML
# elemento colapsable
<details>
  <summary>Abrir</summary>
  
>Con cien cañones por banda  
viento en popa a toda vela

</details>

## Referencias
https://markdown.es/sintaxis-markdown
   
