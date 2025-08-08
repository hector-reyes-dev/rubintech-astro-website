# 🚀 Rubin Tech - Sitio Web Corporativo

Sitio web corporativo moderno para Rubin Tech, desarrollado con **Astro** y **Tailwind CSS**. Transformamos desafíos en oportunidades tecnológicas con soluciones personalizadas.

## ✨ Características

- 🎨 **Diseño Moderno**: UI/UX profesional con gradientes y animaciones suaves
- 📱 **Responsive Design**: Optimizado para todos los dispositivos
- ⚡ **Alto Rendimiento**: Construido con Astro para máxima velocidad
- 🎯 **SEO Optimizado**: Meta tags, Open Graph y Twitter Cards
- 🔧 **TypeScript**: Desarrollo type-safe
- 🎨 **Tailwind CSS**: Sistema de diseño escalable

## 🏗️ Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── layout/          # Header, Footer, Layout
│   │   ├── sections/        # Hero, Services, Projects, etc.
│   │   └── ui/             # Button, Card, Icon
│   ├── pages/
│   │   └── index.astro     # Página principal
│   └── styles/
│       └── global.css      # Estilos globales y variables
├── astro.config.mjs        # Configuración de Astro
├── tailwind.config.mjs     # Configuración de Tailwind
└── package.json
```

## 🎨 Componentes Principales

### Layout
- **Header**: Navegación responsive con menú móvil
- **Footer**: Enlaces organizados y información de contacto
- **Layout**: Estructura base con SEO optimizado

### Secciones
- **Hero**: Sección principal con CTA y elementos visuales
- **Banner**: Indicadores de confianza y estadísticas
- **Services**: Grid de servicios con iconos y características
- **Projects**: Casos de estudio y portfolio
- **Testimonials**: Reseñas de clientes y métricas
- **CTA**: Llamada a la acción final

### UI Components
- **Button**: Botón reutilizable con variantes y tamaños
- **Card**: Tarjetas con diferentes estilos
- **Icon**: Sistema de iconos SVG

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
