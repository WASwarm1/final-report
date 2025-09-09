# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

### 5.1.2. Source Code Management.

### 5.1.3. Source Code Style Guide & Conventions.

### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

<table>
<tr>
    <th colspan="5">Sprint 1</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-09-10</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">21:30</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">via Google Meets</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Werner Lang</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Werner Khalil Lang Nassi, Jorge Francisco Taipe Sangama, Saúl Ortega Muñoz, Matias Gabriel Armestar Heredia, Emilia Duran Santander</td>
</tr>
<tr>
    <td colspan="5">Sprint  1 Review Summary</td>
    <td colspan="8">En este primer sprint se asignaron responsabilidades a cada integrante y planteo los requerimientos para el desarrollo de la Landing Page.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">En esta sección todos los integrantes mencionaron tener aciertos en partes del codigo y en otras partes poder mejorar sus habilidades realizando la Landing Page</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Goal</td>
    <td colspan="8">
Desarollar y desplegar una lading con la finalidad de presentar informacion relevate a los usuarios a través de imágenes.
La pagina debe ser completamente adaptable a todos los dispositovs que puedan utilizar los usuarios, asegurando una experiencia
fluida y responsiva.</td>
</tr>
</table>


#### 5.2.1.2. Aspect Leaders and Collaborators.

| Team member (LastName, First Name) | GitHub UserName | Aspect 1: Landing Page Leader (L) / Collaborator (C) | Aspect 2: Diseños Figma: Leader (L) / Collaborator (C) | Aspect 3: Reporte (L) / Collaborator (C) |
|------------------------------------|-----------------|------------------------------------------------------|--------------------------------------------------------|-----------------------------------------|
| Lang Nassi, Werner Khalil          | 00WernerLang    |                                                      |                                                        | L                                       |
|                                    |     |                                                      |                                                        |                                         |
|                                    |     |                                                      |                                                        |                                         |
|                                    |     |                                                      |                                                        |                                         |
|                                    |     |                                                      |                                                        |                                         |

#### 5.2.1.3. Sprint Backlog 1.

|  Sprint 1  |            Sprint 1             |     |                                      |                                                                          |                    |             |                                                |
|:----------:|:-------------------------------:|:---:|:------------------------------------:|:------------------------------------------------------------------------:|:------------------:|:-----------:|:----------------------------------------------:|
| User Story |        Work-Item / Task         |     |                                      |                                                                          |                    |             |                                                |
|     Id     |              Title              | Id  |                Title                 |                               Description                                | Estimation (Hours) | Assigned To | Status (To do / In process / To review / Done) |
|    US01    |  Ver descripción del producto   | W01 |      Diseñar wireframe de hero       |  Crear wireframe de la sección principal con descripción del producto    |         2          |      -      |                     To do                      |
|            |                                 | W02 |  Redactar contenido descriptivo      |         Escribir textos claros sobre funcionalidad y beneficios          |         3          |      -      |                     To do                      |
|            |                                 | W03 |       Desarrollar sección hero       |         Maquetar y codificar la sección principal de la landing          |         4          |      -      |                     To do                      |
|    US02    |   Conocer al equipo fundador    | W04 |   Recopilar información del equipo   |        Obtener fotos, nombres, roles y biografías de cada miembro        |         1          |      -      |                     To do                      |
|            |                                 | W05 |     Diseñar tarjetas de miembros     |          Crear diseño de las tarjetas para mostrar información           |         2          |      -      |                     To do                      |
|            |                                 | W06 | Desarrollar sección "Sobre nosotros" |          Implementar página completa con información del equipo          |         3          |      -      |                     To do                      |
|    US03    |      Ver misión y visión        | W07 |       Redactar misión y visión       |            Definir y escribir la misión y visión de ChambaPro            |         2          |      -      |                     To do                      |
|            |                                 | W08 |     Diseñar layout misión/visión     |            Crear diseño visual para presentar misión y visión            |         1          |      -      |                     To do                      |
|            |                                 | W09 |   Integrar misión/visión al sitio    |              Implementar sección dentro de "Sobre nosotros"              |         2          |      -      |                     To do                      |
|    US04    |  Ver beneficios para clientes   | W10 |     Identificar beneficios clave     |         Listar y priorizar beneficios principales para clientes          |         1          |      -      |                     To do                      |
|            |                                 | W11 |   Crear iconografía de beneficios    |            Diseñar íconos representativos para cada beneficio            |         2          |      -      |                     To do                      |
|            |                                 | W12 |  Desarrollar sección de beneficios   |         Implementar sección visual con beneficios para clientes          |         3          |      -      |                     To do                      |
|    US05    |  Ver beneficios para técnicos   | W13 |   Definir beneficios para técnicos   |         Especificar ventajas únicas para profesionales técnicos          |         1          |      -      |                     To do                      |
|            |                                 | W14 |    Diseñar sección para técnicos     |         Crear layout específico para mostrar beneficios técnicos         |         2          |      -      |                     To do                      |
|            |                                 | W15 |   Implementar beneficios técnicos    |         Desarrollar sección completa para profesionales técnicos         |         3          |      -      |                     To do                      |
|    US06    |     Ver botón de registro       | W16 |     Diseñar botón call-to-action     |          Crear diseño atractivo del botón de registro principal          |         1          |      -      |                     To do                      |
|            |                                 | W17 |  Configurar redirección de registro  |           Implementar navegación hacia formulario de registro            |         1          |      -      |                     To do                      |
|            |                                 | W18 |      Integrar botón en cabecera      |           Posicionar y maquetar botón en header de la landing            |         1          |      -      |                     To do                      |
|    US07    |     Ver botón de contacto       | W19 |    Recopilar información contacto    |         Definir canales de contacto: email, teléfono, formulario         |         1          |      -      |                     To do                      |
|            |                                 | W20 |      Diseñar footer de contacto      |        Crear diseño del pie de página con información de contacto        |         2          |      -      |                     To do                      |
|            |                                 | W21 |   Desarrollar sección de contacto    |      Implementar footer completo con todos los canales de contacto       |         2          |      -      |                     To do                      |
#### 5.2.1.4. Development Evidence for Sprint Review.



| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
|            |        |           |                |                     |                    |

#### 5.2.1.5. Execution Evidence for Sprint Review.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

#### 5.2.1.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.

### 5.3.2. Registro de Entrevistas.

### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.

## Conclusiones.

### Conclusiones Y Recomendaciones.

### Video About-the-Team.

## Bibliografía.

### Anexos.