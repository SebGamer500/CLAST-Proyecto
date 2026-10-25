# Especificación de Requisitos de Software - Proyecto CLAST
**Versión:** 1.1 (Modificado por CC-01)
**Estado:** Aprobado

## Requisitos Funcionales
* **RF-01:** El sistema debe validar el inicio de sesión de docentes y alumnos de manera 100% offline contra la base de datos local SQLite.
* **RF-02:** El sistema debe proveer una interfaz de calendario donde el docente pueda estructurar su horario y programar actividades interactivas.
* **RF-03:** El sistema debe permitir al dispositivo del docente generar una red de área local (Hotspot/WLAN) sin necesidad de internet.
* **RF-04:** El sistema debe matricular temporalmente a los alumnos en la sesión activa al detectar su conexión a la red local.
* **RF-05:** El sistema debe permitir al docente lanzar cuestionarios en vivo sincronizados en las tabletas de los alumnos conectados a la red local.
* **RF-06:** El sistema debe permitir al docente capturar imágenes de tareas físicas mediante la cámara y extraer el texto con OCR (Google ML Kit) para sugerir una calificación.
* **RF-07:** El sistema debe contar con un panel de monitoreo que indique en tiempo real el estado de conexión de cada estudiante dentro de la red local.
* * **RF-08:** El sistema debe evaluar automáticamente las actividades en vivo finalizadas mediante IA local (Gemma 2B) y distribuir las calificaciones a los alumnos.
* **RF-09:** El sistema debe mostrar en el panel del docente un ranking en vivo resaltando a los alumnos más destacados de la actividad concluida.
* **RF-10:** El sistema debe incluir un módulo de auditoría (Human-in-the-Loop) para que el docente pueda revisar y sobrescribir manualmente cualquier calificación sugerida por la IA.
