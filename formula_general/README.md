<!--
Proyecto: Pensamiento Matemático IV — Fórmula General y Discriminante
Institución: Universidad William Osler — Bachillerato, Zihuatanejo, Guerrero
Autor y desarrollador: L.I. Luis Arturo López Vergara
Edición: 2026
Repositorio: https://github.com/luislopezv71-sudo/pensamiento_matematico_IV
Ruta: formula_general/
-->

# 🧮 Pensamiento Matemático IV — Fórmula General y Discriminante

**Universidad William Osler · Bachillerato · Zihuatanejo, Guerrero · 2026**

Módulo de aprendizaje interactivo para comprender, visualizar y resolver **ecuaciones cuadráticas**, interpretar el **discriminante** y aplicar la **fórmula general** en situaciones cercanas a los estudiantes. Integra explicación conceptual, gráficas, simulación, ejercicios autocorregibles, actividades en cuaderno y práctica gamificada.

## 🚀 Acceso a los módulos

| Etapa | Recurso | Propósito | Abrir |
|---|---|---|---|
| 1. Comprender y visualizar | **Lección principal — Fórmula General v1.4** | Antecedentes, aplicaciones modernas, discriminante, parábola, simulador y actividades | [Abrir lección](https://luislopezv71-sudo.github.io/pensamiento_matematico_IV/formula_general/) |
| 2. Practicar y demostrar | **Ejercicios de Repaso 1** | Cinco ejercicios de práctica y reto final con trabajo en cuaderno | [Abrir repaso](https://luislopezv71-sudo.github.io/pensamiento_matematico_IV/formula_general/ejercicios_repaso_1.html) |
| 3. Reforzar y evaluar | **Niveles y Generador Gamificado** | Ejercicios nuevos por dificultad, validación y puntuación | [Abrir generador](https://luislopezv71-sudo.github.io/pensamiento_matematico_IV/formula_general/niveles_y_generador_gamificado.html) |

## 🎯 Objetivos de aprendizaje

Al concluir la secuencia, el estudiante podrá:

1. Reconocer la ecuación cuadrática en la forma **ax² + bx + c = 0**, con **a ≠ 0**, e identificar los coeficientes **a**, **b** y **c**.
2. Aplicar la fórmula general **x = (−b ± √(b² − 4ac)) / (2a)** y comprobar sus soluciones.
3. Calcular e interpretar el discriminante **Δ = b² − 4ac** y relacionarlo con las intersecciones de la parábola con el eje X.
4. Explorar el efecto de los coeficientes en la gráfica, las raíces, el vértice y el eje de simetría.
5. Resolver situaciones contextualizadas y documentar el procedimiento algebraico y gráfico en el cuaderno.
6. Practicar de manera autónoma mediante ejercicios con retroalimentación inmediata.

## 📚 Secuencia didáctica sugerida

### 1. Lección principal: comprender y visualizar

- **Motivación:** aplicaciones modernas de trayectorias en videojuegos y deportes.
- **Conceptos:** ecuación cuadrática, coeficientes y fórmula general.
- **Discriminante:** tres posibilidades y su interpretación gráfica:
  - **Δ > 0:** dos raíces reales distintas.
  - **Δ = 0:** una raíz real doble.
  - **Δ < 0:** no hay raíces reales.
- **Simulador:** modificación de coeficientes y observación de la parábola, raíces, vértice y tabla de valores.
- **Trabajo escrito:** identificación de datos, sustitución, operaciones, comprobación y gráfica.

### 2. Ejercicios de Repaso 1: practicar y demostrar

- **Fase 1 — 50 puntos:** cinco ejercicios contextualizados con validación inmediata.
- **Fase 2 — 50 puntos:** reto de mayor profundidad y comprobación de resultados obtenidos en el cuaderno.
- El alumno debe **conservar las operaciones en su libreta**: la respuesta correcta en pantalla no sustituye la demostración del procedimiento.
- El avance se guarda localmente en el navegador compatible; no equivale a una entrega automática al docente.

### 3. Niveles y Generador Gamificado: reforzar y evaluar

- **Nivel 1:** identificar coeficientes y calcular el discriminante.
- **Nivel 2:** resolver ecuaciones con soluciones enteras y reconocer la respuesta válida en contexto.
- **Nivel 3:** resolver ejercicios con resultados decimales, registrar el discriminante y justificar la solución en cuaderno.
- **Generador:** permite obtener nuevos ejercicios para practicar.
- **Puntuación:** cada ejercicio correcto suma puntos una sola vez; se utiliza un cronómetro informativo sin penalizar por tardar más.
- **Progreso:** el puntaje se conserva en el navegador cuando el almacenamiento local está disponible.

## ✍️ Evidencia académica para el cuaderno

Para cada ejercicio que el docente solicite entregar, registrar:

1. Enunciado y ecuación cuadrática.
2. Identificación de **a**, **b** y **c**.
3. Cálculo del discriminante **Δ** y explicación de su significado.
4. Sustitución en la fórmula general y operaciones completas.
5. Soluciones y comprobación en la ecuación original.
6. Tabla de valores y gráfica de la parábola cuando corresponda.
7. Interpretación del resultado en el contexto del ejercicio.

**Criterio didáctico:** la plataforma apoya la exploración y la retroalimentación; el cuaderno permite valorar el razonamiento y la argumentación matemática.

## 📁 Estructura de la carpeta `formula_general/`

```text
formula_general/
├── index.html                             # Lección principal v1.4
├── ejercicios_repaso_1.html               # Repaso gamificado y reto para cuaderno
├── niveles_y_generador_gamificado.html    # Práctica aleatoria por niveles
└── README.md                              # Documentación de este módulo
```

Esta es la estructura principal de archivos vigente; no incluye carpetas históricas o versiones anteriores que puedan conservarse en el repositorio.

## 🛠️ Tecnologías

- **HTML5 y CSS3:** estructura, diseño adaptable a computadora y dispositivos móviles.
- **JavaScript:** cálculos, validación, gráficas, generación de ejercicios y gamificación.
- **Canvas y SVG:** representación visual de funciones y casos del discriminante en la lección principal.
- **Almacenamiento local (`localStorage`):** persistencia del avance en los módulos que lo implementan. Los datos permanecen en el dispositivo y navegador usados; no se sincronizan entre estudiantes o equipos.

## ▶️ Uso y publicación

1. Abrir los enlaces de la tabla **Acceso a los módulos** o el archivo `index.html` en un navegador moderno.
2. Seguir el orden sugerido: **lección → repaso → generador**.
3. Para publicar cambios, editar los archivos dentro de `formula_general/` en la rama publicada mediante GitHub Pages.
4. Mantener los nombres de los archivos para conservar los enlaces existentes.

**Nota:** el sistema de puntos es una herramienta de práctica y motivación, no una plataforma de calificaciones con cuentas de estudiantes. El docente verifica las evidencias entregadas.

## 👤 Créditos y autoría

- **Catedrático y desarrollador:** L.I. Luis Arturo López Vergara.
- **Institución:** Universidad William Osler, Bachillerato.
- **Ubicación:** Zihuatanejo, Guerrero, México.
- **Edición:** 2026.
- **Repositorio:** [pensamiento_matematico_IV](https://github.com/luislopezv71-sudo/pensamiento_matematico_IV).
