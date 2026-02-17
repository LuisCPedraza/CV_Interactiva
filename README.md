# Juego Interactivo de Evolución de Vida – Luis Carlos Pedraza

## 1. 📌 Descripción del Proyecto
Este proyecto es un **juego 2D en HTML5 Canvas** que representa, de forma interactiva, la evolución personal y profesional de **Luis Carlos Pedraza** a través de hitos cronológicos.

- **Objetivo del juego:** avanzar esquivando obstáculos y **desbloquear hitos** que cuentan momentos clave de vida.
- **Concepto narrativo:** la experiencia inicia con una **forma abstracta de origen** (simbólica, tipo “célula” en evolución) y progresa visualmente hasta una etapa de **perfil profesional tech**.
- **Enfoque autobiográfico interactivo:** cada hito funciona como un “capítulo” que se revela en una ventana emergente (modal), transformando una hoja de vida en una experiencia jugable.

---

## 2. 🎯 Objetivos Técnicos
- **Qué problemas resuelve:**
  - Presentar una historia profesional de manera memorable (más allá de un CV tradicional).
  - Integrar narrativa, UI y jugabilidad en un solo proyecto web liviano.
- **Qué habilidades demuestra:**
  - Programación de juego 2D con **Canvas** (loop, render, colisiones, spawns).
  - Manejo de **estado** (hitos, obstáculos, vidas, pausa, modales, finalización).
  - Experiencia de usuario (transiciones, retroalimentación visual y sonora).
  - Audio generativo con **Web Audio API**.

---

## 3. 🛠 Tecnologías Utilizadas
- **HTML5** (estructura del proyecto web)
- **CSS3** (estilos y layout del UI)
- **JavaScript (ES6+)** (lógica del juego y UI)
- **HTML5 Canvas API** (renderizado 2D)
- **Web Audio API** (música retro y efectos de sonido)

**Navegadores compatibles (recomendado):**
- Chrome / Edge (últimas versiones)
- Firefox (últimas versiones)

Nota: por políticas del navegador, el audio se activa tras una interacción del usuario (teclado/click).

---

## 4. 📚 Librerías Utilizadas
- **No se utilizaron librerías externas.**

**¿Por qué JavaScript puro?**
- Mantener el proyecto **ligero, portable y fácil de revisar**.
- Mostrar dominio de fundamentos (Canvas, estado, UI y audio) sin depender de frameworks.

---

## 5. 🧠 Arquitectura y Estructura del Proyecto
Estructura simple y directa para un proyecto de portafolio:

- `index.html`
  - Define la interfaz (canvas, paneles, controles) y el **modal** reutilizable.
- `style.css`
  - Estilo visual profesional, layout del panel informativo y estilos de modales.
- `script.js`
  - Motor del juego (loop `update/draw`), generación de hitos/obstáculos, colisiones, vidas,
    modales, audio (música + SFX) y flujo de finalización.

Ejecución local (opcional): abrir `index.html` directamente o usar un servidor local (por ejemplo, Live Server) para una experiencia más consistente.

---

## 6. ⚙ Funcionalidades Principales
- **Sistema de hitos cronológicos**
  - Los hitos aparecen en orden, se desbloquean al contacto y muestran información descriptiva.
- **Sistema de obstáculos**
  - Obstáculos entre hitos para introducir reto y ritmo.
- **Sistema de vidas (3 vidas)**
  - Al chocar con un obstáculo se pierde una vida.
- **Persistencia del progreso hasta perder todas las vidas**
  - El avance de hitos se mantiene mientras queden vidas; el reinicio completo ocurre al perder las 3.
- **Ventanas emergentes (modales)**
  - Pausan el juego para leer el hito con calma.
- **Transformación del personaje por etapas**
  - Evolución visual por etapas de vida (incluyendo origen abstracto) con transiciones suaves.
- **Pantalla final con reflexión y hoja de vida**
  - Al completar el último hito se muestra un mensaje final y, posteriormente, la hoja de vida.

Controles (según configuración actual):
- **Saltar:** barra espaciadora o pulsación/tap sobre el canvas
- **Pausar/Reanudar:** botón o tecla **P**
- **Sonido:** botón de mute/sonido

---

## 7. 🎨 Diseño y Experiencia de Usuario
- **Evolución visual del personaje:** representación por etapas, manteniendo proporciones consistentes.
- **Transiciones:** cambios visuales suaves entre etapas y flujo ordenado de modales.
- **Sonidos y retroalimentación:**
  - Música de fondo estilo retro.
  - Efectos de salto, colisión, hito, pérdida de vida y triunfo.
  - Feedback visual al recibir daño (efecto breve) para sensación de juego “real”.
- **Diseño minimalista profesional:** interfaz limpia, legible y orientada a narrativa.

---

## 8. 🔄 Metodología de Desarrollo
- **Desarrollo incremental:** construcción por módulos (UI → hitos → obstáculos → audio → vidas → final).
- **Mejora iterativa:** ajustes constantes basados en jugabilidad (espaciado, colisiones, ritmo).
- **Pruebas manuales:** verificación en navegador (rendimiento, interacción, modales y flujo final).
- **Ajustes de jugabilidad:** balance de velocidad, separación de segmentos y estabilidad del progreso.

---

## 9. 📈 Estrategias Implementadas
- **Narrativa interactiva:** cada hito es parte del relato y se presenta en el momento exacto del avance.
- **Gamificación de una hoja de vida:** el CV deja de ser estático y se convierte en experiencia.
- **Diseño orientado a experiencia emocional:** énfasis en resiliencia, disciplina y reinvención.

---

## 10. 🚀 Posibles Mejoras Futuras
- **Guardado de progreso** (localStorage) para retomar la partida.
- **Optimización móvil** (controles táctiles más completos y UI responsive avanzada).
- **Animaciones más avanzadas** (más frames de caminata, expresiones, transiciones por keyframes).
- **Backend para estadísticas** (intentos, hitos vistos, métricas de juego, logros compartibles).

---

## 11. 👤 Autor
- **Luis Carlos Pedraza**
- **Tecnología en Desarrollo de Software**
- **Año:** 2026
- **Objetivo profesional:** consolidar una carrera en tecnología con enfoque en **trabajo remoto** y crecimiento continuo.
