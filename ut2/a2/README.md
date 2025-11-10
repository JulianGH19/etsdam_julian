# 🧩 Práctica A2 – Comparación de Modelos de Desarrollo de Software

## 📌 Parte 1: Análisis Comparativo de Modelos de Desarrollo

| Característica / Aspecto       | Modelos Clásicos (Predictivos)                                                                 | Modelos Evolutivos o Incrementales                                                                 | Metodologías Ágiles (Adaptativas)                                                                 |
|--------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **Definición Principal**       | Modelo secuencial donde cada fase se completa antes de iniciar la siguiente.                    | Modelo que desarrolla el software en versiones sucesivas, mejorando progresivamente.               | Modelo iterativo y flexible que se adapta continuamente a los cambios y necesidades del cliente. |
| **Características Clave**     | Planificación detallada, documentación extensa, bajo nivel de flexibilidad.                     | Entregas parciales funcionales, retroalimentación frecuente, mejora continua.                      | Iteraciones cortas (sprints), colaboración constante, enfoque en el valor entregado.              |
| **Ventajas (Pros)**            | Claridad en objetivos, control riguroso del proceso, útil en proyectos estables.                 | Permite validar funcionalidades, mejora la calidad progresiva, reduce riesgos.                     | Alta adaptabilidad, satisfacción del cliente, detección temprana de errores.                      |
| **Desventajas (Contras)**     | Difícil adaptación a cambios, alto coste de corrección, riesgo de obsolescencia.                 | Puede generar acumulación de deuda técnica, requiere buena gestión de versiones.                   | Requiere alta implicación del cliente, difícil de escalar sin disciplina.                         |
| **Aportación en la Actualidad**| Útil en proyectos críticos con requisitos estables (aeroespacial, banca).                       | Muy usado en desarrollo de productos con evolución continua (software comercial).                  | Dominante en startups y empresas tecnológicas por su agilidad y enfoque en el usuario.            |

> Fuente: Material del curso “Desarrollo de Software”, Unidad 3 – Modelos de Ciclo de Vida.

---

## 🛠️ Parte 2: Reflexión sobre la Detección y Corrección de Fallos y Cambios

### 🔄 Corrección de Cambios y Fallos según el Modelo

- **Modelo en Cascada con Realimentación**  
  Aunque originalmente secuencial, la versión con realimentación permite retroceder a fases anteriores si se detectan errores. Sin embargo, este proceso es costoso y complejo, ya que implica revisar documentación y replanificar fases completas.

- **Modelos Evolutivos o Incrementales**  
  Facilitan la corrección mediante versiones sucesivas. Cada incremento permite validar funcionalidades con el usuario, lo que posibilita ajustes rápidos y mejora continua. La retroalimentación es parte integral del ciclo.

- **Metodologías Ágiles**  
  La corrección y adaptación son parte del ADN del modelo. Las iteraciones cortas (sprints) permiten revisar y ajustar el producto constantemente. Prácticas como la programación extrema (XP) promueven mejoras continuas y refactorización constante.

### 🧩 Fase de Mantenimiento

La fase de mantenimiento es esencial en todos los modelos, pero cobra especial relevancia en el ciclo de vida completo del software:

- **Mantenimiento Correctivo**  
  Se encarga de resolver errores detectados tras la entrega del producto. Es fundamental para garantizar la estabilidad del sistema.

- **Mantenimiento Evolutivo y Adaptativo**  
  Permite modificar el software para adaptarse a nuevas necesidades, tecnologías o entornos. En modelos ágiles, esta fase se diluye en el proceso iterativo; en modelos clásicos, se gestiona como una fase posterior.


