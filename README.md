# �️ Tienda de Muebles - Ecommerce con Bootstrap 5

**Una tienda de muebles online completa y responsiva, construida con Bootstrap 5**

Este proyecto es una solución de e-commerce funcional para una tienda de muebles, desarrollada como parte del curso "Bootstrap 5 y SASS - La Guía Práctica". Presenta un diseño moderno, navegación intuitiva y todas las páginas necesarias para una experiencia de compra profesional.

---

## 🎯 Sobre el Proyecto

Tienda de Muebles es un sitio web completo que permite a los usuarios:

- **Explorar productos** - Catálogo de muebles con descripciones, imágenes y precios
- **Conocer la empresa** - Página "Nosotros" que cuenta la historia de la tienda
- **Leer artículos** - Sección de blog con contenido relevante a decoración y muebles
- **Ver galerías** - Galería visual de los productos disponibles
- **Ponerse en contacto** - Formulario para consultas y contacto directo
- **Agregar productos** - Sistema de carrito para seleccionar muebles

---

## 📋 Características del Sitio

- ✅ **7 páginas completas** - Inicio, Tienda, Blog, Galería, Nosotros, Contacto, y más
- 📱 **100% Responsivo** - Se adapta perfectamente a móvil, tablet y desktop
- 🎨 **Diseño Moderno** - Interfaz limpia y profesional con colores atractivos
- ⚡ **Bootstrap 5** - Framework CSS confiable y flexible
- 🛒 **Sistema de Productos** - Visualización de muebles con precio y carrito
- 💬 **Formulario de Contacto** - Permite que los clientes se comuniquen
- 📝 **Blog Funcional** - Sección de artículos y publicaciones
- 🖼️ **Galería de Imágenes** - Showcase de los productos

---

## 🗂️ Estructura del Proyecto

```
tienda-muebles/
├── index.html              # Página de inicio con hero y destacados
├── tienda.html             # Catálogo completo de muebles
├── blog.html               # Artículos sobre decoración y muebles
├── entrada.html            # Detalle de un artículo del blog
├── galeria.html            # Galería visual de productos
├── nosotros.html           # Información de la empresa
├── contacto.html           # Formulario de contacto
├── base.html               # Página base/template
│
├── css/
│   ├── bootstrap.min.css   # Framework Bootstrap 5 minimizado
│   └── app.css             # Estilos personalizados de la tienda
│
├── js/
│   ├── bootstrap.bundle.min.js  # Bootstrap JS con dependencias
│   └── app.js                   # Scripts personalizados
│
└── img/                    # Carpeta de imágenes de productos
```

---

## 🚀 Cómo Usar

### Opción 1: Con VS Code Live Server

1. Abre el proyecto en VS Code
2. Click derecho en `index.html` → "Open with Live Server"
3. ¡Listo! El sitio se abrirá en tu navegador

### Opción 2: Con Python

```bash
python -m http.server 8000
```

Luego abre `http://localhost:8000` en tu navegador.

### Opción 3: Con Node.js

```bash
npx http-server
```

---

## 📄 Páginas Principales

### 🏠 **Inicio (index.html)**

Página principal con elemento hero, bienvenida a la tienda y destacados de productos.

### 🛍️ **Tienda (tienda.html)**

Catálogo completo de muebles con:

- Imágenes de producto
- Descripción
- Precio
- Botón "Agregar al carrito"

### 📝 **Blog (blog.html)**

Sección de artículos sobre:

- Tips de decoración
- Tendencias en muebles
- Cuidado de productos

### 📄 **Entrada Blog (entrada.html)**

Detalle completo de un artículo individual con contenido expandido.

### 🖼️ **Galería (galeria.html)**

Galería visual de todos los muebles disponibles en la tienda.

### ℹ️ **Nosotros (nosotros.html)**

Información sobre:

- La historia de la tienda
- Misión y valores
- Por qué elegir nuestros muebles

### 📧 **Contacto (contacto.html)**

Formulario para que los clientes puedan:

- Hacer consultas
- Solicitar información
- Enviar comentarios

---

## 🛠️ Tecnologías Utilizadas

| Tecnología       | Uso                            |
| ---------------- | ------------------------------ |
| **HTML5**        | Estructura semántica del sitio |
| **CSS3**         | Estilos y diseño responsivo    |
| **Bootstrap 5**  | Framework CSS y componentes    |
| **JavaScript**   | Interactividad y funcionalidad |
| **Google Fonts** | Tipografía moderna             |

---

## 🎨 Características de Diseño

- **Paleta de colores**: Colores cálidos y profesionales para una tienda de muebles
- **Tipografía**: Fuentes de Google para mejor legibilidad
- **Navegación intuitiva**: Menú claro que guía al usuario por toda la tienda
- **Componentes Bootstrap**: Botones, tarjetas, formularios, navbar responsivo
- **Espaciado y layout**: Uso de grid para un diseño ordenado
- **Imágenes**: Productos con fotos de alta calidad

---

## 💡 Cómo Personalizar

### Cambiar el nombre de la tienda

Busca "Tienda Muebles" en todos los archivos HTML y reemplázalo.

### Agregar más productos

En `tienda.html`, duplica la estructura de producto y actualiza:

- Imagen en `img/`
- Nombre del producto
- Descripción
- Precio

### Modificar colores

Edita `css/app.css` para cambiar la paleta de colores principal.

### Actualizar contenido

- Blog: Edita `blog.html` y `entrada.html`
- Nosotros: Actualiza `nosotros.html` con tu información
- Contacto: Configura el formulario en `contacto.html`

---

## 🔗 Estructura de Navegación

```
Inicio
├── Nosotros (conoce la empresa)
├── Tienda (compra muebles)
├── Blog (lee artículos)
├── Galería (ve los productos)
└── Contacto (escríbenos)
```

---

## 📚 Recursos y Referencias

- [Documentación Bootstrap 5](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Google Fonts](https://fonts.google.com/)
- [MDN Web Docs](https://developer.mozilla.org/)

---

## ⚙️ Próximos Pasos

Para llevar esta tienda al siguiente nivel:

1. **Backend**: Agregar base de datos y panel de administración
2. **Carrito**: Implementar funcionalidad real de carrito
3. **Pagos**: Integrar pasarela de pagos (Stripe, PayPal)
4. **Búsqueda**: Sistema de filtros y búsqueda de productos
5. **Email**: Sistema de contacto funcional
6. **SEO**: Optimizar para motores de búsqueda
7. **Hosting**: Publicar el sitio en un servidor

---

## 📄 Licencia

Este proyecto está bajo licencia MIT. Libre para usar, modificar y distribuir.

---

## 🌟 Agradecimiento

Si este proyecto te fue útil y te ayudó a aprender Bootstrap 5, considera:

- ⭐ Dejar una estrella en el repositorio
- 📢 Compartir con otros desarrolladores
- 💬 Dejar tus comentarios y sugerencias

---

**Tienda de Muebles | Hecho con ❤️ | Bootstrap 5 | 2026**
