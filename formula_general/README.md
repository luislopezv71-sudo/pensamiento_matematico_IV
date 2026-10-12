<!--
==========================================================================
SYSTEM / APPLICATION METADATA BLOCK
==========================================================================
Project Name     : Artefactos Interactivos - Fórmula General y Ejercicios de Repaso
Module           : Pensamiento Matemático IV
Institution      : Universidad William Osler - Bachillerato (Zihuatanejo, Gro.)
Author / Developer: L.I. Luis Arturo López Vergara
Edition          : 2026
Repository       : Formula-General-Pensamiento-Matematico-IV
IA               : Gemini Plus - 	luisarturo.lopez.universidad.uwo@gmail.com
==========================================================================
-->

# Pensamiento Matemático IV — Ecuaciones Cuadráticas: Fórmula General y Ejercicios de Repaso 🧮

Este repositorio contiene la colección de **artefactos web interactivos** diseñados para el aprendizaje, ejercitación y gamificación de la **Fórmula General** aplicada a situaciones del mundo real, orientada a los alumnos de Bachillerato de la **Universidad William Osler** (Zihuatanejo, Guerrero).

---

## 🎯 Objetivos Pedagógicos

1. **Definir y Comprender:** Identificar la estructura estándar de una ecuación cuadrática ($ax^2 + bx + c = 0$) y la fórmula general ($x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$).
2. **Visualizar e Interactuar:** Experimentar en tiempo real con los coeficientes $a, b, c$ usando sliders dinámicos para comprender el impacto del discriminante ($\Delta = b^2 - 4ac$).
3. **Practicar y Validar:** Resolver ejercicios contextualizados de física (lanzamiento de proyectiles, caída libre), economía (puntos de equilibrio, maximización de ingresos) y geometría.
4. **Gamificar y Transferir:** Acumular puntos en un entorno interactivo por fases (Fase 1: 50 PTS en casos rápidos) para desbloquear retos complejos para resolución formal en libreta (Fase 2: 50 PTS).

---

## 📁 Estructura del Repositorio

```text
.
├── index.html                   # Artefacto principal (3 Etapas: Teoría + Práctica + Reto Gamificado)
├── ejercicios_de_repaso_1.html  # Artefacto de Repaso Intensivo (Reto Gamificado directo)
└── README.md                    # Documentación principal del proyecto

---
```

### 💻 Contenido de los Artefactos

#### 1️⃣ `index.html` — Artefacto Principal (3 Etapas)
* **Etapa 1 (Definición y Teoría):** Presentación matemática clara renderizada con MathJax y simulador con deslizadores intermedios para $a$, $b$ y $c$.
* **Etapa 2 (Ejercicios Prácticos):** Validación inmediata de coeficientes y solución física para casos contextualizados.
* **Etapa 3 (Reto Gamificado):** Misión de 100 PTS dividida en:
  * **Fase 1 (50 PTS):** 5 casos rápidos con retroalimentación instantánea.
  * **Fase 2 (50 PTS):** Desbloqueo del *Caso Desafío: Diseño del Parque Acuático en Zihuatanejo* para entrega en libreta.

#### 2️⃣ `ejercicios_de_repaso_1.html` — Módulo de Repaso Intensivo
* **Formato Directo:** Enfocado exclusivamente en el reto gamificado progresivo de repaso.
* **Fase 1 (50 PTS):** 5 nuevos casos rápidos (caída de objetos, ventas locales, terrenos rectangulares, tiro con arco y costos).
* **Fase 2 (50 PTS):** Desbloqueo de la guía de ejercicios complejos (*Trayectoria de Proyectil de Rescate* y *Economía de Transporte Turístico*) para comprobación en libreta.

---

### 🛠️ Tecnologías Utilizadas

| Identificador | Tecnología | Descripción / Uso en el Proyecto |
| :---: | :--- | :--- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | **HTML5** | Estructura semántica para los artefactos interactivos de aprendizaje. |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | **CSS3** | Diseño responsivo utilizando CSS Custom Properties (Variables) y maquetación con Flexbox y CSS Grid. |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) | **JavaScript (Vanilla)** | Lógica de validación en tiempo real, cálculos algebraicos, simulador interactivo y sistema de gamificación con barra de progreso. |
| ![MathJax](https://img.shields.io/badge/MathJax-005A9C?style=for-the-badge&logo=mathjax&logoColor=white) | **MathJax v3** | Motor SVG para la renderización nítida y profesional de fórmulas matemáticas en sintaxis LaTeX. |

### 👤 Créditos y Autoría

* **Catedrático / Desarrollador:** L.I. Luis Arturo López Vergara
* **Institución:** Universidad William Osler (Bachillerato)
* **Ubicación:** Zihuatanejo, Guerrero, México
* **Edición:** 2026
