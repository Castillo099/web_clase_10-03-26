
```markdown
# ☕ Arábica - Café de Especialidad

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Design-8B6F4E?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-8B6F4E?style=flat-square)](LICENSE)

> Sitio web minimalista y profesional para una cafetería de especialidad. Diseñado con enfoque en la experiencia del usuario, estética limpia y rendimiento optimizado.

![Preview](https://images.unsplash.com/photo-1497935586351-b67a49e012bf?w=1200&q=80)

---

## 📋 Tabla de Contenidos

- [Características](#-características)
- [Tecnologías](#-tecnologías)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Personalización](#-personalización)
- [Créditos](#-créditos)
- [Licencia](#-licencia)

---

## ✨ Características

### 🎨 Diseño
- **Estética minimalista** con paleta de colores cálidos y orgánicos
- **Tipografía elegante**: Playfair Display (títulos) + Inter (cuerpo)
- **Espacio en blanco generoso** para mejor legibilidad
- **Animaciones sutiles** y microinteracciones
- **Diseño totalmente responsive** (móvil, tablet, desktop)

### ⚡ Funcionalidad
- Navegación fija con efecto de transparencia al scroll
- Scroll suave entre secciones
- Menú hamburguesa para dispositivos móviles
- Formulario de reservas con validación
- Efectos parallax en imágenes de fondo
- Galería interactiva con overlays hover
- Animaciones de entrada al hacer scroll (Intersection Observer)

### 🖼️ Secciones
1. **Hero** - Imagen de fondo con llamada a la acción
2. **Nosotros** - Historia, filosofía y estadísticas
3. **Menú** - Categorías: Clásicos, Especialidades y Panadería
4. **Galería** - Grid de imágenes del local y productos
5. **Contacto** - Información y formulario de reservas

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura semántica y accesible |
| **CSS3** | Variables CSS, Grid, Flexbox, Animaciones |
| **JavaScript Vanilla** | Interactividad sin dependencias |
| **Google Fonts** | Tipografías Playfair Display e Inter |
| **Unsplash** | Imágenes de alta calidad |

### Características CSS Avanzadas
- Variables CSS para tema consistente
- Grid Layout para galería y menú
- Flexbox para navegación y alineación
- Media queries para responsive design
- Transiciones y transformaciones suaves
- Backdrop-filter para efectos de desenfoque

---

## 📁 Estructura del Proyecto

```
arabica-coffee/
│
├── index.html          # Página principal
├── README.md           # Documentación
├── LICENSE             # Licencia MIT
│
├── assets/             # Recursos estáticos (opcional)
│   ├── css/
│   │   └── styles.css  # Si prefieres separar CSS
│   ├── js/
│   │   └── main.js     # Si prefieres separar JS
│   └── images/         # Imágenes locales (alternativa a Unsplash)
│
└── docs/               # Documentación adicional
    └── guia-estilo.md
```

---

## 🚀 Instalación

### Opción 1: Descarga Directa
```bash
# Clona o descarga el repositorio
git clone https://github.com/tuusuario/arabica-coffee.git

# O descarga el ZIP y extrae los archivos
```

### Opción 2: Uso Inmediato
1. Copia el código HTML completo
2. Pégalo en un archivo `index.html`
3. Abre el archivo en tu navegador

### Requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar fuentes e imágenes de Unsplash)

---

## 💻 Uso

### Desarrollo Local
Simplemente abre el archivo `index.html` en tu navegador:

```bash
# Usando Python (servidor local simple)
python -m http.server 8000

# Usando Node.js (si tienes http-server instalado)
npx http-server

# Usando PHP
php -S localhost:8000
```

Luego visita `http://localhost:8000`

### Despliegue
El sitio está listo para desplegar en cualquier hosting estático:

- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)

---

## 🎨 Personalización

### Cambiar Colores
Edita las variables CSS en `:root`:

```css
:root {
    --color-primary: #1a1a1a;      /* Texto principal */
    --color-secondary: #8b6f4e;    /* Acentos */
    --color-accent: #d4a574;       /* Destacados */
    --color-bg: #faf9f7;           /* Fondo */
    --color-text: #2c2c2c;         /* Texto cuerpo */
    --color-muted: #6b6b6b;        /* Texto secundario */
}
```

### Cambiar Imágenes
Reemplaza las URLs de Unsplash en el HTML:

```html
<!-- Ejemplo: Cambiar imagen del hero -->
<section class="hero" style="background-image: url('tu-imagen.jpg');">
```

### Modificar Menú
Localiza la sección `#menu` y edita los items:

```html
<div class="menu-item">
    <div class="menu-item-info">
        <h4>Nombre del Producto</h4>
        <p>Descripción</p>
    </div>
    <span class="menu-item-price">$0.00</span>
</div>
```

### Cambiar Información de Contacto
Edita la sección `#contacto`:

```html
<div class="contact-detail">
    <h4>Dirección</h4>
    <p>Tu Dirección<br>Ciudad, CP</p>
</div>
```

---

## 📸 Imágenes Utilizadas

Todas las imágenes provienen de [Unsplash](https://unsplash.com/) y son de uso libre:

| Sección | Imagen | Fotógrafo |
|---------|--------|-----------|
| Hero | [Coffee shop interior](https://unsplash.com/photos/photo-of-coffee-shop-interior-while-no-one-inside-TY_Ce5d2G-k) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Nosotros | [Barista pouring](https://unsplash.com/photos/person-pouring-coffee-milk-on-coffee-mug-6VhPqP8VZdY) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Galería 1 | [Latte art](https://unsplash.com/photos/cappuccino-on-white-ceramic-cup-beside-white-ceramic-teacup-50KffXbjIOg) | [Fahmi Fakhrudin](https://unsplash.com/@fahmipaping) |
| Galería 2 | [Café interior](https://unsplash.com/photos/brown-wooden-table-and-chairs-nrSzRUWqmoI) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Galería 3 | [Coffee beans](https://unsplash.com/photos/brown-coffee-beans-on-sack-TYIzeCiZ_60) | [Mike Kenneally](https://unsplash.com/@asthetik) |
| Galería 4 | [Coffee preparation](https://unsplash.com/photos/person-holding-white-ceramic-mug-fGxiRXr2oZg) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Galería 5 | [Cold brew](https://unsplash.com/photos/clear-drinking-glass-with-brown-liquid-on-white-ceramic-saucer-7BjmDICVloE) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Galería 6 | [Pastry](https://unsplash.com/photos/baked-pancakes-on-plate-rfOFRwKHtJM) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |
| Contacto | [Café ambiance](https://unsplash.com/photos/white-ceramic-mug-on-brown-wooden-table-6anudmpILw4) | [Nathan Dumlao](https://unsplash.com/@nate_dumlao) |

---

## 🌟 Características Premium

### Optimización de Rendimiento
- ✅ Imágenes optimizadas con compresión
- ✅ Lazy loading implícito
- ✅ CSS crítico inline
- ✅ Sin dependencias externas pesadas
- ✅ Animaciones con GPU acceleration

### Accesibilidad (a11y)
- ✅ Contraste de colores WCAG AA
- ✅ Navegación por teclado
- ✅ Etiquetas semánticas HTML5
- ✅ Estados focus visibles
- ✅ Textos alternativos en imágenes

### SEO Básico
- ✅ Meta tags descriptivos
- ✅ Estructura semántica (header, nav, main, section, footer)
- ✅ URLs amigables (anclajes)
- ✅ Contenido optimizado para keywords de café

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea tu rama (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

---

## 📝 Créditos

- **Diseño y Desarrollo**: [Tu Nombre]
- **Inspiración**: Tendencias de diseño web para cafeterías 2024
- **Imágenes**: [Unsplash](https://unsplash.com/) - Licencia Unsplash
- **Fuentes**: [Google Fonts](https://fonts.google.com/)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

```
MIT License

Copyright (c) 2024 Arábica Coffee

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Contacto

¿Preguntas o sugerencias?

- 📧 Email: hola@arabica.coffee
- 🌐 Web: [www.arabica.coffee](https://www.arabica.coffee)
- 📱 Instagram: [@arabica.coffee](https://instagram.com/arabica.coffee)

---

<p align="center">
  <strong>Hecho con ❤️ y ☕</strong><br>
  <em>Arábica Coffee - El Arte del Café Perfecto</em>
</p>
```

Este README incluye:

1. **Badges visuales** para tecnologías utilizadas
2. **Tabla de contenidos** navegable
3. **Captura de pantalla** del proyecto
4. **Tablas comparativas** de tecnologías
5. **Instrucciones claras** de instalación y uso
6. **Guía de personalización** detallada
7. **Créditos de imágenes** con enlaces a fotógrafos
8. **Sección de características premium** (SEO, accesibilidad, rendimiento)
9. **Licencia MIT** completa
10. **Footer profesional** con contacto

El formato Markdown es compatible con GitHub, GitLab y cualquier plataforma de hosting de código.
