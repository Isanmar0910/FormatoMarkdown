# Pagina de ayuda📚
## Índice De Contenidos

1. [Encabezados](#encabezados-de-nivel-1-2-3-y-4)
2. [Tipografía](#tipografía-)
3. [Listas Sin orden](#listas-sin-orden)
4. [Listas Ordenadas](#listas-ordenadas)
5. [Snippets](#snippets-de-código)
6. [Citas](#citas)
7. [Enlaces Internos](#enlaces-a-otros-elementos-del-mismo-documento)
8. [Enlaces Externos](#enlaces-a-páginas-o-elementos-externos)
9. [Imagenes Externas](#imágenes-externas)
10. [Imagenes enlace](#imágenes-con-enlace)
    



11. ### Encabezados de nivel 1, 2, 3, y 4. 
    
    Ahora mostraresmos como utilizar los distintos niveles de **encabezados**.

    #### **Encabezado de nivel 1**

        

    ********************
    # Ejemplo nivel 1

    #### **Encabezado de nivel 2**

    Para el nivel dos es exactamente igual que el anterior pero usando **"##"**.

    *******************
    ## Ejemplo nivel 2

    #### **Encabezado de nivel 3**

    Para este seria con **"###"**.

    ***
    ### Ejemplo nivel 3

    #### **Encabezado de nivel 4**

    Para este seria con **"####"**.

    ***
    #### Ejemplo nivel 4
    ***

2. ### Tipografía 🔠

    #### Cambios con *

    Estos son los cambios de tipografias que podemos usar agragando asteriscos a la palabra.

    **Negrita**: Para las palabras en negrita hay que añadir ** delante y detras de la palabra **ejemplo **

    *Italico*: Para el texto Itálico es simplemente añadir * delante y detras   *ejemplo *

    #### Cambios con ~

    ~~Tachado~~: Para el texto tachado añadimos dos ~~ delante y detras. ~~ ejemplo~~
    
    #### Cambios con =

    ==Remarcado==: Para el remarcado tachado añadimos dos == delante y detras. == ejemplo==
       

### Listas sin orden
   
    Las listas sin orden se crean usando `-`, `*` o `+`.

   - Elemento de nivel 1
     - Elemento de nivel 2
      - Elemento de nivel 3

---


### Listas ordenadas

    Las listas ordenadas utilizan números seguidos de un punto.

1. Primer elemento
   1. Subnivel
      1. Detalle
    2. Segund   o elemento
    3. Tercer elemento

---


### Snippets de código

Código en línea: `ls -la`

Bloque de código: 

```bash
#!/bin/bash
echo "Hola Papu"
```


### Citas 

Para crear una cita debemos usar el símbolo **">"** al inicio de la línea. Esto permite resaltar un texto como si fuera una nota o comentario importante. Por

> Esto es una cita simple. > Se usa el símbolo `>` al inicio de la línea.
>

También podemos añadir encabezados, listas o incluso código dentro de una cita:

>#### Cita con encabezado > También se pueden incluir **negritas**, *cursivas*, ~~tachados~~ o incluso `código`.

Las citas pueden anidarse usando varios símbolos `>` seguidos:

> > Citas anidadas 
> > > > Se pueden encadenar tantas como quieras. 
---


### Enlaces a páginas o elementos externos 

Para crear un enlace externo debemos escribir el texto entre **corchetes** y la URL entre **paréntesis**. Este formato permite dirigir al lector a páginas web externas.

También podemos poner directamente la URL

  **Enlace directo**: https://www.google.com 
  
  **Enlace con texto personalizado**: [Markdown Guide](https://www.markdownguide.org/) 

  
  **Enlace con título emergente**: [Visitar GitHub](https://github.com "GitHub Homepage")

### Enlaces a otros elementos del mismo documento

Para enlazar a una sección del mismo documento usamos el formato:


Volver al [Índice](#índice-de-contenidos)
Ir a [Listas ordenadas](#listas-ordenadas)

### Imágenes externas

Para insertar una imagen usamos el mismo formato que los enlaces, pero añadiendo un **"!"** al inicio.

`![Texto alternativo](URL-de-la-imagen)`

![PapuPapu](13._papu.webp)

### Imágenes con enlace

Si queremos que una imagen funcione como un enlace, simplemente colocamos la imagen dentro del enlace: 

Formato: 

`[![alt](img)](url)`

[![MegaPapu](revivan-a-pou-fan-papus-v0-1oeylrz4e1fc1.webp)](https://www.reddit.com/r/POUFAN/comments/1acj6t5/revivan_a_pou_fan_papus/?tl=es-419)

### Tablas

Las tablas se crean usando **barras verticales "|"** para separar columnas y **guiones "-"** para definir el encabezado.

| Nombre | Edad | Ciudad |
|--------|------|--------|
| Ana | 22 | Madrid |
| Luis | 30 | Málaga | 
| Sara | 27 | Sevilla | 
---

### Líneas horizontales

Para crear una línea horizontal podemos usar:

- `---`
- `***`
- `___`

Sirven para separar secciones visualmente.
---

### Saltos de línea

Para hacer un salto de línea debemos añadir **dos espacios al final** de la línea. Esto permite separar frases sin crear un nuevo párrafo.

Ejemplo:

Esto es una línea.  
Esto es otra línea.
---

### Lista de tareas

Las listas de tareas se crean usando `- [ ]` para tareas sin completar y `- [x]` para tareas completadas.

Ejemplo:

- [x] Crear documento
- [ ] Añadir más ejemplos
- [x] Revisar formato
- [ ] Publicar en GitHub

### Emojis

Podemos añadir emojis simplemente escribiéndolos directamente en el texto. Son útiles para destacar ideas o hacer el documento más visual.

Ejemplos:

- 😎
- 🔥
- 😍

### Fórmulas matemáticas

Para escribir fórmulas matemáticas podemos usar sintaxis LaTeX.

- Fórmulas en línea se escriben entre acentos graves: `e^{i\pi} + 1 = 0`


    \( A = \pi r^2 \)


### Referencias

Las referencias permiten citar fuentes externas de forma ordenada.
Se escriben usando un identificador entre corchetes y dos puntos.

Ejemplo:

- Papu Guia - https://www.markdownguide.org/basic-syntax/

### Referencias al pie

Las referencias al pie se definen al final del documento usando:

[^nota-importante]: Markdown





