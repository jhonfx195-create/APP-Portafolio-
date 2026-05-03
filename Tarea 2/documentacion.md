# Documentación: Tarea 2 - Hoja de Vida Personal (Curriculum Vitae)

## 1. Descripción del Proyecto
Este proyecto consiste en el diseño y desarrollo de una página web estática que funciona como un Curriculum Vitae (Hoja de Vida Personal). Ha sido desarrollada utilizando exclusivamente **HTML5** para la estructura y **CSS3** para los estilos visuales, cumpliendo con todos los requisitos solicitados en la Tarea 2.

## 2. Estructura del Código (HTML)
El código HTML está estructurado haciendo uso intensivo de contenedores `<div>` para separar la información en bloques lógicos. La hoja de vida se divide visualmente en dos columnas principales dentro de un contenedor global (`.cv-container`):

*   **Columna Izquierda (`.left-column`)**:
    *   **Datos personales con foto**: Incluye la imagen de perfil (`imagenCV.jpeg`), nombre, título profesional y una lista desordenada (`<ul>`) con los datos de contacto esenciales e información personal (Teléfono, Email, Ubicación, Nacimiento).
*   **Columna Derecha (`.right-column`)**:
    *   **Estudios Realizados**: Estructurado usando etiquetas para títulos (`<h3>`, `<h4>`) e información detallada separada en bloques `<div>`.
    *   **Experiencia Laboral**: Emplea divisores similares (`.list-wrapper`) para listar los trabajos previos.
    *   **Capacitaciones**: Enumera los cursos y talleres completados, con fecha e institución.
    *   **Referencias Personales**: Se implementó el elemento `<table>` (tabla) con sus respectivas filas (`<tr>`), cabeceras (`<th>`) y celdas (`<td>`) organizando la información de 3 referencias con columnas para "Nombre", "Cargo/Profesión", "Teléfono" y "Correo electrónico".


## 3. Diseño y Estilos (CSS)
Los estilos están embebidos en el la cabecera `<head>` dentro de la etiqueta `<style>`. Las técnicas implementadas incluyen:
*   **Variables CSS (`:root`)**: Para mantener una paleta de colores consistente (primario, secundario, fondos y textos).
*   **Flexbox**: Uso extensivo de `display: flex` para alinear y centrar las columnas del CV de manera eficiente, así como para distribuir elementos internos.
*   **Diseño Responsivo (Responsive Design)**: Se uso `Media Queries` (`@media (max-width: 768px)`) para garantizar que la pantalla adapte su diseño dividiéndose de 2 columnas a 1 diseño de una sola columna para dispositivos móviles.
*   **Estilos de elementos**: Mejoras visuales tipo sombra de caja (`box-shadow`), bordes redondeados (`border-radius`) y personalización interactiva a filas de la tabla (como `hover`).

## 4. Ejecución del Código
Para llevar a cabo la visualización local de este proyecto, siga estos pasos:
1. Asegúrese de que ambos archivos, `cv.html` y la imagen `imagenCV.jpeg`, se encuentran en el mismo directorio/carpeta.
2. Haga doble clic sobre el archivo `cv.html`, o alternativamente, haga clic derecho sobre él, seleccione "Abrir con" y elija su navegador web preferido (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).
3. La hoja de vida cargará automáticamente con todos sus estilos y mostrará la tabla y la imagen incorporadas de manera local.

## 5. Enlace al Repositorio de GIT
A continuación, se facilita el enlace público al control de versiones de la tarea solicitada:

**Link de Git:** [https://github.com/jhonfx195-create/Aplicaciones-cliente--web]

---
