# El Meridiano — Portada de Diario Digital

Trabajo Práctico: Portada de diario con Flexbox y Responsive Design (Mobile First).

## 🔗 Ver online (GitHub Pages)

**[https://frankito-web.github.io/el-meridiano/](https://frankito-web.github.io/el-meridiano/)**

---

## 📋 Descripción

Portada de diario digital ficticio **El Meridiano**, diseñada con enfoque **Mobile First** y **CSS Flexbox** como herramienta principal de layout.

## 🗂️ Estructura del proyecto

```
el-meridiano/
├── index.html          ← Estructura HTML de la portada
├── css/
│   ├── normalize.css   ← Reset CSS para consistencia entre navegadores
│   ├── base.css        ← Variables CSS, estilos base y utilidades
│   ├── header.css      ← Header, logo y navegación (con hamburguesa)
│   └── layout.css      ← Layout principal, cards, sidebar, footer
└── README.md
```

## ✅ Características

- **Mobile First**: diseñado primero para celulares, luego adaptado a tablets y escritorio
- **Flexbox**: usado en header, nav, grids de noticias, sidebar, footer
- **Responsive con breakpoints**:
  - `640px` → cards en grilla de 2 columnas
  - `768px` → layout de 2 columnas (contenido + sidebar), hero horizontal
  - `1024px` → featured grid en fila completa
- **Menú hamburguesa** ☰ visible en mobile, barra horizontal en desktop
- **Ticker de noticias urgentes** animado con CSS
- **Secciones**: noticias principales con imagen, noticias secundarias, columnas de opinión, clima, más leído
- **Publicidades** en distintas posiciones (horizontal, sidebar, entre secciones)
- **Footer** con grilla responsive de 4 columnas

## 🚀 Cómo ejecutar localmente

```bash
git clone https://github.com/TU-USUARIO/el-meridiano.git
cd el-meridiano
# Abrí index.html en tu navegador, o usá Live Server en VSCode
```

## 📤 Subir a GitHub Pages

```bash
git init
git add .
git commit -m "feat: portada inicial del diario El Meridiano"
git remote add origin https://github.com/TU-USUARIO/el-meridiano.git
git push -u origin main
```

Luego en GitHub: **Settings → Pages → Source: main / (root) → Save**

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3 (Flexbox, Custom Properties, Media Queries, Animations)
- Google Fonts (Playfair Display, Source Serif 4, DM Sans)
- normalize.css v8.0.1

---

*Trabajo Práctico — Desarrollo de Software — Rosario, Argentina · 2025*
