# Design System - Coopetour Ecoturismo La Palma

## 👁️ Visión General (Minimalista & Vibrante)
Basado en las imágenes de las camisetas y el logo, utilizaremos una aproximación **minimalista**: abundante espacio en blanco (negative space) para dar respiro visual, utilizando los colores vibrantes (Naranja y Verde neón) estrictamente como acentos para botones, llamadas a la acción (CTAs) e iconografía. Esto evitará abrumar al usuario y mantendrá una apariencia limpia, profesional, muy estética ("súper linda") y ecológica.

## 🎨 Paleta de Colores

### Brand Colors (Colores de la Marca)
- **Primary (Naranja Coopetour)**: `#FF6600` (Extraído del cuerpo vibrante de la jersey. Uso: Botones primarios, enlaces activos, badges destacados, llamadas a la acción).
- **Secondary (Verde Ecoturismo)**: `#32CD32` (Verde lima brillante extraído de las mangas y palmeras. Uso: Botones secundarios, iconos de naturaleza, checkmarks de éxito, acentos sutiles).
- **Tertiary (Azul Río)**: `#0F172A` o `#1E3A8A` (Azul muy oscuro para anclar el diseño. Uso: Textos principales, footer, para dar un toque elegante y formal contrastando los colores neón).

### Neutral/UI Colors (Esenciales para el Minimalismo)
- **Background**: `#FFFFFF` (Blanco puro para mantener el diseño minimalista y súper limpio, dejando que las fotos resalten).
- **Surface/Cards**: `#F8FAFC` (Un gris/azul ultra claro para separar tarjetas del fondo blanco sin usar líneas o bordes pesados).
- **Primary Text**: `#0F172A` (Slate oscuro para altísima legibilidad).
- **Secondary Text**: `#64748B` (Gris medio para subtítulos y descripciones).

## 🔤 Tipografía
- **Headings (Títulos)**: `Outfit` o `Poppins` - Fuentes modernas, amigables y geométricas que combinan excelente con ecoturismo. Usar `font-bold` (700) o `font-extrabold` (800) para gran impacto.
- **Body (Cuerpo)**: `Inter` - Limpia y de altísima legibilidad.
- **Escala**:
  - H1: `text-5xl` o `text-6xl` (Desktop) / `text-4xl` (Mobile) con `tracking-tight` (letras un poco juntas).
  - Body: `text-base` (16px) o `text-lg` (18px) con un line-height amplio (`leading-relaxed` / 1.6).

## 📐 Reglas UI/UX (Basado en la skill `ui-ux-pro-max`)
1. **Accesibilidad (Contraste)**: El texto sobre el botón naranja `#FF6600` o verde debe ser blanco puro (`#FFFFFF`) y con fuente gruesa para asegurar el contraste.
2. **Espaciado (Whitespace)**: Uso riguroso de múltiplos de 8px. Mucho padding (`py-16` o `py-24`) entre secciones para sostener el estilo minimalista. ¡El espacio vacío es el secreto del minimalismo premium!
3. **Interacción y Animación**:
   - Botones con `hover:scale-105` y transiciones suaves (`transition-transform duration-200 ease-out`).
   - Sombras muy suaves (`shadow-sm` o `shadow-[0_8px_30px_rgb(0,0,0,0.04)]`) solo en tarjetas al hacer hover (para darle un toque moderno sin que se vea sucio).
4. **Bordes y Formas**: Bordes moderadamente redondeados (`rounded-xl` o `rounded-2xl`) para dar una sensación orgánica y amigable, acorde a la naturaleza.
5. **Iconografía**: Usar íconos vectoriales simples (ej. `lucide-react` si estuviéramos en React, o SVG directo en Astro) con `stroke-width` fino de `1.5`. Nada de emojis para iconos estructurales.

## 🖼 Estructura Sugerida para la Landing Page
1. **Navbar**: Limpio, fondo blanco o transparente, con el Logo a la izquierda y un botón Naranja vibrante "Reservar" a la derecha.
2. **Hero Section**: Gran tipografía, fondo blanco o gris súper claro (`#F8FAFC`). Tal vez una foto de la naturaleza o de la camiseta "flotando", con el título "Vive la experiencia La Palma" y dos botones (Primario Naranja, Secundario Verde/Outline).
3. **Features/Servicios**: Tarjetas blancas flotantes sobre fondo casi blanco. Iconos verdes.
4. **Galería**: Cuadrícula (Bento Grid) minimalista para lucir las hermosas fotos y el jersey.
5. **Footer**: Fondo Azul oscuro con links en blanco y acentos en verde o naranja.
