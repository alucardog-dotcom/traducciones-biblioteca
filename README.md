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

## Boundary Gate: Daughter of Kingdom (PlayStation, 1997)

Traducción completa al español del RPG de Pack-In-Video y Victor Interactive Software: diálogos y eventos, menús, objetos, hechizos, monstruos, combate, tiendas, guardado, el prólogo, el final y los créditos, con tildes, eñes y signos de apertura.

**Traducción al español:** Biblioteca de traducciones, hecha con ayuda de inteligencia artificial. Incluye las tildes, eñes y signos de apertura añadidos a la fuente del juego.

**Agradecimientos.** Esta traducción parte de la traducción inglesa de [minhnhattonthat](https://github.com/minhnhattonthat/boundary-gate-daughter-of-kingdom-en), que publica su trabajo y sus herramientas con licencia MIT. Sin su trabajo, este juego no se podría leer en ningún idioma occidental. Si te gusta, pásate por su repositorio.

### Descarga
En [Releases](../../releases), el fichero `Boundary_Gate_Daughter_of_Kingdom_ES_v0.9.0.zip`.

### Cómo se aplica
Hace falta el disco japonés en formato Redump (90 pistas: la 1 de datos y el resto de audio). El parche solo cambia la pista 1; las demás y el `.cue` sirven tal cual. Se puede aplicar con Delta Patcher o con xdelta3: `xdelta3 -d -s "Boundary Gate - Daughter of Kingdom (Japan) (Track 01).bin" parche.xdelta Pista01_ES.bin`, y luego se pone la pista parcheada en lugar de la original, con el mismo nombre. El `LEEME.txt` trae las sumas de comprobación.

### Qué queda en inglés
Los gráficos que el juego japonés ya traía en inglés: el logotipo, «Daughter of Kingdom», «PUSH START BUTTON», «Game Over» y el «END» de los créditos. Las voces siguen en japonés.

### Problemas conocidos
- El español es más largo que el japonés: algunas frases ocupan una página más que en el original.
- En la pantalla de tarjetas de memoria de la BIOS, los nombres de lugar con tilde salen con signos raros (la BIOS solo lee japonés). Dentro del juego se ven bien.
- Es la versión 0.9.0: se ha probado en emulador (todos los eventos, menús, tiendas, posada, guardado, combates y el final), pero no se ha jugado de principio a fin. Si encuentras una frase rara o un fallo, abre un *issue* o escribe a contacto@bibliotecadetraducciones.com.

### Licencia
La traducción inglesa y las herramientas de minhnhattonthat son MIT; su aviso va en el `LICENCIA.txt` del zip. La traducción al español se publica con la misma licencia.

## Castlevania: Rondo of Blood (PC Engine CD, 1993)

Traducción al español del Castlevania de PC Engine (*Akumajō Dracula X: Chi no Rondo*). La historia va en escenas habladas que en el original japonés no tienen texto: esta traducción les añade **subtítulos en español** sincronizados con las voces, y también a las frases que dice la Muerte mientras se juega: las dos de la pelea de la carreta del nivel 0 y la que suelta al aparecer en el barco del nivel 5, con Richter y con Maria. Traduce además el prólogo, los rótulos de entrada de los niveles, los nombres de nivel del mapa y del SOUND TEST, los mensajes de guardado, el barquero y el mercader, y el reparto de los créditos, con una fuente nueva con tildes y eñes.

**Traducción al español:** Biblioteca de traducciones, hecha con ayuda de inteligencia artificial. Las voces se transcribieron con reconocimiento de voz y se revisaron; los nombres siguen la traducción oficial inglesa de Konami (Richter Belmont, Maria Renard, Annette, Tera, Iris, Shaft, conde Drácula).

### Descarga
En [Releases](../../releases), el fichero `Rondo_of_Blood_ES_v0.9.1.zip`.

**Versión 0.9.1 (18-11-2026):** subtitula la frase de la Muerte del nivel 5, que faltaba, y el parche ya no le quita tiempo al juego: sin subtítulo en pantalla, el juego corre con su código original, y con una frase a la vista el subtitulado gasta lo mismo que le ahorra al juego (en la 0.9.0, en los jefes, podía perder algún fotograma más que el original). El parche se aplica siempre al fichero original, no sobre la 0.9.0.

### Cómo se aplica
Hace falta el disco japonés y la System Card 3.0 (Super CD-ROM²). El zip trae el parche para los volcados que circulan: guardan el mismo juego con distinto relleno, y por eso su CRC32 no coincide. Usa la carpeta de tu fichero:

| Carpeta | Tu fichero | CRC32 |
|---|---|---|
| `por_pistas_redump` | Redump con pistas sueltas: la pista 2 (`Track 02.bin`) | C681F9DA |
| `por_pistas_tosec` | TOSEC o TruRip con pistas sueltas: la pista 2 | 42A597B1 |
| `imagen_unica_redump` | Redump en un solo `.bin` (lo que saca `chdman extractcd` de un `.chd`) | E00AC0E2 |
| `imagen_unica_tosec` | TOSEC o TruRip en un solo `.img` o `.bin` | A62E216F |
| `iso_wav` | «ISO + WAV»: la pista de datos `.iso` | E91084DA |

Se puede aplicar con Delta Patcher o con xdelta3: `xdelta3 -d -s "tu fichero" carpeta/Rondo_of_Blood_ES.xdelta "fichero en español"`, y luego se pone el fichero parcheado en lugar del original. Las pistas de audio no cambian. El `LEEME.txt` trae las sumas de comprobación.

### Qué queda sin traducir
- Las voces, que siguen en japonés (con subtítulos).
- Los menús que el juego ya traía en inglés (PLAYER, NAME ENTRY, GAME START, TECHNIC, STAGE…).

### Problemas conocidos
- Cuando abajo hay figuras de la escena, el subtítulo va arriba o a un lado; si no cabe en dos líneas, sale en dos partes seguidas.
- Los subtítulos de las frases de los niveles son sprites, y la consola solo admite 64 a la vez: en algún fotograma suelto en que el juego los usa casi todos puede faltar uno de los suyos (unas gotas de lluvia en el nivel 0).
- Es la versión 0.9.1: probada en emulador (las diez escenas comparadas fotograma a fotograma con el juego original, y las peleas con la Muerte de los niveles 0 y 5 jugadas a la vez con el disco original, con Richter y con Maria), pero no jugada de principio a fin. Si encuentras un fallo, abre un *issue* o escribe a contacto@bibliotecadetraducciones.com.

## Legend of Kartia (PlayStation, 1998)

Traducción completa al español del juego de rol táctico de Atlus: las escenas de las dos historias (Toxa y Lacryma), los combates, la Arena, las narraciones de los capítulos, los resúmenes, el prólogo, los menús, los objetos, las armas, las magias, los Fantasmas, las kartias, el guardado y el modo de entrenamiento.

**Traducción al español:** Biblioteca de traducciones, hecha con ayuda de inteligencia artificial a partir del texto inglés oficial. Incluye las tildes, eñes y signos de apertura añadidos a la fuente del juego. El español ocupa el lugar del francés: en la pantalla de idiomas sale la bandera de España; el inglés y el alemán siguen intactos.

### Descarga
En [Releases](../../releases), el fichero `Legend_of_Kartia_ES_v0.9.0.zip` (parche xdelta). Aparte, en la release `kartia-es-v0.9.0-ppf`, el mismo parche en formato PPF (`Legend_of_Kartia_ES_v0.9.0_PPF.zip`), para PPF-O-Matic y para volcados que no son idénticos al de Redump.

### Cómo se aplica
Hace falta la edición europea (SLES-01710) en formato Redump, de una sola pista: `Legend of Kartia (Europe) (En,Fr,De).bin`, CRC32 0BA490B8. La americana (*Kartia: The Word of Fate*) no sirve.
- **Con la app de la Biblioteca:** acepta el juego en `.cue`/`.bin`, `.chd`, `.zip` o `.7z` y deja al lado un `.chd` traducido.
- **`.cue` y `.bin`:** Delta Patcher, Rom Patcher JS o xdelta3 (`xdelta3 -d -s "Legend of Kartia (Europe) (En,Fr,De).bin" Legend_of_Kartia_ES_v0.9.0.xdelta "Legend of Kartia (Español).bin"`), y se abre con el `.cue` que va en el zip.
- **`.chd`:** sin la app, se pasa antes a `.cue`/`.bin` con `chdman extractcd`.

En el juego, elige la bandera de España. El `LEEME.txt` explica cada caso y trae las sumas de comprobación.

### Qué queda en inglés
Los gráficos que la versión francesa ya traía en inglés: el menú del título (Start, Continue…), «Turn», «Phantom», «Weapon», «Gear», «Mix», «Ok», «Silk», «Mithril», «World Tree», los rótulos del mapa del mundo, los de capítulo y «KARTIA the Record of Fate».

### Problemas conocidos
- Es la versión 0.9.0: se ha probado en emulador (el comienzo de las dos historias y sus primeros combates, menús, creación de Fantasmas y armas, guardado), pero no se ha jugado de principio a fin. Si encuentras una frase rara o un fallo, abre un *issue* o escribe a contacto@bibliotecadetraducciones.com.
- La fuente pequeña de algunos datos de estado solo tiene la «á» como letra acentuada nueva, por eso se abrevia alguna palabra («Cap.»).
