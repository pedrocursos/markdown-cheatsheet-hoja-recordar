# Markdown: hoja para recordar o cheatsheet

## Indice
Indice de los símbolos que utiliza Markdown para dar formato:

* [Texto](#texto)
    - [Títulos](#títulos)
    - [Estilos](#estilos)
        + [Negrita](#negrita)
        + [Itálica](#itálica)
        + [Tachado](#tachado)
        + [Negrita e itálica](#negrita-e-itálica)
    - [Citas de texto](#citas-de-texto)
    - [Nueva línea](#nueva-línea)
    - [Nuevo párrafo](#nuevo-párrafo)
* [Código](#código)
    - [Citas](#citas)
    - [Bloques](#bloques)
* [Enlaces](#enlaces)
    - [URL](#url)
    - [Imágenes](#imágenes)
    - [Enlaces a secciones](#enlaces-a-secciones)
    - [Vídeos de YouTube](#vídeos-de-youtube)
* [Listas](#listas)
    - [Numeradas](#numeradas)
    - [Ordenadas](#ordenadas)
    - [Tareas](#tareas)
* [Tablas](#tablas)
* [Emoticonos](#emoticonos)
* [Ignorando el formato Markdown](#ignorando-el-formato-markdown)

## Texto
### Títulos
Los títulos se crean mediante el símbolo almoadilla `#`. Hay 6 tamaños, siendo más pequeños conforme tienen más almoadillas.

| :pencil2: Código |
| --- |
| `# Título 1` |
| `## Título 2` |
| `### Título 3` |
| `#### Título 4` |
| `##### Título 5` |
| `###### Título 6` |

:computer: **Resultado:**
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

### Estilos
#### Negrita
El texto en negrita va entre dos asteríscos `**`.

| :pencil2: Código |
| --- |
| `**Texto en negrita**` |
| `Los tomates están **deliciosos**` |

:computer: *Resultado*\
**Texto en negrita**\
Los tomates están **deliciosos**

#### Itálica
El texto en cursiva o itálica se escribe entre un arsterísco `*`.

| :pencil2: Código |
| --- |
| `*Texto en itálica*` |
| `Los *tomates* están deliciosos` |

:computer: *Resultado*\
*Texto en itálica*\
Los *tomates* están deliciosos

#### Tachado
El texto tachado tiene que ir entre dos virgulillas `~~`.

| :pencil2: Código |
| --- |
| `~~Texto tachado~~` |
| `Los tomates están ~~deliciosos~~ buenísimos.` |

:computer: *Resultado*\
~~Texto tachado~~\
Los tomates están ~~deliciosos~~ buenísimos.

#### Negrita e itálica
Se pueden poner texto en itálica y negrita dentro de un mismo texto formateado. Para ello se utiliza el guión bajo `_`.

| :pencil2: Código |
| --- |
| `**Texto en negrita con _cursiva_**` |
| `*Texto en cursiva con __negrita__*` |
| `Los higos están que **se _deshacen_ en la boca**` |
| ` Las fresas están maduras, *pero __no están dulces__*` |

:computer: *Resultado*\
**Texto en negrita con _cursiva_**\
*Texto en cursiva con __negrita__*\
Los higos están que **se _deshacen_ en la boca**\
Las fresas están maduras, *pero __no están dulces__*

### Citas de texto
Las citas se crean mediante el símbolo de mayor `>`.

| :pencil2: Código |
| --- |
| `Un refrán huertano dice:` |
| `> Cuando hay frutas en la huerta, hay amigos en la puerta.` |

:computer: *Resultado*\
Un refrán huertano dice:
> Cuando hay frutas en la huerta, hay amigos en la puerta.

### Nueva línea
Para que dos líneas con un punto y a parte se mantengan en el mismo párrafo, hay que utilizar la contrabarra `\` al finalizar la frase.

| :pencil2: Código |
| --- |
| `¿Cuál es la fruta más divertida?` |
| `La naranja ja ja ja ja` |

:computer: *Resultado*\
¿Cuál es la fruta más divertida?\
La naranja ja ja ja ja

### Nuevo párrafo
Los parrafos se separan con una línea en blanco entre ellos.

| :pencil2: Código |
| --- |
| `**Huerta** (definición del diccionario de la RAE):` |
| `` |
| `Terreno de mayor extensión que el huerto, destinado al cultivo de legumbres y árboles frutales.` |

:computer: *Resultado*\
**Huerta** (definición del diccionario de la RAE):

Terreno de mayor extensión que el huerto, destinado al cultivo de legumbres y árboles frutales.

## Código
### Citas
Las citas de texto van entre dos acentos graves `.

| :pencil2: Código |
| --- |
| `Las variables en Swift usan la palabra clave`\`var\``. Ejemplo: ` |
| `var suma = 35 + 2` |

:computer: *Resultado*\
Las variables en Swift usan la palabra clave `var`. Ejemplo:\
`var suma = 35 + 2`

### Bloques
Para escribir bloques de código hay que escribir tres acentos graves ` al comienzo y final.

| :pencil2: Código |
| --- |
| `Las variables en Swift usan la palabra clave `\`var\``. Ejemplo:` |
| ` ``` ` |
| `let estudiantes = ["Alberto, "Estefanía", "Ana", "Manuel"]` |
| `let nombresCortos = estudiantes.filter { $0.count < 5)` |
| `print(nombresCortos)` |
| ` ``` ` |

:computer: *Resultado*\
Las variables en Swift usan la palabra clave `var`. Ejemplo:
```
let estudiantes = ["Alberto, "Estefanía", "Ana", "Manuel"]
let nombresCortos = estudiantes.filter { $0.count < 5)
print(nombresCortos)
```

## Enlaces
### URL
Un enlace basado en una URL tiene una parte escrita y otra el enlace. La parte escrita va entre corchetes `[]` y la URL entre paréntesis `()`.

| :pencil2: Código |
| --- |
| `[Caqui](https://es.wikipedia.org/wiki/Caqui)` |

:computer: *Resultado*\
[Caqui](https://es.wikipedia.org/wiki/Caqui)

### Imágenes
Para embeber una imagen hay que poner un signo de exclamación `!` antes de los corchetes y los paréntesis usados para un enlace.

| :pencil2: Código |
| --- |
| `![Tomatera creciendo con riego por goteo](tomatera_creciendo.jpg)` |

:computer: *Resultado*\
![Tomatera creciendo con riego por goteo](tomatera_creciendo.jpg)

### Enlaces a secciones

Poner entre corchetes el nombre de la sección y dentro de los paréntesis añadir una almoadilla `#`con el nombre de la sección en minúsculas.

| :pencil2: Código |
| --- |
| `[Indice](#indice)` |

:computer: *Resultado*\
[Indice](#indice)

### Vídeos de YouTube
Para mostrar un vídeo de YouTube hay que usar código HTML.

:pencil2: Código

`<a href="https://www.youtube.com/watch?v=código_del_video=0s
">
<img src="enlace_a_una_imagen_de_portada_del_vídeo" 
alt="descripción_del_vídeo'" width="ancho_con_relación_16:9" height="alto_con_relación_16:9" border="10" />
</a>`

:computer: *Resultado*\
<a href="https://goo.gl/UtxQpU
">
<img src="https://github.com/pedrocursos/markdown-cheatsheet-hoja-recordar/blob/master/melocotoneros_en_flor_youtube.jpg" 
alt="floracion de melocotoneros en cieza de murcia'" width="240" height="180" border="10" />
</a>

## Listas
### Numeradas
Una lista con números se crea al poner un número con un punto al final.

| :pencil2: Código |
| --- |
| ` 1. Perejil. ` |
| ` 2. Lechuga. ` |
| ` 3. Tomate. ` |

:computer: *Resultado*

1. Perejil.
2. Lechuga.
3. Tomate.

### Ordenadas
Una lista ordenda se representa con un asterisco `*` o un guión medio `_`. Para hacer sublistas añadir una tabulación.

| :pencil2: Código |
| --- |
| ` * Manzana. ` |
| ` - Ciruela: ` |

:computer: *Resultado*
* Manzana.
- Ciruela:
    - Roja.
    - Claudia.
- Pera.

### Tareas
Una lista de tareas se crean mediante guión medio, corchetes y se pone un x para seleccionar una tarea.

| :pencil2: Código |
| --- |
| ` - [ ] Plantar.` |
| ` - [x] Regar.` |

:computer: *Resultado*
- [ ] Plantar.
- [x] Regar.

## Tablas
Las tablas se crean entre barras verticales `|` y utilizando guiones medios `-` para separar las cabeceras de la tabla de las celdas.

:pencil2: Código

`| Fruta | Kilogramos |`\
`| Melocotón | 20 |`\
`| Pera conferencia | 15 |`

:computer: *Resultado*

| Fruta | Kilogramos |
| --- | --- |
| Melocotón | 20 |
| Pera conferencia | 15 |

## Emoticonos
Los emoticonos o emoji se añaden escribiendo el nombre del emoticono. En esta página puedes encontrarlos [Emoji Cheatsheet](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

| :pencil2: Código |
| --- |
| `:watermelon:` |

:computer: *Resultado*\
:watermelon:

## Ignorando el formato Markdown
Si se escribe una contrabarra `\` se elimina el formateo de texto.

| :pencil2: Código |
| --- |
| `La \*\*luna nueva\*\* madura los tomates.` |

:computer: *Resultado*\
La \*\*luna nueva\*\* madura los tomates.
