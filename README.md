# Rubin Tech - Sitio Web Corporativo

## Descripción

Sitio web corporativo moderno para Rubin Tech, una empresa especializada en soluciones tecnológicas personalizadas. Desarrollado con Astro y Tailwind CSS para ofrecer una experiencia web rápida, moderna y optimizada.

## Características

- ✨ **Diseño Moderno**: Interfaz limpia y profesional con gradientes y animaciones suaves
- 📱 **Totalmente Responsivo**: Optimizado para todos los dispositivos y tamaños de pantalla
- ⚡ **Alto Rendimiento**: Construido con Astro para máxima velocidad de carga
- 🎨 **Tailwind CSS**: Sistema de diseño consistente y mantenible
- 🔍 **SEO Optimizado**: Meta tags, Open Graph y estructura semántica
- ♿ **Accesible**: Cumple con estándares de accesibilidad web
- 🛠️ **TypeScript**: Desarrollo type-safe para mayor robustez

## Estructura del Proyecto

```
src/
├── components/
│   ├── layout/
│   │   ├── Layout.astro      # Layout principal con SEO
│   │   ├── Header.astro      # Navegación principal
│   │   └── Footer.astro      # Pie de página
│   ├── sections/
│   │   ├── Hero.astro        # Sección hero principal
│   │   ├── Banner.astro      # Estadísticas y tecnologías
│   │   ├── Services.astro    # Servicios ofrecidos
│   │   ├── Projects.astro    # Casos de éxito
│   │   ├── Testimonials.astro # Testimonios de clientes
│   │   └── CTA.astro         # Llamada a la acción
│   └── ui/
│       ├── Button.astro      # Componente de botón reutilizable
│       ├── Card.astro        # Componente de tarjeta
│       └── Icon.astro        # Sistema de iconos SVG
├── pages/
│   └── index.astro           # Página principal
└── styles/
    └── global.css            # Estilos globales y variables CSS
```

## Componentes Principales

### Layout
- **Layout.astro**: Estructura HTML base con SEO completo
- **Header.astro**: Navegación responsiva con menú móvil
- **Footer.astro**: Enlaces organizados y información de contacto

### Secciones
- **Hero**: Presentación principal con CTAs y elementos visuales
- **Banner**: Estadísticas de confianza y tecnologías
- **Services**: Servicios detallados con iconos y características
- **Projects**: Casos de éxito con métricas de resultados
- **Testimonials**: Testimonios reales con ratings
- **CTA**: Sección final de conversión

### UI Components
- **Button**: Botón reutilizable con variantes y tamaños
- **Card**: Tarjetas con diferentes estilos según contexto
- **Icon**: Sistema de iconos SVG optimizado

## Tecnologías Utilizadas

- **Astro**: Framework web moderno para sitios estáticos
- **Tailwind CSS**: Framework CSS utility-first
- **TypeScript**: Superset de JavaScript con tipado estático
- **CSS Custom Properties**: Variables CSS para temas consistentes

## Comandos Disponibles

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                        |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`           | Construye el sitio para producción en `./dist/` |
| `npm run preview`         | Vista previa del build local antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI de Astro como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda usando el CLI de Astro             |

## Instalación y Desarrollo

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/hector-reyes-dev/rubintech-astro-website.git
   cd rubintech-astro-website
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**
   ```bash
   npm run dev
   ```

4. **Abre tu navegador**
   Visita `http://localhost:4321` para ver el sitio

## Personalización

### Colores y Temas
Los colores principales se definen en `tailwind.config.mjs` y `src/styles/global.css`:

```css
:root {
  --color-primary: #1E40AF;
  --color-secondary: #059669;
  /* ... más variables */
}
```

### Contenido
El contenido principal se encuentra en:
- `src/pages/index.astro` - Estructura de la página
- `src/components/sections/` - Contenido de cada sección

## Despliegue

Este sitio está optimizado para desplegarse en:
- **Vercel** (recomendado)
- **Netlify**
- **GitHub Pages**
- Cualquier hosting de sitios estáticos

## Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Contacto

**Héctor Reyes** - Desarrollador Full Stack
- GitHub: [@hector-reyes-dev](https://github.com/hector-reyes-dev)
- Email: contacto@rubintech.com

---

¿Quieres saber más sobre Astro? Consulta [la documentación](https://docs.astro.build) o únete a [la comunidad en Discord](https://astro.build/chat).