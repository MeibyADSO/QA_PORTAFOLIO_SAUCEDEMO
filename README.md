Portafolio de Testing Manual QA - E-commerce (SauceDemo)

¡Hola! Soy Tecnóloga en Análisis y Desarrollo de Software (ADSO - SENA)** certificada en QA Software Testing.

Este repositorio contiene la planificación, ejecución y documentación de pruebas de calidad manuales realizadas sobre la plataforma e-commerce [SauceDemo](https://www.saucedemo.com/).

---

Contenido del Repositorio
Portafolio_QA_Saucedemo.xlsx`: Matriz completa de Casos de Prueba y Reporte de Defectos.

---

Alcance del Proyecto
* **Módulos Probados:** Autenticación (Login) y Gestión del Carrito de Compras.
* **Tipos de Pruebas:** Pruebas Funcionales, Smoke Testing, UI/UX, Regresión.

---

Resumen de Resultados

1. Casos de Prueba Destacados (Test Cases)
| ID | Módulo | Título | Estado |
|---|---|---|---|
| **CP001** | Autenticación | Validar inicio de sesión con datos incorrectos | `PASSED` |
| **CP002** | Carrito | Agregar un producto al carrito de compras | `PASSED` |
| **CP003** | Carrito | Agregar 2 o más productos de la misma referencia | `FAILED` |

2. Reporte de Defectos (Bug Report)
* **ID Bug:** `B001` (Asociado a `CP003`)
* **Título:** Imposibilidad de seleccionar/agregar más de un producto de la misma referencia al carrito.
* **Severidad:** Media | **Prioridad:** Alta.
* **Resultado Obtenido:** El sistema no permite modificar la cantidad ni agregar más de 1 unidad por ítem.

---

Herramientas Utilizadas
* **Plataforma de Pruebas:** SauceDemo
* **Documentación:** Microsoft Excel / Google Sheets
* **Control de Versiones:** Git & GitHub
* **Metodología:** Scrum / Agile
