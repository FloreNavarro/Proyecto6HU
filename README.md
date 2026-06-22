# 🥟 Empanadas Gourmet - Doña Carmen

¡Bienvenido al repositorio de **Doña Carmen**, una landing page moderna, responsiva y estilizada desarrollada para la presentación del **Trabajo Práctico N° 5** de la *Tecnicatura Superior en Desarrollo de Software*.

Este proyecto simula la interfaz web de una casa de empanadas gourmet, combinando un diseño visualmente atractivo en tonos cálidos con una experiencia de usuario optimizada para dispositivos móviles y ordenadores.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **HTML5:** Estructuración semántica del contenido (`<header>`, `<main>`, `<section>`, `<footer>`).
* **Bootstrap 5 (v5.3.3 via CDN):** Implementación de la hoja de estilos base, sistema de rejilla y componentes interactivos.
* **Bootstrap Icons (v1.11.3 via CDN):** Iconografía vectorial para las tarjetas de características.
* **CSS3 Personalizado (Archivo Externo):** Modificaciones de diseño, paleta de colores específica del negocio, efectos de transición (`hover`) y manejo adaptativo del fondo.

---

## 🚀 Conceptos Clave de CSS Implementados

### 1. Modelo de Caja (Box Model)
El espaciado y dimensionamiento de la interfaz se controló utilizando las propiedades del modelo de caja:
* **Padding y Margins:** Manejados de forma ágil mediante las clases utilitarias de Bootstrap (ej: `py-5`, `mb-3`, `p-4`) y reforzados en el archivo `style.css` para estructurar los bloques del formulario (`.form-container`).
* **Bordes y Sombras:** Uso de utilidades como `.rounded` y `.shadow-sm` para suavizar las esquinas de los contenedores y dar profundidad visual.

### 2. Introducción a Flexbox y Grid System
El posicionamiento y la distribución del espacio se resolvieron utilizando las herramientas de maquetación flexible:
* **Grid de Bootstrap:** La sección de sabores (`#sabores`) emplea una fila con columnas responsivas (`col-12 col-md-6 col-lg-4`). Esto reordena las tarjetas automáticamente: 1 columna en celulares, 2 en tablets y 3 en pantallas de escritorio.
* **Alineación Flexible:** El encabezado principal (`#inicio`) utiliza clases de Flexbox (`d-flex align-items-center`) para centrar vertical y horizontalmente el texto de presentación (*Hero Section*) sobre el fondo.

### 3. Fluidez e Imágenes Responsivas
* **Imágenes Adaptables:** La sección principal hace uso de la propiedad nativa de CSS `background: ... center center/cover` vinculando la imagen `EMPANADAS.webp`. Esto asegura que el fondo sea fluido, adaptándose al tamaño de cualquier pantalla sin deformarse ni pixelarse.

---

## 📦 Componentes de Bootstrap Incorporados

1. **Navbar (`.navbar`):** Barra de navegación superior fija (`fixed-top`) con menú colapsable automático para pantallas pequeñas.
2. **Badge (`.badge`):** Etiqueta destacada (`bg-warning`) en el Hero para resaltar la propuesta de valor ("Horno de Barro 100% Caseras").
3. **Cards (`.card`):** Contenedores estructurados para empaquetar los servicios clave del negocio, personalizados con efectos de elevación al pasar el cursor (`:hover`).
4. **Formulario con Validación (`.needs-validation`):** Bloque de contacto estilizado con inputs de Bootstrap y lógica nativa por JavaScript para validar que los campos obligatorios no se envíen vacíos.

---

## 🔧 Instalación y Despliegue Local

Para clonar y visualizar este proyecto en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/FloreNavarro/Proyecto6HU.git