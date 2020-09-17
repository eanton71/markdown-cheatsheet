This is [an example][id] reference-style link.  
[id]: http://example.com/  "Optional Title Here"

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

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item




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
Enlace por referencia [mi enlace][web].  
El mismo enlace [el mismo enlace][web].  
[web]: http://enlace.com
````
Enlace por referencia[enlace] [1].
[el mismo enlace] [1].
[1]: http://enlace.com 

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
````
bloque de codigo
otra linea
````
``linea de codigo``
## Tablas
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
## Imagenes  
![desde la carretera](https://lh3.googleusercontent.com/EL6Wful2E1AmqAQKZ_nd15APIkvZCOvl-5P8Keqv55fhjj-QkkeZNCmomqqAnlUs8MiQiW-AGK5Gmx2D70OjnY-ZV4Eqx5Ns6GuA5xwDF97Nh8eiOj3QmDiyaKCPli9bxYHETrFbeirhFRcCJOWAFzFW7WcY86gI0JbD8Y8_7J_tOxRXTh25fFL8vZ-DZaGhE53OzroJn2SiRc3z26QufMpwn4PRvCGgrQUH93Kb8ozllsPTTsEh_vFWxxHJpWcyboku28OSpdNtWe28E1qJcq4v_jNGjEgODoVPWMafnWhX2j6Mqjs0C_9Tpew7R0TYnCLhLZQnVvme-QyJPcB4cwoXeiGVMrXOwq8QbgAmzuRehaFg0-cjVwaygP4zb3DRWQGMOAgMC1CdQ0BTgNYvHqaD4T373XyBwtsY3-X12ZilW9_vz8EkJGbvb8CNgWnvJ4DbUN96CUZdknsJuN63lOi1e3dl-H27NvPhh9PqobchKnCHYLZxsWTFqamoYrs-2xY-KTELqhqEV2KdhiyxxMTJBh8Xvm2ieaPOnTADC8cmE766LSSByAyraNjsD1MeL8eZMGJl5DS_c0WZBs4qspBc4cBujU4ySmvNDUjg0D1qUngBCNYf2k4La3U_TAS94CXAlTAvxeJ3_IJFbWk0Uuyj1-2oJZ_5o8dAPPFii6js3bTX_WdIdBAZ0LLxng=w1168-h657-no?authuser=0)
 
![Texto alternativo](https://lh3.googleusercontent.com/ix1j1FZZKZr8s5VHkf6x0cPeWnJ03lHBdR7pvZx-SkFUKWkloy11mGu-qPCBgCz01rpO05gQt7Ejcc4_TbUmtM-5TgA013VpeBYJFl5E7R6SLrvQLrcb64qXsVHtj9yB5x3-UsvjpJ1916r4XubpXNQQPMTHZXm80ayJsnsZ4UF-HryH8058ZRyfqcUqnLn_vvV8snuQgmV5kzxivHrvT5Jp5hQv4X5SgXlmNoE5Y5UOBk1fcFxbtpGwrzVwXzrEqBi1AlcLexTJvqR8sOxHSyH6EXBAe6ooWi5vJAo6XsOnGlIPaSjmlnt4dHGVbTJailFzZ6_SrpGqu7Py1-bhQlx7OkNp5Fz2dynFm_QUamijBZQQNB_LkHs-RNyLydHJO8kF-qOiHLL-sUJnDGkOjyMFMCZxGMuP7Q7ihDzzmoP480CBEb6FIkaz4gZBEs4Xc3S56lYh7BdeS5OjMmLvvK-P9ChtAFXWfCVcqy_nz8C4Ko2Enq_AIF5s303DaX72CVlH0_kkVKiXPbw33jvHPd_y5bRy3gDy60q_d5SnTZPDl015w_89-3p9efDpUsCgaec0OQgomD2UnIFmVleOXoS_QTZ5l9PEuRcrZFipcHj38dAhUR3w-GbKDuQSJgtT15tyseBQhs-rAPXZCu8ad4FmhOjys9gf50XH8JKaPp-2MtrqJiSutUGOs5HUKg=w1168-h657-no?authuser=0)

16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac  
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac  

## Referencias
https://markdown.es/sintaxis-markdown
   
