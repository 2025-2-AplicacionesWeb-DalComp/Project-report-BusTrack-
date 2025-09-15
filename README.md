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

| Perfil | Descripción |
|--------|-------------|
|  |  |
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

El proceso Lean UX se adapta especialmente bien a Bustrack, una solución digital que busca mejorar la movilidad urbana mediante información en tiempo real sobre el transporte público. Este enfoque prioriza la validación continua con los usuarios, la experimentación y la construcción rápida de prototipos que permiten comprobar si realmente estamos resolviendo problemas reales.

En ciudades como Lima Metropolitana, donde el transporte público se caracteriza por la saturación, la informalidad y la falta de información confiable, implementar un sistema ágil y centrado en el usuario resulta clave para generar confianza. Según la Autoridad de Transporte Urbano (ATU, 2023), el tiempo promedio de viaje en hora punta puede superar los 45 minutos, reflejando las deficiencias en planificación y eficiencia del sistema. Asimismo, apenas un 16.6 % de los pasajeros está satisfecho con el servicio de buses, coasters y combis (Red Desarrollo, 2023).

En este contexto, Bustrack aplica el Lean UX para ofrecer una solución tecnológica centrada en los usuarios: pasajeros que necesitan certezas en sus desplazamientos y operadores que buscan herramientas de gestión más eficientes.

#### 1.2.2.1. Lean UX Problem Statements

Los pasajeros de transporte público en Lima enfrentan incertidumbre diaria: no saben con precisión cuánto demorará en llegar un bus ni cuánto tiempo tomará el viaje. Esta falta de información genera estrés, pérdida de productividad y, en muchos casos, el uso de alternativas más costosas o inseguras.

A la par, las empresas de transporte carecen de herramientas para monitorear sus unidades en tiempo real, lo que impide mejorar el servicio y reduce la confianza de los usuarios.

Bustrack propone una solución que centraliza información en tiempo real sobre la ubicación de los buses, estimaciones precisas de llegada, rutas actualizadas y notificaciones de seguridad. A diferencia de las redes sociales o aplicaciones genéricas de mapas, nuestra plataforma está diseñada específicamente para las condiciones del transporte urbano local, generando confianza y seguridad en los usuarios.

Pregunta clave de diseño:
¿Cómo podemos desarrollar una plataforma que no solo brinde datos en tiempo real sobre el transporte público, sino que también aumente la confianza y reduzca la incertidumbre en los desplazamientos diarios?

#### 1.2.2.2. Lean UX Assumptions

# Supuestos principales para Bustrack

- Creemos que los pasajeros usarán la app de manera recurrente si la información de tiempos y rutas es precisa y confiable.  
- Creemos que los operadores de transporte adoptarán la plataforma si esta les permite monitorear flotas y mejorar la satisfacción del cliente.  
- Creemos que la confianza de los usuarios se fortalecerá mediante transparencia en los datos y notificaciones claras sobre retrasos o cambios de ruta.  
- Suponemos que la falta de información confiable es la principal causa de insatisfacción con el transporte público.  
- Asumimos que la implementación de herramientas tecnológicas puede contribuir a reducir la percepción de inseguridad al brindar alternativas claras y ordenadas de movilidad.  

---

## ¿Quién es el usuario?

**Primarios:**  
- Pasajeros frecuentes (estudiantes, trabajadores, familias).  

**Secundarios:**  
- Empresas de transporte que necesitan gestionar sus unidades.  

---

## Business Outcomes esperados

- Conseguir **50,000 usuarios activos** en el primer año.  
- Reducir en un **30% la percepción de incertidumbre** en los tiempos de espera.  
- Lograr que el **70% de las rutas principales** estén integradas en la app.  
- Aumentar en un **20% la satisfacción general** de los pasajeros en encuestas de movilidad urbana.  

---

## User Outcomes esperados

- Los pasajeros planifican sus viajes con mayor confianza y menos estrés.  
- Los operadores optimizan el control de sus flotas y mejoran su reputación.  

#### 1.2.2.3. Lean UX Hypothesis Statements

# Hipótesis y criterios de validación para Bustrack

## 1. Geolocalización en tiempo real
- **Hipótesis:** Creemos que implementar un sistema de geolocalización en tiempo real de las unidades de transporte aumentará la confianza de los usuarios.  
- **Validación:** Sabremos que esto es cierto cuando observemos un **incremento en el uso recurrente de la aplicación dentro del primer mes** de lanzamiento.  

---

## 2. Notificaciones de llegada
- **Hipótesis:** Creemos que ofrecer notificaciones sobre la llegada de los buses reducirá el tiempo de espera percibido.  
- **Validación:** Sabremos que esto es cierto cuando **al menos el 60% de los usuarios reporten una disminución en su frustración** relacionada a los tiempos de espera.  

---

## 3. Interfaz intuitiva y accesible
- **Hipótesis:** Creemos que la incorporación de una interfaz intuitiva, simple y accesible facilitará la adopción tecnológica en distintos grupos de edad.  
- **Validación:** Sabremos que esto es cierto cuando **el 70% de los usuarios, independientemente de su rango etario, puedan completar las funciones principales sin necesidad de soporte**.  

---

## 4. Calificaciones de rutas y unidades
- **Hipótesis:** Creemos que permitir a los usuarios calificar las rutas y unidades fomentará la mejora del servicio por parte de las empresas de transporte.  
- **Validación:** Sabremos que esto es cierto cuando se registren **al menos 200 calificaciones en el primer trimestre**, y las empresas implementen mejoras a partir de esos datos.  

---

## 5. Historial de rutas frecuentes
- **Hipótesis:** Creemos que integrar un sistema de historial de rutas frecuentes aumentará la retención de usuarios.  
- **Validación:** Sabremos que esto es cierto cuando **el 50% de los usuarios registrados utilicen esta funcionalidad al menos una vez por semana**.  

#### 1.2.2.4. Lean UX Canvas

# Bustrack - Lean UX Canvas

| **Sección** | **Contenido** |
|-------------|---------------|
| **Business Problem** | Los usuarios del transporte público en Lima Metropolitana enfrentan largos tiempos de espera, desinformación sobre los horarios y baja confianza en la puntualidad de las unidades. Esto genera frustración, pérdidas de tiempo y afecta la percepción de seguridad en el servicio. Al mismo tiempo, las empresas de transporte carecen de herramientas digitales que les permitan organizar mejor sus unidades y comunicarse eficazmente con los pasajeros. |
| **Business Outcomes** | - Conseguir 50,000 usuarios activos en el primer año.<br>- Reducir en un 30% la percepción de incertidumbre en los tiempos de espera.<br>- Lograr que el 70% de las rutas principales estén integradas en la app.<br>- Aumentar en un 20% la satisfacción general de los pasajeros en encuestas de movilidad urbana. |
| **Users and Customers** | **Primarios:** Pasajeros que utilizan transporte público a diario.<br>**Secundarios:** Empresas de transporte. |
| **User Benefits** | - Pasajeros: Mayor confianza, reducción de tiempos de espera y mejor planificación.<br>- Empresas: Mejor gestión de flota, mayor satisfacción del cliente. |
| **Solution Ideas** | - Geolocalización en tiempo real de buses.<br>- Estimaciones precisas de llegada.<br>- Mapas interactivos con rutas alternativas.<br>- Notificaciones sobre retrasos y cambios.<br>- Panel de control para empresas de transporte. |
| **Hypotheses** | - Creemos que mostrar buses en tiempo real aumentará la confianza.<br>- Creemos que enviar notificaciones sobre retrasos mejorará la satisfacción.<br>- Creemos que integrar empresas de transporte reducirá los errores en la información. |
| **What's the most important thing we need to learn first?** | ¿Los pasajeros confían y usan de forma recurrente la información en tiempo real para planificar sus viajes? |
| **What’s the least amount of work we need to do to learn the next most important thing?** | MVP: Una app funcional con mapa de rutas principales, localización en tiempo real en una zona piloto y sistema básico de notificaciones. Validar si los usuarios usan la app en sus trayectos diarios. |


# 1.3. Segmentos Objetivo

# Segmentos Objetivo

## Segmento Objetivo #1: Pasajeros de Transporte Público (Estudiantes y Trabajadores)

### Aspectos demográficos
- Sexo: Masculino y femenino  
- Edades: Jóvenes y adultos entre 18 y 50 años  

### Aspectos geográficos
- Nacionalidad: Peruana  
- Zona geográfica: Principalmente Lima Metropolitana y Callao, donde se concentra el 87 % de los viajes en transporte convencional.  
- También con potencial en ciudades intermedias como Arequipa, Trujillo y Chiclayo.  

### Aspectos psicográficos
- Personas que dependen del transporte público como su principal medio de movilidad.  
- Buscan reducir la incertidumbre, los tiempos de espera y la inseguridad en sus trayectos diarios.  
- Valoran aplicaciones fáciles de usar, con información confiable y en tiempo real.  
- Su motivación principal es la puntualidad y la eficiencia para llegar a sus destinos, ya sea clases o centros laborales.  

---

## Segmento Objetivo #2: Empresas de Transporte Urbano (Operadores y Administradores de Flota)

### Aspectos demográficos
- Tipo de entidad: Empresas medianas y grandes que operan buses, coasters o combis.  
- Personal involucrado: Administradores de rutas, supervisores y propietarios de líneas.  

### Aspectos geográficos
- Ubicación: Lima Metropolitana y Callao, con posibilidad de expansión a otras ciudades de alta demanda.  

### Aspectos psicográficos
- Buscan herramientas tecnológicas que permitan optimizar la gestión de flotas y mejorar la eficiencia operativa.  
- Necesitan fortalecer la confianza de los pasajeros mediante transparencia en horarios, puntualidad y seguridad.  
- Están interesados en soluciones que integren datos de movilidad y faciliten la toma de decisiones.  
- Su motivación principal es mejorar la reputación, competitividad y rentabilidad en un mercado dominado por el transporte informal.  

<br><br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

Como parte del proceso de validación del modelo de negocio de BusTrack, se plantean entrevistas semiestructuradas dirigidas a los dos segmentos objetivos: pasajeros de transporte público y empresas de transporte urbano. El propósito es identificar sus motivaciones, comportamientos, expectativas y principales frustraciones en relación con la movilidad urbana, así como validar la propuesta de valor de la plataforma.

### 2.2.1. Diseño de entrevistas

## Segmento 1: Pasajeros de Transporte Público

### Datos generales
- Nombre  
- Edad  
- Distrito de residencia  
- Ocupación (estudiante, trabajador, etc.)  
- Frecuencia de uso del transporte público (diaria, varias veces por semana, esporádica)  

### Motivaciones y comportamientos
- ¿Qué medio de transporte público usas con más frecuencia (bus, coaster, combi, Metropolitano, Metro)?  
- ¿Qué es lo que más te preocupa cuando viajas en transporte público?  
- ¿Cómo planificas actualmente tus viajes?  
- ¿Has usado alguna aplicación para movilizarte en la ciudad (Waze, Google Maps, Moovit, etc.)? ¿Cómo fue tu experiencia?  
- ¿Qué importancia le das a recibir información en tiempo real sobre la llegada de buses?  

### Miedos, expectativas y canales
- ¿Qué problemas enfrentas con mayor frecuencia en tus traslados (tiempo de espera, congestión, inseguridad, falta de información)?  
- ¿Qué haría que confíes en una aplicación como BusTrack para planificar tus viajes?  
- ¿Te gustaría recibir notificaciones sobre la llegada del bus, retrasos o desvíos de ruta?  
- ¿Qué redes sociales o aplicaciones móviles usas más para informarte en tu día a día?  
- ¿Cómo medirías que una aplicación realmente mejora tu experiencia de viaje?  

---

## Segmento 2: Empresas de Transporte Urbano

### Datos generales
- Nombre del entrevistado  
- Cargo (administrador, supervisor de rutas, propietario)  
- Empresa / línea de transporte  
- Número de unidades en operación  
- Zonas o rutas que cubren  

### Operaciones y herramientas
- ¿Cómo gestionan actualmente la ubicación y monitoreo de sus unidades?  
- ¿Qué herramientas digitales o manuales utilizan para el control de flotas?  
- ¿Qué información reciben de los conductores y cómo la gestionan?  
- ¿Han usado o considerado alguna aplicación para interactuar con pasajeros?  
- ¿Cuáles son los mayores retos para mantener la puntualidad y la seguridad de los viajes?  

### Expectativas y valor esperado
- ¿Qué tipo de datos o reportes serían más valiosos para su gestión diaria (tiempos de llegada, cantidad de pasajeros, retrasos)?  
- ¿Qué funcionalidades de una aplicación como BusTrack les motivarían a adoptarla?  
- ¿Cómo creen que una plataforma de información en tiempo real podría mejorar la confianza de los pasajeros?  
- ¿Qué beneficios esperan obtener al implementar una solución tecnológica (mayor satisfacción, competitividad, reducción de costos)?  
- ¿Qué barreras ven para adoptar una aplicación digital de gestión de transporte?  

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas 

## Segmento Objetivo 1: Pasajeros de Transporte Público

| **Atributo**     | **Valor** |
|------------------|-----------|
| **Name**         | Manuel Suarez |
| **Age**          | 29 años |
| **Occupation**   | Trabajo de oficina |
| **Status**       | Soltero |
| **Location**     | Lima, Perú |
| **Tier**         | Pasajero frecuente |
| **Archetype**    | Usuario Pragmático |
| **Image**        | ![Manuel Suarez](img/commons/manuelSuarez.png) |
| **Quote**        | "Lo que más necesito es saber con certeza cuándo llegará el bus para no perder tiempo ni arriesgarme." |
| **Motivations**  | Incentive: 80/100<br>Fear: 70/100<br>Achievement: 75/100<br>Growth: 65/100<br>Power: 40/100<br>Social: 85/100 |
| **Goals**        | - Planificar viajes con menor incertidumbre.<br>- Ahorrar tiempo en traslados.<br>- Sentirse más seguro en sus trayectos diarios. |
| **Frustrations** | - No saber cuándo pasará el bus.<br>- Pérdida de tiempo en paraderos inseguros.<br>- Información poco confiable en apps genéricas. |
| **Biography**    | Manuel viaja dos veces al día en transporte público para ir a su trabajo en el centro de Lima. Gasta en promedio más de 1 hora diaria en esperas. Ha probado apps de mapas, pero no le resultan útiles porque no están adaptadas al sistema de transporte local. Busca una solución confiable y sencilla que le permita organizar mejor su día. |
| **Personality**  | Extrovert: 60/100<br>Thinking: 80/100<br>Judging: 70/100 |
| **Technology**   | IT and Internet: 85/100<br>Software: 70/100<br>Mobile Apps: 90/100<br>Social Networks: 95/100 |
| **Brands**       | WhatsApp, Google Maps, TikTok |

---

## Segmento Objetivo 2: Empresas de Transporte Urbano

| **Atributo**     | **Valor** |
|------------------|-----------|
| **Name**         | Rosa Palacios |
| **Age**          | 45 años |
| **Occupation**   | Administradora de empresas de transporte |
| **Status**       | Casada |
| **Location**     | Lima, Perú |
| **Tier**         | Empresa de transporte urbano |
| **Archetype**    | Gestora Eficiente |
| **Image**        | ![Rosa Palacios](.....) |
| **Quote**        | "Si puedo monitorear mis buses en tiempo real, puedo ofrecer un mejor servicio y ganar más pasajeros." |
| **Motivations**  | Incentive: 85/100<br>Fear: 60/100<br>Achievement: 90/100<br>Growth: 80/100<br>Power: 75/100<br>Social: 70/100 |
| **Goals**        | - Monitorear las unidades en tiempo real.<br>- Mejorar la puntualidad y satisfacción del cliente.<br>- Optimizar costos operativos. |
| **Frustrations** | - No contar con datos centralizados.<br>- Reclamaciones frecuentes por retrasos.<br>- Falta de herramientas tecnológicas para competir con apps modernas. |
| **Biography**    | Rosa administra una empresa con 20 buses en Lima. Actualmente depende de llamadas de choferes para conocer incidencias, lo que le genera pérdidas de tiempo y poca precisión. Está interesada en adoptar soluciones digitales que le den control, transparencia y ventaja competitiva en el mercado. |
| **Personality**  | Extrovert: 65/100<br>Thinking: 85/100<br>Judging: 75/100 |
| **Technology**   | IT and Internet: 75/100<br>Software: 65/100<br>Mobile Apps: 70/100<br>Social Networks: 60/100 |
| **Brands**       | WhatsApp Business, Facebook, LinkedIn |

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

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
