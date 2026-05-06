# 🎨 Tab Bar Navigation - Tubelight Effect

Una **navegación interactiva moderna** con efecto **tubelight** (luz de neón suave). 
Componente reutilizable perfecto para dashboards, aplicaciones móviles web e interfaces premium.

## ✨ Características

- ✅ **Animación Fluida**: Efecto de luz de neón que sigue suavemente la navegación
- ✅ **Sin Dependencias**: HTML5, CSS3 y JavaScript vanilla puro
- ✅ **Componente Reutilizable**: Fácil de integrar en cualquier proyecto
- ✅ **Performance**: Animaciones optimizadas

## 🔗 Live Demo

👉 [View on GitHub Pages](https://olaigv.github.io/GSAP-ScrollHorizontal/)

---

## 🚀 Cómo Usar

### 1. Clonar o descargar el proyecto
```bash
git clone https://github.com/tu-usuario/OlaiGV-TabBarNavigation.git
cd OlaiGV-TabBarNavigation
```

### 2. Abrir en el navegador
Simplemente abre el archivo `index.html` en tu navegador favorito.

```bash
# Opción 1: Doble clic en index.html

# Opción 2: Con Python
python -m http.server 8000
# Luego abre http://localhost:8000

# Opción 3: Con Live Server en VS Code
# Click derecho en index.html → Open with Live Server
```

## 📱 Demo

La navegación es completamente interactiva:
- Haz clic en los iconos para cambiar de sección
- Observa cómo el efecto tubelight se anima suavemente
- El efecto de luz sigue tu selección

## 🛠️ Tecnologías

| Tecnología | Descripción |
|-----------|------------|
| **HTML5** | Estructura semántica con SVG |
| **CSS3** | Animaciones con Grid y Transitions |
| **JavaScript** | Vanilla JS, sin frameworks |

## 📂 Estructura

```
OlaiGV-TabBarNavigation/
├── index.html        # Página principal
├── README.md         # Este archivo
├── CSS/
│   ├── style.css     # Estilos de la navegación
│   └── favicon_io/   # Favicon
└── JS/
    └── script.js     # Lógica interactiva
```

## 💡 Casos de Uso

Perfecto para:
- 📊 **Dashboards**: Menú de navegación principal
- 📱 **PWA**: Aplicaciones web progresivas tipo móvil
- 🎨 **Portfolios**: Navegación de secciones
- 🏪 **E-commerce**: Menú de categorías
- 🎮 **Aplicaciones Interactivas**: Interfaz de navegación

## 🎯 Cómo Funciona

1. **HTML**: Define los botones de navegación con iconos SVG
2. **CSS**: Estiliza la barra y crea el efecto tubelight
3. **JavaScript**: Maneja los clicks y anima la posición del tubelight

```javascript
// El script detecta clics en los enlaces
// y anima suavemente la posición de la luz
link.addEventListener("click", (e) => {
  // Actualiza la posición del tubelight
  light.style.left = `${e.target.offsetLeft + offset}px`;
});
```

## 🎨 Personalización

Edita las variables CSS en `CSS/style.css` para personalizarlo:

```css
:root {
  --background: #252432;  /* Color de fondo */
  --icon-size: 24px;      /* Tamaño de iconos */
}
```

Cambiar colores del tubelight:
```css
nav .tubelight {
  background: #ffffff;    /* Color de la luz */
  transition: left 400ms ease;  /* Velocidad de animación */
}
```

## 📊 Compatibilidad

✅ Chrome, Firefox, Safari, Edge (versiones modernas)

## 🚀 Mejoras Futuras

- [ ] Responsive mejorado
- [ ] Temas claro/oscuro
- [ ] Más iconos disponibles
- [ ] Accesibilidad WCAG AA
- [ ] Versión React/Vue

## 📝 Licencia

MIT - Libre para usar y modificar

## 👨‍💻 Autor

**Olai GV** - Desarrollador Frontend

---

**¿Te gusta el proyecto?** Déjale una ⭐ en GitHub!
