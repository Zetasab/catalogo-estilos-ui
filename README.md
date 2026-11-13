# Catálogo de estilos UI

🔗 **Live:** [zetasab.github.io/catalogo-estilos-ui](https://zetasab.github.io/catalogo-estilos-ui/)

Un HTML sencillo para comparar distintos estilos de interfaz aplicados sobre los mismos componentes. Todo está en un único archivo, sin dependencias ni paso de build: basta con abrir `index.html` en el navegador.

## Qué incluye

- **Una lista de 35 estilos** agrupados por familia, cada uno con su nombre, una descripción corta y etiquetas.
- **Una tarjeta de muestra por estilo** (widget de "Peso actual") para verlos todos de un vistazo.
- **Una demo detallada** al abrir un estilo, con un conjunto fijo de componentes: título, campo de texto con ayuda, checkbox, switch, control segmentado, chips, badges, barra de progreso, alerta, tabla y botones (principal, secundario y fantasma).
- Navegación entre estilos (anterior / siguiente) desde la propia demo.

Como los componentes son siempre los mismos, lo único que cambia entre estilos es la apariencia, y así es fácil compararlos.

## Estilos

### Limpios y sobrios
Minimalismo suizo · Apple / iOS · Material Design 3 · Fluent 2 · IBM Carbon · shadcn/ui · Notion · Dark tech · Flat design · Editorial

### Volumen y textura
Glassmorphism · Liquid Glass · Neumorphism · Claymorphism · Skeuomorfismo · Aurora / mesh gradient · Frutiger Aero

### Expresivos
Neo-brutalismo · Brutalismo · Memphis · Bauhaus · Art Déco · Kawaii · Cyberpunk / neón · Bento grid

### Retro
Mac OS clásico · Windows 95 · Windows XP · Y2K · Synthwave · Pixel art / 8-bit · Terminal

### Cálidos y artesanales
Orgánico · Japandi · Dibujado a mano

## Añadir un estilo

Los estilos se definen en el array de grupos dentro del `<script>` del HTML (`id`, `name`, `desc`, `tags`). Cada `id` tiene sus reglas CSS asociadas para la tarjeta y para la demo.
