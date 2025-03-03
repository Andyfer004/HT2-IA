# Proceso de Decisión de Markov (MDP) - Análisis y Simulación

## Introducción

Este proyecto tiene como objetivo analizar y simular **Procesos de Decisión de Markov (MDP)**, un modelo matemático clave para la toma de decisiones en entornos inciertos. A través de un enfoque teórico y práctico, se abordan conceptos fundamentales, críticas a los supuestos subyacentes y estrategias para mejorar la robustez de las decisiones.

El proyecto está dividido en dos grandes secciones:

- **Task 1 - Preguntas Teóricas:** Se desarrollan definiciones, explicaciones y comparaciones entre técnicas utilizadas en MDP.
- **Task 2 - Preguntas Analíticas y Simulación:** Se realiza un análisis crítico de los supuestos de Markov, se exploran los desafíos de modelar incertidumbre y se propone un enfoque robusto basado en un entorno de tipo **Frozen Lake** simulado en Python.

---

## Contenido

### Task 1 - Preguntas Teóricas
En esta sección se explican:
- Definición y componentes de un MDP.
- Diferencias entre políticas, evaluación de políticas, mejora de políticas e iteración de políticas.
- Importancia del factor de descuento (gamma) y cómo afecta la toma de decisiones.
- Comparación entre iteración de valores e iteración de políticas.
- Principales desafíos al resolver MDP a gran escala y estrategias para mitigarlos.

---

### Task 2 - Preguntas Analíticas y Simulación
En esta parte se aborda:
- Análisis crítico de los supuestos subyacentes a la propiedad de Markov.
- Escenarios donde estos supuestos pueden fallar y las consecuencias sobre la toma de decisiones.
- Estrategias para una toma de decisiones robusta en entornos inciertos.
- Ejemplo práctico: Implementación de un entorno tipo **Frozen Lake** con un algoritmo de **Value Iteration** para encontrar la política óptima.

---

## Resultados
- Se analizó críticamente la validez de los supuestos de Markov en entornos reales.
- Se identificaron estrategias como **POMDP**, simulación de escenarios y aprendizaje por refuerzo para mejorar la toma de decisiones.
- Se creó un entorno simulado 4x4 donde un agente aprende a navegar desde un punto inicial (Start) hasta un objetivo (Goal) evitando obstáculos (Holes).
- Los resultados muestran las políticas óptimas para diferentes configuraciones aleatorias del entorno, mostrando trayectorias óptimas aprendidas.

Ejemplos de resultados gráficos generados:

✅ Grillas simuladas con diferentes configuraciones.  
✅ Políticas óptimas calculadas por iteración de valores.  
✅ Trayectorias óptimas graficadas.

---

## Requisitos

Para ejecutar el notebook necesitas:

- Python 3.8+
- Librerías:
    - numpy
    - matplotlib

Puedes instalar las dependencias usando:

```bash
pip install numpy matplotlib
