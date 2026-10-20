# Plantilla editorial multilingüe — Barracuda F.C.

Esta carpeta contiene el modelo para futuras noticias y artículos oficiales. No altera la portada ni publica contenido de ejemplo.

## Idiomas
- es: Español (original institucional)
- en: English
- pt: Português
- fr: Français
- de: Deutsch
- it: Italiano

## Procedimiento para cada artículo
1. Redactar y aprobar primero el texto original en español. Comprobar nombres, fechas, categorías, fotografías y pies de foto.
2. Crear un archivo nuevo en la raíz con nombre corto y sin tildes, por ejemplo `noticia-nombre.html`. No sobrescribir `index.html` ni `mucho-mas-que-futbol.html`.
3. Mantener el diseño del artículo `mucho-mas-que-futbol.html`: encabezado institucional, selector de idioma, cuerpo, fotos reales con texto alternativo, firma al final y pie institucional.
4. Preparar traducciones COMPLETAS para los cinco idiomas adicionales. Traducir títulos, entradilla, párrafos, subtítulos, notas, pies de foto y texto alternativo. Mantener nombres propios y hechos históricos.
5. Guardar las fotografías originales en una carpeta exclusiva del artículo, por ejemplo `imagenes/nombre-articulo/`, para evitar sobrescribir las de otras noticias.
6. Incluir el mismo selector de idiomas ES / EN / PT / FR / DE / IT y utilizar la preferencia guardada en `localStorage` bajo `barracuda-lang`, igual que el primer artículo.
7. Revisar las seis versiones y todas las fotografías en móvil y escritorio. Evitar mostrar un texto en español bajo una opción de otro idioma; si falta traducción, indicar que está pendiente.
8. Solo tras aprobar el artículo, agregar su enlace a la sección Noticias de `index.html`; mantener accesibles las noticias anteriores.
9. Comprobar el despliegue de GitHub Pages y los enlaces públicos.

## Criterios editoriales
- La Ciudad Deportiva Barracuda 2026–2046 debe describirse como proyecto en planificación, nunca como obra ejecutada.
- No anunciar `presidencia@barracudafc.com` como correo operativo hasta confirmar su activación.
- Utilizar únicamente fotografías auténticas y autorizadas del club.
- La firma del autor va al final del artículo.
- Revisar las traducciones antes de su difusión internacional.

## Referencia de implementación
Artículo multilingüe de referencia: [Barracuda F.C.: mucho más que fútbol](../mucho-mas-que-futbol.html).

**Nota:** Esta es una guía editorial y técnica. Cada artículo nuevo requiere su propio contenido y traducciones; no se publican noticias ficticias.
