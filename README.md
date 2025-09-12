# PROYECTO INTERMODULAR

### 

## 1. Retos a realizar

### Diseño de los dos retos

- Reto 1 (producto mínimo viable): construir un servicio web con front responsive, CRUD con autenticación y despliegue básico; integra POO, acceso a BD, API REST, interfaz, control de versiones y CI mínima.
- Reto 2 (valor diferencial): extender el producto con innovación aplicable (p. ej., búsqueda semántica, pagos, cache/CDN, accesibilidad AA, observabilidad), hipótesis de cliente y mini-experimento de validación.

### Ejemplos concretos de retos DAW

- Comercio local “headless”: back con API REST, front SPA/SSR, inventario y pedidos, panel de administración, y despliegue en cloud escolar; simula un encargo real.
- Portal de citas previas para servicios municipales: roles, colas, calendario, notificaciones, SLAs y medición de uso; énfasis en accesibilidad y protección de datos.
- Plataforma de microformaciones: alta de cursos, matrículas, contenidos multimedia y trazabilidad; experimento de adopción con encuesta y métricas.

### Evidencias de los cuatro ejes

- Búsqueda de información: diario técnico con fuentes evaluadas y decisiones motivadas; checklist de calidad de fuentes.
- Innovación: propuesta de valor y benchmarking de soluciones; justificación técnica y de impacto.
- Investigación aplicada: mini-experimento A/B o pruebas de rendimiento con informe y acciones.
- Emprendimiento: canvas del modelo, estimación de costes y plan de entrega; pitch de negocio de 3 minutos.

### Organización y roles de equipo

- Roles rotatorios: tech lead, QA, devops; cada estudiante cubre al menos dos roles durante el curso para evidenciar competencias.
- Carta del equipo: acuerdos de comunicación, DoD/DoR, horarios y gestión de conflictos; repositorio único con issues y PRs asignados.

### Evaluación formativa e individual

- Rúbricas por RA/CE: calidad del código y diseño, cumplimiento funcional, pruebas, despliegue, documentación, accesibilidad y seguridad básica.
- Instrumentos: revisiones de código con checklist, dailies semanales, bitácora individual, pruebas demo y defensa oral con preguntas técnicas diferenciadas.
- Ponderación orientativa: 40% entregables técnicos, 30% proceso/evidencias, 20% defensa individual, 10% impacto/innovación; siempre mapeado a RA/CE.

### Gestión del tiempo y tutorización

- Cadencia: 1 sesión semanal obligatoria de proyecto con objetivos claros; tutorías rápidas en otros módulos para desbloqueos; tablero visible por equipo.
- Entregables mínimos por sprint: backlog priorizado, incremento funcional desplegado, pruebas automatizadas básicas, documentación viva y notas de retrospectiva.

### Documentación y calidad

- Plantillas: README con contexto, arquitectura, instrucciones de despliegue, criterios de aceptación; ADRs para decisiones técnicas clave.
- Trazabilidad RA→tareas: matriz que relaciona historias de usuario con RA y criterios de evaluación del proyecto y de los módulos implicados.

### Coordinación docente

- Alineación inicial para seleccionar RA activables por reto y reparto de evaluaciones entre módulos; actas de seguimiento conjuntas.
- Tribunal de defensa: presencia del equipo docente y, si procede, tutor/a de empresa para enriquecer el feedback profesional.

### Entrega final y difusión

- Demo pública interna con rúbrica común y feedback cruzado entre equipos; informe final y repositorio archivado con tag de release.
- Memoria individual breve: aportaciones, lecciones y evidencias vinculadas a RA/CE, para sustentar calificación individual.



## 2. Contenidos previos a los retos

### Control de versiones con Git

- Objetivos: flujo Git básico y colaborativo; ramas por feature; PRs y revisiones con checklist.
- Contenidos: init/clone, commit/branch/merge/rebase, .gitignore, tags, Git Flow vs Trunk-Based, resolución de conflictos.
- Entregables: repo por equipo, reglas de branching, plantilla de PR, protección de ramas y convención de commits.

### Fundamentos de despliegue en la nube (AWS)

- Objetivos: que cada equipo pueda publicar un MVP y mantenerlo.
- Contenidos: opciones cloud educativas (AWS Educate/Academy), servicios básicos (EC2, S3, RDS), costes y teardown; alternativas PaaS.
- Entregables: cuenta educativa activada, playbook de despliegue, política de costes y script de apagado/limpieza.

### Gestión de proyecto ágil (Scrum)

- Objetivos: trabajo por sprints, historias de usuario, criterios de aceptación, DoR/DoD y retrospectivas.
- Contenidos: tablero Kanban/Scrum, estimación relativa, definición de objetivos de sprint.
- Entregables: backlog priorizado, tablero visible, acta de retrospectiva y demo checklist.

### CI/CD esencial

- Objetivos: integrar y desplegar con automatización mínima para asegurar calidad y reproducibilidad. Github actions
- Contenidos: pipelines con pruebas y linters, build y empaquetado, artefactos y versionado semántico, gates en PR.
- Entregables: pipeline que ejecuta test y lint en cada PR, build con versión etiquetada y badge de estado.

### Calidad de código y pruebas

- Objetivos: estándares de estilo, análisis estático, cobertura de tests y TDD básico.
- Contenidos: linters/formatters, code smells, pruebas unitarias y de integración, mocks.
- Entregables: reglas de lint, suite de tests y reporte automático.

## 

## 3. Resultados de aprendizaje involucrados

### Entorno servidor

- Selecciona arquitecturas y tecnologías web en servidor, analizando capacidades, integración con lenguajes de marcas y herramientas del entorno.
- Implementa lógica de negocio y acceso a datos en el servidor, utilizando estructuras de control, gestión de sesiones, seguridad básica y plantillas/servicios REST.

### Entorno cliente

- Selecciona arquitecturas y tecnologías de programación sobre clientes web y organiza el código en componentes reutilizables.
- Programa interacción y manipulación del DOM/datos en cliente, aplicando eventos, validaciones, consumo de APIs y manejo de estados y rutas.

### Despliegue de aplicaciones

- Implanta aplicaciones web en servidores y plataformas, configurando servicios, variables de entorno, logs, copias y medidas de seguridad básicas en el despliegue.
- Automatiza el ciclo de build, pruebas e integración continua, gestionando dependencias, artefactos y versiones en el pipeline de entrega.

### Diseño de interfaces

- Planifica y diseña interfaces accesibles y responsivas, aplicando guías de estilo, patrones de interacción y criterios WCAG AA.
- Prototipa y evalúa la usabilidad con usuarios, iterando sobre feedback y evidenciando mejoras en la experiencia.
