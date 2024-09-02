---
title: App Escritorio con .NET Framework
publishDate: 2020-03-02 00:00:00
img: /assets/TP2.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  .Net Framework 4.8 + SQL Server 2019 + POO
tags:
  - .NET Framework
  - C#
  - SQL
  - POO
  - GitHub
---

<div class="tag-container">
    <a class="tag" href="https://github.com/ggonzalez1985/TPFinalNivel2_Gonzalez.git" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
        <path d="M12 .297c-6.627 0-12 5.373-12 12 0 5.305 3.438 9.8 8.118 11.4.593.113.81-.257.81-.573v-2.044c-3.305.722-4.003-1.577-4.003-1.577-.541-1.371-1.322-1.734-1.322-1.734-1.082-.741.083-.725.083-.725 1.197.084 1.823 1.226 1.823 1.226 1.064 1.82 2.795 1.294 3.477.991.107-.771.417-1.294.76-1.594-2.665-.306-5.467-1.334-5.467-5.93 0-1.31.469-2.376 1.237-3.22-.124-.305-.537-1.527.118-3.176 0 0 1.012-.324 3.312 1.236.96-.267 1.989-.4 3.014-.404 1.024.003 2.055.137 3.013.404 2.299-1.56 3.311-1.236 3.311-1.236.655 1.649.242 2.871.118 3.176.768.844 1.236 1.91 1.236 3.22 0 4.614-2.81 5.624-5.478 5.926.431.372.81 1.102.81 2.222v3.293c0 .318.215.691.822.574C20.563 22.098 24 17.605 24 12.297c0-6.627-5.373-12-12-12z"/></svg>GitHub</a>
    <a class="tag" href="https://www.youtube.com/watch?v=SLwDc7Ksgps" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
        <path d="M23.498 6.186a2.998 2.998 0 00-2.11-2.122C19.482 3.5 12 3.5 12 3.5s-7.482 0-9.389.564a2.998 2.998 0 00-2.109 2.122C0 8.09 0 12 0 12s0 3.91.502 5.814a2.998 2.998 0 002.109 2.122C4.518 20.5 12 20.5 12 20.5s7.482 0 9.389-.564a2.998 2.998 0 002.109-2.122C24 15.91 24 12 24 12s0-3.91-.502-5.814zM9.751 15.509V8.491L15.682 12l-5.931 3.509z"/></svg>YouTube</a>
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

### Aplicación de escritorio para la gestión de un catalogo de artículos.


Permite a los usuarios gestionar y organizar sus artículos de manera eficiente con las siguientes funcionalidades clave:

- **Listado de Artículos**: Muestra todos los artículos disponibles en una interfaz clara y organizada, facilitando la visualización del catálogo completo.<br><br>

- **Búsqueda de Artículos**: Permite encontrar artículos de manera rápida mediante distintos criterios como nombre, categoría o código, optimizando la búsqueda dentro del catálogo.<br><br>

- **Agregar Artículos**: Facilita la inclusión de nuevos artículos en el catálogo, permitiendo la introducción de detalles como nombre, descripción y precio.<br><br>

- **Modificar Artículos**: Ofrece herramientas para editar y actualizar la información de artículos existentes, asegurando que los datos sean siempre precisos y actuales.<br><br>

- **Eliminar Artículos**: Gestiona la eliminación de artículos del sistema de manera segura, garantizando que el proceso se realice de forma controlada y sin errores.<br><br>

- **Ver Detalle de un Artículo**: Proporciona acceso a información detallada sobre cada artículo, incluyendo especificaciones y características completas.
