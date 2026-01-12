# 🦁 Proyecto Comparativo: Bootstrap vs Tailwind CSS

> Comparativa técnica de frameworks de diseño web aplicada a una interfaz de gestión de zoológico

Este repositorio presenta un análisis práctico sobre la instalación, configuración y estructura de dos de los frameworks CSS más populares del desarrollo web moderno, implementados en un proyecto real de gestión para zoológico.

---

## 📋 Tabla de Contenidos

- [Requisitos Previos](#-requisitos-previos)
- [Instalación y Configuración](#-instalación-y-configuración)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Instrucciones de Ejecución](#-instrucciones-de-ejecución)
- [Comparativa de Frameworks](#-comparativa-de-frameworks)

---

## 🔧 Requisitos Previos

Para ejecutar este proyecto en Windows o Linux, necesitarás las siguientes herramientas:

| Herramienta | Propósito |
|-------------|-----------|
| **Git** | Clonación del repositorio y control de versiones |
| **Navegador Web** | Compatible con estándares HTML5 y CSS3 |
| **Node.js y NPM** | Gestión de dependencias y procesos de compilación |

---

## 🚀 Instalación y Configuración

### 1️⃣ Clonar el Repositorio

```bash
git clone https://github.com/oiramdevelop/Pagina-en-Tailwind.git
cd Pagina-en-Tailwind
```

### 2️⃣ Configuración de Bootstrap 5

**Instalación**
```bash
npm install bootstrap
```

**Características**
- Sistema basado en componentes predefinidos (navbar, cards, buttons)
- Personalización mediante estilos en línea
- Diseño rápido con clases utilitarias integradas

### 3️⃣ Configuración de Tailwind CSS

**Instalación**
```bash
npm install tailwindcss
```

**Inicialización**
```bash
npx tailwindcss init
```

**Características**
- Configuración dinámica mediante archivo `tailwind.config.js`
- Sistema de utilidades altamente personalizable
- Optimización automática en producción

---

## 📁 Estructura del Proyecto

```
Pagina-en-Tailwind/
│
├── paginaBoost.html      # Implementación con Bootstrap 5
├── main.html             # Implementación con Tailwind CSS
├── img/                  # Recursos gráficos y fondos
│   └── logo.png
├── package.json          # Dependencias del proyecto
└── README.md             # Documentación
```

### Descripción de Archivos

- **`paginaBoost.html`**: Versión completa utilizando la arquitectura de componentes de Bootstrap
- **`main.html`**: Versión completa utilizando el sistema de utilidades de Tailwind CSS
- **`img/`**: Directorio con todos los recursos gráficos necesarios para ambas versiones

---

## ▶️ Instrucciones de Ejecución

### Versión Bootstrap

1. Abre el archivo `paginaBoost.html` en tu navegador
2. Los estilos se cargan automáticamente a través de CDN
3. No requiere compilación adicional

```bash
# Opción: Servidor local
npx serve .
```

### Versión Tailwind

1. Abre el archivo `main.html` en tu navegador
2. Utiliza Play CDN con configuración interna
3. Las clases de utilidad se procesan en tiempo real

```bash
# Opción: Servidor local
npx serve .
```

---

## ⚖️ Comparativa de Frameworks

| Aspecto | Bootstrap 5 | Tailwind CSS |
|---------|-------------|--------------|
| **Enfoque** | Componentes predefinidos | Utilidades atómicas |
| **Curva de aprendizaje** | Baja | Media |
| **Personalización** | Limitada sin SASS | Altamente flexible |
| **Tamaño final** | Mayor (~200KB) | Optimizado (~10KB) |
| **Velocidad de desarrollo** | Rápida para prototipos | Rápida con experiencia |
| **Consistencia visual** | Alta por defecto | Requiere sistema de diseño |

---

## 🎯 Objetivo del Proyecto

Este proyecto tiene como finalidad:

- Comparar dos enfoques diferentes de desarrollo con CSS
- Demostrar las ventajas y limitaciones de cada framework
- Proporcionar una base para la toma de decisiones técnicas
- Servir como referencia educativa para desarrolladores

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Haz un fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## 👨‍💻 Autor

**oiramdevelop**

- GitHub: [@oiramdevelop](https://github.com/oiramdevelop)

---

<div align="center">

**⭐ Si este proyecto te fue útil, considera darle una estrella ⭐**

Hecho con 💚 para la comunidad de desarrollo web

</div>
