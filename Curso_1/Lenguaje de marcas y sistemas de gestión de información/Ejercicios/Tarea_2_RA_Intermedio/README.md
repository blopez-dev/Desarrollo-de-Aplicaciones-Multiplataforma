# Penyagolosa Trails (guia no oficial) — Tarea 2 (R.A. Intermedio)

Sitio web de tematica libre (guia de aficionado, no oficial, sobre la carrera
de montana **Penyagolosa Trails**, en Castellon de la Plana) creado para la
Tarea 2 de Lenguaje de Marcas y Sistemas de Gestion de Informacion.

Este proyecto no tiene relacion con la organizacion de la carrera. Para
inscripciones, normativa oficial, tracks GPX actualizados y material
obligatorio definitivo, consulta siempre <https://www.penyagolosatrails.com/>.

## Estructura del sitio

```
Tarea_2_RA_Intermedio/
├── index.html          → Inicio
├── rutas.html           → Recorridos (FUGA, MiM, CSP: tabla, fichas, video)
├── consejos.html        → Avituallamiento y material (glosario, imagen, audio)
├── contacto.html        → Contacto (formulario, mapa)
├── css/
│   └── estilos.css      → Hoja de estilos unica, comentada por bloques
└── assets/
    └── img/
        ├── logotipo.svg
        └── hero-sierra.svg
```

Las 4 paginas estan enlazadas entre si desde el menu de la cabecera y desde
el pie de pagina. Todas las rutas son **relativas**, por lo que el sitio
funciona abriendo `index.html` directamente en el navegador, sin necesidad
de servidor ni de instalar nada.

## Como se cubre cada requisito obligatorio

| # | Requisito | Donde se ve |
|---|---|---|
| 1 | Al menos 3 paginas enlazadas | `index.html`, `rutas.html`, `consejos.html`, `contacto.html` (menu y pie) |
| 2 | Enlaces externos | penyagolosatrails.com, UTMB World, Wikipedia, Wikiloc, Decathlon, Barrabes (varias paginas) |
| 3 | Enlaces internos (anclas) | Indices `.indice` en cada pagina y enlaces `rutas.html#mim` desde `index.html` |
| 4 | Listas | `ul` (material, enlaces), `ol` (avituallamientos, recomendaciones), `dl` (fichas, glosario) |
| 5 | Elementos multimedia | Imagenes SVG, video de YouTube embebido, audio con `<audio>`, mapa embebido |
| 6 | Tablas | Tabla comparativa de recorridos en `rutas.html` (con `thead`/`tbody`/`tfoot`) |
| 7 | Formulario | `contacto.html`: texto, email, telefono, fecha, select, radio, checkbox, textarea |

## Contenidos por recorrido

`rutas.html` incluye fichas independientes para las tres distancias de la
carrera (FUGA, Marato i Mitja y Curs Suprema), con salida, meta, distancia,
desnivel y dificultad. `consejos.html` reune el material obligatorio (frontal,
cortavientos, manta termica, silbato, vaso reutilizable, bastones, etc.) y un
ejemplo de puntos de avituallamiento a lo largo del recorrido.

## Checklist para grabar el video (maximo 6 minutos)

Recuerda ir nombrando en voz alta cada punto mientras lo muestras:

- [ ] Ensenar la carpeta del proyecto y explicar la estructura de archivos.
- [ ] Abrir `index.html` en el navegador y navegar por las 4 paginas.
- [ ] Mostrar un enlace **externo** y comprobar que abre otra web.
- [ ] Mostrar un enlace **interno** (ancla) y comprobar que salta a otra parte de la pagina o a otra pagina.
- [ ] Ensenar al menos una **lista** (ordenada, no ordenada o de definiciones).
- [ ] Ensenar el **elemento multimedia** (video, audio o imagen destacada).
- [ ] Ensenar la **tabla** de `rutas.html`.
- [ ] Rellenar y explicar el **formulario** de `contacto.html`.
- [ ] Abrir el codigo en el editor y ensenar que esta **tabulado y comentado**.
- [ ] Comentar brevemente la hoja de estilos y como se organiza.

## Empaquetado para la entrega

1. Comprimir **todo el contenido de esta carpeta** (no la carpeta contenedora)
   en un `.zip`, de modo que al descomprimirlo `index.html` quede en la raiz.
2. Verificar, descomprimiendo en otra carpeta distinta, que todos los enlaces
   y recursos (CSS, imagenes) siguen funcionando.
3. Subir el `.zip` junto con el video grabado con Studio a la tarea de Canvas
   antes del **1 de diciembre a las 23:59**.

## Tabla de registro para el examen

| Tarea | Fecha de inicio | Fecha limite | Entrega correcta en Canvas (SI/NO) | Demostracion en video de todos los puntos (SI/NO) |
|---|---|---|---|---|
| Tarea 2 (R.A. Intermedio) |  | 1 de diciembre 23:59 |  |  |

## Dificultades encontradas (maximo 100 palabras)

_Espacio para que el alumno complete, en no mas de 100 palabras, las
dificultades encontradas al realizar la tarea._
