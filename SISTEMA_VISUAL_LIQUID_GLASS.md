# Sistema de diseño — Liquid Glass TeP

Este documento define el lenguaje visual reutilizable para las próximas páginas del proyecto.

- Fondo marfil continuo con iluminación ambiental suave; **sin franjas duras entre secciones**.
- Cristal semitransparente con desenfoque moderado, borde interior claro y una sola fuente de reflejo por componente.
- Paleta de TeP: blanco cálido, grafito, naranja quemado; tipografía legible y contraste consistente.
- Animaciones: entrada progresiva discreta, reflejos exclusivamente horizontales en botones y sin movimientos permanentes invasivos.
- Responsive: ancho fluido, grillas que se adaptan, sin corte de textos ni controles. Pantallas objetivo desde 320 px a 3840 px.
- Accesibilidad: respetar `prefers-reduced-motion`, teclado, foco visible y campos editables.
- Contenido ilustrativo claramente señalado; TeP vende servicios de tapicería, no productos predefinidos.
- Evitar apilar parches CSS contradictorios en futuras versiones; consolidar reglas por componente y probar cada breakpoint.

Regla de interfaz específica solicitada para este sitio: el texto de presentación no se puede seleccionar/copiar con el mouse. Los campos de formulario permanecen editables y se conserva el botón intencional para copiar el mensaje. Esta medida es de experiencia de uso, no una protección técnica del contenido.
