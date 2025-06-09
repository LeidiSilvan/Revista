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
<html lang="en">
<head>
    ...
</head>
<body>
    ...
</body>
</html>
```
- `<!DOCTYPE html>`: Indica que el documento es HTML5.
- `<html lang="en">`: Raíz del documento, con idioma inglés.
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

Define los estilos visuales de la página:
- Colores de fondo para cada sección.
- Distribución en cuadrícula para los artículos.
- Estilos para la navegación, imágenes, tipografía y espaciados.
- Uso de `flex` y `grid` para el diseño responsivo.

## Personalización

Puedes modificar los textos, imágenes y estilos para adaptar la revista a tus necesidades. Solo edita los archivos `index.html` y `style.css`.

## Cómo visualizar

1. Descarga o clona el repositorio.
2. Abre `index.html` en tu navegador web.

---
Proyecto realizado como ejemplo educativo para practicar HTML y CSS.
