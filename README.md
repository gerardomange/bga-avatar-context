# Base de Conocimiento para Asesor Virtual BGA

Este repositorio contiene un sitio estático público de prueba para alimentar el Live Avatar de BGA Business mediante URLs públicas.

El sitio es una prueba temporal mientras no se tiene acceso al WordPress de BGA. El contenido de las páginas HTML fue extraído de los PDFs fuente incluidos en el folder del proyecto y convertido a texto HTML real para facilitar lectura por scrapers y herramientas de IA.

## Archivos principales

- `index.html`: índice general del sitio.
- `avatar-contexto-completo.html`: p?gina consolidada con el contenido textual de todas las p?ginas para usar cuando LiveAvatar solo acepta un URL.
- `contexto-general.html`: contenido de Contexto General BGA.
- `faq-bga.html`: preguntas frecuentes de BGA.
- `sectores-resultados.html`: sectores, experiencia y resultados documentados.
- `testimonios-casos.html`: testimonios y casos documentados.
- `metodologia-bga.html`: metodología BGA, autodiagnóstico, 4x3, Gestión Horizontal y PASER.
- `styles.css`: estilos visuales del sitio.

## Cómo editar las páginas

1. Abre el archivo HTML que quieras modificar.
2. Edita únicamente el texto dentro de la sección de contenido correspondiente.
3. Conserva la estructura semántica con `header`, `nav`, `main`, `section`, `article` y `footer`.
4. No incrustes PDFs, screenshots ni imágenes como sustituto del contenido textual.
5. Verifica que el contenido siga siendo texto HTML real y legible.

## Cómo activar GitHub Pages

1. Ir a `Settings`.
2. Entrar a `Pages`.
3. En `Source`, seleccionar `Deploy from branch`.
4. En `Branch`, seleccionar `main`.
5. En `Folder`, seleccionar `root`.

## Cómo usar las URLs en LiveAvatar

Después de activar GitHub Pages, copia las URLs finales de cada página HTML y pégalas como fuentes públicas de contexto en LiveAvatar.

URLs esperadas si el repositorio se publica como `bga-avatar-context`:

- `https://USUARIO.github.io/bga-avatar-context/avatar-contexto-completo.html`
- `https://USUARIO.github.io/bga-avatar-context/contexto-general.html`
- `https://USUARIO.github.io/bga-avatar-context/faq-bga.html`
- `https://USUARIO.github.io/bga-avatar-context/sectores-resultados.html`
- `https://USUARIO.github.io/bga-avatar-context/testimonios-casos.html`
- `https://USUARIO.github.io/bga-avatar-context/metodologia-bga.html`

## Recomendación de prueba

Antes de pegar las URLs en LiveAvatar, abre cada URL en una ventana incógnita para confirmar que las páginas son públicas y accesibles sin login.
