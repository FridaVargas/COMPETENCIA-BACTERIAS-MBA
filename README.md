# Competencia bacteriana y simulación de sistemas dinámicos

Este repositorio contiene el proyecto final desarrollado por **Frida Michelle Vargas Bautista** como parte del curso *Proyecto I* de la Facultad de Ciencias de la UNAM, impartido por el **Biol. Luis Guillermo García Jácome**.

El trabajo integra una simulación construida desde cero en **NetLogo**, complementada con un documento escrito que desarrolla la motivación biológica, la justificación del modelo, su estructura técnica y un análisis de los resultados. Además, el proyecto está inspirado en un ejercicio propuesto dentro de un texto de investigación en biología computacional.

---

## 🔎 Descripción general

El modelo simula la **competencia entre tres cepas bacterianas** en un entorno cerrado, a través de una dinámica cíclica tipo *piedra-papel-tijera*. Cada tipo bacteriano domina sobre otro, lo que permite observar fenómenos como alternancia, ciclos de dominancia, y estabilidad ecológica.

El proyecto busca representar procesos de interacción ecológica mediante reglas locales entre agentes, demostrando cómo patrones globales pueden emerger de dinámicas simples.

> *"Si nuestro cuerpo funciona es porque nuestras células se comunican."*  
> Esta idea me acompaña todavía, y cobra vida en estos modelos donde agentes simples, al interactuar, dan lugar a algo mucho más grande y complejo.

---

## 📂 Archivos incluidos

- `modelo_final.nlogo` — Modelo completo implementado en NetLogo.
- `Trabajo_Frida_Vargas.pdf` — Documento escrito con introducción, modelo, análisis y resultados.
- `Trabajo_Frida_Vargas_con_anotaciones.pdf` — Versión del trabajo con anotaciones realizadas durante la retroalimentación académica.

> Se incluye la versión anotada como parte del proceso formativo, conservando la evidencia de revisión y mejora del trabajo.

---

## 💡 Características del modelo

- Espacio toroidal (mundo sin bordes).
- Tres tipos de bacterias representadas por colores: rojo, azul y amarillo.
- Dominancia cíclica:
  - Rojo vence a azul.
  - Azul vence a amarillo.
  - Amarillo vence a rojo.
- Competencia por invasión de espacio según reglas locales.
- Variabilidad estocástica: el modelo puede producir dinámicas cíclicas, equilibrio o dominancia.

---

## 📘 Inspiración bibliográfica

Este trabajo fue inspirado por un ejercicio sugerido en el siguiente texto:

**MacKinnon, R. J., Cline, E. R., Hillen, T., & Louis, P. Y.** (2019).  
_An Introduction to Undergraduate Research in Computational and Mathematical Biology._ Springer.

> 📚 Capítulo 5: *Simulating Bacterial Growth, Competition, and Resistance with Agent-Based Models and Laboratory Experiments* (pp. 217–243)

---

## 🎓 Contexto académico

- **Curso:** Proyecto I  
- **Profesor:** Biol. Luis Guillermo García Jácome  
- **Facultad:** Ciencias, UNAM  
- **Semestre:** 2025-I

---

## ✨ Nota personal

Este proyecto fue realizado de forma completamente individual como entrega final del curso. La simulación y el trabajo escrito reflejan el proceso de exploración, integración interdisciplinaria y aplicación de herramientas computacionales al modelado biológico. Fue evaluado y mejorado con base en observaciones académicas, lo que fortaleció aún más su desarrollo.

