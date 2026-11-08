# Órbita 2: sistema visual de [nombre de tu aplicación]

## Enlaces

| Qué | Enlace |
|---|---|
| Archivo de Figma (versión "Entrega Órbita 2") | https://www.figma.com/design/fXkjqkbQOoF6tKuPvWUBe0/Proyecto-interfaz-web?m=auto&t=zIcAYP8A1SB7xu6R-1|
| Prototipo (enlace que empieza por `figma.com/proto/`) | https://www.figma.com/proto/fXkjqkbQOoF6tKuPvWUBe0/Proyecto-interfaz-web?node-id=731-525&p=f&viewport=7203%2C-1575%2C0.7&t=4aXtkljcneIDRq1w-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=731%3A525&show-proto-sidebar=1&page-id=731%3A291|
| Proyecto de Google Stitch (solo si lo has usado) |https://stitch.google.com/projects/11943427591223915912 |

## Dónde está cada cosa en Figma

| Entregable | Página y sección del archivo |
|---|---|
| Inventario de decisiones | orbita 2 |
| Wireframes rediseñados con sus notas | orbita 2 |
| Componentes | componentes |
| Mockups del happy path | mockup |
| Pantalla principal en el segundo ancho | |
| Pantallas en modo oscuro | en el prototipo |
| Guía de estilo | orbita 2 |

## Lista de comprobación de Figma

- [X] Variables en dos colecciones (primitivos y semánticos), con alias, modos claro y oscuro, ámbito, descripción y sintaxis de código.
- [X] Estilos de texto, efecto y retícula vinculados a las variables.
- [X] Componentes con Auto layout, variables, propiedades y variantes de estado.
- [X] Mockups construidos enteros con Auto layout y espacios sacados de variables.
- [X] Pantalla principal en un segundo ancho, con los mismos componentes.
- [X] Modo oscuro aplicado con el selector de modo.
- [X] Prototipo que recorre el happy path completo.
- [X] Prueba 1 superada: al cambiar `color/primary`, cambian todas las pantallas a la vez.
- [X] Prueba 2 superada: con todos los mockups en modo oscuro, nada desaparece contra el fondo.

## Resumen de decisiones

### Rediseño de los wireframes
He cambiado practicamente todas las paginas, algunas son solo cambios mínimos en la que solo toco el radio de una caja o el tamaño de la letra y en otras cambio mas como esta estructurada, la forma y demas, estos cambios estan hechos asi porque asi el usuario podra tener un mejor visual de la aplicacion.

### Color
Para los colores he elegido como principal el azul vibrante (#092ED7) para destacar las acciones clave como los botones de reserva o guardar, y como secundario el azul marino profundo (#10264F) para dar contraste y orden en las cabeceras y menús, sumando el azul claro (#CCDEFF) de fondo para paneles y tarjetas para que la interfaz no resulte pesada al personal del hotel tras varias horas de trabajo. 

### Tipografía
Para la tipografía, he seleccionado Plus Jakarta Sans usando los pesos Regular (400), Medium (500) y Bold (700), porque al tener una gran altura de la "x" y formas limpias facilita mucho que un recepcionista distinga rápido los números de habitación y datos de clientes desde el móvil, mientras que a los administradores les resulta muy cómoda de leer en escritorio sin cansar la vista en jornadas largas.

### Espaciado y retícula
La base de la escala para los diferentes tamaños es de 8 en 8 tambien teniendo en cuenta el 4

### Componentes
Componentes realmente usados es el del modo claro u oscuro, hay mas en el proyecto pero no estan bien implementados.

### Responsive y modo oscuro
Cree una variable para poder trabajar con el modo oscuro para que al pulsar el icono se cambien los colores

## Uso de IA
La IA que se ha usado a sifo stitch ai para el rediseño de los wireframes de forma que segun el modelo generado yo em quedaba con las partes que me interesa implementar y lo adaptaba a mi wireframe, tambien he hecho uso de IA para cuando tenia dudas o no sabia como realizar alguna accion dentro de figma

El detalle está en el [CHANGELOG.md](CHANGELOG.md).

## Lo que ha quedado pendiente

Queda pendiente una buena implementacion de componentes y mejoras generales en proyecto
Lo que no has terminado o sabes que no funciona del todo, y por qué. Si está todo terminado, indícalo.
