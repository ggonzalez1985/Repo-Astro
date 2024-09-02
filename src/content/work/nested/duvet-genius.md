---

title: Aplicación Web con ASP.NET WebForms
publishDate: 2020-03-04 00:00:00
img: /assets/Default.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  Aplicación web interactiva para la gestión de artículos y datos.
tags:
  - ASP.NET
  - SQL
  - HTML
  - CSS
  - JS
  - GitHub
  - Bootstrap
---

<div class="tag-container">
    <a class="tag" href="https://github.com/ggonzalez1985/" target="_blank">
    <i class="fab fa-github" style="margin-right: 5px;"></i> GitHub
</a>
    <a class="tag" href="https://www.youtube.com/watch?v=O-NJLU6kEts" target="_blank">YouTube</a>
    <a class="tag" href="http://catalogo-web.somee.com/" target="_blank">Deploy</a>
</div>

<style>
    .tag-container {
        display: flex;
        gap: 0.75rem;
        flex-wrap: wrap;
    }

    .tag {
        display: flex;
        align-items: center;
        padding: 0.5rem 1rem;
        gap: 0.5rem;
        border-radius: 999rem;
        font-size: var(--text-md);
        font-weight: bold;
        line-height: 1.35;
        text-decoration: none;
        transition: background-color 0.3s, color 0.3s, transform 0.3s;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    /* Estilos para modo claro */
    @media (prefers-color-scheme: light) {
        .tag {
            color: #333; /* Texto oscuro */
            background-color: #f0f0f0; /* Fondo claro */
            border: 2px solid #ddd; /* Borde claro */
        }

        .tag:hover {
            background-color: #e0e0e0; /* Fondo un poco más oscuro al pasar el mouse */
            transform: scale(1.05);
        }

        .tag:active {
            background-color: #ccc; /* Fondo más oscuro al hacer clic */
        }
    }

    /* Estilos para modo oscuro */
    @media (prefers-color-scheme: dark) {
        .tag {
            color: #f0f0f0; /* Texto claro */
            background-color: #333; /* Fondo oscuro */
            border: 2px solid #444; /* Borde oscuro */
        }

        .tag:hover {
            background-color: #444; /* Fondo un poco más claro al pasar el mouse */
            transform: scale(1.05);
        }

        .tag:active {
            background-color: #555; /* Fondo más claro al hacer clic */
        }
    }
</style>



Gestión de Artículos en una Aplicación Web con ASP.NET WebForms

Permite a los usuarios gestionar y organizar sus artículos de manera eficiente a través de las siguientes funcionalidades clave:

- Listado de Artículos: Visualiza todos los artículos disponibles en una interfaz amigable y organizada.
- Búsqueda Avanzada: Encuentra rápidamente artículos utilizando criterios como nombre, categoría o código.
- Agregar Artículos: Añade nuevos artículos al catálogo, incluyendo detalles como nombre, descripción, precio, y más.
- Modificación de Artículos: Edita y actualiza la información de los artículos existentes de manera sencilla.
- Eliminación de Artículos: Gestiona la eliminación de artículos del sistema de forma segura y controlada.
- Detalles de Artículos: Accede a información detallada de cada artículo, incluyendo imágenes y especificaciones.


