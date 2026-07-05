# AulaTalent ATS

Maqueta funcional educativa de un ATS para clases de reclutamiento, filtro curricular, sesgos, trazabilidad e inteligencia artificial aplicada a seleccion.

## Caso docente incluido

**De 12 postulantes a una terna defendible**

El caso trabaja una vacante de **Asistente de Atencion y Gestion Administrativa** en modalidad presencial en Valparaiso. Incluye 12 candidatos ficticios con distintos niveles de calce, alertas y tensiones pedagogicas:

- score ATS alto con poca evidencia,
- score ATS bajo con potencial,
- requisito excluyente incumplido,
- CV desordenado pero experiencia relevante,
- candidatos para terna final.

## Modulos

- Dashboard.
- Dashboard con checklist operativo de 12 actividades, progreso guardado y alerta al completar hitos.
- Plan de trabajo del proceso.
- Requisiciones y criterios del cargo.
- Creacion de nuevas requisiciones ficticias.
- Modo desde cero para que estudiantes completen requisicion, criterios, postulaciones, entrevistas y comunicaciones sin textos prellenados.
- Proceso de seleccion con Kanban.
- Portal candidato con postulacion ficticia.
- Base de candidatos y ficha individual.
- Matriz de filtro curricular.
- Entrevistas e invitaciones simuladas.
- Scorecards de entrevista.
- Comunicaciones simuladas.
- Reporte ejecutivo basado en candidatos movidos a la etapa Finalista.
- Configuracion, roles, privacidad y trazabilidad.

## Uso

Abrir `index.html` en el navegador o publicar la carpeta en GitHub Pages. No requiere backend ni instalacion.

La app guarda los cambios en `localStorage` e incluye un boton **Reiniciar demo** para volver al caso original.

Al reiniciar, las 12 actividades vuelven a quedar pendientes. Cuando el usuario realiza y guarda una accion clave, la plataforma marca el hito como completado y muestra una alerta de avance.

El boton **Modo desde cero** deja vacios los campos que debe construir el estudiante. Los formularios validan que no se guarden hitos sin datos suficientes, por ejemplo requisicion incompleta, criterios vacios, postulacion sin respuestas o mensaje de descarte sin candidato descartado.

## Enfoque pedagogico

El ATS ordena informacion y apoya decisiones, pero no reemplaza el juicio profesional. El ranking automatico debe compararse con evidencia humana, criterios definidos y trazabilidad de motivos. La terna final se construye moviendo candidatos dentro del pipeline, no desde un boton aislado de reporte.
