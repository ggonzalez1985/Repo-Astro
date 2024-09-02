---
title: App Web con ASP.NET WebForms
publishDate: 2020-03-04 00:00:00
img: /assets/Default.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
 ASP.Net WebForms + SQL Server 2019 + POO
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
    <a class="tag" href="https://github.com/ggonzalez1985/TPFinalNivel3_Gonzalez.git" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
        <path d="M12 0C5.37 0 0 5.37 0 12c0 5.304 3.438 9.796 8.206 11.4.6.111.823-.26.823-.577v-2.22c-3.338.724-4.042-1.607-4.042-1.607-.546-1.38-1.333-1.748-1.333-1.748-1.088-.745.083-.729.083-.729 1.206.084 1.838 1.236 1.838 1.236 1.071 1.832 2.807 1.3 3.494.996.107-.774.418-1.3.762-1.597-2.665-.303-5.466-1.335-5.466-5.935 0-1.309.469-2.379 1.237-3.22-.125-.303-.536-1.528.117-3.183 0 0 1.008-.322 3.308 1.23.958-.266 1.985-.398 3.005-.402 1.02.004 2.048.136 3.004.402 2.297-1.552 3.306-1.23 3.306-1.23.652 1.655.243 2.88.117 3.183.77.841 1.236 1.91 1.236 3.22 0 4.61-2.81 5.632-5.481 5.92.43.371.821 1.102.821 2.223v3.292c0 .319.221.69.826.573C20.564 21.796 24 17.304 24 12 24 5.37 18.63 0 12 0z"/></svg>GitHub</a>
    <a class="tag" href="https://www.youtube.com/watch?v=O-NJLU6kEts" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
        <path d="M23.498 6.186a2.998 2.998 0 00-2.11-2.122C19.482 3.5 12 3.5 12 3.5s-7.482 0-9.389.564a2.998 2.998 0 00-2.109 2.122C0 8.09 0 12 0 12s0 3.91.502 5.814a2.998 2.998 0 002.109 2.122C4.518 20.5 12 20.5 12 20.5s7.482 0 9.389-.564a2.998 2.998 0 002.109-2.122C24 15.91 24 12 24 12s0-3.91-.502-5.814zM9.751 15.509V8.491L15.682 12l-5.931 3.509z"/></svg>YouTube</a>
    <a class="tag" href="http://catalogo-web.somee.com/" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="black" viewBox="0 0 24 24">
        <path d="M12 2a1 1 0 0 1 .707.293l8 8a1 1 0 1 1-1.414 1.414L13 5.414V20a1 1 0 0 1-2 0V5.414L4.707 11.707a1 1 0 0 1-1.414-1.414l8-8A1 1 0 0 1 12 2z"/></svg>Deploy</a>
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



#### Aplicación Web con ASP.NET WebForms

 Permite a los usuarios gestionar y organizar sus artículos de manera eficiente a través de las siguientes funcionalidades clave:

- **Listado de Artículos**: Visualiza todos los artículos disponibles en una interfaz amigable y organizada.<br><br>

- **Búsqueda Avanzada**: Encuentra rápidamente artículos utilizando criterios como nombre, categoría o código.<br><br>

- **Agregar Artículos**: Añade nuevos artículos al catálogo, incluyendo detalles como nombre, descripción, precio, y más.<br><br>

- **Modificación de Artículos**: Edita y actualiza la información de los artículos existentes de manera sencilla.<br><br>

- **Eliminación de Artículos**: Gestiona la eliminación de artículos del sistema de forma segura y controlada.<br><br>

- **Detalles de Artículos**: Accede a información detallada de cada artículo, incluyendo imágenes y especificaciones.<br><br>


