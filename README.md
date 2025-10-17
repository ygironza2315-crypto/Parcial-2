# Guía de Evaluación: Landing Page de "Snow White"

> **Importante:** Solo recibirás una imagen del resultado final como diseño objetivo. Tu tarea es reproducirlo **exactamente** usando solo **HTML y CSS**. El código fuente y los estilos utilizados no serán compartidos.

---

## 📷 Resultado Esperado

![Mockup Final](images/webpage-disney.png)

> Observa con atención la disposición, tipografía, espaciados, botones e imagen de fondo que debes replicar.

---

## 📝 Pasos de la Evaluación

1. **Analiza el mockup**  
   - Identifica la estructura general: encabezado (navegación), banner, secciones de contenido y pie de página.  
   - Toma nota de colores, tipografías, estilos de botones y espacios.

2. **Planifica tu HTML**  
   - Define las etiquetas semánticas principales (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).  
   - Marca los patrones repetibles con clases coherentes (por ejemplo, `.navbar`, `.banner`, `.card`).

3. **Crea la estructura de archivos**  
   - `index.html` para el marcado.  
   - `css/style.css` para los estilos.  
   - Carpeta `images/` con los recursos proporcionados (logo, banner, imágenes de contenido).

4. **Esqueleto HTML básico**  
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Snow White Landing Page</title>
     <link rel="stylesheet" href="css/style.css">
   </head>
   <body>
     <header>…</header>
     <main>…</main>
     <footer>…</footer>
   </body>
   </html>
   ```
   - Usa etiquetas semánticas y nombres de clases en **inglés/español**, legibles y descriptivos.

5. **Añade la navegación**  
   - Crea un `<nav>` con un `<ul>` de enlaces según el mockup.  
   - Inserta el logo a la izquierda.  
   - Más tarde, aplica Flexbox para espaciar los elementos.

6. **Implementa el banner**  
   - Usa `<section class="banner">`.  
   - Aplica en CSS: `background-size: cover; background-position: center; background-repeat: no-repeat;`.  
   - Dentro, coloca el logo/texto principal, subtítulo y los dos botones centrados.

7. **Construye las secciones de contenido**  
   - Para cada bloque (Shop, Disney+, Movies, Parks), emplea `<section>` y `<article>`.  
   - Utiliza Flexbox o CSS Grid para alinear las tarjetas horizontalmente con espacios iguales.

8. **Agrega el pie de página**  
   - Inserta el logo y dos listas de enlaces.  
   - Centra el texto de derechos de autor.

9. **Aplica los estilos con CSS**  
   - Inicia con un reset:  
     ```css
     * {
       box-sizing: border-box;
       margin: 0;
       padding: 0;
     }
     ```
   - Define variables en `:root` para colores, tipografía y espaciados.  
   - Usa unidades relativas (`rem`, `%`, `vh`) para escalabilidad.  
   - Implementa Flexbox/Grid según lo planificado.
   - Estiliza botones con clases tipo `.btn`, `.btn--primary`, `.btn--secondary`.

10. **Inserta las imágenes**  
    - Enlaza las imágenes proporcionadas por rutas relativas (`<img src="images/logo.png" alt="Logo">`).  
    - Para fondos, usa en CSS `background-image: url("../images/banner-background.png");`.

11. **Verifica en navegador**  
    - Abre `index.html` en distintos anchos de pantalla de escritorio.  
    - Usa DevTools para medir márgenes y paddings y comprobar que coinciden con el mockup.

12. **Modalidades de entrega**  
    - **Trabajo en parejas:**  
      1. Se proporcionará un repositorio plantilla con la estructura básica y todos los recursos necesarios.  
      2. Cada pareja creará un repositorio nuevo en GitHub.  
      3. Ambos integrantes enviarán sus cambios mediante **commits** regulares.  
      4. Al finalizar, compartirán el enlace del repositorio para revisar los commits y los aportes de cada integrante.  
    - **Trabajo individual:**  
      1. Se proporcionará un repositorio plantilla con la estructura básica y todos los recursos necesarios.  
      2. Cada estudiante creará una **rama** nueva con su nombre (por ejemplo, `nombres-apellidos`).  
      3. Realizará múltiples **commits** en esa rama para reflejar su progreso.  
      4. Al concluir, compartirá el **enlace** a su rama creada en el repositorio.

13. **Enlaces de apoyo:**

  - [HTML Cheatsheet](https://docs.emmet.io/cheat-sheet/) 
  - [Responsive Search Bar](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_searchbar3)
  - [CSS Cheatsheet](https://htmlcheatsheet.com/css/)
  - [CSS Background Cheatsheet](https://learntheweb.courses/topics/images-cheat-sheet/)
  - CSS Flexbox and CSS Grid Cheatsheets
      - [Flexbox sheet](https://jonitrythall.com/content/flexboxsheet.pdf)
      - [Flexbox and Grid sheet](https://www.paradigmadigital.com/assets/cms/cheat_sheet_flexbox_6fb013edd1.pdf)
---

> **Entrega:** Envía únicamente tu enlace de repositorio donde contendra tu `index.html`, `css/style.css` y una captura de pantalla mostrando tu resultado final ajustado al mockup.

---

*¡Éxito en tu evaluación! Este ejercicio pondrá a prueba tus habilidades de maquetación profesional con HTML y CSS.*

*Good Luck 💪, and Happy Coding! 👨‍💻👩‍💻💻⌨🖱*

