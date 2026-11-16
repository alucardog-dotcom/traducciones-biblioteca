# Traducciones de la Biblioteca de traducciones

Parches de traducción al español hechos por la [Biblioteca de traducciones](https://bibliotecadetraducciones.com/). Aquí solo hay parches: nunca juegos.

## Athena: Awakening from the Ordinary Life (PlayStation, 1999)

Traducción completa al español de la aventura de SNK y Yumekobo, en sus tres discos: diálogos, menús de texto, mensajes del sistema y subtítulos de los vídeos, con tildes, eñes y signos de apertura.

**Traducción al español:** Biblioteca de traducciones, hecha con ayuda de inteligencia artificial. Incluye las tildes, eñes y signos de apertura añadidos a la fuente del juego y los subtítulos de los vídeos.

**Agradecimientos.** Esta traducción parte de la traducción inglesa 1.0.0 de Plissken y se publica con su permiso. Muchas gracias a:
- [Plissken](https://boosty.to/plissken), por el romhacking
- Deep_wolf y playerrr, por la traducción al inglés

Sin su trabajo, este juego no se podría leer en ningún idioma occidental. Si te gusta, pásate por la página de Plissken.

### Descarga
En [Releases](../../releases), el fichero `Athena_ES_v0.9.0.zip`.

### Cómo se aplica
Hacen falta los tres discos japoneses (SLPM-86185, 86186 y 86187). El zip trae tres juegos de parches; usa el de tus imágenes:
- `por_pistas`: para volcados con las pistas separadas (Redump), lo más habitual. Se parchea la pista 1 de cada disco; la pista 2 de los discos 2 y 3 no cambia y el `.cue` sirve tal cual.
- `pistas_unidas`: para la imagen japonesa con todas las pistas unidas en un solo `.bin`, como pide el parche inglés.
- `desde_ingles`: para la imagen ya parcheada con el inglés 1.0.0 de Plissken.

Se puede aplicar con Delta Patcher o con xdelta3: `xdelta3 -d -s original.bin parche.xdelta traducido.bin`. El `LEEME.txt` trae las sumas MD5 de cada imagen.

### Qué queda en inglés
Lo que son imágenes: el menú del título, el menú de pausa (MAP, ITEMS, ESP), los menús de ESP y de objetos, los mapas, las pantallas de guardar y cargar y el aviso de cambio de disco.

### Problemas conocidos
- En DuckStation, el juego se cuelga con «PGXP Geometry Correction» activado. Le pasa también al original y lo avisa Plissken.
- Cada frase en español va en el hueco exacto de la inglesa, así que algunas son más escuetas de lo ideal.
- Es la versión 0.9.0: se ha probado el principio de cada disco, pero no se ha jugado de principio a fin. Si encuentras una frase rara o un fallo, abre un *issue* o escribe a contacto@bibliotecadetraducciones.com.
