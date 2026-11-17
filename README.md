# Tema 19: Entropía y Neguentropía en los Sistemas

Objeto Virtual de Aprendizaje (OVA) interactivo para el curso de **Teoría de Sistemas** — **Universidad Simón Bolívar, Campus Cúcuta**.

- **Enlace público (GitHub Pages):** `https://jncamilo20-art.github.io/OVA_/`
- **Enlace directo (Raw.githack):** `https://raw.githack.com/jncamilo20-art/OVA/main/index.html`

## Contenido

1. [Descripción](#1-descripción)
2. [Objetivos](#2-objetivos)
3. [Lineamientos del proyecto y cómo se cumplen](#3-lineamientos-del-proyecto-y-cómo-se-cumplen)
4. [Criterios de evaluación](#4-criterios-de-evaluación)
5. [Funcionalidades](#5-funcionalidades)
6. [Tecnologías y herramientas](#6-tecnologías-y-herramientas)
7. [Estructura del proyecto](#7-estructura-del-proyecto)
8. [Ejecución local y publicación](#8-ejecución-local-y-publicación)
   - [Ejecución local](#ejecución-local)
   - [Publicación en GitHub Pages](#publicación-en-github-pages)
9. [Actividades interactivas y gamificación](#9-actividades-interactivas-y-gamificación)
10. [Accesibilidad](#10-accesibilidad)
11. [Créditos](#11-créditos)
12. [Declaración de uso de inteligencia artificial](#12-declaración-de-uso-de-inteligencia-artificial)
13. [Licencia](#13-licencia)
14. [Referencias](#14-referencias)

---

## 1. Descripción
Este Objeto Virtual de Aprendizaje explora cómo la **entropía** representa la tendencia natural de los sistemas al desgaste, desorden e incertidumbre, y cómo los **sistemas abiertos** importan **neguentropía** (energía, materia e información) desde su entorno para sostener su organización, homeostasis y viabilidad en el tiempo.

## 2. Objetivos
- Comprender la Segunda Ley de la Termodinámica aplicada a los sistemas abiertos y cerrados.
- Analizar el flujo **E-P-S-R** (Entrada, Proceso, Salida y Retroalimentación).
- Relacionar la entropía negativa de Schrödinger con la información de Shannon/Brillouin y la homeostasis de Wiener.
- Aplicar estrategias neguentrópicas en casos reales de Ingeniería de Sistemas, organizaciones y biología.

## 3. Lineamientos del proyecto y cómo se cumplen
- **Navegación modular enfocada (SPA):** Inicio con índice de temas; cada tema se abre de forma independiente con botón de retorno al principio y avance al siguiente módulo.
- **Diseño responsivo:** Adaptado para computador, tablet y celular (`<= 640px`).
- **Portabilidad:** Ejecución sin servidor (`index.html` modular y copia todo-en-uno `OVA-Portable.html`).

## 4. Criterios de evaluación
- Sistema de puntos **XP (0 a 1000 XP)** e insignias desbloqueables en la barra superior.
- **Prueba Evaluativa** de 5 preguntas con retroalimentación inmediata y cálculo de desempeño.
- Retos prácticos en el Taller de Clasificación, Toma de Decisiones y Laboratorio de 3 juegos.

## 5. Funcionalidades
- Monitor radial interactivo de estado entrópico/neguentrópico en Inicio.
- Modelo interactivo E-P-S-R y taller de emparejamiento conceptual.
- Casos comparativos reales y simulador de toma de decisiones.
- Laboratorio Gamificado con 3 juegos en pestañas (`Clasificador 30s`, `Simulador de Neguentropía`, `Desafío de Acoplamiento`).
- Sección de videos explicativos en español y asistente `RoboTGS`.

## 6. Tecnologías y herramientas
- **HTML5**, **CSS3** (variables CSS, diseño responsivo, modo oscuro/día suave) y **JavaScript Vanilla (ES6)**.
- **Web Audio API** (efectos de sonido sintetizados) y **Web Speech API** (narración por voz en español).

## 7. Estructura del proyecto
```text
OVA/
├── index.html          # Estructura principal del OVA (vista modular SPA)
├── css/
│   └── style.css       # Estilos cyber-aurora, modo día suave y diseño móvil
├── js/
│   └── script.js       # Lógica interactiva, juegos, simuladores, voz y quiz
├── assets/
│   ├── logo.png        # Escudo oficial Universidad Simón Bolívar
│   └── FONDO.png       # Recurso visual institucional
├── .nojekyll           # Configuración limpia para GitHub Pages
├── FICHA_TECNICA.md    # Metadatos técnicos y pedagógicos del OVA
├── README.md           # Documentación general del proyecto
└── OVA-Portable.html   # Copia autocontenida en un solo archivo
```

## 8. Ejecución local y publicación
### Ejecución local
Abre directamente `index.html` en Google Chrome, Microsoft Edge o Firefox (no requiere servidor ni instalación).

### Publicación en GitHub Pages
1. Sube la carpeta completa al repositorio `jncamilo20-art/OVA`.
2. En GitHub ve a **Settings → Pages → Branch: `main` → `/ (root)` → Save**.
3. El sitio quedará publicado en `https://jncamilo20-art.github.io/OVA/` (y también accesible vía `https://raw.githack.com/jncamilo20-art/OVA/main/index.html`).

## 9. Actividades interactivas y gamificación
- **Juego 1:** Clasificador de Sistemas (30 segundos).
- **Juego 2:** Simulador en tiempo real de Entropía vs. Neguentropía.
- **Juego 3:** Desafío de Acoplamiento Sistémico (5 retos).

## 10. Accesibilidad
- Cambio de tema (**Modo Oscuro / Modo Día Suave** anti-deslumbramiento).
- Ajuste tipográfico (**`A-` / `A+`**).
- Narrador de texto por voz (**`Leer Voz` / `Detener Voz`**) con filtrado de emojis.
- Ventana modal de **Ficha Técnica**.

## 11. Créditos
- **Estudiante Autor:** Juan Camilo Ramírez Cáceres — Ingeniería de Sistemas.
- **Docente Titular:** Eddy Ramírez — Curso de Teoría de Sistemas.
- **Institución:** Universidad Simón Bolívar — Campus Cúcuta.

## 12. Declaración de uso de inteligencia artificial
Se emplearon modelos de Inteligencia Artificial generativa como herramienta de apoyo en el diseño visual, estructuración modular de código (HTML, CSS y JS) y refinamiento pedagógico del OVA, bajo revisión y dirección del autor.

## 13. Licencia
Uso académico y educativo — Universidad Simón Bolívar, Campus Cúcuta.

## 14. Referencias
- Bertalanffy, L. von (1968). *General System Theory: Foundations, Development, Applications*. George Braziller.
- Schrödinger, E. (1944). *What is Life? The Physical Aspect of the Living Cell*. Cambridge University Press.
- Shannon, C. E. (1948). *A Mathematical Theory of Communication*. Bell System Technical Journal.
- Brillouin, L. (1956). *Science and Information Theory*. Academic Press.
- Wiener, N. (1948). *Cybernetics: Or Control and Communication in the Animal and the Machine*. MIT Press.
- Ashby, W. R. (1956). *An Introduction to Cybernetics*. Chapman & Hall.
