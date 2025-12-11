Cosas importantes para crear la web:

--------------------------------------------------------------------------------------------------
            SUBIR IMÁGENES

En el front matter de cada producto usar la ruta /assets/img/nombre.jpg.
--------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------
            CREAR MÁS PRODUCTOS

Para añadir un producto nuevo: crear un nuevo archivo /_products/2025-12-01-nombre-producto.md o /_products/nombre-producto.md con la misma estructura de front matter. GitHub generará la página automáticamente.

(Recomendación de nombres: usar slugs claros sin acentos ni espacios, por ejemplo organizador-cajones-modular.)
--------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------
            SEO Y BUENAS PRÁCTICAS

- Títulos claros y orientados a intención de compra: “Mejor organizador de cajones para cocina pequeña”.
- excerpt corto y descriptivo (se usa en meta description si lo configuras).
- Usa al menos 400–800 palabras útiles por página de producto cuando compitas por keywords. Para páginas “Top 10” 800–1500 palabras suele funcionar mejor.
- Usa imágenes de calidad y alt text (alt).
- Añade enlaces internos entre productos y entre categorías (interlinking).
- Pon rel="nofollow sponsored" en tus enlaces afiliados (buena práctica).
- Añade datos de precio y marca en front matter para mostrarlos en el layout.
- Consistencia en la URL: /products/nombre-producto/.
--------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------
            USAR MÁS ADELANTE PLUGINS NO SOPORTADOS POR GITHUB PAGES

Algunos plugins Jekyll no son permitidos por el motor de Pages. Si en el futuro quieres usar plugins avanzados (p. ej. para generar sitemaps custom o paginación especial), te diré cómo crear un workflow de GitHub Actions que construya Jekyll con todos los plugins y despliegue el resultado. Pero ahora mismo no hacen falta para arrancar y posicionar bien.
--------------------------------------------------------------------------------------------------