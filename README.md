
<img width="700" height="264" alt="photoalbumint" src="https://github.com/user-attachments/assets/d552e243-c7b9-40d1-8473-0147157e1312" />



![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

#### **Alma's PhotoRoom Album** es una aplicación web de código abierto diseñada para la creación y edición de álbumes fotográficos digitales de forma intuitiva y directamente en el navegador. Permite manipular plantillas, redimensionar marcos, añadir texto con fuentes artísticas y exportar el resultado en alta resolución.

#### <a href="https://rhinosecurity.xyz/XtoolsR/photoalbum%20v%201.0/">VISTA PREVIA DEL PROYECTO</a>


### 1. Gestión de Marcos (Frames) Dinámicos
La versión 1.0 introduce un sistema de plantillas flexible basado en coordenadas, permitiendo una personalización total que rompe los esquemas rígidos de diseño tradicional:
*   **Redimensionamiento:** Agranda o reduce el tamaño de los marcos de fotos arrastrando la esquina inferior derecha.
*   **Movimiento:** Reposiciona los marcos en cualquier lugar del lienzo arrastrándolos desde sus bordes.
*   **Eliminación:** Elimina marcos individuales de la plantilla para crear diseños minimalistas o ajustar el espacio.

### 2. Sistema de Plantillas
Incluye **16 plantillas predefinidas** que se aplican instantáneamente:
*   Cuadrícula, Mosaico, Horizontal, Vertical.
*   Estilos "Spotlight" (Principal Izquierda/Derecha).
*   Estilos "Feature" (Cabecera/Pie de página).
*   Portadas (Centro, Izquierda, Derecha) y diseños apilados.

### 3. Edición de Fotografías
*   **Carga de Imágenes:** Importación local de imágenes mediante selección de archivos.
*   **Ajuste de Posición:** Arrastra la foto dentro del marco para encuadrarla perfectamente.
*   **Zoom:** Usa la rueda del ratón (scroll) para acercar o alejar la imagen dentro del marco.

### 4. Herramientas de Texto
*   **Añadir Cajas de Texto:** Crea elementos de texto arrastrables.
*   **Tipografías Premium:** Selección entre más de 30 fuentes de Google Fonts (Dancing Script, Pacifico, Orbitron, Cinzel, etc.).
*   **Formato:** Control de tamaño de fuente, color, negrita, cursiva y subrayado.
*   **Interactividad:** Las cajas de texto se pueden mover y eliminar libremente.

### 5. Gestión de Proyectos Multi-Página
*   **Múltiples Páginas:** Añade páginas ilimitadas al álbum con navegación fluida.
*   **Persistencia de Datos:**
    *   **Guardar:** Exporta el proyecto completo (diseño, fotos, textos) en un archivo `.json`.
    *   **Cargar:** Restaura proyectos previamente guardados para continuar la edición.
    *   *Los cambios de tamaño y posición de los frames se guardan automáticamente.*

### 6. Exportación e Impresión
*   **Descarga HD:** Genera una imagen `.png` de la página actual en alta resolución (Escala x5) utilizando la librería `html2canvas`.
*   **Impresión Optimizada:** Función de impresión preparada para formato A4 horizontal, ocultando elementos de interfaz y ajustando colores.

### 7. Fondos Personalizables
*   Sube una imagen de fondo única para cada página del álbum.
*   Opción para limpiar el fondo y volver al color base.

---

## 🛠️ Tecnologías Utilizadas

Este proyecto está construido con tecnologías web estándar, sin necesidad de frameworks complejos de backend:

*   **HTML5:** Estructura semántica y API de archivos.
*   **CSS3:** Diseño flexible (Flexbox), posicionamiento absoluto para los marcos, propiedades de `resize` nativo y estilos de impresión `@media print`.
*   **JavaScript (Vanilla JS):** Lógica de manipulación del DOM, sistema de coordenadas para plantillas, manejo de eventos de arrastre y cálculos de transformación.
*   **html2canvas:** Librería externa para la captura y exportación del DOM a imagen.
*   **Google Fonts:** Integración de tipografías externas.

---

## 📖 Cómo Usar

1.  **Descarga el código:** Clona el repositorio o descarga el archivo `index.html`.
2.  **Apertura:** Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge).
3.  **Selección de Plantilla:** Haz clic en una de las plantillas en el panel izquierdo.
4.  **Personalización:**
    *   Haz clic en un marco para subir una foto.
    *   Arrastra los bordes del marco para moverlo o la esquina para cambiar su tamaño.
    *   Usa la rueda del ratón sobre una foto para hacer zoom.
    *   Añade texto y elige la fuente deseada.
5.  **Guardado:** Guarda tu progreso con el botón "Guardar Proyecto".
6.  **Exportación:** Descarga la imagen en HD o imprime tu álbum.

---

## 📁 Estructura del Archivo

El proyecto se contiene en un único archivo HTML para facilitar su distribución y uso:

*   `index.html`: Contiene el CSS embebido (`<style>`), la estructura HTML y la lógica JavaScript (`<script>`).

---

## 💻 Autores y Créditos

Este software fue desarrollado en respuesta a los requerimientos de diseño y funcionalidad para la creación de álbumes fotográficos interactivos.

*   **Desarrollador:** [Rodolfo Hernández Baz aKa Pr@fEs0r X]
*   **Empresa / Proyecto:** Alma's PhotoAlbum Creator v 1.0
*   **Versión:** 1.0 (Release Estable)

---
*Desarrollado con ❤️ para la comunidad creativa.*
```
