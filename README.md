# Revista

Este proyecto es una página web sencilla que simula la portada de una revista digital. A continuación se explica la estructura, el propósito de cada archivo y el significado de las principales etiquetas y secciones utilizadas.

## Estructura del proyecto

- **index.html**: Archivo principal que contiene la estructura HTML de la página.
- **style.css**: Archivo de estilos CSS que define la apariencia visual de la web.
- **README.md**: Este archivo, con la documentación del proyecto.

## Explicación de `index.html`

### Estructura general

```html
<!DOCTYPE html>
<html lang="es">
<head>
    ...
</head>
<body>
    ...
</body>
</html>
```
- `<!DOCTYPE html>`: Indica que el documento es HTML5.
- `<html lang="es">`: Raíz del documento, con idioma Español.
- `<head>`: Contiene metadatos, título y enlace a la hoja de estilos.
- `<body>`: Contiene todo el contenido visible de la página.

### Secciones principales

#### 1. `<nav>` (Navegación)
Barra superior con el nombre de la revista y un menú de secciones.
- `<h1>`: Título principal de la revista.
- `<ul>` y `<li>`: Lista de secciones del menú (Último momento, Farandula, Más noticias, TV).

#### 2. `<main>` (Contenido principal)
Contiene una imagen destacada y un texto introductorio.
- `<img>`: Imagen principal de la portada.
- `<div>`: Contenedor del título y párrafo introductorio.
- `<h2>`: Subtítulo o titular destacado.
- `<p>`: Párrafo descriptivo.

#### 3. `<section>` (Artículos)
Sección con varios artículos de ejemplo.
- `<article>`: Cada uno representa una noticia o entrada.
- `<h3>`: Título del artículo.
- `<p>`: Resumen o contenido del artículo.

#### 4. `<footer>` (Pie de página)
Información de derechos reservados y nombre de la revista.
- `<h1>`: Nombre de la revista.
- `<p>`: Texto de derechos reservados.

## Explicación de `style.css`

El archivo `style.css` define la apariencia visual de la página web. A continuación se detallan las principales reglas y su función:

- **nav**: Establece el color de fondo de la barra de navegación, el espaciado interno (`padding`), y usa `flex` para alinear el título y el menú a los extremos.
- **ul**: Elimina los puntos de la lista y usa `flex` para mostrar los elementos del menú en línea, con separación entre ellos (`gap`).
- **div**: Aplica un margen horizontal para separar el contenido del borde.
- **img**: Define un ancho fijo para la imagen principal y usa `object-fit: cover` para que la imagen no se deforme y ocupe bien el espacio.
- **main**: Usa `flex` para colocar la imagen y el texto uno al lado del otro, y aplica un color de fondo y margen vertical.
- **article**: Da color de fondo a cada artículo, agrega espaciado interno y limita el ancho máximo para que los artículos sean compactos.
- **section**: Utiliza `grid` para organizar los artículos en tres columnas, con separación entre ellos (`gap`) y espaciado lateral (`padding`).
- **footer**: Usa `flex` para alinear el nombre de la revista y el texto de derechos reservados en los extremos, con color de fondo y espaciado.
- **h1**: Cambia la fuente del título principal a 'Times New Roman' para dar un aspecto más clásico.
- **body**: Define la fuente general de la página, elimina márgenes y rellenos por defecto, aplica el modelo de caja (`box-sizing: border-box`), limita el ancho máximo de la página y centra el contenido, además de establecer un color de fondo suave.

### Otras consideraciones
- Se utilizan colores suaves y agradables para dar un aspecto moderno y limpio.
- El uso de `flex` y `grid` permite que la página sea adaptable y responsiva, facilitando la visualización en diferentes tamaños de pantalla.
- Los márgenes y rellenos están pensados para que el contenido no quede pegado a los bordes y sea más legible.

Puedes modificar cualquier regla de este archivo para personalizar la apariencia de la revista según tus preferencias.

## Personalización

Puedes modificar los textos, imágenes y estilos para adaptar la revista a tus necesidades. Solo edita los archivos `index.html` y `style.css`.

## Cómo visualizar

1. Descarga o clona el repositorio.
2. Abre `index.html` en tu navegador web.

---
Proyecto realizado como ejemplo educativo para practicar HTML y CSS.
