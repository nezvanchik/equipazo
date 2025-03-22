¿Qué es HTML semántico?

📌 Semántica significa significado. Las etiquetas semánticas ayudan a los navegadores y a las personas a comprender la estructura de una página web.

Etiquetas semánticas importantes

📝 Ayudan a que el código sea más comprensible:

Etiqueta	¿Qué significa?
<header>	Encabezado del sitio (logotipo, menú, título)
<nav>	Navegación (menú)
<main>	Contenido principal
<article>	Artículo o publicación independiente
<section>	Sección del sitio
<aside>	Barra lateral (información adicional)
<footer>	Pie de página (contactos, redes sociales)

<div> es una etiqueta no semántica. Un lector de pantalla no podrá entender su propósito.

Ejemplo de código:

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

❓ ¿Qué sucede si reemplazamos todo con <div>?

❌ Mal ejemplo:

<div>Menú</div>
<div>Título principal</div>
<div>Texto principal</div>

✅ Buen código semántico:

<nav>Menú</nav>
<h1>Título principal</h1>
<p>Texto principal</p>

Atributos de HTML

Un atributo proporciona información adicional sobre una etiqueta.

Atributo	Descripción
alt	Descripción de la imagen para personas con discapacidad visual o en caso de error de carga.
title	Muestra un mensaje emergente al pasar el cursor.

Ejemplos:

<img src="photo.jpg" alt="Foto del sol">
<a href="#" title="¡Haz clic aquí!">Clic</a>

Importancia del código accesible

👀 ¿Por qué es importante?

Las personas con discapacidades visuales o motoras deben poder acceder al sitio web.

🔹 Principios básicos de accesibilidad:

✅ Usa alt para las imágenes.
✅ Agrega colores contrastantes para mejorar la legibilidad.
✅ Usa títulos claros con <h1> - <h6>.
✅ Asegúrate de que el sitio sea navegable con el teclado (sin ratón).

📌 Ejemplo:

❌ Mal código:

<img src="dog.jpg">

✅ Buen código:

<img src="dog.jpg" alt="Un lindo perro negro mirando a la cámara">

Ejercicios prácticos 🎲

❓ ¿Qué sucede si una persona no puede ver la imagen?
El navegador no podrá “ver” la imagen, pero podrá leer el texto alternativo en alt. Si alt falta, la persona perderá información importante.

¿Cómo comprobar la accesibilidad de tu sitio web?

✅ Usa un lector de pantalla.
✅ Usa herramientas de accesibilidad en el navegador.
✅ Verifica si el sitio es funcional sin ratón (usando la tecla Tab).
✅ Usa texto con buen contraste para facilitar la lectura.

¿Qué pasa si el navegador no puede cargar CSS?

Si CSS no se carga, el sitio se verá como texto sin estilos.

📌 Ejemplo sin CSS:
	•	🔹 Si se usaron etiquetas semánticas (h1, p, nav, article), el texto seguirá estando estructurado.
	•	🔹 Si solo se usó <div>, todo el texto aparecerá como un solo bloque y será difícil de entender.

💡 Conclusión: ¡El HTML semántico es útil incluso sin CSS!

Listas (ul, ol, dl)

📌 ¿Qué son las listas y para qué sirven?
Las listas ayudan a organizar la información.

🔹 Tipos de listas:

✔ Lista desordenada (ul) – cuando el orden no es importante.
✔ Lista ordenada (ol) – cuando el orden sí es importante.
✔ Lista de definiciones (dl) – cuando se necesita explicar términos.

❌ Mal ejemplo (sin lista):

<p class="intro">Frutas: manzana, plátano, naranja</p>

✅ Buen ejemplo (lista desordenada ul):

<ul>
  <li>Manzana</li>
  <li>Plátano</li>
  <li>Naranja</li>
</ul>

✅ Buen ejemplo (lista ordenada ol):

<ol>
  <li>Abrir el navegador</li>
  <li>Ir a Google</li>
  <li>Escribir la consulta</li>
</ol>

✅ Lista de definiciones dl:

<dl>
  <dt>HTML</dt>
  <dd>Lenguaje de marcado para crear páginas web</dd>
  <dt>CSS</dt>
  <dd>Lenguaje de estilos para diseñar páginas web</dd>
</dl>

💡 Conclusión:
El HTML semántico mejora la accesibilidad, hace que el código sea más comprensible, ayuda a los motores de búsqueda y facilita el mantenimiento del proyecto.