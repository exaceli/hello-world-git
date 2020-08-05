# Version
v.1.1.0

---
---

Soy un readme 
# Cabecera H1 
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1 (H1)
=
Underline 2 (H2)
-

# Formato de enfasis
- formato *italica modo 1*.
- formato _italica modo 2_.
- formato **bold BOLD**
- formato __bold BOLD__
- formato ~~tachado~~ , formato normal 

### Listas ordenada y desordenada

1. item 1
1. item 2
1. item 3
1. item 4 
- item 1
- item 2
- item 3
# Links
- <a href="http://google.cl">Links de prueba html </a>
- [Links en Markdown](http://google.cl)
- [Links en Markdown al index](index.html)

# Imagenes
![Logo Github](https://anthoncode.com/wp-content/uploads/2019/01/github-octocat-logo-png.png)
# Snippets
```Bash
#!/bin/bash

###### CONFIG
ACCEPTED_HOSTS="/root/.hag_accepted.conf"
BE_VERBOSE=false

if [ "$UID" -ne 0 ]
then
 echo "Superuser rights required"
 exit 2
fi
genApacheConf(){
 echo -e "# Host ${HOME_DIR}$1/$2 :"
}
echo '"quoted"' | tr -d \" > text.txt
 ```

 ```JSON
 [
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
 ```

 # Tabla
  Nombre | Apellido | oficio 
 -|-|-
 maxi|perez|cartero
felipe|cuevas|doctor
Andres|Abad|Cantautor
Carla|Bravo|atleta

# Citas
Texto referente a una cita:
> el que la sigue la consigue

otro texto no citado

# Lines divisorias horizontales
Texto 1 triple guion medio

---

Texto 2 tres arteristos

***
Texto  3 tres lineas bajas
___

# Saltos de linea (ENTER)

Un texto es una composición de signos codificados en un sistema de escritura que forma una unidad de sentido. 

También es una composición de caracteres imprimibles generados por un algoritmo de cifrado que, aunque no tienen sentido para cualquier persona, sí puede ser descifrado por su destinatario original

- lista
