[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/gv2H4LL7)
# 🧪 Examen Práctico — Auditoría y Corrección Bootstrap
## PixelFest 2026

Duración: **50 minutos**  
Modalidad: **Individual**

---

# 🎯 Objetivo

Este examen evalúa tu capacidad para:

- Analizar una interfaz web existente
- Detectar problemas de **UX, estructura y responsive**
- Corregirlos utilizando **Bootstrap**

Recibirás una **landing page con errores intencionales**.  
Tu trabajo será **identificar problemas y mejorar el diseño**.

---

# 🧩 Archivos del repositorio

El repositorio contiene:

index.html → página con errores intencionales
styles.css → estilos mínimos
AUDITORIA.md → archivo para registrar problemas encontrados
README.md → instrucciones del examen


---

# 🧠 Parte 1 — Auditoría (Análisis)

Antes de modificar el código, revisa el archivo **index.html** y detecta problemas de diseño.

Debes identificar **al menos 6 problemas** relacionados con:

- UX (claridad, navegación, acciones)
- Responsive design
- Uso incorrecto de Bootstrap
- Jerarquía visual
- Layout o grid mal aplicado
- Links o navegación incorrecta

Registra los hallazgos en el archivo:
AUDITORIA.md


Ejemplo de estructura:

| # | Problema detectado | Categoría | Explicación |
|---|---|---|---|
| 1 | Navbar no colapsa correctamente | Responsive | El botón toggler no funciona |
| 2 | Botones con href="#" | UX | No realizan ninguna acción |

---

# 🔧 Parte 2 — Corrección

Después de identificar los problemas, debes **corregir el diseño de la página**.

La versión final debe cumplir con lo siguiente:

### Navbar
Debe ser **responsive** y funcional.

Debe incluir:

- `container`
- collapse funcional
- navegación a secciones reales (`#actividades`, `#boletos`, `#contacto`)

---

### Hero

Debe tener:

- jerarquía visual clara
- espaciado adecuado
- botón funcional

Ejemplo esperado:
<section class="bg-light py-5 text-center"> <div class="container">


---

### Sección de Cards

Las cards deben usar un **grid responsive**.

Se espera una estructura similar a:
<div class="row g-4"> <div class="col-12 col-md-6 col-lg-4"> <div class="card h-100 shadow-sm">


Todas las cards deben:

- tener **misma altura**
- incluir **imagen, título, texto y botón**
- mantener buen espaciado

---

### Imágenes

Las imágenes deben ser **responsive**.

Ejemplo:
<img src="..." class="card-img-top img-fluid">


---

### Links

No deben existir enlaces sin función como:
href="#"


Los botones deben navegar a secciones reales o URLs válidas.

---

# 📱 Responsive

El diseño debe verse correctamente en:

- **móvil**
- **tablet**
- **escritorio**

Usa correctamente el sistema de columnas de Bootstrap.

---

# 📦 Entregables

Tu repositorio debe contener:
index.html corregido
styles.css
AUDITORIA.md (mínimo 6 problemas identificados)


---

# 💾 Commit final

Realiza un commit final con el siguiente mensaje:
