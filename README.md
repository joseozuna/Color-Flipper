# Cambiador de Colores de Fondo

Este proyecto es una simple aplicación web que cambia el color de fondo de la página al hacer clic en un botón. Los colores son seleccionados aleatoriamente de una lista predefinida de colores.

## Descripción

La aplicación consta de un botón y un elemento de texto que muestra el color actual del fondo. Al hacer clic en el botón, el color de fondo de la página cambia a uno de los colores definidos en el array `colors`. El nombre del color también se actualiza en el elemento de texto.

## Estructura del Proyecto

El proyecto incluye los siguientes archivos:

- `index.html`: Contiene la estructura HTML de la página.
- `style.css`: Define los estilos CSS para la página.
- `app.js`: Contiene el código JavaScript que maneja la lógica de cambio de color.

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cambiador de Colores</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <main>
        <div class="container">
            <h2>Color de fondo: <span class="color">#f1f5f8</span></h2>
            <button id="btn" class="btn">Cambiar Color</button>
        </div>
    </main>
    <script src="app.js"></script>
</body>
</html>
