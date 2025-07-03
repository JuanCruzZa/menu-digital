# 🍝 Menú Digital – Restaurante Italiano  
**Trabajo Práctico 2 (HTML + CSS estático, sin Flexbox / Grid)**

Este proyecto corresponde al TP 2 del curso **Full Stack UTN**.  
Consiste en una página web que muestra el menú de un restaurante italiano ficticio.

---
## 🚀 Cómo ver el proyecto
- **Demo en GitHub Pages**: <https://juancruzza.github.io/menu-digital/>
---

## 🎯 Objetivo de la consigna

> **Crear** un menú con HTML & CSS **básico** que incluya:  
> - Nombre del restaurante  
> - 3 – 4 platos con **nombre, imagen, descripción y precio**  
> - Uso de `<h1> <h2> <p> <img> <ul> <li>`  
> - CSS externo con fondo, tamaños de fuente, bordes/separación y **colores coherentes**  
> - **Sin Flexbox ni Grid**  
> - **Desafíos opcionales**: sección de postres/bebidas, enlaces `mailto:` y `tel:`

---

## ✅ Cómo se cubrió cada punto

| Requisito | Implementación en el proyecto |
|-----------|------------------------------|
| **HTML estructurado** | `<h1>` nombre del sitio; `<h2>` secciones; `<p>` descripciones; `<img>` cada plato; `<ul><li>` lista de bebidas. |
| **CSS externo** | Archivo `css/style.css` enlazado en `<head>`. |
| **Fondo de color** | `main { background-color: whitesmoke; }` y degradado gris semitransparente en el `header`. |
| **Tamaños de fuente** | 100 px (`h1`), 60 px (`h2`), 30 px (`h3`), 20–25 px texto. |
| **Bordes / separación** | Bordes de 3 px en imágenes y títulos (`h3`); márgenes y paddings para separar cada `.plato`. |
| **Colores coherentes** | Paleta “bandera italiana”: rojo vino (`h2`), verde oscuro (`h3`), blanco. |
| **Sin Flex / Grid** | Imágenes centradas con `text-align:center` (en `.plato`) y `margin:auto`; layout fluido estándar. |
| **Opcional 1 – Sección de bebidas/postres** | `<ul><li>`Bebidas con lista de precios. |
| **Opcional 2 – Enlaces `mailto:` y `tel:`** | Footer con enlaces de correo y teléfono. |

---

## 🧩 Estructura del proyecto
````
menu-digital/
├── index.html
├── css/
│ └── style.css
├── img/
│ ├── Bolognesa.png
│ ├── Burrata.png
│ ├── Carbonara.png
│ ├── Margherita.png
│ ├── Marinara.png
│ ├── Pepperoni.png
│ ├── Salssa de tomate.png
│ └── restaurante.jpg
└── README.md
