# Auditoría rápida — PixelFest 2026

| # | Problema detectado | Categoría | ¿Por qué es problema? |
|---|---|---|---|
| 1 | Falta etiqueta meta viewport | Responsive design | Sin la etiqueta `<meta name="viewport">`, la página no detectará el ancho de los dispositivos móviles, mostrando la versión de escritorio en tamaño miniatura. |
| 2 | Menú móvil roto (IDs no coinciden) | Responsive / UX | El botón `navbar-toggler` apunta a `#menu-principal`, pero el contenedor colapsable se llama `#menu`. Al hacer clic en celulares, el menú no se abrirá. |
| 3 | Navbar sin contenedor | Layout o grid | La `<nav>` no tiene un `<div class="container">` por dentro. El logo y el menú están pegados a los bordes extremos de la pantalla, rompiendo el diseño. |
| 4 | Sistema de columnas rígido y sin márgenes | Layout o grid | El `<div class="row">` no tiene espaciado (`g-4`) y las columnas solo usan `col-md-4`. En móviles no se apilarán correctamente ni tendrán espacio entre ellas. |
| 5 | Altura de tarjetas y botones desalineados | Uso incorrecto de Bootstrap | Faltan las clases `h-100`, `d-flex flex-column` y `mt-auto`. La tarjeta de "Streaming Zone" tiene más texto y deforma todo el diseño. |
| 6 | Navegación muerta (href="#") | Links / UX | Los enlaces del menú superior y los botones de compra (Call to Action) usan `#`, por lo que no dirigen a las secciones reales de `#actividades`, `#boletos` o `#contacto`. |