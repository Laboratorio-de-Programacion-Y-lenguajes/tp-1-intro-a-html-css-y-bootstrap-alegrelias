# Portfolio Personal - Elías Alegre

Este es un proyecto estático de frontend desarrollado como trabajo práctico.

## 🚀 Cómo ver el proyecto

Al ser un sitio web estático, no requiere instalación de dependencias ni levantar un servidor backend.

**Opción 1: Visualización directa**
1. Cloná o descargá este repositorio en tu computadora.
2. Hacé doble clic sobre el archivo `index.html`.
3. El sitio se abrirá automáticamente en tu navegador web predeterminado.

**Opción 2: Modo desarrollo (Recomendado)**
Si usás Visual Studio Code, se recomienda utilizar la extensión **Live Server**.
1. Abrí la carpeta del proyecto en VS Code.
2. Hacé clic derecho sobre `index.html` y seleccioná "Open with Live Server".

## 📁 Estructura del Proyecto

* `index.html`: Página principal con el Hero section y el grid de artículos recientes.
* `about.html`: Sección "Acerca de mí" con información de perfil y background técnico.
* `contact.html`: Formulario de contacto interactivo.
* `assets/`: 
    * `styles.css`: Hoja de estilos principal.
    * `images/`: Recursos gráficos, iconos y foto de perfil.
    * `fonts/`: Archivos de la tipografía local (TT Supermolot Neue).

## 🛠️ Tecnologías y Prácticas Utilizadas

* **HTML5:** Estructura semántica y validación nativa de formularios.
* **CSS3:** Estilos personalizados, variables (`:root`), y uso avanzado de pseudoclases (`:valid`, `:invalid`) para dar feedback visual al usuario.
* **Bootstrap 5:** Utilizado mediante CDN para el sistema de grillas, la barra de navegación responsive y la estructura base de las tarjetas.
* **Arquitectura CSS:** Implementación de la metodología BEM (kebab-case) para nombrar clases, garantizando la separación entre los estilos del framework y los estilos personalizados.
