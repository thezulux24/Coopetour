# Memoria del Proyecto - Coopetour

## Estado Actual
- **Fase**: Desarrollo de Landing Page (Propuesta para el Gobierno/Clientes).
- **Diseño**: Se implementó exitosamente el estilo "Minimalismo Icónico" basado en la referencia de Stitch. El diseño es extremadamente limpio, tipográfico, con bordes rectos y alto uso de espacios en blanco (Glassmorphism sutil y fondos blancos).
- **Componentes Creados**: `Layout`, `Navbar`, `Hero`, `Contexto` (con carrusel interactivo), `Pilares` (estilo abstracto con SVGs), `Galeria` (Bento Grid estilo museo), `LocationMap`, `Footer`, y `WhatsAppWidget`.
- **Integración de Imágenes**: Se removió el fondo negro de los logos (`logoFondoNegro.png`) preservando la opacidad de los colores, y se integraron las fotos del "Estado Actual" y "Renders" en la galería y contexto.

## Tareas Pendientes / Próximos Pasos
- **Corrección del Mapa**: Mejorar la visibilidad del iframe de Google Maps en `LocationMap.astro`, eliminando el efecto oscuro/lavado que lo hace ver raro.
- **Expansión de Contenido (Pitching)**: Agregar más información (textos simulados pero realistas) para que la página funcione como una propuesta sólida (Experiencias, Testimonios/Comunidad, Preguntas Frecuentes).
- **Páginas Legales**: Crear rutas para Términos y Condiciones, y Políticas de Privacidad, para dar un aspecto 100% profesional y corporativo.
- **Refinamiento de UX**: Asegurar que todas las anclas y botones de "Apoyar Ahora" tengan sentido en el flujo de la página.

## Notas de Diseño
- Mantener la paleta de colores: Blanco puro (`#FFFFFF`), Gris Pizarra para textos (`#0F172A` y `#475569`), y Naranja Brillante como acento (`#FF6600`).
- Tipografías: `Outfit` (Títulos) e `Inter` (Cuerpos de texto).
- Evitar bordes redondeados en las fotografías para mantener el look arquitectónico y minimalista.
