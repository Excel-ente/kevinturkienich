# 🚀 Portfolio de Kevin Turkienich

Una landing page estática moderna y completamente responsiva, diseñada como portfolio personal y profesional para mostrar proyectos, experiencia y habilidades en desarrollo de software y automatización de procesos.

## ✨ Características

### 🎨 Diseño y UX
- **Modo oscuro por defecto** con toggle para modo claro
- **Animación de terminal interactiva** en la sección hero con efecto de typing
- **Preloader personalizado** con secuencia de boot estilo terminal
- **Animaciones suaves** con Intersection Observer para elementos que aparecen al hacer scroll
- **Diseño completamente responsivo** para móviles, tablets y desktop
- **Paleta de colores moderna** basada en variables CSS con tema verde como color primario

### 🛠️ Tecnologías Utilizadas
- **HTML5 semántico**
- **CSS3 puro** con variables CSS y Grid/Flexbox
- **JavaScript vanilla** para todas las interacciones
- **Google Fonts** (Inter y Fira Code)
- **Lucide Icons** para iconografía
- **Font Awesome** para iconos específicos

### 📱 Secciones Incluidas

1. **Hero Section** - Terminal animado con información personal
2. **Sobre Mí** - Presentación profesional y competencias destacadas
3. **Proyectos** - Grid de proyectos con enlaces y tags tecnológicos
4. **Stack Tecnológico** - Showcase de habilidades organizadas por categorías
5. **Trayectoria Profesional** - Timeline de experiencia laboral
6. **Contacto** - Formulario funcional y enlaces a redes sociales

### 🎯 Funcionalidades Interactivas

- **Animación de terminal** que simula comandos de bash
- **Barras de progreso animadas** para skills técnicos
- **Modal de contacto** para mostrar información personal
- **Smooth scrolling** entre secciones
- **Formulario de contacto** con validación y feedback visual
- **Persistencia del tema** seleccionado en localStorage

## 🚀 Instalación y Uso

### Opción 1: Uso Directo
1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador
3. ¡Listo! El portfolio funciona completamente offline

### Opción 2: Servidor Local (Recomendado)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego visita `http://localhost:8000` en tu navegador.

## 🎨 Personalización

### Colores y Tema
Los colores están definidos como variables CSS en `:root` y `.dark`:
```css
:root {
  --primary: 142.1 76.2% 36.3%; /* Verde principal */
  --background: 20 14.3% 4.1%;   /* Fondo oscuro */
  /* ... más variables */
}
```

### Contenido Dinámico
El contenido de proyectos, skills y experiencia se genera dinámicamente desde arrays de JavaScript:
- `projectsData` - Lista de proyectos
- `skillsData` - Tecnologías organizadas por categorías  
- `experiencesData` - Historial profesional

### Animaciones del Terminal
Personaliza los mensajes del terminal editando el array `terminalLines` en el JavaScript.

## 📂 Estructura del Proyecto

```
kevinturkienich/
├── index.html          # Archivo principal con HTML, CSS y JS
├── README.md           # Este archivo
└── LICENSE            # Licencia del proyecto
```

## 🔧 Modificación para tu Uso

Para adaptar este portfolio a tus necesidades:

1. **Información Personal**: Modifica los datos en las variables JavaScript
2. **Proyectos**: Actualiza el array `projectsData` con tus proyectos
3. **Skills**: Edita `skillsData` con tus tecnologías
4. **Experiencia**: Modifica `experiencesData` con tu historial
5. **Colores**: Cambia las variables CSS para tu paleta de colores
6. **Enlaces**: Actualiza URLs de redes sociales y contacto

## 📱 Compatibilidad

- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)  
- ✅ Safari (últimas versiones)
- ✅ Móviles iOS/Android
- ✅ Tabletas

## 🤝 Contribución

Este es un proyecto de código abierto. Si encuentras bugs o tienes ideas de mejora:

1. Abre un **Issue** describiendo el problema o sugerencia
2. Haz un **Fork** del proyecto
3. Crea una **rama** para tu feature (`git checkout -b feature/AmazingFeature`)
4. **Commit** tus cambios (`git commit -m 'Add some AmazingFeature'`)
5. **Push** a la rama (`git push origin feature/AmazingFeature`)
6. Abre un **Pull Request**

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🌟 Demo

Puedes ver el portfolio en vivo en: [kevinturkienich.com](https://kevinturkienich.com)

## 📧 Contacto

Kevin Turkienich - [LinkedIn](https://linkedin.com/in/kevinturkienich) - [YouTube: Excel-ente](https://youtube.com/@excel-ente)

---

⭐ **¡Si te gusta este proyecto, dale una estrella!** ⭐

*Desarrollado con ❤️ por Kevin Turkienich - Buenos Aires, Argentina*
