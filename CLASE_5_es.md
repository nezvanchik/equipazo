# ¿Qué es HTML semántico?

📌 **Semántica** significa significado. Las etiquetas semánticas ayudan a los navegadores y las personas a comprender la estructura de la página.

## Etiquetas semánticas importantes

📝 Hacen que el código sea más comprensible:

| Etiqueta     | ¿Qué significa?                          |
|-------------|----------------------------------------|
| `<header>`  | Encabezado del sitio (logo, menú, título) |
| `<nav>`     | Navegación (menú)                      |
| `<main>`    | Contenido principal                    |
| `<article>` | Artículo o publicación individual       |
| `<section>` | Sección del sitio                      |
| `<aside>`   | Barra lateral (información adicional)  |
| `<footer>`  | Pie de página (contactos, redes sociales) |

`<div>` es universal, pero **no es semántico**. Un lector de pantalla no entenderá su significado.

### Ejemplo de código:

```html
<header>
  <h1>Mi blog</h1>
</header>
<nav>
  <ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Sobre mí</a></li>
  </ul>
</nav>
<main>
  <article>
    <h2>Primer artículo</h2>
    <p>Esta es mi primera publicación.</p>
  </article>
</main>
<footer>
  <p>&copy; 2024. Todos los derechos reservados.</p>
</footer>
```

❓ **¿Qué pasa si reemplazamos `<div>` en todas partes?**

❌ **Mal ejemplo:**

```html
<div>Menú</div>
<div>Título principal</div>
<div>Texto principal</div>
```

✅ **Buen código semántico:**

```html
<nav>Menú</nav>
<h1>Título principal</h1>
<p>Texto principal</p>
```

## Atributos HTML

Un atributo proporciona información adicional sobre una etiqueta.

| Atributo  | Descripción |
|-----------|----------------------------------------------------|
| `alt`     | Descripción de la imagen para personas con discapacidad visual o en caso de error de carga. |
| `title`   | Sugerencia emergente al pasar el cursor. |

Ejemplos:

```html
<img src="foto.jpg" alt="Foto del sol">
<a href="#" title="¡Haz clic aquí!">Clic</a>
```

## Importancia de un código accesible

👀 **¿Por qué es importante?**

Las personas con discapacidades visuales u otras limitaciones deben poder usar el sitio web.

🔹 **Principales reglas de accesibilidad:**

✅ Usa `alt` para las imágenes.  
✅ Agrega colores contrastantes para mejorar la legibilidad.  
✅ Usa encabezados claros `<h1>` - `<h6>`.  
✅ Permite la navegación con teclado (sin mouse).  

📌 **Ejemplo:**

❌ **Incorrecto:**

```html
<img src="perro.jpg">
```

✅ **Correcto:**

```html
<img src="perro.jpg" alt="Un lindo perro negro mirando a la cámara">
```

## Ejercicios prácticos 🎲

❓ **¿Qué pasa si una persona no puede ver la imagen?**  
El navegador no podrá "ver" la imagen, pero podrá leer el texto en `alt`. Si `alt` falta, la persona perderá información importante.

## ¿Cómo comprobar la accesibilidad de tu sitio?

✅ Usar un lector de pantalla.  
✅ Usar herramientas de accesibilidad del navegador.  
✅ Probar si el sitio funciona sin mouse (usando `Tab`).  
✅ Usar texto contrastante para que sea legible para personas con problemas visuales.  

## ¿Qué pasa si el navegador no carga CSS?

Si CSS no se carga, el sitio se mostrará como texto sin estilos.

📌 **Ejemplo sin CSS:**

- 🔹 **Si se usaron etiquetas semánticas** (`h1`, `p`, `nav`, `article`), el texto seguirá estructurado.  
- 🔹 **Si solo se usó `<div>`**, el texto quedará en un solo bloque, dificultando la comprensión de la página.  

💡 **Conclusión:** HTML semántico ayuda incluso sin CSS.

## Listas (`ul`, `ol`, `dl`)

📌 **¿Qué son las listas y para qué sirven?**
Las listas ayudan a estructurar información.

🔹 **Tipos de listas:**

✔ **Lista no ordenada (`ul`)** – cuando el orden no importa.  
✔ **Lista ordenada (`ol`)** – cuando el orden es importante.  
✔ **Lista de definiciones (`dl`)** – para explicar términos.  

❌ **Mal ejemplo (sin lista)**

```html
<p class="intro">Frutas: manzana, plátano, naranja</p>
```

✅ **Bien (lista no ordenada `ul`)**

```html
<ul>
  <li>Manzana</li>
  <li>Plátano</li>
  <li>Naranja</li>
</ul>
```

✅ **Bien (lista ordenada `ol`)**

```html
<ol>
  <li>Abrir el navegador</li>
  <li>Ir a Google</li>
  <li>Escribir la búsqueda</li>
</ol>
```

✅ **Lista de definiciones `dl`**

```html
<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcado para crear páginas web</dd>
  <dt>CSS</dt>
  <dd>Lenguaje de estilos para diseñar páginas web</dd>
</dl>
```

💡 **Conclusión:**  
HTML semántico mejora la accesibilidad, facilita la comprensión del código, ayuda a los motores de búsqueda y simplifica el mantenimiento del proyecto.