# 🛠️ Taller 7: Opportunities & Solutions

## 🎯 Objetivo

Proponer la arquitectura objetivo (TO-BE) de Aplicaciones y de Tecnología del cliente real, identificando las brechas frente al estado actual (AS-IS) documentado en los Talleres 1 a 6 — incluyendo seguridad y cumplimiento normativo — y priorizando las soluciones que las cierran.

---

## 📘 Guía paso a paso

Antes de proponer el TO-BE, revise la [**Guía Paso a Paso: Opportunities & Solutions**](clase/guia_paso_a_paso_opportunities_solutions.md). Incluye qué cuenta como una brecha válida en este taller, la metodología de 5 pasos (de brechas consolidadas a soluciones priorizadas), un ejemplo completo construido paso a paso sobre el AS-IS de RedExpress ya trabajado en los Talleres 3 y 4, y una tabla de errores comunes.

## 🚚 Caso base de referencia: RedExpress (continuación de los Talleres 3 y 4)

Este taller no introduce un cliente ficticio nuevo: retoma el C1/C2 de RedExpress (Taller 3) y su mapa de infraestructura con los 3 riesgos ya diagnosticados (Taller 4) para proponer, sobre esa misma base, una arquitectura objetivo.

**Por qué este taller va después de Seguridad y Normatividad:**
- Proponer un TO-BE antes de conocer las amenazas de seguridad (Taller 5) o las brechas de cumplimiento (Taller 6) significa diseñar una solución que puede quedar insegura o incumplir la normativa desde el primer día.
- Aquí se consolidan brechas técnicas, funcionales, de seguridad y normativas en una sola matriz — no solo las de infraestructura.

---

## 🧪 Parte 1: Trabajo en Clase

Durante la clase se espera que el equipo:

Siga la metodología de 5 pasos de la [guía paso a paso](clase/guia_paso_a_paso_opportunities_solutions.md) sobre el AS-IS de RedExpress:

1. Consolide los hallazgos del AS-IS (Talleres 3 y 4, y en su cliente real también 5 y 6).
2. Defina el TO-BE de Aplicaciones extendiendo el C2 del Taller 3.
3. Defina el TO-BE de Tecnología extendiendo el mapa del Taller 4.
4. Construya la matriz de brechas (Gap Analysis): AS-IS vs TO-BE y beneficio esperado.
5. Priorice las soluciones por esfuerzo e impacto, y valide con la [checklist de autoevaluación](clase/guia_paso_a_paso_opportunities_solutions.md#5-checklist-de-autoevaluación-antes-de-entregar).

- Use draw.io o Astah UML para los diagramas TO-BE.
- Reciba retroalimentación del docente y registre avances en `clase/notas.md` (use la [plantilla de notas](plantillas/plantilla_notas.md)).

---

## 🧠 Parte 2: Aplicación al Cliente Real

Después de la clase, el equipo debe:

- Consolidar las brechas técnicas (Talleres 3 y 4), de seguridad (Taller 5) y de cumplimiento (Taller 6) identificadas para su cliente real.
- Proponer el TO-BE de Aplicaciones y de Tecnología del cliente, extendiendo sus propios entregables de los Talleres 3 y 4.
- Construir la matriz de brechas priorizada en `entrega/matriz-brechas.xlsx`.
- Redactar el informe en `entrega/informe.md` usando la [plantilla de informe del taller](plantillas/plantilla_informe_taller.md); explicar cada decisión de diseño del TO-BE y su trazabilidad a una brecha concreta.
- Investigar patrones de solución reales para brechas similares en el sector del cliente, y registrar las fuentes en `entrega/referencias.md` con la [plantilla de referencias](plantillas/plantilla_referencias.md).

---

## 📁 Estructura esperada del repositorio

```text
taller-07-opportunities-solutions/
├── README.md
├── clase/
│   ├── guia_paso_a_paso_opportunities_solutions.md   # Qué es una brecha, metodología de 5 pasos y ejemplo guiado
│   ├── to-be-borrador.drawio
│   └── notas.md                                      # Ver plantillas/plantilla_notas.md
├── entrega/
│   ├── to-be-aplicaciones-final.drawio
│   ├── to-be-tecnologia-final.drawio
│   ├── matriz-brechas.xlsx
│   ├── informe.md                                    # Ver plantillas/plantilla_informe_taller.md
│   └── referencias.md                                # Ver plantillas/plantilla_referencias.md
└── plantillas/
    ├── plantilla_informe_taller.md
    ├── plantilla_notas.md
    └── plantilla_referencias.md
```

---

## ⚠️ Errores comunes

Antes de entregar, compare su TO-BE y su matriz contra los errores más frecuentes (TO-BE sin brechas concretas de origen, brechas de seguridad/normatividad ignoradas, priorización solo por impacto) documentados en la [sección 4 de la guía paso a paso](clase/guia_paso_a_paso_opportunities_solutions.md#4-errores-comunes-a-evitar).

## 📤 Entregables

- Modelo TO-BE de Aplicaciones (extensión del C2 del Taller 3)
- Modelo TO-BE de Tecnología (extensión del mapa del Taller 4)
- Matriz de brechas (Gap Analysis) priorizada
- Informe técnico (`informe.md`)
- Referencias e investigación complementaria

---

## 📊 Rúbrica de Evaluación

| Criterio                              | Excelente (5)                                                              | Aceptable (3) / Insuficiente (1–2)                         |
|----------------------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------|
| Consolidación de brechas               | Reúne brechas técnicas, de seguridad y normativas de talleres previos, bien trazadas | Brechas incompletas o inventadas sin base en talleres previos |
| TO-BE de Aplicaciones y Tecnología     | Extiende coherentemente el C2 y el mapa de infraestructura ya construidos     | TO-BE desconectado del AS-IS o genérico                        |
| Matriz de brechas y priorización       | Gap analysis claro, con beneficio esperado y prioridad justificada           | Priorización arbitraria o sin justificación                    |
| Investigación complementaria           | Referencias a patrones de solución reales del sector del cliente             | Sin fuentes o poco relevantes                                  |

---

## ✅ Licencia

Este taller hace parte del curso de Arquitectura Empresarial - Universidad de La Sabana. Uso académico bajo licencia MIT.
