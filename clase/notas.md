# 🗒️ Registro de Trabajo en Clase - Taller 6

## 📆 Fecha de la sesión
12 de septiembre de 2026

## 👥 Integrantes presentes
- Jorge Alarcon
- Julian Aguirre
- Brayan Presiga

## 🧠 Actividades realizadas en clase

- Se analizó cada uno de los pasos en el desarrollo del ejemplo guiado buscando puntos con los cuales tuviéramos dudas para buscar asesoramiento con el profesor. No se encontró ninguno.
- Se realizó la planificación del desarrollo del taller y la visita con el cliente.
- Se decidió utilizar excel para realizar la entrega del trabajo dentro del repositorio y adicionalmente crear un html con base a ese excel con alguna herramienta de inteligencia artificial para mejorar su visualización durante la sustentación del corte.

## 🧩 Boceto inicial del modelo

Las siguientes tablas corresponden al ejemplo guiado de la primera parte de la actividad. Estas fueron las tables las cuales se analizaron durante la clase.

### Checklist general

| **N°** | **Categoría**             | **Criterio de Cumplimiento**                                 | **Nivel de Cumplimiento** | **Evidencia / Justificación**                                | **Recomendación**                                      |
| ------ | ------------------------- | ------------------------------------------------------------ | ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| 1      | Consentimiento            | Se solicita consentimiento informado al ciudadano antes del tratamiento de datos. | ✅ Cumple                  | Casilla de aceptación de términos en el registro de usuario. | Detallar fines específicos del tratamiento.            |
| 2      | Consentimiento            | Mecanismo para revocar el consentimiento disponible.         | ⚠️ Parcial                 | Solo mediante solicitud escrita.                             | Implementar botón o formulario en línea.               |
| 3      | Seguridad (ISO 27001)     | Existe política formal de seguridad.                         | ✅ Cumple                  | Política de TI estatal basada en ISO/IEC 27001:2013.         | Mantenerla actualizada conforme a versión 2022.        |
| 4      | Seguridad (ISO 27001)     | Cifrado de datos en tránsito y reposo.                       | ✅ Cumple                  | HTTPS/TLS y cifrado de campos sensibles.                     | Revisar certificados y algoritmos anualmente.          |
| 5      | Seguridad (ISO 27001)     | Plan de continuidad y recuperación.                          | ⚠️ Parcial                 | Respaldos diarios sin plan BCP/DRP formal.                   | Diseñar e implementar plan de continuidad documentado. |
| 6      | Protección de Datos       | Se cuenta con un Oficial de Protección de Datos (DPO).       | ✅ Cumple                  | Funcionario asignado conforme a Ley 1581.                    | Reforzar su rol en auditorías y reportes.              |
| 7      | Protección de Datos       | Logs de acceso a información personal.                       | ✅ Cumple                  | Sistema registra y audita consultas.                         | Revisar integridad y retención de logs.                |
| 8      | Prevención de Fugas       | Se controlan exportaciones manuales.                         | ⚠️ Parcial                 | No hay controles DLP.                                        | Implementar políticas y herramientas DLP.              |
| 9      | Retención                 | Política formal de retención de datos.                       | ✅ Cumple                  | Cumple con Ley General de Archivos.                          | Automatizar procesos de eliminación.                   |
| 10     | Retención                 | Datos sensibles se anonimizarán cuando dejen de ser necesarios. | ⚠️ Parcial                 | No hay proceso implementado.                                 | Desarrollar política de anonimización.                 |
| 11     | Roles y Responsabilidades | Roles y permisos documentados.                               | ✅ Cumple                  | Manual de seguridad define roles (dueño, custodio, usuario). | Actualizar trimestralmente.                            |
| 12     | Roles y Responsabilidades | Formación del personal en protección de datos.               | ⚠️ Parcial                 | Capacitación anual sin evaluación.                           | Medir efectividad y reforzar entrenamiento.            |

### Brechas identificadas

| **Categoría**       | **Brecha**                                     | **Riesgo** | **Recomendación Prioritaria**                             | **Nivel de Prioridad** |
| ------------------- | ---------------------------------------------- | ---------- | --------------------------------------------------------- | ---------------------- |
| Consentimiento      | No existe mecanismo automático de revocatoria. | Medio      | Crear funcionalidad de eliminación y revocatoria digital. | Alta                   |
| Seguridad           | No hay plan formal de continuidad (BCP/DRP).   | Alto       | Diseñar, probar e implementar plan de continuidad.        | Alta                   |
| Prevención de Fugas | Exportación manual no controlada.              | Alto       | Implementar DLP para controlar descargas y exportaciones. | Alta                   |
| Retención           | No existe eliminación automatizada.            | Medio      | Configurar reglas de caducidad en base de datos.          | Media                  |
| Formación           | Sin evaluación de efectividad.                 | Bajo       | Aplicar pruebas posteriores a capacitación.               | Media                  |

## 🔁 Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Identificación y evaluación de los datos y procesos sensibles del sistema en 'Parcial' o 'Cumple'. Redacción del informe. | Brayan Presiga | 18/09 |
| Listado y recomendación de las brechas identificadas. Redacción del informe | Jorge Alarcon | 18/09 |
| Revisión de la checklist y brechas identificadas. Investigación y referencias | Julian Aguirre | 20/09 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller 6 en el curso AREM - Universidad de La Sabana._
