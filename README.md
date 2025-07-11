# Te lo Vendo

## Cambios:

### 1. Integración de Sass y Patrón 7-1

Los estilos del proyecto ahora usan Sass, siguiendo el patrón de arquitectura 7-1.

### 2. Reutilización de Código con Variables Sass

Valores comunes como colores, fuentes y espaciados se han centralizado en variables Sass (`scss/abstracts/_variables.scss`).

### 3. Estilos Mejorados con Anidamiento Sass

Se ha usado anidamiento Sass para pseudo-selectores (`:hover`, `:focus`) y cambios de estado (`&`), haciendo los estilos más legibles y contextuales.

### 4. Separación de Lógica Visual

La lógica visual se ha dividido en parciales (`_*.scss`), importados a través de `main.scss` usando `@use`. Esto mejora la modularidad y la claridad de las dependencias.
