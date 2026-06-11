# Práctica Formativa Obligatoria 2: Prompt Engineering en Agentes de IA

## 👤 Datos del Estudiante
* **Nombre y Apellido:** Rodrigo Damian Berger
* **Institución:** Instituto de Formación Técnica Superior (IFTS) N.° 29
* **Asignatura:** Desarrollo de Sistemas Web (Front End)
* **Fecha de Entrega:** 26 de Junio de 2026

---

## 🚀 Despliegue (Deploy)
El proyecto se encuentra unificado y desplegado en la plataforma Vercel a través del siguiente enlace:
* **Link al Deploy:** https://pfo2-eight.vercel.app/

---

## 🎯 Objetivo del Proyecto
El propósito de esta práctica es diseñar y estructurar un único prompt inicial de alta precisión basado en los lineamientos de las guías oficiales de OpenAI y Anthropic. Este prompt fue ejecutado en dos agentes de desarrollo de software de manera autónoma (sin edición manual de código) para evaluar y comparar su capacidad de resolución, diseño, adaptabilidad responsive y completitud visual.

La temática elegida para el desarrollo de la Landing Page es una **Compañía y Taller de Teatro Independiente ("En el Acto")**.

---

## 🛠️ Agentes de Desarrollo Utilizados

1. **Agente 1: OpenCode**
   * **Modelo de Lenguaje:** DeepSeek V4 Flash Free
   * **Entorno:** Extensión de chat/agente sobre entorno OpenCode.

2. **Agente 2: Cursor**
   * **Modelo de Lenguaje:** Composer 2.5 Fast
   * **Entorno:** Modo Composer / Generación autónoma de archivos en directorio.

---

## 📝 Prompt Único Utilizado
A continuación se detalla la instrucción exacta provista de forma idéntica a ambos agentes:

```text
CONTEST / ROLE:
You are an expert Senior Frontend Developer and UI/UX Designer. Your task is to autonomously generate a complete, production-ready, single-page Landing Page for an Independent Theater and Improvisation Workshop Company named "En el Acto".

TECHNICAL STACK & CONSTRAINTS:
- Use clean, modern, semantic HTML5 and CSS3.
- To ensure a highly professional and modern visual design without manual intervention, you MUST use Tailwind CSS via CDN linked in the <head>.
- Do not use any external custom JavaScript files or backend dependencies. 
- If interactive elements (like mobile menu toggles) are needed, implement them using simple, inline vanilla JavaScript within a <script> tag at the bottom.
- The layout must be 100% responsive (mobile-first approach) and look flawless on mobile, tablet, and desktop viewports.
- All images must use high-quality, reliable placeholders from Unsplash (e.g., [https://images.unsplash.com/](https://images.unsplash.com/)... using terms like "theater", "stage", "acting").
- DO NOT leave any placeholder text like "Lorem Ipsum". Write realistic, engaging copy in Spanish.

DESIGN SYSTEM & AESTHETICS:
- Vibe: Artistic, dramatic, modern, and welcoming.
- Palette: 
  * Primary: Deep Charcoal / Dark Slate (Backgrounds to simulate a theater stage environment).
  * Secondary: Vibrant Crimson Red or Warm Amber/Gold (For Call-To-Actions, highlights, and dramatic accents).
  * Text: Crisp White and Light Gray for readability.
- Typography: Sans-serif, bold headers for high contrast and clean body text.

REQUIRED STRUCTURE (7 MANDATORY SECTIONS):
Your output must contain a single index.html file with the following sections clearly structured:
1. HEADER (Navigation Bar)
2. HERO SECTION
3. DESCRIPTION / ABOUT US ("Sobre Nosotros")
4. SERVICES / FEATURES ("Nuestros Talleres")
5. TESTIMONIALS ("Reseñas de Alumnos")
6. CONTACT FORM ("Sumate a la Compañía")
7. FOOTER

OUTPUT REQUIREMENT:
Generate the entire code in one single block. Ensure every section is visually distinguished with appropriate spacing (padding/margin), clean alignment, and professional design choices. Do not truncate the code.