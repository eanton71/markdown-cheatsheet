 
Titulo 
===
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

> Cita en uno o varios parrafos (blockquote). **Espacio, Espacio, Enter**  
segunda linea
>> cita anidada  
````
> Cita  

> Cita en uno o varios parrafos (blockquote).  
segunda linea
>> cita anidada
>>> subcita anidada
>
> retorno

>sdgdg
# Listas
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
```markdown
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

- [x] comprar pan
- [x] ir al supermercado 
  - [x] comprar tomates
- [ ] comprar loteria




# lineas horizontales
````markdown
***
---
___

````
***
---
___


# emfasis   
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

Some text with [a link][1] and  
another [link][2]
[1]: http://example.com/ "Title"
[2]: http://example.org/ "Title"

[un enlace a otro lugar][otro lugar].  
[otro enlace más][otro-enlace].  
Y de nuevo regresamos al [primer enlace][otro lugar].  

[otro lugar]: www.github.com  
[otro-enlace]: www.google.com  

¿Quiere ver [algo divertido][un lugar divertido]?
Bien, tengo [el sitio web para usted][otro sitio divertido]!
[un lugar divertido]:(www.zombo.com)
[otro sitio divertido]:(www.stumbleupon.com)


## Codigo
````
bloque de codigo
otra linea
````
Imprimir una linea en java``System.out.println("Hola Facundo")``

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
```python
def foo():
    if not bar:
        return True
````

## Tablas

cabecera     | otro
------------ | -------------
celda 1,2    | celda 2,1 
celda 1,2    | celda 2,2

## Imagenes   
 
 
![Texto alternativo|100px x 100px](https://github.com/eanton71/markdown-cheatsheet/blob/master/IMG_20200224_161708.jpg)

 


## HTML
# elemento colapsable
<details>
  <summary>Abrir</summary>
  
>Con cien cañones por banda  
viento en popa a toda vela

</details>

## Referencias
https://markdown.es/sintaxis-markdown
   
