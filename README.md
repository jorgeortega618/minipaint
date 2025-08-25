# Mini-Paint 🎨

Un proyecto educativo interactivo que implementa y compara diferentes algoritmos de dibujo de líneas en gráficos por computadora.

## 🚀 Demo en Vivo

Visita el proyecto: [Mini-Paint](https://jorgeortega618.github.io/minipaint)

## 📋 Descripción

Mini-Paint es una herramienta educativa que permite visualizar y comparar tres algoritmos fundamentales para el dibujo de líneas en sistemas de gráficos raster:

- **Algoritmo Básico con Redondeo** - Implementación simple y directa
- **Algoritmo DDA** (Digital Differential Analyzer) - Método incremental eficiente
- **Algoritmo de Bresenham** - Optimización usando solo aritmética entera

## ✨ Características

### 🎯 Funcionalidades Principales
- **Interfaz interactiva** con canvas HTML5
- **Animación paso a paso** para visualizar cada algoritmo
- **Comparación visual** entre diferentes métodos
- **Controles personalizables** (color, grosor, velocidad)
- **Cuadrícula opcional** para mejor visualización
- **Exportación a PNG** de los dibujos creados

### 🎨 Interfaz de Usuario
- **Tema oscuro moderno** con colores distintivos por algoritmo
- **Navegación fluida** entre páginas
- **Responsive design** que funciona en diferentes dispositivos
- **Atajos de teclado** para acceso rápido

## 🏗️ Estructura del Proyecto

```
miniPaint/
├── index.html          # Página principal con navegación
├── redondeo.html       # Algoritmo básico con redondeo
├── DDA.html           # Algoritmo DDA incremental
├── bresenham.html     # Algoritmo de Bresenham
└── README.md          # Este archivo
```

## 🔧 Uso

### Instalación Local
1. Clona el repositorio:
```bash
git clone https://github.com/jorgeortega618/minipaint.git
cd minipaint
```

2. Abre `index.html` en tu navegador web favorito

### Cómo Usar
1. **Selecciona un algoritmo** desde la página principal
2. **Haz clic** en el canvas para establecer el punto inicial
3. **Haz clic nuevamente** para establecer el punto final
4. **Observa** cómo se dibuja la línea
5. **Activa la animación** para ver el proceso paso a paso

### Controles Disponibles
- **Color**: Selector de color para las líneas
- **Grosor**: Ajusta el grosor de 1 a 9 píxeles
- **Cuadrícula**: Muestra/oculta la cuadrícula de referencia
- **Puntos de control**: Muestra/oculta los marcadores de inicio y fin
- **Animación**: Activa la visualización paso a paso
- **Velocidad**: Controla la velocidad de animación (ms por paso)

### Atajos de Teclado
- **G**: Alternar cuadrícula
- **C**: Limpiar canvas

## 🧮 Algoritmos Implementados

### 1. Algoritmo Básico (Redondeo)
- **Color de acento**: Azul (`#38bdf8`)
- **Método**: Avanza por el eje con mayor diferencia y redondea el otro
- **Ventajas**: Simple de entender e implementar
- **Desventajas**: Puede generar líneas desiguales

### 2. Algoritmo DDA
- **Color de acento**: Cian (`#22d3ee`)
- **Método**: Usa incrementos constantes calculados una vez
- **Ventajas**: Evita divisiones por iteración, trazo uniforme
- **Desventajas**: Usa aritmética de punto flotante

### 3. Algoritmo de Bresenham
- **Color de acento**: Morado (`#a78bfa`)
- **Método**: Solo aritmética entera con acumulador de error
- **Ventajas**: Más eficiente, funciona en todos los octantes
- **Desventajas**: Más complejo de implementar

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura y Canvas API
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript ES6+** - Lógica de los algoritmos e interactividad
- **Git** - Control de versiones

## 📚 Propósito Educativo

Este proyecto está diseñado para:

- **Estudiantes de gráficos por computadora** que quieren entender algoritmos de rasterización
- **Profesores** que buscan herramientas interactivas para enseñar
- **Desarrolladores** interesados en implementaciones de algoritmos clásicos
- **Cualquier persona** curiosa sobre cómo funcionan los gráficos por computadora

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Jorge Ortega**
- GitHub: [@jorgeortega618](https://github.com/jorgeortega618)
- Email: jorgeortega618@gmail.com

## 🙏 Agradecimientos

- Inspirado en los algoritmos clásicos de gráficos por computadora
- Diseño basado en principios modernos de UX/UI
- Comunidad de desarrolladores por el feedback y sugerencias

---

⭐ Si este proyecto te fue útil, ¡no olvides darle una estrella!
