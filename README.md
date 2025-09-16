<h3 align="center"> Universidad Peruana de Ciencias Aplicadas <h3 align="center">

![UPC](img/commons/logoUpc.png) 

<h3 align="center"> Ingeniería de Software </h3>
<h3 align="center"> Ciclo 2025 - 2 </h3>


# Informe del Trabajo Final (TB1)  

<h3 align="center"> Aplicaciones Web</h3>
<h3 align="center"> Sección: 7452  </h3>
<h3 align="center"> Docente: Mori Paiva, Hugo Allan </h3>
<h3> Startup: DaL Company </h3>
<h3> Product: BusTrack </h3>
<div align="center">

| Member                           |    Code    |
| :------------------------------- | :--------: |
| Fátima Belén Florez Shimabukuro | U202320610 |
| Mathias Andree Cardenas Huaman | U202316353 |
| Elizabeth Noelia Apaza Bocanegra | U20231c197 |
| Diego Andres Avalos Cordova | U202313922 |
| Joaquin Alberto Cuentas Peña | U20201f788 |

</div>

<h3 align="center">Septiembre, 2025</h3>

<br><br>

# Registro de Versiones del Informe

<div align="center">

| Versión | Fecha | Autor | Descripción de modificación |
| :-----: | :---: | :---: | :-------------------------- |
| TB1 | 14/09 |

</div>

<br><br>

# Project Report Collaboration Insights

<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción-1)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)

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
- [2.4. Big Picture Event Storning](#24-big-picture-event-storning)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)
 
### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)

- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design-1)

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
  - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment-1)

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
- [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4. Video About the Product](#534-video-about-the-product)

<br><br>
# Student Outcome

<div align="center">

### ABET – EAC - Student Outcome 5

| Criterio específico                                                                                                                                 | Acciones realizadas | Conclusiones |
| :-------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------ | :----------- |
| ¿Participó activamente en el equipo, respetando y valorando las ideas de los demás? | | |
| ¿Asumió y cumplió con sus responsabilidades y tareas asignadas dentro de los plazos? | | |
| ¿Se comunicó de manera clara y constructiva, aportando al logro de los objetivos del equipo? | | |

</div>
<br><br>

## Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Description de la StartUp

Descripción del producto: BusTrack es una plataforma web que ofrece información confiable y actualizada sobre rutas, horarios y tiempos de llegada de buses y transporte público en áreas urbanas de Lima Metropolitana. Los usuarios pueden buscar rutas, guardar trayectos frecuentes y recibir notificaciones en tiempo real sobre la llegada de los buses. Además, la aplicación incorpora servicios de mapas y APIs externas para brindar estimaciones más precisas de los tiempos de viaje, mejorando la planificación diaria de movilidad. Está especialmente diseñada para estudiantes y trabajadores que dependen del transporte público en zonas urbanas, facilitando sus viajes diarios y ofreciéndoles una experiencia más eficiente y agradable.

- Misión: Nuestra misión es desarrollar una plataforma web que optimice la experiencia del transporte público urbano, ofreciendo información precisa, en tiempo real y adaptada a las necesidades de estudiantes y trabajadores.

- Visión: Nuestra visión es contribuir a que el transporte público en el Perú sea más eficaz, seguro y accesible, reduciendo los tiempos de espera en zonas urbanas y mejorando la calidad de vida de los ciudadanos que dependen de este servicio.


### 1.1.2. Perfiles de integrantes del equipo

| Perfil | Alumno |
|--------|-------------|
|  | Nombre: Mathias Andree Cárdenas Huaman Código: U202316353 Descripción: Actualmente estoy cursando el quinto ciclo de la carrera de Ingeniería de Software. Soy proactivo y comunicativo, trabajo en equipo y resolución de problemas, también me gusta colocarme objetivos desafiantes para mejorar. Me encanta el curso y mi meta es completarla con la máxima nota posible. |
|  |  |
|  |  |
|  |  |
|  |  |


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El transporte urbano en Lima Metropolitana se ha convertido, en los últimos años, en uno de los problemas más críticos de la ciudad, evidenciando deficiencias tanto en seguridad vial como en eficiencia del servicio. En 2023 se registraron 41,627 accidentes de tránsito, lo que representó un aumento del 10.2 % respecto al año anterior (ComexPerú, 2024). Además, Lima ocupa el quinto lugar en el ranking mundial de ciudades con peor tráfico, según el índice TomTom, un estudio internacional que mide la congestión vehicular en más de 380 ciudades del mundo. Esta situación tiene un impacto significativo en la calidad de vida de los limeños, que en su mayoría dependen de un transporte poco confiable: el 34.4 % se moviliza en coasters o combis y el 42.2 % de los usuarios se siente insatisfecho con el servicio (ComexPerú, 2024).

Por otro lado, la magnitud del sistema de transporte en la capital evidencia la complejidad del problema. Según la ATU, en Lima y Callao se realizan diariamente 24 millones de viajes, de los cuales el 87 % es cubierto por el transporte público convencional, que opera mediante 507 rutas y una flota de 22,000 vehículos. En contraste, solo el 12.1 % corresponde a sistemas formales como los corredores complementarios, el Metro de Lima y el Metropolitano (Gob.pe, 2024). Para afrontar esta situación, la ATU ha iniciado un proceso de reorganización de rutas y renovación gradual de la flota, promoviendo el uso de buses híbridos, eléctricos y a gas natural. Sin embargo, estos avances resultan insuficientes frente a la creciente demanda y el predominio del transporte informal, lo que mantiene el descontento ciudadano y refuerza la urgencia de implementar soluciones tecnológicas innovadoras que permitan mejorar la movilidad urbana. 

En este contexto, surge BusTrack como una propuesta tecnológica orientada a optimizar la planificación y experiencia de viaje de los usuarios, respondiendo a la urgencia de contar con soluciones innovadoras y confiables.

Para la elaboración de la descripción de los antecedentes y problemática, hemos aplicado la técnica de The 5´W´s y 2´H´s - Who, What, Where, When, Why, How & How Much: 

- **What (Qué):** El problema principal es la ineficiencia del sistema de transporte urbano en Lima Metropolitana, reflejada en altos índices de accidentes de tránsito, congestión vehicular e insatisfacción ciudadana. La mayoría de los viajes se realizan en sistemas convencionales con baja regulación, lo que genera inseguridad, informalidad y demoras constantes.

- **When (Cuándo):**  El problema se presenta a diario, especialmente en horas punta, cuando la congestión vehicular alcanza niveles críticos y los limeños enfrentan largas esperas para llegar a sus destinos.

- **Where (Dónde):**  La problemática se concentra en Lima Metropolitana y el Callao, zonas con alta densidad poblacional y más de 507 rutas de transporte convencional. La infraestructura vial es insuficiente y los sistemas formales, como el Metropolitano, los corredores complementarios y el Metro, solo cubren el 12.1 % de la demanda.

- **Who (Quién):**  El problema afecta principalmente a estudiantes y trabajadores que dependen de combis, coasters y buses convencionales, así como a la ciudadanía en general, que sufre las consecuencias en términos de tiempo perdido, inseguridad y menor productividad.

- **Why (Por qué):**  Este problema ocurre debido a la dependencia excesiva del transporte convencional, la superposición de rutas y la incapacidad de los sistemas formales de cubrir la demanda existente.

- **How (Cómo):** Los usuarios enfrentan largas esperas, vehículos inseguros y viajes en condiciones de exceso de pasajeros, donde los buses circulan sobrecargados y sin garantizar comodidad ni seguridad. La congestión incrementa los tiempos de desplazamiento y provoca un mayor número de accidentes. La falta de fiscalización permite que colectivos y unidades informales circulen sin controles técnicos ni seguros, elevando el riesgo para los pasajeros.

- **How much (Cuánto costará):** El impacto es considerable ya que cada limeño pierde en promedio 157 horas al año en congestión vehicular y la ciudad registra más de 41,000 accidentes de tránsito anuales. Además, estos problemas generan costos económicos, sociales y ambientales que afectan directamente la calidad de vida de los ciudadanos.


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

# 1.3. Segmentos Objetivo

<br><br>

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

| Tarea / Funcionalidad                | Estudiante | Trabajador | Adulto mayor | Turista |
|--------------------------------------|------------|------------|--------------|---------|
| Consultar rutas y horarios           | Alta       | Alta       | Alta         | Alta    |
| Recibir notificaciones en tiempo real| Alta       | Alta       | Media        | Media   |
| Guardar trayectos frecuentes         | Alta       | Alta       | Media        | Baja    |
| Revisar estimaciones según tráfico   | Media      | Alta       | Baja         | Media   |
| Identificar paraderos cercanos       | Media      | Media      | Alta         | Alta    |
| Alertas de seguridad en paraderos    | Media      | Media      | Alta         | Media   |
| Consultar rutas hacia puntos turísticos | Baja    | Baja       | Baja         | Alta    |
| Administración de datos (rol admin)  | Baja       | Baja       | Baja         | Baja    |

En el User Task Matrix pudimos ver que cada grupo de usuarios tiene prioridades distintas: estudiantes y trabajadores buscan sobre todo rapidez e información en tiempo real; los adultos mayores se enfocan más en la seguridad y paraderos cercanos; y los turistas necesitan rutas claras hacia lugares de interés. Aunque las tareas administrativas no se notan directamente, son clave para mantener la información confiable. En general, BusTrack debe centrarse en ofrecer datos precisos, opciones personalizadas y una experiencia segura para todos.

### 2.3.3. User Journey Mapping

| Journey Phases        | Acción                                                   | Herramientas/Canales              | Emoción           | Punto de Dolor                                  |
|------------------------|----------------------------------------------------------|-----------------------------------|------------------|------------------------------------------------|
| Identificación de Necesidad | Se da cuenta de que necesita llegar a clases a tiempo  | Reloj, calendario personal         | Ansioso          | Desconoce horarios y frecuencia de buses        |
| Búsqueda de Información | Abre BusTrack y consulta rutas y horarios                | BusTrack web/app                   | Esperanzado      | Puede encontrar info incompleta o confusa       |
| Planificación del Viaje | Guarda su ruta frecuente y revisa el tiempo estimado     | Función de favoritos, notificaciones | Tranquilo        | Estimaciones pueden no ser totalmente precisas  |
| Espera en Paradero     | Llega al paradero y revisa notificación de llegada        | BusTrack en el celular             | Impaciente       | El bus se retrasa o no coincide con la app      |
| Viaje en Bus           | Revisa en tiempo real la ubicación y tiempo restante      | BusTrack GPS + mapas               | Confiado         | No siempre hay señal estable de GPS o internet  |
| Llegada al Destino     | Llega a la universidad a tiempo                          | Confirmación visual en la app      | Satisfecho       | Si hubo retraso, llega con estrés o cansancio   |

### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storning

## 2.5. Ubiquitous Language

<br><br>

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.2. Impact Mapping

## 3.3. Product Backlog

<br><br>

# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

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

### 4.7.2. Class Dictionary

## 4.8. Database Design

### 4.8.1. Database Diagram

<br><br>

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

## 5.3. Validation Interviews 

### 5.3.1. Diseño de entrevistas
### 5.3.2. Registro de entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-The-Product

<br><br>

# Conclusiones

## Conclusiones y recomendaciones

<br><br>

# Bibliografía

<br><br>

# Anexos
