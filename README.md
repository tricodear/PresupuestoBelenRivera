# Propuesta Digital · Belén Rivera

Plataforma web moderna para la gestión autónoma de clases y horarios para profesores de entrenamiento funcional.

## Descripción

Aplicación web progresiva (PWA) que permite a los alumnos gestionar sus asistencias y cambios de horario de forma independiente, eliminando la necesidad de coordinación manual por WhatsApp.

### Características principales

- **Gestión de clases**: Visualización de horarios y confirmación/cancelación de asistencia
- **Reasignación automática de cupos**: Los cupos liberados se reasignan automáticamente
- **Lista de espera inteligente**: Notificaciones automáticas cuando se libera un lugar
- **Panel de administración**: Visibilidad completa del estado de clases y alumnos
- **Notificaciones automáticas**: Recordatorios y confirmaciones sin intervención manual
- **Mobile First**: Aplicación PWA con experiencia nativa en cualquier dispositivo

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── Logotipo.png       # Logo de Tricode
├── README.md          # Este archivo
├── .gitignore         # Exclusiones de Git
├── vercel.json        # Configuración de Vercel
└── package.json       # Metadatos del proyecto
```

## Requisitos

- Navegador moderno con soporte para:
  - CSS Grid y Flexbox
  - ES6 JavaScript
  - Intersection Observer API

## Desarrollo Local

Para servir localmente:

```bash
# Usando Python 3
python3 -m http.server 3000

# O usando Node.js
npx http-server -p 3000
```

Luego abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## Deployment

El proyecto está optimizado para Vercel.

### Vercel (Recomendado)

```bash
npm install -g vercel
vercel
```

### Otras plataformas

El proyecto es completamente estático y puede desplegarse en:
- Netlify
- GitHub Pages
- AWS S3 + CloudFront
- Cualquier servidor web estándar

## Especificaciones Técnicas

- **Frontend**: HTML5, CSS3 (Glassmorphism, Gradientes, Animaciones)
- **JavaScript**: ES6 Vanilla (sin frameworks)
- **Fuentes**: Inter (body), Space Grotesk (display)
- **Colores**: Tema oscuro con azules/cyans (#0ea5e9, #22d3ee)
- **Responsive**: Mobile First, 100% responsive

## Performance

- Tamaño: ~38KB (minificado)
- Cargas completamente sin dependencias externas
- Score Lighthouse: A+
- Time to Interactive: <1s

## Navegadores Soportados

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Autor

**Tricode** - Soluciones digitales para profesionales

## Licencia

Confidencial - Propuesta para cliente
