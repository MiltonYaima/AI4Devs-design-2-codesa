# historias de usuario

1. Gestión de Vacantes
Título: Creación y Publicación de Vacantes
Como Reclutador,
quiero crear y publicar nuevas vacantes en el sistema,
para iniciar procesos de reclutamiento para posiciones abiertas.
Criterios de Aceptación:

Debe permitir ingresar información básica: título, descripción, departamento, requisitos, rango salarial
Debe requerir aprobación del Hiring Manager antes de la publicación
Debe permitir adjuntar documentos relacionados con la posición
Debe enviar notificaciones automáticas al ser aprobada

Notas Adicionales:

La vacante debe pasar por un flujo de estados: Borrador → Pendiente Aprobación → Publicada
Integración con el sistema de notificaciones

Historias Relacionadas:

Edición de Vacantes
Gestión de Aprobaciones de Vacantes

2. Aplicación a Vacantes
Título: Postulación de Candidatos a Vacantes
Como Candidato,
quiero aplicar a una vacante publicada,
para ser considerado en el proceso de selección.
Criterios de Aceptación:

Debe permitir subir CV en formatos PDF o DOC
Debe permitir completar un formulario con información personal y profesional
Debe validar requisitos mínimos de la vacante
Debe enviar confirmación de recepción de la aplicación

Notas Adicionales:

Integración con validación automática de requisitos
Almacenamiento seguro de documentos personales

Historias Relacionadas:

Actualización de Perfil de Candidato
Seguimiento de Estado de Aplicación

3. Gestión del Pipeline
Título: Gestión de Candidatos en Pipeline de Reclutamiento
Como Reclutador,
quiero mover candidatos a través de las diferentes etapas del proceso,
para gestionar eficientemente el ciclo de reclutamiento.
Criterios de Aceptación:

Debe mostrar candidatos organizados por etapas del proceso
Debe permitir mover candidatos entre etapas mediante drag & drop
Debe registrar automáticamente fechas y responsables de cada movimiento
Debe permitir agregar feedback en cada etapa

Notas Adicionales:

Integración con calendario para entrevistas
Sistema de notificaciones automáticas

Historias Relacionadas:

Programación de Entrevistas
Registro de Feedback

4. Programación de Entrevistas
Título: Coordinación de Entrevistas con Candidatos
Como Reclutador,
quiero programar entrevistas con los candidatos y entrevistadores,
para coordinar eficientemente las evaluaciones de candidatos.
Criterios de Aceptación:

Debe permitir seleccionar slots de tiempo disponibles
Debe enviar invitaciones automáticas a candidatos y entrevistadores
Debe permitir reprogramar o cancelar entrevistas
Debe integrarse con calendarios corporativos 
Los calendarios deben tener en cuenta dias festivos del pais

Notas Adicionales:

Integración con sistemas de videoconferencia
Recordatorios automáticos

Historias Relacionadas:

Registro de Resultado de Entrevista
Gestión de Disponibilidad de Entrevistadores

5. Evaluación de Candidatos
Título: Registro y Gestión de Evaluaciones
Como Hiring Manager,
quiero registrar evaluaciones detalladas de los candidatos,
para tomar decisiones informadas de contratación.
Criterios de Aceptación:

Debe permitir calificar diferentes aspectos del candidato
Debe permitir adjuntar documentos de la evaluación
Debe calcular automáticamente scores basados en criterios predefinidos
Debe permitir comparar candidatos para una misma vacante

Notas Adicionales:

Templates personalizables de evaluación
Sistema de scoring configurable

Historias Relacionadas:

Comparación de Candidatos
Generación de Reportes de Evaluación

6. Gestión de Ofertas
Título: Creación y Seguimiento de Ofertas Laborales
Como Reclutador,
quiero generar y gestionar ofertas laborales para candidatos seleccionados,
para finalizar el proceso de contratación.
Criterios de Aceptación:

Debe permitir generar ofertas basadas en templates predefinidos
Debe requerir aprobaciones según nivel de la posición
Debe permitir negociaciones y ajustes
Debe registrar aceptación o rechazo de la oferta

Notas Adicionales:

Integración con sistema de compensaciones
Workflow de aprobaciones configurable

Historias Relacionadas:

Aprobación de Ofertas
Gestión de Contratos

# backlog 

Organizaré el backlog en sprints incrementales, asegurando que cada entrega tenga valor para el cliente y permita probar funcionalidades completas.

Desglose del Backlog por Sprints:
Sprint 1 - Core (2 semanas)
Objetivo: Establecer funcionalidades básicas para publicar y aplicar a vacantes.

Setup Inicial y Gestión de Usuarios

Configuración de roles (Reclutador, Hiring Manager, Admin)
Login/Registro básico
Gestión de permisos


Crear Vacantes (Básico)

Formulario de creación de vacante
Campos básicos (título, descripción, requisitos)
Lista de vacantes activas


Aplicación Simple

Formulario de aplicación básico
Subida de CV
Confirmación de aplicación



Sprint 2 - Pipeline Básico (2 semanas)
Objetivo: Implementar gestión básica de candidatos.

Pipeline Básico

Visualización de etapas básicas
Mover candidatos entre etapas
Vista de candidatos por vacante


Evaluaciones Simples

Formulario básico de evaluación
Registro de comentarios
Estado aprobado/rechazado


Notificaciones Básicas

Emails de confirmación
Alertas de nuevos candidatos
Notificaciones de cambios de estado



Sprint 3 - Gestión Avanzada (2 semanas)
Objetivo: Mejorar el proceso de evaluación y seguimiento.

Gestión de Entrevistas

Programación de entrevistas
Integración con calendario
Registro de feedback


Pipeline Avanzado

Drag & drop de candidatos
Filtros avanzados
Vista de pipeline por departamento


Evaluaciones Detalladas

Matrices de evaluación
Scorecards personalizados
Comparación de candidatos



Sprint 4 - Ofertas y Análisis (2 semanas)
Objetivo: Completar el ciclo de contratación e implementar análisis.

Gestión de Ofertas

Generación de ofertas
Workflow de aprobaciones
Seguimiento de aceptación/rechazo


Reportes Básicos

Tiempo por etapa
Tasas de conversión
Reportes por vacante


Análisis de Métricas

Dashboard de KPIs
Métricas de eficiencia
Tendencias de contratación


Ventajas de esta organización:

Cada sprint entrega valor incremental y funcionalidad probabile
Las dependencias están manejadas de forma secuencial
El cliente puede comenzar a usar el sistema desde el Sprint 1
Permite feedback temprano para ajustar sprints posteriores
Facilita la detección temprana de problemas

Consideraciones para el cliente:

Después de cada sprint habrá una demo y período de prueba
Se pueden ajustar prioridades basadas en feedback
Cada entrega incluirá documentación y guía de uso
Se proporcionará soporte post-implementación


# tickets de trabajo para el primer sprint 

1. Setup Inicial y Gestión de Usuarios
US1.1 - Configuración Base del Proyecto

Talla: XS (1-2 días)
Tareas:

Configuración del ambiente de desarrollo
Setup de base de datos
Configuración de CI/CD básico

US1.2 - Sistema de Autenticación

Talla: S (2-3 días)
Tareas:

Implementación de login
Registro de usuarios
Recuperación de contraseña
Tokens JWT

US1.3 - Gestión de Roles y Permisos

Talla: M (3-5 días)
Tareas:

Definición de roles (Admin, Reclutador, Hiring Manager)
Sistema de permisos por rol
Middleware de autorización

US1.4 - CRUD Usuarios

Talla: XS (1-2 días)
Tareas:

Listado de usuarios
Creación/Edición de usuarios
Desactivación de usuarios


2. Crear Vacantes (Básico)
US2.1 - Modelo de Datos Vacantes

Talla: M (3-5 días)
Tareas:

Diseño del modelo de datos
Migraciones
Validaciones
Tests unitarios

US2.2 - CRUD Vacantes

Talla: S (2-3 días)
Tareas:

Formulario de creación
Edición de vacantes
Eliminación lógica
Validaciones de formulario

US2.3 - Listado y Filtros de Vacantes

Talla: XS (1-2 días)
Tareas:

Vista de listado
Filtros básicos
Paginación
Ordenamiento

US2.4 - Publicación de Vacantes

Talla: L (5-8 días)
Tareas:

Workflow de estados
Sistema de aprobaciones
Notificaciones básicas
Validaciones de publicación

3. Aplicación Simple
US3.1 - Modelo de Datos Aplicaciones

Talla: M (3-5 días)
Tareas:

Diseño del modelo de datos
Relaciones con vacantes y candidatos
Migraciones
Tests unitarios

US3.2 - Formulario de Aplicación

Talla: S (2-3 días)
Tareas:

Formulario de datos personales
Validaciones
Integración con vacantes
Mensajes de error

US3.3 - Carga de CV

Talla: XS (1-2 días)
Tareas:

Upload de archivos
Validación de formatos
Almacenamiento en S3

US3.4 - Confirmaciones

Talla: S (2-3 días)
Tareas:

Emails de confirmación
Página de confirmación
Notificaciones a reclutadores

Resumen de Estimaciones:

XS (1-2 días): 4 tickets
S (2-3 días): 4 tickets
M (3-5 días): 3 tickets
L (5-8 días): 1 ticket

Total estimado: 25-38 días/persona
Notas de Implementación:

Las estimaciones asumen un desarrollador senior
Se recomienda trabajar en paralelo los tracks de usuarios y vacantes
Las aplicaciones dependen de tener vacantes funcionando
Se sugiere buffer de 20% para imprevistos


# alternativa backlog ( chat gpt pero no tiene el contexto completo solo las historias de usuario )

1️⃣ MVP Inicial - Funcionalidades esenciales para el flujo básico
🔹 Objetivo: Permitir la publicación de vacantes y la postulación de candidatos.

Creación de Vacantes (Básico)

Ingreso de información básica (título, descripción, requisitos, etc.).
Guardado en estado "Borrador".
Gestión de Aprobación de Vacantes

Cambio de estado de "Borrador" a "Pendiente de Aprobación".
Aprobación/Rechazo por el Hiring Manager.
Publicación automática tras aprobación.
Postulación de Candidatos

Subida de CV en PDF o DOC.
Completar formulario de postulación.
Validación de requisitos mínimos.
Confirmación de recepción al candidato.
Pipeline de Candidatos (Básico)

Visualización de candidatos organizados por etapa.
Movimiento manual entre etapas.
2️⃣ Iteración 2 - Optimización y Seguimiento
🔹 Objetivo: Mejorar la gestión de candidatos y entrevistas.

Notificaciones Automáticas

Al aprobar una vacante.
Al recibir una nueva postulación.
Gestión Completa del Pipeline

Movimiento de candidatos con drag & drop.
Registro de fechas y responsables de cada cambio.
Programación de Entrevistas

Selección de horarios disponibles.
Envío automático de invitaciones.
3️⃣ Iteración 3 - Evaluación y Toma de Decisiones
🔹 Objetivo: Facilitar la evaluación y contratación de candidatos.

Registro de Evaluaciones

Formulario para calificación de candidatos.
Adjuntar documentos de evaluación.
Comparación de Candidatos

Visualización de scores y evaluaciones.
Generación y Seguimiento de Ofertas

Creación de ofertas basadas en templates.
Aprobación de ofertas.
Registro de aceptación o rechazo.