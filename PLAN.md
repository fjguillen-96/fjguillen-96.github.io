# Plan de Mejora Estética - fjguillen-96.github.io

## Fase 1: Correcciones críticas
1. **Arreglar links rotos de WhatsApp** - Cambiar `TUNUMERO` por `663673688` en nav y footer
2. **Eliminar texto de desarrollador** - Quitar referencias a `<iframe>`, `<video>`, "Pegar enlace", "Subir archivo" visibles para el usuario final
3. **Añadir meta tags** - Description, Open Graph (og:title, og:description, og:image), favicon básico via emoji/SVG

## Fase 2: Hero Section - Impacto visual
4. **Fondo con gradiente sutil** - Añadir un gradiente radial suave (blue → transparent) detrás del hero para dar profundidad
5. **Hacer la foto de perfil más grande** - Aumentar a `w-56 h-56 md:w-72 md:h-72` con un efecto de halo/glow sutil
6. **Badge "En línea" animado** - Añadir un punto verde pulsante (CSS animation) al badge "En línea ahora"
7. **Texto hero con gradiente** - Aplicar gradiente de color al nombre "Francisco Javier" para más impacto
8. **Mejorar CTAs** - Hacer el botón principal más grande con gradiente y el secundario con un icono de WhatsApp

## Fase 3: Animaciones de scroll
9. **Fade-in al hacer scroll** - Añadir animaciones CSS con Intersection Observer para que las secciones y cards aparezcan con fade-in + slide-up al entrar en viewport
10. **Navbar con sombra dinámica** - Añadir sombra progresiva al navbar al scrollear (más sombra cuanto más scroll)

## Fase 4: Cards y demos mejorados
11. **Jerarquía visual en cards** - La card principal ("La Agenda Perfecta") con borde gradiente o fondo sutil que la diferencie de las secundarias
12. **Video placeholders simplificados** - Reemplazar los placeholders con instrucciones de dev por un diseño más limpio: solo icono de play + descripción breve
13. **Hover effects en cards** - Añadir transición suave de elevación (shadow + translateY) al hover de cada card
14. **Iconos más expresivos** - Reemplazar emojis por iconos SVG inline más profesionales (o al menos mejorar el tamaño/presentación de los emojis actuales)

## Fase 5: Social proof y credibilidad
15. **Sección de métricas/números** - Reemplazar "Próximamente: Casos Reales" por una tira de métricas: "X negocios automatizados", "Xh ahorradas", "X% menos no-shows" (pueden ser estimaciones)
16. **Testimonios placeholder mejorados** - En vez de cards vacías con borde dashed, cards sólidas con comillas y "Próximamente" elegante

## Fase 6: Footer mejorado
17. **Fondo del footer con gradiente** - Gradiente sutil de slate a blue oscuro para más personalidad
18. **Botón WhatsApp con animación pulse** - Efecto pulsante sutil para atraer la atención al CTA principal

## Resumen de tecnologías
- Todo se implementa en el mismo `index.html`
- CSS puro (keyframes) para animaciones, sin librerías extra
- Intersection Observer nativo para animaciones de scroll
- Tailwind CSS (CDN existente) para estilos
- Sin dependencias nuevas
