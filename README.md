# Portafolio Personal — Práctica Formativa Obligatoria 1 — Rodrigo Zocco

Este proyecto de la materia Desarrollo de Sistemas Web (Front End) de la comisión 2° E, consiste en la construcción de un sitio web de portafolio personal utilizando únicamente HTML y CSS, aplicando las prácticas que se ven en los mosaicos, sobretodo el de CSS, incluyendo diseño responsivo. Para no usar mis datos reales solo coloque mi nombre y segundo nombre, junto a una imagen generada por la IA.

---

## Checklist

### Estructura del Proyecto
- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluye una breve descripción del TP y este checklist.

### Repositorio y Publicación
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] En el `README.md` se indica la URL de GitHub Pages.

> **URL de GitHub Pages:** _(ToDo: ME FALTA PUBLICARLO Y ACTUALIZARLO ACA)_

---

### Uso de Google Fonts
- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**
  > Elegí **Playfair Display** y **DM Sans**. La primera porque me parece profesional y llamativa, mientras que DM Sans para el contenido parece una letra sobria y correcta, me pareció bueno así para mostrar profesionalidad pero a la vez algo de estilo, evitando ser aburrido

---

### HTML
- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo (`Mi Portafolio Personal`).
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

### Secciones obligatorias en `main`
- [x] Sección **Presentación Personal** (`id="sobre-mi"`) con párrafo e imagen con `alt`.
- [x] Sección **Tarjetas/Columnas** (`id="tarjetas"`) con al menos 2 tarjetas organizadas con Flexbox.
- [x] Sección **Habilidades** (`id="habilidades"`) con tabla y listas.
- [x] Sección **Contacto** (`id="contacto"`) con formulario (Nombre, Apellido, Email, Teléfono) y botón submit.
- [x] Sección **Películas Favoritas** (`id="peliculas"`) con 3 películas, imagen y descripción.

### Barra de Navegación
- [x] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces (contiene 5).

### Comentarios en el HTML
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML

---

### CSS
- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica en todos los elementos.

### Layout y Organización
- [x] Se ha organizado el layout con **Flexbox** en la sección `#tarjetas` y **Grid** en `#sobre-mi` y `#habilidades`.
- [x] **¿Qué ventajas encontraste al utilizar Flexbox o Grid?**
  > Flexbox me dejo poner las tarjetas en columnas con `flex-wrap: wrap`, adaptándose a los anchos de pantalla. CSS Grid te da un mejor control para layouts/estructuras mas simples de dos dimensiones, como la sección "Sobre mí" (imagen + texto) y la grilla de películas.

### Estilización de Componentes
- [x] Se han personalizado los estilos de tablas (`.tabla-habilidades`), botones (`.btn-primary`), enlaces (`.nav-link`, `.red-social`) y formularios (`.formulario`).
- [x] Se han ajustado dimensiones de imágenes y contenedores con unidades relativas: `%`, `rem`, `vh`.
- [x] Se ha implementado al menos una animación o transición.
- [x] **¿Qué animación o transición implementaste y por qué?**
  > Primero implmenté una animación `fadeUp` con `@keyframes` para la entrada del header y las secciones al cargar la página, generando una aparición suave desde abajo (lo ví en muchas paginas y me parece que queda bien). Además agregue la transición `translateY(-8px)` en las tarjetas al hacer hover (para que no parezca aburrido o simple) y efecto de subrayado animado en los enlaces del nav para dejar ver la interactividad.

---

### Consideraciones Adicionales
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos alt en
las imágenes).
- [x] Se añadieron comentarios adicionales donde se describan decisiones de diseño o la lógica de
implementación.
