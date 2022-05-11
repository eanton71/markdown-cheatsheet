 
<style>
  img {width: 300px}
</style>

1. Markdown cheatsheet    
===

- [1. Markdown cheatsheet](#1-markdown-cheatsheet)
  - [1.1. Parrafos](#11-parrafos)
  - [1.2. Encabezados](#12-encabezados)
- [Header 1](#header-1)
- [Header 1](#header-1-1)
  - [Header 2](#header-2)
    - [Header 3](#header-3)
      - [Header 4](#header-4)
        - [Header 5](#header-5)
          - [Header 6](#header-6)
- [Header 1](#header-1-2)
- [Header 1](#header-1-3)
  - [Header 2](#header-2-1)
    - [Header 3](#header-3-1)
      - [Header 4](#header-4-1)
        - [Header 5](#header-5-1)
          - [Header 6](#header-6-1)
  - [3.2. Citas](#32-citas)
  - [3.3. Listas](#33-listas)
    - [3.3.1. Desordenadas](#331-desordenadas)
    - [3.3.2. Ordenadas](#332-ordenadas)
  - [3.4. Tablas](#34-tablas)
  - [3.5. Imagenes](#35-imagenes)
  - [3.6. HTML](#36-html)
    - [3.6.1. elemento colapsable](#361-elemento-colapsable)
  - [3.7. Referencias](#37-referencias)
 
## 1.1. Parrafos
````markdown
Esto es un parrafo. Enter, Enter ...

Otro parrafo. Espacio, Espacio.  
Salto de linea en un parrafo.  
````
Esto es un parrafo.  

Otro parrafo.  
Salto de linea en un parrafo.   


## 1.2. Encabezados 
Para encabezados 1 es valido # o = debajo del texto. Para encabezados 2: ## o - debajo del texto

````markdown
# Header 1
Header 1
=
## Header 2
Header 2
- 
### Header 3
####  Header 4
#####  Header 5 
######  Header 6 
````
# Header 1
Header 1
=
## Header 2
Header 2
- 
### Header 3
####  Header 4
#####  Header 5 
######  Header 6  

## 3.2. Citas
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
## 3.3. Listas
### 3.3.1. Desordenadas
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
### 3.3.2. Ordenadas
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
~~tachado~~ 
````
*cursiva*  
_cursiva_  
**negrita**  
__negrita__  
***cursiva y negrita***  
~~tachado~~ 

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
 
## 3.4. Tablas

````
   | 1ª col | 2ª col |
   | ------ | ------ |
   | 1,1    | 2,1    |
   | 1,2    | 2,2    |
````

   | 1ª col | 2ª col |
   | ------ | ------ |
   | 1,1    | 2,1    |
   | 1,2    | 2,2    |
````
|           | Alineacion |         |
| :-------- | :--------: | ------: |
| izquierda |   centro   | derecha |
| 1,1       |    2,1     |     3,1 |
| 1,2       |    2,2     |     3,2 |
````
|           | Alineacion |         |
| :-------- | :--------: | ------: |
| izquierda |   centro   | derecha |
| 1,1       |    2,1     |     3,1 |
| 1,2       |    2,2     |     3,2 |

## 3.5. Imagenes   

````
![Texto alternativo](https://github.com/eanton71/markdown-cheatsheet/blob/master/IMG_20200224_161708.jpg)
````
 
![Texto alternativo](https://github.com/eanton71/markdown-cheatsheet/blob/master/IMG_20200224_161708.jpg)


 


## 3.6. HTML   
### 3.6.1. elemento colapsable   

<details>
  <summary>Abrir</summary>
  
>Con cien cañones por banda  
viento en popa a toda vela

</details>

## 3.7. Referencias
https://markdown.es/sintaxis-markdown  
https://daringfireball.net/projects/markdown/  
https://www.markdowntutorial.com/es   
