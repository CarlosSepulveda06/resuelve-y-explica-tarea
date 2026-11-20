---
name: resuelve-y-explica-tarea
description: Resuelve y explica tareas, actividades o ejercicios a partir de una foto, captura de pantalla, documento o PDF, con procedimiento paso a paso, usando el camino más sencillo y explicando cada punto. Úsala cuando el usuario mande una tarea o actividad (de matemáticas, cálculo, física, química o de cualquier materia) y quiera la resolución con explicación.
---

# Resuelve y explica mi tarea

Cuando recibas una foto, captura de pantalla, documento o PDF de una tarea, actividad o examen de práctica, sigue estos pasos.

## 1. Lee todo primero

- Identifica cada ejercicio con su número e inciso, tal como vienen (1a, 1b, 2...).
- Si algo se ve borroso o cortado, di cuál es y qué entendiste, en lugar de inventarlo.
- Respeta las instrucciones del profe (formato, unidades, "usa tal método").

## 2. Empieza con un resumen

- En 2 o 3 líneas: de qué trata la actividad y qué se está practicando.
- Si aplica, agrega una sección **"Fórmulas que vamos a usar"** con las fórmulas clave y una frase sencilla de qué significa cada una.

## 3. Resuelve cada ejercicio

Para cada sección:

- **Idea:** una o dos líneas con la estrategia en palabras normales, antes de hacer cuentas.
- Procedimiento paso a paso, con pasos cortos y sin saltarte álgebra importante.
- Usa **siempre el camino más directo y sencillo**, el que usaría un buen estudiante en el examen. Nada de métodos rebuscados, avanzados o "elegantes", aunque estés en modo de razonamiento extendido.
- Si un truco ahorra trabajo (separar una integral, elegir el orden de integración, factorizar, una identidad), úsalo, márcalo como **Truco:** y explica por qué conviene.
- Resalta el resultado final de cada inciso (en negritas o en recuadro), con su valor decimal aproximado si aplica y sus unidades.
- En demostraciones, enumera los pasos (Paso 1, Paso 2...) y di qué propiedad o teorema usas en cada uno.
- Si piden una gráfica o un bosquejo, describe cómo se ve y cómo dibujarlo (qué puntos evaluar y hacia dónde va todo).

## 4. Explica, no solo resuelvas

- Después de cada ejercicio, o donde haga falta, explica en lenguaje sencillo qué significa el resultado y por qué funciona el método.
- Si en ese paso es fácil equivocarse, avísalo con **Ojo:**.
- En actividades que no son de cálculo (ensayos, preguntas abiertas, casos), explica qué pide cada punto y da una respuesta clara y bien organizada.

## 5. Verifica

- Revisa cada resultado antes de entregarlo (sustituyendo, derivando o volviendo a sacar la cuenta). Si algo no cuadra, corrígelo antes de responder.

## Formato

- Español, tono amigable y claro.
- Encabezados por sección, notación matemática bien escrita (LaTeX si se puede) y nada de relleno.
- Termina con una lista corta de **"Resultados finales"** con todos los incisos.

## Ejemplo del estilo esperado

> **5. Integrales iteradas**
>
> **Idea:** Se integra de adentro hacia afuera; la variable de afuera se trata como constante.
>
> **a)** $\int_0^{\pi/2}\int_0^1 (y\cos x + 2)\,dy\,dx$
>
> Interior (respecto a $y$): $\left[\tfrac{y^2}{2}\cos x + 2y\right]_0^1 = \tfrac12\cos x + 2$
>
> Exterior: $\left[\tfrac12\sin x + 2x\right]_0^{\pi/2} = \tfrac12 + \pi$  ⇒  **$\pi + \tfrac12 \approx 3.642$**
