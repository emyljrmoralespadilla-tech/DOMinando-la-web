# Galería de Imágenes — Interactiva (Bootstrap)

Proyecto: Galería interactiva que permite agregar imágenes por URL, filtrar por categoría y eliminar elementos. Las imágenes iniciales se cargan desde internet (picsum).

## Funcionalidades incluidas
- Imágenes iniciales cargadas desde internet (picsum.photos).
- Agregar imágenes por URL y categoría (formulario validado).
- Filtrado por categoría con botones (delegación de eventos, active state).
- Eliminar imágenes (delegación en la galería).
- Persistencia en localStorage (`gallery_images_v1`).
- Modo oscuro / claro persistente.
- Diseño responsive con Bootstrap 5.
- Accesibilidad básica (aria-live, labels, roles, foco visible).

## Estructura
```
index.html
/css/styles.css
/js/app.js
/img/ (opcional, vacío)
README.md
```

## Uso
1. Abre `index.html` en tu navegador.
2. Añade imágenes pegando una URL (http/https) y seleccionando categoría.
3. Filtra por categoría con los botones o limpia filtros con "Limpiar filtros".
4. Presiona "Eliminar" en una tarjeta para borrarla. Las imágenes se guardan en localStorage.

Hecho por *Tu Nombre* — ADSO / SENA
