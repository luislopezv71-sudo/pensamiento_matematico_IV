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
