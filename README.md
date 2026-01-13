# GobApp Municipal - Landing Page Interactiva

Presentación web interactiva estilo Silicon Valley para GobApp Municipal.

## 🚀 Deploy en GitHub Pages

### Opción 1: Método Rápido (recomendado)

1. **Crea un nuevo repositorio en GitHub**
   - Ve a [github.com/new](https://github.com/new)
   - Nombre sugerido: `gobapp-landing` o `gobapp-presentacion`
   - Marca como **Public**
   - Click en "Create repository"

2. **Sube el archivo `index.html`**
   - En tu nuevo repo, click en "uploading an existing file"
   - Arrastra el archivo `index.html`
   - Click en "Commit changes"

3. **Activa GitHub Pages**
   - Ve a **Settings** → **Pages** (en el menú lateral)
   - En "Source", selecciona **Deploy from a branch**
   - En "Branch", selecciona **main** y **/ (root)**
   - Click en **Save**

4. **¡Listo!**
   - En 1-2 minutos tu página estará disponible en:
   - `https://TU-USUARIO.github.io/gobapp-landing/`

---

### Opción 2: Usando Git (línea de comandos)

```bash
# Clona tu repositorio vacío
git clone https://github.com/TU-USUARIO/gobapp-landing.git
cd gobapp-landing

# Copia el index.html a esta carpeta
# (el archivo que descargaste)

# Sube los cambios
git add .
git commit -m "Add GobApp landing page"
git push origin main
```

Luego activa GitHub Pages en Settings → Pages.

---

## 📁 Estructura del proyecto

```
gobapp-landing/
└── index.html    ← Todo está en un solo archivo (HTML + CSS + JS)
```

## ✨ Características

- **100% autocontenido** - Un solo archivo HTML, sin dependencias externas
- **Responsive** - Se adapta a móvil, tablet y desktop
- **Animaciones** - Contadores, transiciones, efectos de scroll
- **Interactivo** - Toggles antes/después, cards expandibles, timeline animado
- **Profesional** - Diseño dark mode con gradientes neón estilo Silicon Valley

## 🎨 Personalización

Para cambiar colores, edita las variables CSS al inicio del archivo:

```css
:root {
  --primary: #00F5D4;    /* Cyan/Turquesa */
  --secondary: #7B61FF;  /* Púrpura */
  --accent: #FF6B6B;     /* Coral/Rojo */
  --dark: #0A0A0F;       /* Fondo oscuro */
}
```

## 📱 Compartir

Una vez publicado, comparte el link:
- Para presentaciones en persona
- Por WhatsApp/email a prospectos
- En propuestas comerciales
- Como QR en materiales impresos

---

**Hecho con ❤️ para transformar la gestión municipal**
