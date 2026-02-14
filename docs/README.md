# OctoAcme — Documentación sobre Gestión de Proyectos

## Propósito

Este repositorio centraliza la documentación de gestión de proyectos de OctoAcme, proporcionando un marco estructurado para planificar, ejecutar y entregar proyectos de software con excelencia. La documentación está diseñada para ser una referencia práctica para todos los miembros del equipo, desde desarrolladores hasta gerentes de proyecto, asegurando consistencia, claridad y alineación en todos los proyectos de la organización.

## Alcance

La documentación cubre todo el ciclo de vida del proyecto, desde la validación inicial de ideas hasta el cierre y retrospectiva, incluyendo prácticas de comunicación, gestión de riesgos, aseguramiento de calidad y mejora continua. Este conjunto de documentos refleja los procesos reales utilizados en OctoAcme y se actualiza periódicamente para reflejar aprendizajes y mejoras.

---

## Resumen de Procesos de Gestión

### Ciclo de Vida del Proyecto y Flujos de Trabajo

OctoAcme implementa un ciclo de vida estructurado en cinco fases principales: iniciación, planificación, ejecución, lanzamiento y cierre con retrospectiva. En iniciación, se valida la necesidad empresarial mediante un documento de una página. Durante planificación, el trabajo se desglosa en incrementos entregables. En ejecución, se utiliza un tablero de proyecto con columnas estandarizadas y se mantiene un ritmo con reuniones diarias, sincronizaciones semanales y revisiones de sprint. El lanzamiento incluye verificaciones pre-despliegue rigurosas, y el cierre incorpora retrospectivas para capturar aprendizajes.

### Roles y Responsabilidades

La estructura de OctoAcme se sustenta en roles claramente definidos: Project Managers coordinan actividades y riesgos, Product Managers definen qué construir, Developers implementan características, QA/Testing valida calidad, y Stakeholders proporcionan entradas. Además, se han definido roles especializados adicionales para garantizar la excelencia en áreas clave: UX/UI Designer para experiencias de usuario, DevOps/Release Engineer para automatización y confiabilidad, Documentation Specialist para captura de conocimiento, Support/Customer Success para éxito del cliente, y Security Lead para seguridad y cumplimiento. Esta claridad de roles reduce ambigüedad y mejora la responsabilidad en todas las dimensiones del proyecto.

### Estrategias de Comunicación y Gestión de Riesgos

La comunicación se estructura mediante: reuniones semanales PM+PdM, standups dos veces por semana, actualizaciones mensuales de stakeholders, y escalaciones ad-hoc. La gestión de riesgos se mantiene mediante un Registro de Riesgos con ID, descripción, impacto, probabilidad, propietario, plan de mitigación y estado, revisado semanalmente.

### Control de Calidad y Mejora Continua

La garantía de calidad es multi-capa: pruebas unitarias, pruebas de integración, pruebas de humo, escaneo de seguridad y QA manual. OctoAcme cierra cada proyecto con retrospectivas estructuradas que generan elementos de acción con propietarios y fechas, creando una cultura de mejora continua.

---

## Documentos de Referencia

| Documento | Descripción |
|-----------|-------------|
| [Visión General de Gestión de Proyectos](./octoacme-project-management-overview.md) | Guía fundacional que define el enfoque, principios, roles centrales (PM, PdM, Developers, QA), artefactos clave y el ciclo de vida de cinco fases de OctoAcme. |
| [Guía de Inicio de Proyectos](./octoacme-project-initiation.md) | Describe cómo validar nuevas ideas de proyectos mediante un documento de una página, identificar stakeholders, definir métricas de éxito y realizar la decisión go/no-go antes de la planificación. |
| [Guía de Planificación](./octoacme-project-planning.md) | Detalla la conversión de iniciativas aprobadas en backlogs accionables y planes de lanzamiento, incluyendo kickoff, priorización, estimación, Definition of Done e identificación de dependencias y riesgos. |
| [Ejecución y Seguimiento](./octoacme-execution-and-tracking.md) | Cubre la ejecución diaria con ritmos de equipo (standups, sincronizaciones, demos), flujos de trabajo del tablero de proyecto, guías de PR, estrategias de calidad y pruebas, y procedimientos de escalación de bloqueos. |
| [Gestión de Riesgos y Comunicación](./octoacme-risks-and-communication.md) | Explica cómo mantener un registro de riesgos, gestionar el ciclo de vida del riesgo y comunicar el estado a stakeholders usando plantillas para actualizaciones semanales y respuestas a incidentes. |
| [Guía de Lanzamiento y Despliegue](./octoacme-release-and-deployment.md) | Estandariza la gestión de lanzamientos con requisitos pre-lanzamiento, listas de verificación de despliegue, tipos de lanzamiento (Patch/Minor/Major) y playbooks de rollback/incidentes. |
| [Retrospectiva y Mejora Continua](./octoacme-retrospective-and-continuous-improvement.md) | Guía para ejecutar retrospectivas después de sprints/lanzamientos para capturar aprendizajes, convertir feedback en elementos de acción rastreados y fomentar una cultura de mejora continua. |
| [Roles y Personas](./octoacme-roles-and-personas.md) | Define personas clave (Developers, Product Managers, Project Managers, UX/UI Designer, DevOps/Release Engineer, Documentation Specialist, Support/Customer Success, Security Lead) con sus responsabilidades, objetivos, patrones de comunicación e interacciones. Incluye listas de verificación de onboarding específicas por rol. |
| [Plantilla de Lista de Verificación de Onboarding](./onboarding-checklist-template.md) | Plantilla genérica y personalizable para incorporar nuevos miembros del equipo a proyectos de OctoAcme, con actividades estructuradas por semana y verificaciones periódicas a 30, 60 y 90 días. |

---

## Guía de Uso

### Para Nuevos Miembros del Equipo

Si eres nuevo en OctoAcme, te recomendamos seguir este orden de lectura:

1. **Comienza con la [Visión General de Gestión de Proyectos](./octoacme-project-management-overview.md)** para entender el enfoque general y la filosofía de trabajo.
2. **Lee [Roles y Personas](./octoacme-roles-and-personas.md)** para entender tu rol y cómo interactúas con otros miembros del equipo.
3. **Usa la [Plantilla de Lista de Verificación de Onboarding](./onboarding-checklist-template.md)** como guía para tu incorporación al proyecto.
4. **Revisa los documentos específicos** del ciclo de vida según la fase actual de tu proyecto.

### Para Iniciar un Nuevo Proyecto

Sigue el flujo secuencial de la documentación:

1. **[Guía de Inicio de Proyectos](./octoacme-project-initiation.md)** — Valida la idea y obtén aprobación para proceder.
2. **[Guía de Planificación](./octoacme-project-planning.md)** — Crea el backlog y el plan de lanzamiento.
3. **[Ejecución y Seguimiento](./octoacme-execution-and-tracking.md)** — Ejecuta el trabajo y mantén el ritmo del equipo.
4. **[Gestión de Riesgos y Comunicación](./octoacme-risks-and-communication.md)** — Gestiona riesgos y comunica el progreso.
5. **[Guía de Lanzamiento y Despliegue](./octoacme-release-and-deployment.md)** — Prepara y ejecuta el despliegue.
6. **[Retrospectiva y Mejora Continua](./octoacme-retrospective-and-continuous-improvement.md)** — Cierra el proyecto y captura aprendizajes.

### Para Consultas Específicas

Usa esta guía rápida según tu necesidad:

- **¿Cómo gestiono riesgos?** → [Gestión de Riesgos y Comunicación](./octoacme-risks-and-communication.md)
- **¿Cómo planifico un sprint?** → [Guía de Planificación](./octoacme-project-planning.md)
- **¿Qué procesos sigo para lanzamiento?** → [Guía de Lanzamiento y Despliegue](./octoacme-release-and-deployment.md)
- **¿Cómo ejecuto una retrospectiva?** → [Retrospectiva y Mejora Continua](./octoacme-retrospective-and-continuous-improvement.md)
- **¿Cuál es mi responsabilidad en el proyecto?** → [Roles y Personas](./octoacme-roles-and-personas.md)
- **¿Cómo manejo el día a día del proyecto?** → [Ejecución y Seguimiento](./octoacme-execution-and-tracking.md)
- **¿Cómo incorporo un nuevo miembro al equipo?** → [Plantilla de Lista de Verificación de Onboarding](./onboarding-checklist-template.md)

### Para Mejoras y Feedback

Esta documentación es un recurso vivo que evoluciona con nuestra organización. Si encuentras:

- **Información desactualizada** — Abre un issue describiendo qué necesita actualizarse.
- **Procesos faltantes** — Propón nuevos documentos o secciones mediante un issue o PR.
- **Mejoras o clarificaciones** — Crea un PR con tus sugerencias y etiqueta a los maintainers para revisión.
- **Preguntas sin respuesta** — Abre un issue de tipo "pregunta" para que pueda convertirse en documentación futura.

Todos los miembros del equipo son bienvenidos a contribuir para hacer esta documentación más útil y completa.

---

## Contribuciones

Para contribuir a esta documentación, por favor:

1. Crea un branch desde `main`
2. Realiza tus cambios siguiendo el formato y tono existente
3. Abre un Pull Request con una descripción clara de los cambios
4. Solicita revisión de los Project Managers o maintainers del repositorio

---

## Contacto

Para preguntas sobre la documentación o procesos de gestión de proyectos, contacta al equipo de Project Management de OctoAcme o abre un issue en este repositorio.
