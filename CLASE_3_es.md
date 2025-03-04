### **Fundamentos de HTML**  

## **¿Qué son los sitios web?**  

Cuando visitas un sitio web, como YouTube o Instagram, ves texto, imágenes, botones y videos. Pero, ¿cómo funciona?  

En realidad, un sitio web es un conjunto de archivos con código que el navegador (Chrome, Firefox) convierte en una página visualmente atractiva.  

Para crear un sitio web, necesitas conocer **tres tecnologías principales**:  
✅ **HTML** – la estructura base (esqueleto del sitio).  
✅ **CSS** – el diseño (colores, fuentes, márgenes).  
✅ **JavaScript** – las animaciones e interacciones (botones, efectos, sliders).  

🔹 **HTML** es como los cimientos y las paredes de una casa.  
🔹 **CSS** es la pintura, la decoración y los muebles.  
🔹 **JavaScript** son las puertas que se abren automáticamente.  

Hoy conoceremos **HTML**, y en la próxima clase aprenderemos CSS. 🚀  

---

## **Fundamentos de HTML: ¿cómo funciona?**  

**HTML (HyperText Markup Language)** es un lenguaje de marcado que nos ayuda a crear sitios web.  
HTML funciona con un conjunto de "etiquetas" que definen la estructura de una página web.  

### **¿Qué son las etiquetas?**  
✅ **Una etiqueta** es un comando especial que indica al navegador cómo debe verse un elemento.  
✅ Las etiquetas son como **bloques de construcción** que forman un sitio web.  
✅ Las etiquetas pueden ser **de apertura** (`<p>`) y **de cierre** (`</p>`).  
✅ Hay etiquetas **autocontenidas**, que no necesitan una etiqueta de cierre, como `<img />` para imágenes.  

📌 **Ejemplo de estructura básica en HTML**  

```html
<!DOCTYPE html>  <!-- Indica que este es un documento HTML -->
<html>           <!-- Etiqueta principal -->
<head>          <!-- Sección con información técnica -->
    <title>Mi primera página web</title> <!-- Nombre de la página en la pestaña del navegador -->
</head>
<body>          <!-- Contenido principal de la página -->
    <h1>¡Hola, mundo!</h1> <!-- Encabezado -->
    <p>Esta es mi primera página web.</p> <!-- Párrafo -->
</body>
</html>
```

👉 Este código crea una página simple con un título y un texto.  

## **Todo el código debe escribirse dentro de la etiqueta `<body>`**  

```html
<body> AQUÍ VA NUESTRA PÁGINA </body>
```

Además, podemos usar **Emmet**, un asistente que nos ayuda a escribir código HTML más rápido. Simplemente escribiendo "!" y presionando Enter, se genera toda la estructura base.  

---

## **Principales etiquetas de HTML**  

No hay demasiadas etiquetas, solo necesitamos conocer las más importantes. Hemos visto tres:  

✅ **`<h1>` - `<h6>`** – encabezados, desde el más grande (`h1`) hasta el más pequeño (`h6`).  
Ejemplo:  
```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
```

✅ **`<p>`** – párrafo de texto.  
Ejemplo:  
```html
<p>Este es un párrafo de texto.</p>
```

✅ **`<img>`** – insertar imágenes.  
Ejemplo:  
```html
<img src="foto.jpg" alt="Descripción de la imagen">
```

📌 **Dos formas de agregar imágenes en un proyecto:**  
1. **Desde tu computadora**  
   - La imagen debe guardarse en una carpeta del proyecto (por ejemplo, `images`).  
   - Ejemplo de ruta:  
     ```html
     <img src="images/foto.jpg" alt="Foto">
     ```
2. **Desde un enlace de internet**  
   - Puedes usar imágenes directamente desde la web.  
   - Ejemplo:  
     ```html
     <img src="https://ejemplo.com/foto.jpg" alt="Foto">
     ```

💡 *Es recomendable usar imágenes locales para que la carga sea más rápida.*  

---

## **Otras etiquetas útiles que aprenderemos más adelante:**  

| **Etiqueta**  | **Descripción**                 | **Ejemplo**                                      |
|--------------|--------------------------------|------------------------------------------------|
| `<a>`        | Crea un enlace                 | `<a href="https://google.com">Google</a>`     |
| `<ul> <li>`  | Lista desordenada              | `<ul><li>Manzana</li><li>Banana</li></ul>`    |
| `<ol> <li>`  | Lista ordenada                 | `<ol><li>Primero</li><li>Segundo</li></ol>`  |
| `<strong>`   | Texto en negrita               | `<strong>Texto importante</strong>`           |
| `<em>`       | Texto en cursiva               | `<em>Texto en cursiva</em>`                   |

💡 **En la próxima clase exploraremos estas etiquetas y crearemos una página web más completa.** 🚀