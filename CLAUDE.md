# gfa-alertas-regulatorias

Repositorio de informes semanales de monitoreo regulatorio (fiscal y societario,
normativa argentina) para el estudio GFA. Los informes son generados
automáticamente por una tarea programada.

## Formato de entrega de cada informe semanal

Para cada ejecución del informe de alerta regulatoria, generar SIEMPRE dos
archivos en la raíz del repositorio, con el mismo nombre base `YYYY-MM-DD-alerta`:

1. `YYYY-MM-DD-alerta.md` — el informe en Markdown (formato ya definido en el
   prompt de la tarea programada).
2. `YYYY-MM-DD-alerta.pdf` — el mismo informe en PDF, con diseño legible
   (encabezado con fecha, secciones de alta/media relevancia y "sin novedades"
   diferenciadas visualmente). Generar con reportlab (ver skill `pdf`).

Ambos archivos deben commitearse y pushearse a la rama de trabajo junto con el
resto de los cambios de esa ejecución.
