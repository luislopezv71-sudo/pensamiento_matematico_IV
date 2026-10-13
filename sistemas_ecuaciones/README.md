# Pensamiento Matemático IV — Sistemas de ecuaciones lineales 2×2

**Universidad William Osler · Bachillerato · Zihuatanejo, Guerrero · 2026**  
**Catedrático y desarrollador:** L.I. Luis Arturo López Vergara

## Propósito
Comprender, representar gráficamente, resolver y comprobar sistemas de dos ecuaciones lineales con dos incógnitas. Se sigue la ruta **comprender → visualizar → practicar → demostrar → evaluar**.

## Recursos
1. [`index.html`](index.html): teoría, clasificación, métodos de sustitución, igualación, eliminación y método gráfico; laboratorio interactivo de dos rectas, determinante y comprobaciones.
2. [`ejercicios_repaso_1.html`](ejercicios_repaso_1.html): cinco problemas contextualizados (50 puntos) y desafío final desbloqueable (50 puntos). Requiere cuaderno.
3. [`niveles_y_generador_gamificado.html`](niveles_y_generador_gamificado.html): tres niveles de generación aleatoria, cronómetro, comprobación y puntuación acumulada.

## Secuencia sugerida de 4 sesiones de 50 minutos
| Sesión | Contenido | Evidencia |
|---|---|---|
| 1 | Concepto, variables, gráficas, solución única, sin solución e infinitas | Interpretar intersecciones |
| 2 | Sustitución e igualación | Desarrollar soluciones en cuaderno |
| 3 | Eliminación, comprobación y clasificación | Justificar resultados |
| 4 | Modelación contextual y retos gamificados | Resolución completa y explicación |

## Uso
1. Abrir `index.html` desde la carpeta `sistemas_ecuaciones/`.
2. Seguir la navegación superior. Los archivos conservan nombres equivalentes a los del módulo Fórmula General.
3. En GitHub Pages, el acceso será `https://luislopezv71-sudo.github.io/pensamiento_matematico_IV/sistemas_ecuaciones/` **después de publicar la carpeta**.
4. Para enlazarlo desde el inicio principal, agregar un vínculo al directorio `/sistemas_ecuaciones/` cuando se integre el portal.

## Notas de implementación
- HTML5, CSS3, JavaScript y Canvas. Sin dependencias externas.
- `localStorage` utiliza claves independientes: `pmiv-sistemas-repaso-v1` y `pmiv-sistemas-generador-v1`.
- Los puntos son apoyo formativo, no registro de calificación institucional.
- En los ejercicios escritos se exige: definir variables, plantear ecuaciones, mostrar operaciones, comprobar e interpretar.
- El gráfico usa escala fija; algunas intersecciones pueden quedar fuera de la ventana visible aunque se calculen correctamente.
- No se modifica el contenido publicado de `formula_general/`.


## Ampliación v1.2: Taller de métodos

La lección principal incorpora un taller de resolución interactiva sobre los seis coeficientes del laboratorio, con procedimientos para sustitución, igualación y eliminación, y un ejercicio de decisión de método con cinco casos rotativos.

- Las soluciones únicas se comprueban en ambas ecuaciones.
- Los sistemas sin solución única se clasifican, sin inventar un par de valores.
- Cuando no resulta práctico igualar directamente la misma incógnita, se explica por qué sustitución es más conveniente.
- El repaso y el generador conservan la lógica y las claves de almacenamiento de v1.0, para preservar el progreso local.
- Las expresiones en pantalla pueden estar redondeadas a cuatro decimales: el cuaderno debe registrar las operaciones exactas.

**Publicación:** subir los cuatro archivos a la carpeta `sistemas_ecuaciones/` del repositorio, sin alterar `formula_general/`.


## Versión 1.2 — Resolución activa paso a paso

En la lección principal se agregó el **laboratorio guiado** con tres métodos: sustitución, igualación y eliminación. El estudiante debe introducir cada resultado de despeje, reducción, solución y comprobación antes de pasar al siguiente paso. Las actividades emplean los coeficientes del laboratorio gráfico y se reinician al cambiarlos mediante los controles. Incluye pistas y tolerancia de 0.01 en resultados numéricos. Para sistemas sin solución única se solicita seleccionar un sistema secante para la práctica guiada; la clasificación de los demás sistemas permanece disponible en el simulador. No se modifica la puntuación del repaso ni del generador.
