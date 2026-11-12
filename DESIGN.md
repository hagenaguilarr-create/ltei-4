---
version: alpha
name: HAR — Sistema de diseño de marca personal
description: Estética sobria, elegante y minimalista construida alrededor del monograma HAR, con marfil, verde oliva, terracota y negro.
colors:
  primary: "#3F5228"
  on-primary: "#F4F1EA"
  tertiary: "#D8492E"
  neutral: "#F4F1EA"
  on-neutral: "#111111"
  surface: "#F4F1EA"
  on-surface: "#111111"
  border: "{colors.primary}"
  focus-ring: "{colors.primary}"
  error: "{colors.tertiary}"
typography:
  display-desktop:
    fontFamily: Cinzel
    fontSize: 64px
    fontWeight: 500
    lineHeight: 72px
    letterSpacing: 0em
  display-mobile:
    fontFamily: Cinzel
    fontSize: 40px
    fontWeight: 500
    lineHeight: 48px
    letterSpacing: 0em
  section-desktop:
    fontFamily: Cinzel
    fontSize: 40px
    fontWeight: 400
    lineHeight: 48px
    letterSpacing: 0em
  section-mobile:
    fontFamily: Cinzel
    fontSize: 28px
    fontWeight: 400
    lineHeight: 36px
    letterSpacing: 0em
  card-title-desktop:
    fontFamily: Fira Sans
    fontSize: 24px
    fontWeight: 600
    lineHeight: 30px
  card-title-mobile:
    fontFamily: Fira Sans
    fontSize: 20px
    fontWeight: 600
    lineHeight: 26px
  body-desktop:
    fontFamily: Fira Sans
    fontSize: 18px
    fontWeight: 400
    lineHeight: 27px
  body-mobile:
    fontFamily: Fira Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  body-field:
    fontFamily: Fira Sans
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  body-sm:
    fontFamily: Fira Sans
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
  label:
    fontFamily: Fira Sans
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  label-sm:
    fontFamily: Fira Sans
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
spacing:
  xs: 6px
  sm: 12px
  md: 18px
  lg: 24px
  xl: 36px
  2xl: 48px
  3xl: 72px
  4xl: 108px
  5xl: 144px
  max-width: 1240px
  columns-wide: 12
  columns-tablet: 8
  columns-mobile: 4
  margin-wide: 72px
  margin-compact: 48px
  margin-tablet: 32px
  margin-mobile: 16px
  section-gap: 108px
  section-gap-tablet: 72px
  section-gap-mobile: 48px
  card-padding: 36px
  card-padding-mobile: 20px
  control-gap: 6px
  icon-gap: 12px
  touch-target: 44px
  field-padding-block: 12px
  field-padding-inline: 18px
  focus-width: 2px
  focus-offset: 3px
rounded:
  none: 0px
  sm: 4px
  full: 9999px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: 12px
    height: "{spacing.touch-target}"
  button-secondary:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: 12px
    height: "{spacing.touch-target}"
  button-disabled:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: 12px
    height: "{spacing.touch-target}"
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-neutral}"
    rounded: "{rounded.sm}"
    padding: "{spacing.card-padding}"
  card-mobile:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-neutral}"
    rounded: "{rounded.sm}"
    padding: "{spacing.card-padding-mobile}"
  card-title:
    textColor: "{colors.on-surface}"
    typography: "{typography.card-title-desktop}"
  card-title-mobile:
    textColor: "{colors.on-surface}"
    typography: "{typography.card-title-mobile}"
  card-link:
    textColor: "{colors.primary}"
    typography: "{typography.body-desktop}"
  field:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-field}"
    rounded: "{rounded.sm}"
    padding: "{spacing.field-padding-block}"
  field-label:
    textColor: "{colors.primary}"
    typography: "{typography.label}"
  chip:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.sm}"
    padding: 6px
  nav-link:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
  nav-link-active:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
  icon-link:
    textColor: "{colors.primary}"
    size: 24px
    width: "{spacing.touch-target}"
    height: "{spacing.touch-target}"
  avatar:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-neutral}"
    rounded: "{rounded.full}"
    size: 64px
  section-intro:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-neutral}"
    rounded: "{rounded.none}"
---

# HAR — Sistema de diseño de marca personal

## Overview

Mi marca personal tiene una estética **sobria, elegante y minimalista**. La presencia monumental nace de la escala del monograma HAR y del espacio libre que lo rodea: en la firma, la H, la A y la R comparten trazos y cada letra se distingue por los espacios que quedan entre ellas. Ese mismo principio gobierna el portafolio, donde acerco una imagen a su pie y dejo una pausa más amplia antes del siguiente proyecto.

Diseño principalmente para **reclutadores y profesionales del diseño**. Al abrir un proyecto quiero que reconozcan qué diseñé, cuál fue mi responsabilidad y dónde ver el resultado. La portada permite recorrer el trabajo de un vistazo; las páginas interiores dan espacio a las imágenes y a las decisiones que explican cada pieza.

La página se lee como una publicación impresa: tipografía con remates en las aperturas, texto de lectura sin adornos, líneas finas y mucho aire. La interfaz nunca compite con el trabajo: los colores fuertes se reservan para la acción y para un único punto de atención por pantalla.

## Colors

La paleta se apoya en dos neutros cálidos y dos acentos de la tierra. El marfil y el negro construyen la lectura; el oliva identifica la acción y el terracota señala un punto concreto.

- **Primary — Verde oliva (#3F5228):** identifica las acciones principales. Se aplica a botones, enlaces subrayados e indicadores de foco sobre marfil, y puede usarse como fondo de introducción cuando quiero destacar la firma. La combinación oliva–marfil alcanza un contraste de **7.60:1**.
- **Tertiary — Terracota (#D8492E):** dirige la atención a un punto concreto, como la línea bajo la sección activa del menú o la marca junto a «Proyecto destacado». Sobre marfil alcanza **3.79:1**, por lo que se usa en indicadores gráficos y, de forma puntual, en títulos de al menos 24 px. Cuando acompaña una etiqueta pequeña, las palabras se escriben en oliva o negro.
- **Neutral — Marfil suave (#F4F1EA):** es el fondo principal de páginas, tarjetas y formularios. También se usa para texto, iconos y monograma sobre superficies oliva.
- **On-surface — Negro (#111111):** es la tinta de lectura. Se usa para el monograma sobre marfil, los párrafos, los datos profesionales y la información escrita en los campos. Sobre marfil alcanza **16.74:1**.

El terracota no se usa como color de texto pequeño ni como color de error tipográfico: en los formularios, el mensaje se escribe en negro y una marca terracota lo acompaña.

## Typography

Uso **Cinzel** para abrir páginas y secciones: sus remates en cuña dialogan con las terminaciones del monograma HAR. **Fira Sans** acompaña la lectura y las acciones del portafolio. Los usos se organizan en cinco variantes:

- **Cinzel Medium 500 · Portada y título de proyecto:** encabezado principal de cada página. En escritorio, 64 px con 72 px de interlineado; en móvil, 40 px con 48 px. Si el nombre del proyecto es largo, puede ocupar dos líneas.
- **Cinzel Regular 400 · Títulos de sección:** identifica capítulos como «Proyectos», «Experiencia» y «Formación». En escritorio, 40 px con 48 px de interlineado; en móvil, 28 px con 36 px.
- **Fira Sans SemiBold 600 · Títulos de ficha y énfasis:** nombre de cada proyecto dentro de una tarjeta, puestos y programas de formación. En escritorio, 24 px con 30 px de interlineado; en móvil, 20 px con 26 px. Para destacar una frase dentro de un párrafo se mantiene el tamaño y solo cambia el peso.
- **Fira Sans Regular 400 · Lectura y datos:** párrafos, descripciones y campos. El cuerpo principal va a 18 px con 27 px de interlineado en escritorio y a 16 px con 24 px en móvil. Fechas, pies de imagen y avisos legales usan 14 px con 20 px.
- **Fira Sans Medium 500 · Navegación e interfaz:** botones, menús y etiquetas de formulario a 16 px con 24 px de interlineado. Las etiquetas breves de categorías y herramientas van a 14 px con 20 px. Los enlaces dentro de un párrafo heredan su tamaño e interlineado y llevan subrayado.

Para cubrir las cinco variantes se guardan cuatro archivos WOFF2 en la carpeta de assets: un archivo variable de Cinzel para los pesos 400 y 500, y tres archivos de Fira Sans, uno por cada peso (400, 500 y 600). Se usa el subconjunto latino para conservar las tildes, la ñ y los signos de apertura del español.

## Layout

El diseño es primero para escritorio y se centra en un ancho máximo de **1240 px**. La cabecera, los títulos, las imágenes y las fichas comparten ejes de alineación. Una fotografía puede ocupar más columnas que su descripción, y el pie se alinea con el borde de la imagen para dejar clara su relación.

La escala de espaciado parte de **6 px**: 6, 12, 18, 24, 36, 48, 72, 108 y 144 px. Cada distancia se elige según la relación entre los elementos:

- **6–12 px** unen un icono con su etiqueta, un campo con su ayuda o una fotografía con su pie.
- **18–24 px** separan un título de su descripción, dos párrafos o dos controles relacionados.
- **24–48 px** distinguen grupos de contenido dentro de una sección. En una tarjeta amplia se dejan 36–48 px de espacio interior; en móvil se ajusta a 20–24 px.
- **72–144 px** marcan los cambios de sección en tableta y escritorio. En móvil se usan 48–60 px para conservar una pausa reconocible durante el desplazamiento.

La introducción se reparte en una retícula de 12 columnas: el título, la presentación y la acción principal ocupan siete columnas; el monograma ocupa las cinco restantes y conserva sus proporciones.

**Reglamento responsivo:**

- **Escritorio amplio (1440 px o más):** 12 columnas, contenido centrado en 1240 px, márgenes laterales de 72–96 px y 108–144 px entre secciones. La presentación y el monograma se muestran en paralelo.
- **Escritorio compacto (1024–1439 px):** 12 columnas, márgenes de 48–64 px y 108 px entre secciones. Si un título necesita más ancho, se permite un salto de línea antes de modificar su tamaño.
- **Tableta (768–1023 px):** 8 columnas, márgenes de 32 px y 72 px entre secciones. Dos fichas por fila, cada una sobre cuatro columnas. Cuando los nombres del índice dejan de caber, se activa el menú «Secciones».
- **Móvil (320–767 px):** retícula de 4 columnas, márgenes de 16–20 px y un flujo principal. Cada ficha ocupa las cuatro columnas, las secciones se separan entre 48 y 60 px, los campos se apilan y cada acción permanece junto al contenido al que pertenece. Título principal a 40 px, títulos de sección a 28 px y cuerpo de lectura de 16 px como mínimo.

## Elevation & Depth

La composición es **principalmente plana**. La escala de los títulos, la separación entre bloques y los cambios de fondo organizan la página; la profundidad aparece solo cuando algo ocurre en pantalla.

- **En reposo:** tarjetas, botones, campos y navegación permanecen sin sombra. Un borde delimita el campo de escritura y un fondo oliva identifica el botón principal.
- **Al pasar el cursor por una ficha enlazada:** se subraya el título y se aplica una sombra difusa de `0 8px 24px rgba(17, 17, 17, 0.06)`. La elevación indica que el proyecto se puede abrir. Una ficha exclusivamente informativa permanece plana.
- **Al navegar con teclado:** el control enfocado muestra un contorno de 2 px separado 3 px del borde. Se usa oliva sobre superficies marfil y marfil sobre superficies oliva.
- **Al abrir un menú o panel emergente:** fondo sólido y sombra de `0 12px 36px rgba(17, 17, 17, 0.10)`. El borde del panel y la sombra lo distinguen del contenido que queda debajo.
- **En la introducción:** se puede aplicar un desenfoque de 24–48 px a una mancha de color situada detrás de la composición. El monograma, el texto y las fotografías que documentan el trabajo permanecen nítidos.

## Shapes

La forma es **arquitectónica y contenida**. Botones, tarjetas, campos y paneles usan un radio de **4 px**: la cantidad justa de suavidad para sentirse contemporáneos sin perder rigidez. No se usan píldoras ni radios grandes, salvo el avatar, que es circular.

El borde delimita las superficies sin decorarlas: 1 px en campos y botones secundarios; 2 px en el contorno de foco, separado 3 px del borde. Los estados deshabilitados se reconocen por un borde discontinuo, nunca por una reducción de contraste que oculte la etiqueta.

El monograma conserva siempre sus proporciones: no se estira, no se comprime y mantiene aire suficiente alrededor para distinguir la H, la A y la R.

## Components

**Botones.** El botón principal lleva fondo oliva, texto marfil en Fira Sans 500 a 16 px, radio de 4 px y espacio interior de 12 px verticales y 24 px horizontales. La etiqueta anticipa el resultado, como «Ver proyecto» o «Descargar CV». El botón secundario mantiene las medidas y usa fondo marfil con texto y borde oliva de 1 px. Al pasar el cursor se subraya la etiqueta; al presionar aparece un borde interior de 2 px. Si la acción está deshabilitada se usa un borde discontinuo, se impide la activación y se explica el motivo cuando la persona necesita hacer algo para continuar.

**Tarjetas y contenedores.** Cada ficha de proyecto presenta la imagen, el nombre en Fira Sans 600, la descripción en Fira Sans 400 y un enlace oliva subrayado. Fondo marfil, radio de 4 px y espacio interior de 36–48 px en escritorio. En una pieza destacada, una línea terracota acompaña la etiqueta «Proyecto destacado».

**Sección de introducción.** En escritorio, el título, la presentación y la acción principal ocupan siete columnas; el monograma ocupa las cinco restantes y conserva sus proporciones. Se usa la versión negra sobre marfil o la versión marfil sobre oliva. En móvil se agrupan el título, la presentación y la acción para que el acceso a los proyectos quede junto al texto que los introduce.

**Campos y formularios.** La etiqueta va en Fira Sans 500, 6 px por encima del campo. El campo lleva fondo marfil, borde oliva de 1 px, radio de 4 px y espacio interior de 12 px verticales y 18 px horizontales. El dato escrito aparece en negro, en Fira Sans 400 a 16 px como mínimo. Ante un error se conserva el dato y se explica debajo cómo corregirlo; una marca terracota puede acompañar una indicación como «Incluye el dominio después de la @», pero el texto se escribe en negro u oliva.

**Navegación y enlaces.** La cabecera usa fondo marfil y texto oliva en Fira Sans 500. Al pasar el cursor, el enlace muestra un subrayado oliva. La sección actual conserva una línea terracota de 3 px bajo su nombre. Los enlaces dentro de los párrafos están subrayados desde el inicio. En móvil, el botón «Secciones» abre el índice con los mismos nombres y en el mismo orden.

**Iconos sociales y contacto.** Los iconos miden 24 × 24 px dentro de un área interactiva mínima de 44 × 44 px. Cada enlace tiene un nombre accesible que identifica su destino. Cuando el icono acompaña una acción escrita, como «Enviar correo», se dejan 12 px entre el símbolo y el texto.

**Etiquetas, avatar y habilidades.** Las etiquetas de disciplinas y herramientas llevan Fira Sans 500 a 14 px, fondo marfil, texto oliva y borde fino, con espacio interior de 6 px verticales y 12 px horizontales. Las habilidades se agrupan por categoría y las etiquetas pueden pasar a la siguiente línea. El avatar acompaña el nombre y la función dentro del perfil.

**Formación, experiencia y recursos.** Cada entrada comienza con el puesto o el programa en Fira Sans 600. La institución, el periodo y la descripción van en Fira Sans 400. En escritorio la fecha puede alinearse a la derecha; en móvil se coloca debajo de la institución. Cuando hay un recurso asociado, el enlace identifica el documento, por ejemplo «Descargar portafolio en PDF».

## Do's and Don'ts

**Sí:**

- Mantener un contraste mínimo de 4.5:1 para texto normal y 3:1 para texto grande. Para lectura extensa, usar negro sobre marfil o marfil sobre oliva.
- Reservar Cinzel para portadas y aperturas de sección; en fichas, párrafos y controles usar el peso de Fira Sans que corresponda a su función.
- Alinear cada imagen con su pie y dejar menos espacio entre un título y su descripción que entre dos proyectos consecutivos.
- Conservar las proporciones del monograma y dejar aire suficiente alrededor para distinguir la H, la A y la R.
- Mantener un área mínima de 44 × 44 px en botones y controles de icono, hacer visible el foco de teclado y acompañar los estados de selección o error con una línea, una marca o un mensaje.
- Usar el terracota en indicadores gráficos y en títulos de al menos 24 px.
- Mantener la misma acción disponible con ratón, teclado y pantalla táctil.

**No:**

- Usar terracota para fechas, etiquetas pequeñas e instrucciones de formulario sobre marfil; en esos casos, aplicarlo solo a una marca junto al texto.
- Sumar pesos tipográficos para separar contenidos que se pueden agrupar mediante alineación o espaciado.
- Comprimir los márgenes para introducir una tarjeta adicional en la fila.
- Estirar o desenfocar el monograma, ni colocarlo sobre imágenes que oculten sus trazos finos.
- Elevar fichas estáticas u ocultar acciones esenciales hasta que pase el cursor.
- Mezclar radios: el radio de 4 px es la norma y las píldoras no forman parte del sistema.
- Usar sombras para separar bloques de contenido; para eso están el espacio y el cambio de fondo.

## Notas de revisión

Los siguientes valores no estaban especificados en el documento original y se completaron con un criterio razonable. Están marcados para revisión:

- **letterSpacing:** el documento no define tracking. Se fijó en `0em` para todas las variantes; conviene revisar los títulos en Cinzel, donde un ligero tracking positivo puede mejorar la lectura en mayúsculas.
- **Avatar:** se asumió circular, de 64 px, con radio `full`. El documento solo indica que acompaña el nombre y la función.
- **Alturas de control:** botones e iconos usan 44 px de alto o de área interactiva, derivado del mínimo de 44 × 44 px indicado para accesibilidad.
- **Espaciado interno:** las tarjetas usan el extremo inferior del rango (36 px en escritorio, 20 px en móvil); los márgenes de sección usan 108/72/48 px. Los rangos completos se describen en prosa.
- **Estados:** el hover del botón oliva no oscurece el fondo —solo subraya la etiqueta— y el estado presionado se resuelve con un borde interior de 2 px, tal como describe el documento. No se definieron colores adicionales para `disabled`.
- **Error:** el token `error` reutiliza el terracota, pero por su contraste de 3.79:1 solo se admite como marca o línea; el mensaje se escribe en negro u oliva.
- **Bordes:** el esquema de tokens no admite `borderColor` como sub-token de componente (el linter lo marca como no reconocido), así que el color queda en `colors.border` y las reglas —1 px en campos y botones secundarios, 2 px en el foco— se describen en prosa.
- **Elevación:** el esquema de tokens de DESIGN.md no incluye sombras, así que los valores de profundidad quedan documentados en la sección *Elevation & Depth*.
