# MaquiGest
<div align="center">

  <img src="assets/md-images-front/upc-logo.png" width="150px" />

  <p>Universidad Peruana de Ciencias Aplicadas</p>
  <p>Facultad de Ingeniería</p>
  <p>Carrera de Ingeniería de Software</p>

  <p>Ciclo académico 2026-20</p><br>

  <p><b>1ASI0729</b></p>
  <p><b>Desarrollo de Aplicaciones Open Source</b></p>
  <p>NRC</p>
  <p><b>7750</b></p>
  <p><b>Informe de Trabajo Final</b></p>
  <p>Docente</p>
  <p><b>Bautista Ubillús, Efraín Ricardo</b></p>
  <p>Startup</p>
  <p><b>CleanCode</b></p><br>
  <p>Producto</p>
  <p><b>MaquiGest</b></p>

</div>

<div align="center">
  <h3>Integrantes</h3>

  <table>
    <thead>
      <tr>
        <th>Código</th>
        <th>Apellidos y Nombres</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>U202115277</td>
        <td>Delgado Perez, James Caleb</td>
      </tr>
      <tr>
        <td>U202111529</td>
        <td>Montalvo Vasquez, Bruno Rodrigo</td>
      </tr>
      <tr>
        <td>U202410211</td>
        <td>Manosalva Tovar, Miroslav</td>
      </tr>
    </tbody>
  </table>
  <br>

  <p><b>Septiembre, 2026</b></p>

</div>

<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

| Versión | Fecha |  Autor   |                                                  Descripción de modificación                                                   |
| :-----: |:-----:|:--------:| :----------------------------------------------------------------------------------------------------------------------------: |
|   AV1   |       |  Todos   | Se agregó la primera versión del informe, incluyendo carátula, registro de versiones, perfiles del equipo, análisis inicial del problema, artefactos de UX, arquitectura preliminar y evidencias del Sprint 1. |

<div style="page-break-after: always;"></div>


## Project Report Collaboration Insights

A continuación, se presenta el repositorio utilizado para la elaboración colaborativa del informe del proyecto MaquiGest.

#### Link del repositorio del Reporte:

- https://github.com/upc-pre-202620-1asi0729-7750-cleancode/maquigest-report

### Entrega AV1:

#### Participación por integrante:

##### Commits en el Project Report:

<div style="page-break-after: always;"></div>


# Contenido

## Índice

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Personas](#231-user-personas)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:  
**ABET - EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET - EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Delgado Perez, James Caleb**<br>**AV1:**<br><br>**Montalvo Vasquez, Bruno Rodrigo**<br>**AV1:**<br><br>**Manosalva Tovar, Miroslav**<br>**AV1:** | **AV1:** |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Delgado Perez, James Caleb**<br>**AV1:**<br><br>**Montalvo Vasquez, Bruno Rodrigo**<br>**AV1:**<br><br>**Manosalva Tovar, Miroslav**<br>**AV1:** | **AV1:** |

<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

CleanCode es una startup orientada al desarrollo de soluciones digitales accesibles que permitan organizar y optimizar los procesos de pequeñas y medianas empresas. Su propuesta se enfoca en resolver problemas operativos mediante herramientas especializadas, sencillas de utilizar y adaptadas a las necesidades de sus usuarios.

Como parte de esta iniciativa, CleanCode desarrolla MaquiGest, una plataforma SaaS dirigida principalmente a pequeñas y medianas empresas dedicadas al alquiler de maquinaria y equipos para obras de construcción de pequeña escala. Estas empresas suelen gestionar sus operaciones mediante hojas de cálculo, llamadas, mensajes y sistemas independientes, lo cual dificulta el control de sus equipos y aumenta la posibilidad de cometer errores.

MaquiGest centralizará la gestión del inventario, disponibilidad, reservas, contratos, pagos, entregas, devoluciones, incidencias y mantenimiento de los equipos. De esta manera, permitirá realizar el seguimiento de la maquinaria durante todo su ciclo de alquiler y facilitará la interacción con las personas que necesitan alquilar equipos para sus proyectos personales relacionados con la construcción.

#### Misión

Nuestra misión es facilitar la gestión integral de las pequeñas y medianas empresas dedicadas al alquiler de maquinaria y equipos para construcción mediante una plataforma digital sencilla, accesible y confiable. Buscamos centralizar sus operaciones, reducir errores relacionados con la disponibilidad y las reservas, mejorar el control del estado de los equipos y brindar una mejor experiencia tanto a las empresas como a las personas que alquilan maquinaria.

#### Visión

Nuestra visión es convertirnos en una startup referente en el Perú en soluciones digitales para la gestión del alquiler de maquinaria de construcción, contribuyendo a que las pequeñas y medianas empresas profesionalicen sus operaciones y brinden servicios más eficientes, organizados y confiables.

#### Valores

Nuestros valores principales son los siguientes:

* **Innovación:** Aplicamos tecnología para mejorar y simplificar los procesos tradicionales del alquiler de maquinaria.
* **Simplicidad:** Diseñamos soluciones comprensibles y accesibles para empresas con diferentes niveles de experiencia tecnológica.
* **Responsabilidad:** Promovemos una gestión adecuada de los equipos, la información y las operaciones de alquiler.
* **Colaboración:** Valoramos el trabajo en equipo y la comunicación con las empresas y personas que utilizarán MaquiGest.
* **Calidad:** Buscamos ofrecer una plataforma confiable, organizada y orientada a las necesidades reales de sus usuarios.

### 1.1.2. Perfiles de integrantes del equipo

|   Código   | Nombre completo del integrante  | Descripción de la carrera                                          |                               Fotografía                                | Conocimientos y habilidades                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :--------: |:--------------------------------| :----------------------------------------------------------------- |:-----------------------------------------------------------------------:| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| U202115277 | Delgado Perez, James Caleb      | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/james-delgado.jpeg" width="150px" /> | Soy estudiante de Ingeniería de Software y me apasiona la creación de productos digitales que simplifiquen procesos y ayuden a las personas a ahorrar tiempo para enfocarse en lo que realmente importa. Me motiva transformar problemas en soluciones prácticas, eficientes y con impacto real. Actualmente estoy fortaleciendo mis conocimientos en C# y tengo experiencia con C++, HTML, CSS, JavaScript y Java, este último desarrollado durante el curso de Diseño y Patrones de Software. Me interesa especialmente el área de frontend, bases de datos y aplicaciones web. Lo que más me motiva de este proyecto es que representa una gran oportunidad para incorporarme al mundo laboral, adquirir nuevos conocimientos y seguir fortaleciendo mi perfil profesional. Además, me considero una persona organizada, que aprende rápido y que trabaja bien en equipo. Fuera del ámbito académico y tecnológico, me gustan los deportes, y también encuentro en la programación y la música una forma de expresión y creatividad. |
| U202111529 | Montalvo Vasquez, Bruno Rodrigo | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/bruno-montalvo.png" width="150px" /> | Soy Bruno Rodrigo Montalvo Vasquez, estudiante de la carrera de Ingeniería de Software. Me encuentro interesado y motivado por aprender nuevos temas relacionados con mi carrera. Asimismo, estoy abierto a trabajar con profesionales de mi área académica para mejorar mis conocimientos, adquirir experiencia y fortalecer mis habilidades de trabajo en equipo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |           
| U202410211 | Manosalva Tovar, Miroslav       | Ingeniería de Software - Universidad Peruana de Ciencias Aplicadas | <img src="assets/md-images-members/miroslav-manosalva.jpeg" width="150px" /> | Soy Miroslav Manosalva Tovar, estudiante de Ingeniería de Software. Tengo conocimientos en el área de programación y experiencia en la elaboración de interfaces de usuario (UI), que puedo aportar al desarrollo de MaquiGest. Mi experiencia trabajando con interfaces me permite contribuir a la presentación de la información y a la organización visual de las funcionalidades de la plataforma. Me considero una persona responsable y persistente: procuro cumplir con las actividades que asumo y mantener el esfuerzo cuando encuentro dificultades. En este proyecto, busco aplicar mis conocimientos de programación y diseño de interfaces, seguir fortaleciendo mi formación y contribuir al desarrollo de una solución útil para sus usuarios. |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Actualmente, muchas pequeñas y medianas empresas dedicadas al alquiler de maquinaria y equipos para construcción gestionan sus operaciones mediante herramientas dispersas, como hojas de cálculo, documentos físicos, llamadas telefónicas y aplicaciones de mensajería. Aunque estos medios permiten registrar información básica, no proporcionan una visión integrada y actualizada sobre la disponibilidad, ubicación, condición y mantenimiento de cada equipo.

El alquiler de maquinaria comprende distintas actividades que deben mantenerse coordinadas, entre ellas el registro del inventario, la consulta de disponibilidad, la creación de reservas, la elaboración de contratos, el registro de pagos, la programación de entregas, la recepción de devoluciones y la atención de incidencias. Cuando esta información se encuentra distribuida en diferentes medios, aumenta la posibilidad de generar reservas duplicadas, entregar equipos que no están disponibles, perder el seguimiento de los contratos o retrasar los mantenimientos correspondientes.

Esta situación también afecta a las personas que necesitan alquilar maquinaria para remodelaciones, reparaciones u obras personales. La comunicación con las empresas suele realizarse mediante llamadas o mensajes, por lo que el cliente puede tener dificultades para conocer qué equipos están disponibles, cuáles son sus condiciones de alquiler y en qué estado se encuentra su solicitud.

Existen plataformas orientadas a empresas de alquiler de gran escala; sin embargo, pueden resultar complejas o poco accesibles para negocios pequeños que necesitan organizar sus operaciones sin incorporar sistemas sobredimensionados. En consecuencia, se identifica la necesidad de una solución especializada que centralice el ciclo de alquiler y que pueda ser utilizada tanto por las empresas proveedoras como por las personas interesadas en alquilar los equipos.

MaquiGest abordará esta problemática mediante una plataforma SaaS que permitirá administrar en un único entorno el inventario, la disponibilidad, las reservas, los contratos, los pagos, las entregas, las devoluciones, las incidencias y el mantenimiento. De esta manera, las empresas podrán mantener un mejor control de sus equipos y los clientes podrán realizar sus procesos de alquiler de forma más organizada.

#### 5W & 2H

**Who (¿Quiénes?)**

La problemática afecta principalmente a los propietarios, administradores y trabajadores de pequeñas y medianas empresas dedicadas al alquiler de maquinaria para construcción. También afecta a personas que necesitan alquilar equipos para ejecutar remodelaciones, reparaciones u otros proyectos personales relacionados con la construcción.

**What (¿Qué?)**

El problema principal es la ausencia de una plataforma especializada que permita administrar integralmente el ciclo de alquiler de la maquinaria. La información sobre inventario, disponibilidad, reservas, contratos, pagos, entregas, devoluciones, incidencias y mantenimiento suele encontrarse distribuida en diferentes herramientas y medios de comunicación.

**Where (¿Dónde?)**

La problemática se presenta en las operaciones internas de las pequeñas y medianas empresas de alquiler y durante la comunicación con sus clientes. Abarca tanto la gestión administrativa del negocio como el seguimiento de los equipos que son entregados para obras de construcción de pequeña escala.

**When (¿Cuándo?)**

Puede manifestarse durante cualquier etapa del ciclo de alquiler: cuando un cliente consulta la disponibilidad, realiza una reserva, firma un contrato, efectúa un pago, recibe el equipo, comunica una incidencia, devuelve la maquinaria o cuando la empresa debe programar su mantenimiento.

**Why (¿Por qué?)**

La problemática ocurre porque las herramientas utilizadas no se encuentran integradas y requieren que la información sea registrada o comprobada manualmente. Asimismo, muchas soluciones existentes están orientadas a operaciones de mayor escala y pueden resultar excesivamente complejas para pequeñas empresas.

**How (¿Cómo?)**

Las empresas revisan y actualizan manualmente hojas de cálculo, documentos, llamadas y conversaciones por mensajería para determinar el estado de sus alquileres. Esta forma de trabajo puede producir información desactualizada, registros duplicados, dificultades de coordinación y pérdida de trazabilidad sobre los equipos.

**How Much (¿Cuánto impacta?)**

El impacto se refleja en el tiempo empleado para comprobar información, los posibles conflictos de disponibilidad, los retrasos en entregas y devoluciones, la inmovilización de equipos que requieren mantenimiento y la pérdida de oportunidades de alquiler. También puede afectar la confianza y satisfacción de los clientes. La dimensión cuantitativa de este impacto se determinará posteriormente mediante las entrevistas y la investigación de los segmentos objetivo.

#### Objetivos

**Corto plazo**

* Identificar y validar las necesidades principales de las empresas de alquiler y de las personas que solicitan maquinaria.
* Diseñar una experiencia digital comprensible para los dos segmentos objetivo.
* Implementar y desplegar la primera versión del Landing Page de MaquiGest.
* Definir las funcionalidades iniciales relacionadas con inventario, disponibilidad, reservas y alquileres.

**Mediano plazo**

* Implementar progresivamente la gestión de contratos, pagos, entregas, devoluciones, incidencias y mantenimiento.
* Integrar la Web Application con el RESTful API desarrollado por el equipo.
* Incorporar un servicio externo que complemente las funcionalidades de la plataforma.
* Mejorar el producto a partir de las entrevistas y validaciones realizadas con los segmentos objetivo.

**Largo plazo**

* Conseguir una adopción recurrente de MaquiGest por parte de pequeñas y medianas empresas del sector.
* Reducir los errores relacionados con reservas, disponibilidad y seguimiento de equipos.
* Incorporar nuevas herramientas de análisis y seguimiento de las operaciones.
* Posicionar MaquiGest como una solución especializada para la gestión del alquiler de maquinaria de construcción.

#### Restricciones

* MaquiGest debe desarrollarse como una solución web distribuida compuesta por un Landing Page, una Web Application y un RESTful API propio.
* La lógica del lado servidor debe desarrollarse con Java y tecnologías open-source, conforme a los lineamientos del curso.
* La plataforma debe integrar al menos un servicio externo de terceros.
* La interfaz debe adaptarse a las dimensiones de computadoras, tabletas y dispositivos móviles.
* La experiencia visual y funcional debe ser consistente entre el Landing Page y la Web Application.
* Los call-to-action del Landing Page deben dirigir a las vistas correspondientes de la Web Application.
* El funcionamiento de la plataforma dependerá de una conexión a Internet para consultar y actualizar la información.
* El alcance de la primera versión debe priorizar las funcionalidades principales que puedan desarrollarse dentro del ciclo académico.
* El código y la documentación deben gestionarse en repositorios públicos de la organización de GitHub de CleanCode.
* El equipo debe aplicar GitFlow y Conventional Commits durante la evolución del proyecto.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.1. User Stories

<table>
<tr>
<th>Epic / Story ID</th>
<th>Título</th>
<th>Descripción</th>
<th>Criterios de Aceptación</th>
<th>Relacionado con</th>
</tr>

<tr>
<td>EP01</td>
<td>Gestión de usuarios y acceso</td>
<td>Epic orientado al registro, autenticación y gestión básica de las cuentas de los usuarios de MaquiGest.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US01</td>
<td>Registro de usuario</td>
<td>Como usuario, quiero registrarme en MaquiGest para acceder a las funcionalidades de la plataforma.</td>
<td>
Given que el usuario accede al formulario de registro<br>
When ingresa sus datos correctamente<br>
Then el sistema crea su cuenta<br>
And muestra un mensaje de confirmación
</td>
<td>EP01</td>
</tr>

<tr>
<td>US02</td>
<td>Inicio de sesión</td>
<td>Como usuario registrado, quiero iniciar sesión para acceder a las funcionalidades correspondientes a mi cuenta.</td>
<td>
Given que el usuario posee una cuenta registrada<br>
When ingresa credenciales válidas<br>
Then el sistema permite el acceso a la plataforma
</td>
<td>EP01</td>
</tr>

<tr>
<td>US03</td>
<td>Gestionar perfil</td>
<td>Como usuario, quiero consultar y actualizar mis datos personales y de contacto para mantener mi información actualizada.</td>
<td>
Given que el usuario ha iniciado sesión<br>
When modifica sus datos de perfil<br>
Then el sistema guarda la información actualizada<br>
And muestra los nuevos datos
</td>
<td>EP01</td>
</tr>

<tr>
<td>EP02</td>
<td>Gestión de maquinaria</td>
<td>Epic orientado al registro, organización y consulta del inventario de maquinaria disponible para alquiler.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US04</td>
<td>Registrar maquinaria</td>
<td>Como empresa de alquiler, quiero registrar mis máquinas y equipos para mantener organizado mi inventario.</td>
<td>
Given que el usuario tiene permisos para gestionar maquinaria<br>
When registra los datos de un equipo<br>
Then el sistema almacena la maquinaria en el inventario<br>
And muestra el equipo registrado
</td>
<td>EP02</td>
</tr>

<tr>
<td>US05</td>
<td>Consultar maquinaria</td>
<td>Como empresa de alquiler, quiero consultar las máquinas registradas para conocer la información de mis equipos.</td>
<td>
Given que existen equipos registrados<br>
When el usuario consulta el inventario<br>
Then el sistema muestra la lista de maquinaria<br>
And muestra información relevante de cada equipo
</td>
<td>EP02</td>
</tr>

<tr>
<td>US06</td>
<td>Actualizar información de maquinaria</td>
<td>Como empresa de alquiler, quiero actualizar la información de mis equipos para mantener el inventario actualizado.</td>
<td>
Given que existe una maquinaria registrada<br>
When el usuario modifica sus datos<br>
Then el sistema guarda la información actualizada
</td>
<td>EP02</td>
</tr>

<tr>
<td>US07</td>
<td>Consultar disponibilidad de maquinaria</td>
<td>Como empresa de alquiler, quiero conocer la disponibilidad de cada equipo para evitar conflictos al gestionar nuevos alquileres.</td>
<td>
Given que existen equipos registrados<br>
When el usuario consulta su disponibilidad<br>
Then el sistema muestra si cada equipo está disponible, reservado o alquilado
</td>
<td>EP02</td>
</tr>

<tr>
<td>US08</td>
<td>Consultar estado de maquinaria</td>
<td>Como empresa de alquiler, quiero conocer el estado de mis equipos para evitar alquilar maquinaria que no se encuentra en condiciones de uso.</td>
<td>
Given que existe una maquinaria registrada<br>
When el usuario consulta su información<br>
Then el sistema muestra su estado actual<br>
And permite identificar si está disponible para alquiler
</td>
<td>EP02</td>
</tr>

<tr>
<td>EP03</td>
<td>Búsqueda y solicitud de alquiler</td>
<td>Epic orientado a permitir que las pequeñas empresas constructoras encuentren maquinaria y gestionen solicitudes de alquiler.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US09</td>
<td>Buscar maquinaria</td>
<td>Como empresa constructora, quiero buscar maquinaria según mis necesidades para encontrar equipos adecuados para mi proyecto.</td>
<td>
Given que el usuario accede al catálogo de maquinaria<br>
When busca o filtra equipos<br>
Then el sistema muestra las maquinarias que coinciden con sus necesidades
</td>
<td>EP03</td>
</tr>

<tr>
<td>US10</td>
<td>Consultar información de maquinaria</td>
<td>Como empresa constructora, quiero consultar las características de una maquinaria para determinar si es adecuada para mi proyecto.</td>
<td>
Given que el usuario visualiza una maquinaria<br>
When selecciona el equipo<br>
Then el sistema muestra sus características, estado y condiciones de alquiler
</td>
<td>EP03</td>
</tr>

<tr>
<td>US11</td>
<td>Consultar disponibilidad para un periodo</td>
<td>Como empresa constructora, quiero consultar la disponibilidad de una maquinaria para un periodo determinado antes de solicitar el alquiler.</td>
<td>
Given que el usuario selecciona una maquinaria y un periodo<br>
When consulta su disponibilidad<br>
Then el sistema indica si el equipo puede ser alquilado durante dicho periodo
</td>
<td>EP03</td>
</tr>

<tr>
<td>US12</td>
<td>Solicitar alquiler de maquinaria</td>
<td>Como empresa constructora, quiero solicitar el alquiler de una maquinaria para utilizarla en mi proyecto.</td>
<td>
Given que la maquinaria está disponible<br>
When el usuario registra una solicitud de alquiler<br>
Then el sistema registra la solicitud<br>
And muestra su estado
</td>
<td>EP03</td>
</tr>

<tr>
<td>EP04</td>
<td>Gestión de reservas y alquileres</td>
<td>Epic orientado a la administración de reservas y al seguimiento del ciclo de alquiler de los equipos.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US13</td>
<td>Gestionar solicitudes de alquiler</td>
<td>Como empresa de alquiler, quiero revisar las solicitudes recibidas para decidir cuáles atender y mantener control sobre mis alquileres.</td>
<td>
Given que existen solicitudes de alquiler<br>
When el usuario consulta las solicitudes<br>
Then el sistema muestra la información de cada solicitud<br>
And permite identificar su estado
</td>
<td>EP04</td>
</tr>

<tr>
<td>US14</td>
<td>Confirmar o rechazar una solicitud</td>
<td>Como empresa de alquiler, quiero aceptar o rechazar solicitudes de alquiler para controlar la disponibilidad de mis equipos.</td>
<td>
Given que existe una solicitud pendiente<br>
When el usuario selecciona aceptar o rechazar<br>
Then el sistema actualiza el estado de la solicitud<br>
And muestra el nuevo estado
</td>
<td>EP04</td>
</tr>

<tr>
<td>US15</td>
<td>Consultar alquileres activos</td>
<td>Como empresa de alquiler, quiero consultar mis alquileres activos para conocer qué equipos están actualmente alquilados.</td>
<td>
Given que existen alquileres activos<br>
When el usuario consulta sus alquileres<br>
Then el sistema muestra los equipos alquilados<br>
And muestra información del periodo correspondiente
</td>
<td>EP04</td>
</tr>

<tr>
<td>US16</td>
<td>Consultar estado de una solicitud de alquiler</td>
<td>Como empresa constructora, quiero consultar el estado de mi solicitud para saber si mi alquiler fue aceptado, rechazado o aún está pendiente.</td>
<td>
Given que el usuario ha realizado una solicitud<br>
When consulta sus solicitudes<br>
Then el sistema muestra el estado actualizado de cada una
</td>
<td>EP04</td>
</tr>

<tr>
<td>US17</td>
<td>Gestionar entregas y devoluciones</td>
<td>Como empresa de alquiler, quiero registrar las entregas y devoluciones de maquinaria para mantener trazabilidad sobre los equipos alquilados.</td>
<td>
Given que existe un alquiler confirmado<br>
When se registra la entrega o devolución<br>
Then el sistema actualiza el estado del alquiler<br>
And registra la operación realizada
</td>
<td>EP04</td>
</tr>

<tr>
<td>EP05</td>
<td>Gestión de mantenimiento e incidencias</td>
<td>Epic orientado al seguimiento del estado operativo de la maquinaria y a la gestión de mantenimientos e incidencias.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US18</td>
<td>Registrar mantenimiento</td>
<td>Como empresa de alquiler, quiero registrar mantenimientos realizados a una maquinaria para mantener un historial de su estado operativo.</td>
<td>
Given que existe una maquinaria registrada<br>
When el usuario registra un mantenimiento<br>
Then el sistema almacena la información<br>
And la relaciona con el equipo correspondiente
</td>
<td>EP05</td>
</tr>

<tr>
<td>US19</td>
<td>Programar mantenimiento</td>
<td>Como empresa de alquiler, quiero programar mantenimientos para evitar que los equipos sean utilizados cuando requieren atención.</td>
<td>
Given que una maquinaria requiere mantenimiento<br>
When el usuario registra una fecha de mantenimiento<br>
Then el sistema guarda la programación<br>
And permite consultar el mantenimiento pendiente
</td>
<td>EP05</td>
</tr>

<tr>
<td>US20</td>
<td>Registrar incidencia de maquinaria</td>
<td>Como empresa de alquiler, quiero registrar incidencias de mis equipos para llevar un control de problemas y reparaciones.</td>
<td>
Given que una maquinaria presenta una incidencia<br>
When el usuario registra el problema<br>
Then el sistema almacena la incidencia<br>
And la relaciona con la maquinaria correspondiente
</td>
<td>EP05</td>
</tr>

<tr>
<td>US21</td>
<td>Consultar historial de maquinaria</td>
<td>Como empresa de alquiler, quiero consultar el historial de una maquinaria para conocer sus alquileres, incidencias y mantenimientos.</td>
<td>
Given que existe una maquinaria registrada<br>
When el usuario consulta su historial<br>
Then el sistema muestra las operaciones asociadas al equipo
</td>
<td>EP05</td>
</tr>

<tr>
<td>EP06</td>
<td>Información y contratación del servicio</td>
<td>Epic orientado a brindar información sobre MaquiGest y facilitar el contacto de potenciales clientes con la plataforma.</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>US22</td>
<td>Consultar información de MaquiGest</td>
<td>Como visitante, quiero conocer las funcionalidades y beneficios de MaquiGest para determinar si la solución se adapta a las necesidades de mi empresa.</td>
<td>
Given que el visitante accede al Landing Page<br>
When revisa la información del producto<br>
Then el sistema muestra sus principales funcionalidades y beneficios
</td>
<td>EP06</td>
</tr>

<tr>
<td>US23</td>
<td>Solicitar demostración</td>
<td>Como potencial cliente, quiero solicitar una demostración de MaquiGest para conocer cómo funciona antes de utilizar el servicio.</td>
<td>
Given que el visitante desea conocer la plataforma<br>
When completa y envía el formulario de demostración<br>
Then el sistema registra la solicitud<br>
And muestra un mensaje de confirmación
</td>
<td>EP06</td>
</tr>

<tr>
<td>US24</td>
<td>Contactar con MaquiGest</td>
<td>Como potencial cliente, quiero contactar con el equipo de MaquiGest para realizar consultas sobre el servicio.</td>
<td>
Given que el visitante accede a la sección de contacto<br>
When completa y envía sus datos y consulta<br>
Then el sistema registra la solicitud de contacto
</td>
<td>EP06</td>
</tr>

</table>

## 3.2. Impact Mapping

## 3.3. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines

Los Style Guidelines establecen los lineamientos visuales utilizados en el diseño de la interfaz, con el propósito de mantener una experiencia coherente y consistente a lo largo del producto digital. 


### 4.1.1. General Style Guidelines

**Branding**: El isotipo de MaquiGest representa la combinación de los dos conceptos principales que conforman el nombre de la plataforma: maquinaria y gestión. Su diseño parte de una forma geométrica inspirada en la inicial “M”, integrando elementos visuales asociados a la maquinaria de construcción. 

<img src = "assets/md-images-isotype/isotypeMaquiGest.png" width = 300px>

**Typography:** Se ha escogido la tipografía Inter debido a su excelente legibilidad, tanto en textos pequeños como en títulos y botones. Además, es una tipografía moderna y profesional, características que se adaptan favorablemente a las necesidades y objetivos de nuestra plataforma. 

<img src = "assets/md-images-typography/inter_typography.png" width = 300px>

**Spacing:** Se establece un sistema de espaciado consistente con el propósito de mantener una interfaz ordenada, legible y visualmente equilibrada. La separación entre textos, botones, campos de formulario, tarjetas y secciones permite diferenciar y agrupar los elementos según su relación, evitando la saturación visual y facilitando el recorrido del contenido. Asimismo, mantener valores de espaciado definidos contribuye a la consistencia entre los diferentes componentes de MaquiGest y favorece su adaptación a distintos tamaños de pantalla.

**Dimensiones (Tonos de voz):** El lenguaje de MaquiGest apunta a una comunicación profesional, clara, directa y orientada a la acción, buscando transmitir confianza y facilitar que los usuarios comprendan rápidamente la información y las acciones disponibles en la plataforma.
- **Enfoque:** Nuestro enfoque es profesional y práctico. Por un lado, es profesional porque buscamos transmitir confianza, seriedad y seguridad en la gestión de las operaciones. Por otro lado, es práctico porque comunicamos soluciones concretas y útiles para las necesidades de nuestros usuarios. De esta manera, evitamos presentar información innecesaria y nos enfocamos en facilitar la realización de las tareas.
- **Lenguaje:** Establecemos un lenguaje claro y directo, priorizando términos conocidos por las empresas del sector de alquiler de maquinaria y construcción. Evitamos tecnicismos innecesarios y utilizamos expresiones sencillas que permitan comprender rápidamente las funciones, instrucciones, mensajes y acciones disponibles en la plataforma.
- **Estilo de comunicación:** Nuestro estilo de comunicación será profesional, cercano y orientado a la acción. Los mensajes serán breves y fáciles de comprender, utilizando verbos que indiquen claramente qué puede hacer el usuario, como registrar, consultar, reservar, alquilar o devolver. Asimismo, los mensajes de confirmación, advertencia y error proporcionarán información concreta para que el usuario pueda comprender la situación y saber qué acción realizar.


### 4.1.2. Web Style Guidelines

1. Diseño Responsivo y Adaptabilidad
- **Adaptación fluida:** El sitio utiliza un sistema de retícula flexible basado en CSS Flexbox y Media Queries. Por un lado, Flexbox permite distribuir y reorganizar los elementos de manera flexible según el espacio disponible; por otro, las Media Queries permiten modificar esta distribución en función del tamaño de la pantalla.
- **Puntos de ruptura (breakpoints):** Se establece un punto de ruptura en 980 px, a partir del cual la navegación cambia de una barra horizontal a un menú vertical optimizado para pantallas de menor tamaño. Asimismo, las tarjetas de servicios (planes) pasan de una disposición en cuadrícula (grid) a una organización vertical.

2. Sistema de Layout y Patrones de Lectura
- **Patrón de lectura:** La Landing Page presenta principalmente un patrón de lectura vertical y centrado, guiado por una clara jerarquía visual. En la sección principal (hero), la atención se dirige desde el encabezado y el título principal hacia la descripción, las llamadas a la acción (CTA) y, posteriormente, los elementos visuales inferiores. Este recorrido favorece una exploración secuencial del contenido y la identificación de las acciones principales. 
- **Jerarquía Visual:** La interfaz establece una jerarquía visual clara mediante variaciones de tamaño, color, contraste, peso tipográfico y espaciado. Los títulos principales reciben mayor protagonismo, seguidos por los textos descriptivos y las llamadas a la acción (CTA). Asimismo, el uso de colores diferenciados permite destacar las acciones prioritarias y orientar al usuario durante el recorrido del contenido. 
3. Elementos Visuales
- **Imágenes:** La identidad visual de la página utiliza dos versiones del logotipo de MaquiGest: una versión en azul oscuro, destinada principalmente a fondos claros, y una versión en blanco, utilizada sobre fondos oscuros para garantizar un contraste y una legibilidad adecuados. 
4. Componentes de Interacción
- **Botón primario (Action):** Botón de color naranja con texto en azul oscuro, utilizado para destacar la acción principal “Solicitar demo”. Al seleccionarlo, dirige al usuario a una sección donde puede completar un formulario con los datos de su empresa para solicitar posteriormente una demostración del funcionamiento de la plataforma. 
- **Enlaces de navegación:** Enlaces ubicados en la barra de navegación superior que permiten dirigir al usuario hacia distintas secciones de la página. Presentan un estado hover que oscurece ligeramente el texto al posicionar el cursor sobre ellos. 
- **Estados visuales:** Cada elemento interactivo cuenta con dos estados claramente definidos: default y hover.
5. Formularios y Entradas de Datos
- **Claridad y visualización:** El formulario de solicitud de demostración presenta una estructura clara y organizada, utilizando distintos tipos de campos según la información requerida: campos de texto, una lista desplegable y un área de texto. Cada campo cuenta con una etiqueta descriptiva y los campos obligatorios se identifican mediante un asterisco (*), mientras que el campo no requerido se señala explícitamente como opcional. Finalmente, el formulario presenta un botón de acción principal claramente diferenciado para enviar la solicitud. 
6. Accesibilidad y Estándares de Calidad:
Se evalúa el cumplimiento de los principios de accesibilidad establecidos por las Web Content Accessibility Guidelines (WCAG): perceptible:  operable, comprensible y robusto. 
- **Perceptible:** El contenido presenta una estructura visual clara, con textos legibles y un contraste adecuado entre los elementos y sus fondos. La información relevante puede distinguirse mediante diferentes recursos visuales, como tamaño, tipografía y color. 
- **Operable:** Los elementos interactivos de la página pueden utilizarse mediante diferentes métodos de entrada. La navegación mediante teclado permite recorrer enlaces, botones y campos de formulario, facilitando la interacción sin depender exclusivamente del mouse. 
- **Comprensible:** La interfaz utiliza textos, etiquetas y acciones claramente identificables. Los formularios indican los campos obligatorios y opcionales, mientras que la organización y comportamiento de los componentes permiten al usuario comprender las acciones disponibles. 
- **Robusto:** El código utiliza correctamente elementos HTML semánticos y componentes apropiados según su función, favoreciendo una correcta interpretación del contenido por navegadores y tecnologías de asistencia. 

## 4.2. Information Architecture

Para el desarrollo del proyecto, la Arquitectura de la Información se plantea considerando las necesidades de los usuarios y la estructura del contenido de la plataforma. Esto permite establecer una organización coherente de las funcionalidades y reducir la complejidad durante la navegación e interacción con el sistema. 

### 4.2.1. Organization Systems

**Organización jerárquica visual:** Empecemos con la vista de nuestro segmento principal: las empresas de alquiler de maquinaria. En la parte lateral de la plataforma se encontrarán las siguientes opciones de navegación: Dashboard, Equipos, Reservas, Alquileres, Mantenimiento, Clientes y Reportes.
Al ingresar a la plataforma, el usuario se encontrará en la sección Dashboard, donde podrá visualizar y monitorear información relevante, como la cantidad de equipos disponibles, equipos alquilados, equipos en mantenimiento y próximas reservas. Asimismo, en esta sección se encontrarán las principales acciones que puede realizar el usuario, como registrar un equipo, crear una reserva y registrar un alquiler.
Además, en la parte inferior del Dashboard se visualizarán las próximas reservas, los alquileres activos, los equipos que requieren mantenimiento y la actividad reciente, permitiendo al usuario tener una visión general del estado de sus operaciones.
Continuamos con la vista de nuestro segundo segmento: las pequeñas empresas constructoras. En la parte lateral de la plataforma se encontrarán las siguientes opciones de navegación: Dashboard, Buscar equipos, Mis reservas, Mis alquileres y Perfil.
Al ingresar a la plataforma, el usuario se encontrará en la sección Dashboard, donde podrá visualizar información relevante sobre sus alquileres, como las reservas próximas, los alquileres activos y las fechas de devolución. De esta manera, podrá conocer rápidamente el estado de los equipos que está utilizando en sus proyectos.
Asimismo, en esta sección se encontrarán las principales acciones que puede realizar el usuario, como buscar maquinaria, realizar una solicitud de alquiler y consultar sus alquileres activos.
Debajo de estas acciones se visualizará información complementaria, como las reservas próximas, los alquileres activos, las fechas de devolución y la actividad reciente, permitiendo al usuario tener una visión general de los equipos que tiene reservados o actualmente en alquiler.

**Organización Secuencial:** Para la organización secuencial del segmento de empresas de alquiler de maquinaria, se ha definido un flujo basado en el ciclo de gestión de los equipos dentro de MaquiGest. El proceso comienza con el registro de la maquinaria, donde se ingresan sus principales características y datos de identificación.
Una vez registrado el equipo, el usuario puede consultar su disponibilidad y, cuando un cliente solicita la maquinaria, crear una reserva para un período determinado. Posteriormente, la reserva puede convertirse en un alquiler, dando paso a las acciones relacionadas con la entrega del equipo.
Durante el alquiler, la empresa podrá consultar el estado de la operación y, cuando finalice el período establecido, registrar la devolución de la maquinaria. Después de la devolución, se realizará una inspección del equipo para verificar su estado. Si se detecta algún daño o se requiere mantenimiento, la maquinaria pasará al proceso correspondiente; de lo contrario, podrá volver a estar disponible para un nuevo alquiler.
De esta manera, la organización secuencial permite que el usuario siga un flujo lógico y ordenado, acompañando el ciclo de vida de la maquinaria desde su registro hasta su disponibilidad nuevamente, reduciendo la necesidad de realizar procesos desconectados entre diferentes secciones de la plataforma.

**Organización matricial:** En la sección de Equipos, los usuarios podrán visualizar la información de las maquinarias registradas mediante una estructura matricial. Cada equipo se mostrará en una fila y sus principales características se organizarán en diferentes columnas, como nombre o código del equipo, categoría, estado, ubicación, disponibilidad y acciones.
Esta organización permitirá que los usuarios puedan consultar, comparar y gestionar rápidamente los diferentes equipos registrados en la plataforma sin necesidad de acceder individualmente a cada uno. Asimismo, se podrán aplicar filtros para facilitar la búsqueda de una maquinaria específica según su estado, categoría o disponibilidad.
De esta manera, la organización matricial permitirá presentar una gran cantidad de información de forma estructurada, facilitando la consulta y gestión del inventario de maquinaria.

**Sistemas de categorización:**
- Por tópicos: Equipos, Reservas, Alquileres, Mantenimiento, Clientes y Reportes.
- Por audiencia: Se presenta diferente información y funciones a las empresas de alquiler y pequeñas empresas constructoras. 


### 4.2.2. Labeling Systems

**Etiquetas para la navegación principal:** 
- Dashboard: Vista general del estado de los equipos, reservas, alquileres y mantenimiento. 
- Equipos: Permite registrar, consultar y administrar las maquinarias disponibles en la empresa. 
- Reservas: Permite gestionar las solicitudes y reservas de equipos para determinados períodos. 
- Alquileres: Permite administrar los alquileres activos, sus detalles y su estado. 
- Mantenimiento: Permite registrar inspecciones, mantenimientos, incidencias y reparaciones de los equipos. 
- Clientes: Permite registrar y consultar la información de las empresas o personas que alquilan los equipos.
- Reportes: Permite consultar información resumida sobre alquileres, utilización de equipos, ingresos y mantenimiento.

**Etiquetas para acciones:**
- Registrar equipo: Permite agregar una nueva maquinaria al inventario.
Editar equipo: Permite modificar la información de una maquinaria registrada.
- Crear reserva: Permite apartar un equipo para un período determinado.
- Confirmar reserva: Permite confirmar una reserva solicitada por un cliente.
- Registrar alquiler: Permite iniciar y registrar formalmente un nuevo alquiler.
- Registrar entrega: Permite registrar la entrega del equipo al cliente.
- Registrar devolución: Permite registrar el retorno de la maquinaria.
- Registrar mantenimiento: Permite registrar una actividad de mantenimiento para un equipo. 
- Registrar incidencia: Permite registrar daños, fallas u otros problemas detectados en un equipo. 
Ver detalles: Permite consultar toda la información relacionada con un registro.
- Editar: Permite modificar la información de un registro.
- Eliminar: Permite eliminar un registro cuando corresponda.

### 4.2.3. SEO Tags and Meta Tags
- Titulo:
```html
<title>MaquiGest | Gestión de alquiler de maquinaria</title>
```

- Descripción:
```html
<meta name="description" content="Gestiona el alquiler de maquinaria para construcción en un solo lugar. Controla equipos, reservas, alquileres, mantenimiento y operaciones con MaquiGest."> 
```

- Palabras clave (keywords):
```html
<meta name="keywords" content="alquiler de maquinaria, gestión de maquinaria, alquiler de equipos, maquinaria para construcción, software de alquiler, gestión de alquileres, MaquiGest"> 
```

- Autor:
```html
<meta name="author" content="CleanCode"> 
```
### 4.2.4. Searching Systems

- **Sistema de búsqueda local:** Dentro de la sección “Equipos”, se dispone de una barra de búsqueda que permite localizar equipos mediante su nombre, código o categoría. Adicionalmente, se incorporan filtros que permiten refinar los resultados según categoría, estado y ubicación.

### 4.2.5. Navigation Systems

- **Sistema de navegación global:** Se implementa mediante una barra lateral (sidebar) que permite al usuario acceder a las principales secciones del sistema, como Dashboard, Equipos, Reservas, Alquileres, Mantenimiento, Clientes y Reportes.
- **Botones de Acción Rápida:** Botones “Registrar Equipo” y “Crear Reserva” ubicados en el Dashboard, que permiten acceder directamente a procesos frecuentes.


## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones

## Conclusiones y recomendaciones

# Bibliografía

# Anexos