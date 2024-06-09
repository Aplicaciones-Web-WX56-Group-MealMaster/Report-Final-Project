# UPC
# INGENIERÍA DE SOFTWARE
## CURSO: SI730 Aplicaciones Web | SECCIÓN WX56 
 Profesor: Alex Humberto Sánchez Ponce
# Informe de Trabajo Final

"MealMaster"
### Integrantes:
- Cortés Casas, Joaquin Marcelo U202114545
- Diaz Silva, Fernando Josué U202112722
- Chávez Rojas, Carlos Raúl Guillermo U201910317
- Ruiz Blas, Luciano U20211F978
- Becerra Llempen, Fabiola U20171A518

---

Abril, 2024-1

# Contenido



[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup) 

[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo]()  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)  

[3.2. User Stories](#32-user-stories)  

[3.3. Impact Mapping](#33-impact-mapping)  

[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)  

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)  

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up) 

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)  

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)  

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)  

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  

[Video About-the-Team](#video-about-the-team)  

[Bibliografía](#bibliografía)  

[Anexos](#anexos)  


---
# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| --------| ----------- | ----------- | ----------- |
| TB1     | 04/04/2024 |MealMaster |Documentación de los capítulos I-V. Implementación y despliegue de la primera versión del Landing Page.|
| TP     | 02/05/2024 |MealMaster |Documentación y código del Sprint N°2, desplegando la primera versión del aplicativo web.|

# Project Report Collaboration Insights
[URL del repositorio](https://github.com/orgs/Aplicaciones-Web-WX56-Group-MealMaster/repositories)

(Imagenes de los commits cada entrega)

# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.| **TB1** <br> *Cortés Casas, Joaquín Marcelo*: Comunicación de ideas para: <br> <li> Lean UX Problem Statements <br> <li> Lean UX Problem Assumptions <br> <li> Lean UX Problem Hypothesis <br> <li> Registro de entrevistas <br> <li> Needfinding <br> <li> User Stories <br> <li> Domain-Driven Software Architecture <br> <li> Sprint 1 <br><br> *Díaz Silva, Fernando Josué*: Comunicación de ideas para: <br> <li> Lean Ux Canvas <br> <li> Segmento Objetivo. <br> <li> Desarrollo de To-be Scenario mapping, Historias de Usuario <br> <br> *Chávez Rojas, Carlos Raúl Guillermo:* Comunicación de ideas para: <br> Capítulo IV: Product Design<br><li> Style Guidelines<br><li> Information Architecture<br><li> Landing Page UI Design<br><li> Web Applications UX/UI Design <br><br> *Ruiz Blas, Luciano:* Comunicación de ideas para: <br>x<br><br> *Becerra Llempen, Fabiola:* Comunicación de ideas para: <br><li> Solution Profile <br><li> Lean UX Problem Statements <br><li> Competidores <br><li> Estrategias y tácticas frente a competidores <br><li> Information Architecture <br><li> Landing Page Mock-up <br><li>Web Applications User Flow Diagrams <br><br> **TP** <br> *Cortés Casas, Joaquín Marcelo:* Comunicación de ideas para: <br> <li> Landing Page (Diseño y Código) <br> <li> Sprint 2 <br> <br> *Díaz Silva, Fernando Josué:* Comunicación de ideas para: <br> x <br> *Chávez Rojas, Carlos Raúl Guillermo:* Comunicación de ideas para: <br> <li> Sprint 2 <br> <br> *Ruiz Blas, Luciano:* Comunicación de ideas para: <br> x <br> <br> *Becerra Llempen, Fabiola:* Comunicación de ideas para: <br> <li>  Conclusiones y Recomendaciones <br> <li> Anexos <br> <li> Bibliografías <br> <li> Impact Mapping <br> <li> Spring 1 | **Conclusión 1:** <br> Como equipo, hemos llevado a cabo una serie de iniciativas destinadas a reforzar nuestra dedicación a la comunicación clara y precisa dentro del proyecto. Cada miembro ha contribuido escribiendo y documentando aspectos esenciales como perfiles de inicio y solución, contexto y desafíos, segmentación de audiencias y la aplicación de metodologías como Lean UX. <br><br> Estas acciones no solo evidencian un profundo entendimiento del proyecto, sino también una habilidad destacada para transmitir sus elementos fundamentales a diversos públicos. Es importante destacar que esta capacidad comunicativa se ha forjado a través de una comunicación constante entre los miembros del equipo, que han colaborado para validar la precisión y relevancia de las ideas en cada etapa del proceso mediante discusiones y evaluaciones rigurosas. Este enfoque colaborativo no solo garantiza una comprensión compartida de los objetivos y desafíos del proyecto, sino que también promueve la cohesión y el compromiso entre los miembros del equipo.|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.| **TB1** <br> *Cortés Casas, Joaquín Marcelo*: Comunicación de ideas para: <br> <li> Lean UX Problem Statements <br> <li> Lean UX Problem Assumptions <br> <li> Lean UX Problem Hypothesis <br> <li> Registro de entrevistas <br> <li> Needfinding <br> <li> User Stories <br> <li> Domain-Driven Software Architecture <br> <li> Sprint 1 <br><br> *Díaz Silva, Fernando Josué*: Comunicación de ideas para: <br> <li> Lean Ux Canvas <br> <li> Segmento Objetivo. <br> <li> Desarrollo de To-be Scenario mapping, Historias de Usuario <br> <br> *Chávez Rojas, Carlos Raúl Guillermo:* Comunicación de ideas para: <br> Capítulo IV: Product Design<br><li> Style Guidelines<br><li> Information Architecture<br><li> Landing Page UI Design<br><li> Web Applications UX/UI Design <br><br> *Ruiz Blas, Luciano:* Comunicación de ideas para: <br>x<br><br> *Becerra Llempen, Fabiola:* Comunicación de ideas para: <br><li> Solution Profile <br><li> Lean UX Problem Statements <br><li> Competidores <br><li> Estrategias y tácticas frente a competidores <br><li> Information Architecture <br><li> Landing Page Mock-up <br><li>Web Applications User Flow Diagrams <br><br> **TP** <br> *Cortés Casas, Joaquín Marcelo:* Comunicación de ideas para: <br> <li> Landing Page (Diseño y Código) <br> <li> Sprint 2 <br> <br> *Díaz Silva, Fernando Josué:* Comunicación de ideas para: <br> x <br> *Chávez Rojas, Carlos Raúl Guillermo:* Comunicación de ideas para: <br> <li> Sprint 2 <br> <br> *Ruiz Blas, Luciano:* Comunicación de ideas para: <br> x <br> <br> *Becerra Llempen, Fabiola:* Comunicación de ideas para: <br> <li>  Conclusiones y Recomendaciones <br> <li> Anexos <br> <li> Bibliografías <br> <li> Impact Mapping <br> <li> Spring 1 |**Conclusión 1:** <br> Como grupo, hemos alcanzado un nivel más profundo de comprensión y dominio del campo de aplicación a través de la articulación escrita de conceptos y hallazgos vinculados al proyecto de ingeniería. Cada integrante ha desempeñado un papel activo al redactar y documentar aspectos cruciales dentro del informe, lo que ha sido fundamental para el progreso y la ejecución exitosa del proyecto de ingeniería <br> Este compromiso con la comunicación escrita no solo ha fortalecido nuestro conocimiento colectivo del dominio de la aplicación, sino que también ha facilitado la colaboración efectiva entre los miembros del equipo. Además, el proceso de redacción y documentación ha permitido identificar y abordar áreas de mejora, así como también ha servido como una herramienta para la consolidación y la difusión del conocimiento generado durante el desarrollo del proyecto. En resumen, la comunicación escrita ha sido un elemento crucial en el éxito del equipo, facilitando el intercambio de ideas, la toma de decisiones informadas y la creación de un producto final de alta calidad.
|

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

MealMaster es una plataforma web diseñada para ayudar a cocineros inexpertos y entusiastas de la nutrición a seleccionar y organizar sus recetas de comida para alcanzar sus objetivos culinarios y mejorar su salud, transformando la planificación de comidas con una interfaz intuitiva y fácil de utilizar. Al ingresar sus ingredientes, los usuarios reciben recomendaciones adaptadas a sus necesidades específicas, garantizando una experiencia culinaria saludable y eficiente.

Misión: Brindar una plataforma de planificación de comidas fácil de utilizar, que simplifique la preparación diaria de alimentos, ofreciendo opciones saludables y económicas que se ajusten a diferentes estilos de vida.

Visión: Convertirnos en la plataforma líder en organización y planificación de comidas, empoderando a las personas para tomar decisiones alimenticias más saludables y conscientes.

#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Cortés Casas, Joaquin Marcelo	![Imagen del compañero](image.jpg)|U202114545 |Ingenieria de software|Mi edad es de 20 años, soy un estudiante de la carrera de Ingeniería de Software en la UPC. Desde una edad temprana, he tenido un interés por el manejo de la tecnología y la interacción con los videojuegos. Tengo un fuerte sentido de liderazgo al asumir la responsabilidad de coordinar y motivar a los equipos de trabajo en momentos clave. Siempre estoy dispuesto a enfrentar nuevos desafíos y desarrollar mis conocimientos en el entorno del Software.| Diaz Silva, Fernando Josué|U202112722|Ingenieria de software|Soy Fernando Diaz, tengo 20 años, me apasiona la tecnología, actualmente estudio la carrera de  ingeniería de software en la Universidad Peruana de Ciencias Aplicadas(UPC). A lo largo de la carrera he desarrollado distintas habilidades, mi principal enfoque en esta carrera parte del software como tal y el ámbito empresarial, para lo cual planeo realizar un MBA. Soy una persona proactiva, responsable y disciplinada. Estoy preparado para desarrollar un buen trabajo junto a mi equipo y aplicar todo el conocimiento adquirido a lo largo de mi carrera.|
|Chávez Rojas, Carlos Raúl Guillermo
|U201910317|Ingenieria de software|Tengo 22 años y estudió la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me apasiona el mundo digital y la capacidad de la tecnología para solucionar problemas y crear nuevas experiencias. Soy una persona proactiva, responsable y con gran capacidad de aprendizaje. Tengo un fuerte interés por la investigación y la innovación, y estoy siempre buscando nuevas formas de mejorar mis habilidades y conocimientos.
|
|Ruiz Blas, Luciano Stefano|U20211F978|Ingenieria de software|Soy Luciano Ruiz, tengo 20 años y estudió la carrera de Ingeniería de Software. Soy un apasionado de la tecnología y la creación de software. Además, cuento con conocimiento de diferentes lenguajes de programación como C++, C#, Java, Python, etc. Me gusta aprender intensamente temas de mi interés como la inteligencia artificial y el desarrollo de aplicaciones móviles. Finalmente, me considero una persona con cualidades aptas para trabajar en equipo y aprender rápidamente conocimientos.
|
|Becerra Llempen, Fabiola Dayane
|U20171a518|Ingenieria de software|Soy Fabiola Becerra, actualmente estudio la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una apasionada de la tecnología e innovación, utilizando todas las herramientas de software disponibles. Me considero una persona dinámica, responsable y con muchas ganas de enfrentar nuevos retos y experiencias. Mis temas de interés son la inteligencia artificial y la innovación en estos campos. Siempre estoy al tanto de los temas actuales para reforzar mis conocimientos y mejorar mis habilidades blandas. Por último, me siento capacitada para colaborar en equipo y asimilar con rapidez nuevos aprendizajes.
|

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
|Business Assumptions|User Assumptions|
|-|-|
|1. - 12. |1. - 6.|
#### 1.2.2.3. Lean UX Hypothesis Statements.
Texto
#### 1.2.2.4. Lean UX Canvas.
(imagen con texto)
## 1.3. Segmentos objetivo.
| | Segmento 1 | Segmento 2  |
| - | - |-|
| Variables                 |  |  |
| Geográfica                |  |  |
| Demográfica               |  |  |
| Psicológica               |  |  |
| Función de comportamiento |  |  |

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | -- |


| |  | (Nosotros) | Competidor  | Comptdor |
|-|-|-|-|-|
| PERFIL| Overview | lorem | ipsum | lorem |
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? |  ipsu | impuz |
|| Mercado Objetivo                                        | Jeda | asa | asa2 |
| Perfil de marketing                                     | Estrategia de Marketing | Redes Sociales | Redes Sociales | Televisión, Redes Sociales |
| Perfil del producto                                     | Productos y servicios | Elementos Gráficos Interactivos Enseñanza de Matemáticas Lúdica y Autodidacta Educación matemática interactiva Ámbito Freemium | Educación matemática interactiva Mas de 100 cursos en 28 idiomas diferentes | Educación general interactiva Contratos con Movistar |
|| Precios y costos                                        | Freemium (Cuenta Premium permite personalizar los juegos) Gratis | Gratuito | Gratuito |
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web |
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores ->|  | Nosotros | Competidor2| Competidor3|
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | lorem | Lorem | lorem |
|| Debilidades   | lorem | lorem | lorem | lorem | 
|| Oportunidades | lorem | lorem | lorem | lorem | 
|| Amenazas      | lorem | lorem | lorem | lorem |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}

### 2.2.3. Análisis de entrevistas.
**Segmento 1:**
{texto}
**Segmento 2:**
{texto}
## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  
![Imagen User Persona 1](image.jpg)

**Segmento 2:**
![Imagen User Persona 1](image.jpg)

### 2.3.2. User Task Matrix.
| --- | ------ | Segmento 1  | ------/----- | Segmento 2  | ---------- |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| U01X| {Texto}| Alta        | Alta         | Media       | Baja       |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- s
- s
- s
  
**Onboarding and first use:**
How can they feel successful?
- s
- s
- s  
  
**Sharing:**
Why would they invite others?
- s
- s
- s

### 2.3.4. Empathy Mapping.
**Segmento 1:**
![Empathy Map Segmento1](image.jpg)

**Segmento 2:**
![Empathy Map Segmento1](image.jpg)
### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: {escenario}

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|

**Segmento 2**  
Escenario: Dificultad para entender Matemáticas

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|
## 2.4. Ubiquitous Language.
```
Texto ubiquo: Definicion de este
```

---

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

Segmento 1:

| Fases    |  fase 1 as is | fase 2| fase 3|
| -------- | ------- | ---- | ---------------- |
| Doing    | | texto| texto | texto| texto|
| Thinking | | texto| texto | texto| texto|
| Feeling  | | texto| texto | texto| texto|

Segmento 2:
| Fases    |  fase 1 as is | fase 2| fase 3|
| -------- | ------- | ---- | ---------------- |
| Doing    | | texto| texto | texto| texto|
| Thinking | | texto| texto | texto| texto|
| Feeling  | | texto| texto | texto| texto|

## 3.2. User Stories.

| HU0X | Historia Usuario | "Descripcion"  |
|-|-|-|

## 3.3. Impact Mapping.

![Impact Mapping](image.jpg)

## 3.4. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1      | HU01          | titulo his | desc  | 5                        |

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

#### Branding
Con el propósito de dar estilo y reconocimiento a nuestra aplicación web que posee una variedad de ajustes en los temas de colores, fuentes tipográficas y en el aspecto de diseño estructural, para el desarrollo correcto de nuestro banding hemos tomado en cuenta cada una de las características de nuestra solución .

#### Typography
El tipo de tipografía escogida es Raleway, resalta elegancia y modernidad. Ofreciendo así, una visión amigable y fácil de leer para nuestra plataforma.

#### Logotipo
![Imgur](https://imgur.com/01ZzG81.jpg)

![Imgur](https://imgur.com/pzpkb3P.jpg)

#### Colors

![Imgur](https://imgur.com/oLdpYAb.jpg)

#### Spacing
El spacing mantiene:
- Botones: padding de 16px vertical y 32px horizontal
- Margin entre texto 16px
- Margin entre elementos 24px
- Margin entre secciones 72px

#### Dimension
La dimensión para adoptar en cuanto al diseño es un tono formal y entusiasta, aplicando colores profesionales como el verde presentado y un tono entusiasta con colores celeste y beige. Asimismo, para el diseño de los íconos y formas adoptaremos diseños amigables al usuario utilizando bordes curvos en su mayoría.

### 4.1.2. Web Style Guidelines.
En el presente apartado, enseñaremos las decisiones que fueron tomadas en base a los estándares visuales y los distintos tipos de interacción con respecto al responsive web interface.


## 4.2. Information Architecture.
En esta sección profundizaremos y sustentamos las decisiones de diseño que escogimos como equipo durante el desarrollo del proyecto. Nuestro objetivo es facilitar al usuario adaptarse a nuestra aplicación, brevemente explicaremos las propuestas claves para el diseño de nuestra Landing Page y las aplicaciones.
### 4.2.1. Organization Systems.
#### Visual:

En este campo, nos organizamos de manera jerárquica. Este modelo incluye el diseño de características visuales que facilitan la comprensión del usuario. Los elementos más grandes de nuestra página web se encuentran en la jerarquía de primer orden o máximo nivel. Estos incluyen los elementos principales que captarán la atención de nuestros usuarios empleados y empleadores al ingresar a la web, como los logotipos, los títulos, las tarjetas botones, entre otros. Los componentes que están directamente relacionados con los subtítulos de descripción y los cuadros de ingreso de información se encuentran en el segundo nivel. Finalmente, el tercer y último nivel corresponde a los componentes complementarios, como el icono de búsqueda, la foto de perfil, entre otros.


#### Por contenido:


- **Alfabético**: se distribuyen alfabéticamente los nombres de platos de comida en los que esté actualmente en la aplicación.
- **Cronológico**: se distribuyen las nuevas recetas por la fecha más reciente.
- **Según prioridad**: se muestran perfiles recomendados según los especialistas que requiera un tipo de dieta en específico o tips personalizados. 

### 4.2.2. Labeling Systems.
- **Encabezados (headings):** Estas etiquetas benefician al usuario para poder comprender toda la información de un apartado en el que se encuentre con tan solo leerla.
- **Etiquetas textuales:** Son etiquetas que se usan comúnmente para indicar ciertos apartados.
- **Etiquetas icónicas (conics labels):** Consiste en utilizar imágenes para que esta etiqueta pueda tener significado pleno sin necesidad de texto adicional, pero normalmente, van acompañadas de etiquetas textuales para que el usuario no se confunda

Estas dos etiquetas en cuestión se evidencian en la barra de navegación de nuestro mockup.

### 4.2.3. SEO Tags and Meta Tags

Las metas etiquetas nos brindan apoyo en  indicar información codificada y especificar los metadatos. Estas no son visualizadas en los sitios web, estos son leídos por los navegadores o rastreadores web. Estas metas etiquetas facilitan el análisis de archivos HTML y facilita el mantenimiento del contenido del archivo. Además, estas etiquetas nos ayudan en el posicionamiento de nuestra página web en los buscadores para así obtener buenos resultados de búsquedas.

#### Meta Description Tag:
- **Título**   
Esta etiqueta es una de las más importantes y por lo general se pone antes que cualquier otra meta etiqueta. Esta etiqueta es utilizada o leída por todos los motores de búsqueda como encabezado en las páginas de resultados de los motores de búsqueda (SERP).

`<title> Mejora tu salud con Meal Master</title>`
 
- **Codificación de caracteres**   
Esta etiqueta ayudará a que muestre correctamente los caracteres especiales en la página. 

`<meta charset="utf-8"/>`
- **Descripción**  
Esta meta etiqueta nos sirve para proporcionar un resumen del contenido de la página web. Aquí debemos dar una breve información de lo que se puede visualizar en la página.

`<meta name="description" content="Índice de dietas. El índice de dietas ayuda a que el usuario pueda ver.... "/>`

- **Palabras clave**   
En esta etiqueta se pone las palabras claves relacionadas con el tema o contenido de la página web.

`<meta name="keywords" content="dietas, dietas saludables, comidas diarias, comida sana"/>`


### 4.2.4. Searching Systems.
Hemos implementado los sistemas de búsqueda en el apartado de búsqueda de platos de comida.  Aquí el usuario escribirá y buscará dentro de una caja de texto el tipo de plato que desea cocinar. Entonces se desplegará una overlay hacia abajo mostrando las recomendaciones de tipo de dietas o platos de comida que quizá esté buscando o sea de su interés.

### 4.2.5. Navigation Systems.
	
**Landing Page:**   
El usuario podrá direccionarse a otra frame por medio de realizar un click en los linklabel, cada uno con una dirección relacionada al contenido del label, que se encontraran en los encabezados o headers. Para mostrar nuestros diseños, usaremos un encabezado. Los llevará a las secciones con sus temas correspondientes al hacer clic en "Características" o "Testimonios". Asimismo, se implementarán botones para facilitar la búsqueda del usuario si se quedó interesado en algún bloque de la página principal.

**Aplicación Web:**  
Para la aplicación web haremos uso de un sidebar para la navegación entre los distintos apartados disponibles en ella. También haremos uso de secciones con “Accesos directos” desde la sección inicial o “Home” de la Aplicación web.

## 4.3. Landing Page UI Design
### 4.3.2. Landing Page Wireframe
 Link Figma Landing Page Wireframe: https://www.figma.com/proto/nEypHPwCcG8EhmtVhJOvJr/MealMaster?page-id=0%3A1&type=design&node-id=167-834&viewport=4399%2C734%2C0.39&t=Ho8sRzWynTSVflcb-1&scaling=min-zoom&starting-point-node-id=167%3A834&show-proto-sidebar=1&mode=design 

![Imgur](https://imgur.com/LqIUOY3.jpg)

### 4.3.2. Landing Page Mock-up
 Link Figma Landing Page Mock-Up: https://www.figma.com/proto/nEypHPwCcG8EhmtVhJOvJr/MealMaster?page-id=0%3A1&type=design&node-id=54-332&viewport=4399%2C734%2C0.39&t=otNJnnSFIW0hXd45-1&scaling=min-zoom&starting-point-node-id=54%3A332&show-proto-sidebar=1&mode=design 

![Imgur](https://imgur.com/C3EdZp9.jpg)
![Imgur](https://imgur.com/xlHjv7e.jpg)
![Imgur](https://imgur.com/IACnVKM.jpg)

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
En primer lugar, se presentarán los wireframes de la aplicación, que luego serán usados como plantilla.
![Imgur](https://imgur.com/0DR3Qvn.jpg)
![Imgur](https://imgur.com/YegBn2H.jpg)
![Imgur](https://imgur.com/TRj2sp9.jpg)
![Imgur](https://imgur.com/3xRzXAw.jpg)
![Imgur](https://imgur.com/3F5UWrr.jpg)
![Imgur](https://imgur.com/ssa7pBB.jpg)

### 4.4.2. Web Applications Wireflow Diagrams.
Wireflow es como se va a navegar por la pagina (boton me lleva a esta pagina y este me regresa)
![Web Aplication Wireflow](image.jpg)
### 4.4.2. Web Applications Mock-ups.
En esta sección, se presentan los wireflows de la aplicación, guiándose de las historias de usuario respectivas.

**User Goal: El usuario se registra, recupera su contraseña o inicia sesión**

![Imgur](https://imgur.com/yoq8kua.jpg)

Descripción:
Al ingresar a la aplicación el usuario se encuentra con un formulario para inicio de sesión. Además, tiene también la opción de registrarse en caso no posea una cuenta y la opción de cambiar su contraseña en caso de que la haya olvidado. Dentro del formulario de registro podrá llenar todos sus datos y el mismo formulario le confirmará que su registro fue exitoso. Cuando el usuario ingrese correctamente sus credenciales podrá ingresar a su página de inicio.


**User Goal: Perfil de usuario**

![Imgur](https://imgur.com/NxZ0Apj.jpg)

Descripción:
Si el usuario desea acceder a su perfil. Desde la página de inicio puede hacer click en el menú “Hamburger” ubicado en la esquina superior izquierda, lo que desplegará un “Sidebar” donde se mostrarán todas las opciones disponibles, entre ellas el “Perfil”. Haciendo click en la opción “Perfil” el usuario podrá acceder a su perfil y visualizar toda su información.

### 4.4.3. Web Applications Mock-Ups

![Imgur](https://imgur.com/j1HjiQX.jpg)

link: https://www.figma.com/proto/nEypHPwCcG8EhmtVhJOvJr/MealMaster?page-id=0%3A1&type=design&node-id=52-1044&viewport=2279%2C660%2C0.24&t=d8bNesaa3lxnFw7a-1&scaling=min-zoom&starting-point-node-id=52%3A1044&show-proto-sidebar=1&mode=design 


## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://www.example.com)
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
1. System Context Diagram: Diagrama que muestra la relacion del aplicativo con los usuarios
se incluyen servicios externos (si hay pocos bounded context se incluyen ahi)

2. Bounded Context Map: Muestra la relacion entre bounded contexts (los bounded context son como una burbuja que encapsula palabras clave en los procesos para poder diferenciarlos [Ej. Bounded context enfocado en las ventas(ventas), otro en revisar el stock(gestion) y otro enfocado en los proveedores (suministros)]) Se hace como un brainstorm y se ve en que pueden conectarse o comunicarse [se usa un circulo entre conexiones lineales (upstream o downstream) para definir comunicacion, algunos context se pueden integrar para representar por ejemplo un share model por database, tambien se mencionan los (third party context para definir los restful apis)]
   
### 4.6.2. Software Architecture Container Diagrams.
1. Bounded Context Deployable / Container Diagrams. Sirve para entender como funciona y el proceso, Se especifican DB's, indexers, Search engine, las Apis que usen los bounded context y se conectan por flechas, las cuales tienen como objetivo explicar la direcion y relacion junto a que se esta enviando/comunicando (TCP) 

### 4.6.3. Software Architecture Components Diagrams.
1. Component diagrams: Estos van a mostrar las ordenes, procesos, mensajes y componentes utilizados en el uso del aplicativo, claro se deben hacer diferentes de estos para cada bounded o USER GOALS
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
Esta yaselasaben (diagrama de clases)
Clases(name), objetos(nombre-objeto [como objeto]), metodos("Accion") y atributos(Correo, edad,nombre como valor, ID)
### 4.7.2. Class Dictionary.
Inherit (ave(superclase) -> (subclase)canario )
Polymorphism (Ej. funcion de persona hablar() -> Peruano hablar() , Gringo hablar() todos tienen una funcion que contiene persona y van cambiando sus formas)
Abstraction (Ej. Solo muestra el usuario, pero esta su edad, correo y veces usada que uso app en la base de datos (fuera de vista))
Encapsulation (cuando tienes tus variables y metodos en la misma clase las estas encapsulando, aun mas se encapsulan en Private y Public )
## 4.8. Database Design.
### 4.8.1. Database Diagram.
Diagrama de base de datos (la relacion entre clases PK FK el Normalizar tmbn, isiyisi 🕸)
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
Especificaciones de donde vamos a hacer el proyecto (vscode supongo)
extensiones tmbn? nose bn q quieren aca
### 5.1.2. Source Code Management.
El gitjab donde tengamos el proyecto
### 5.1.3. Source Code Style Guide & Conventions.
Que usamos con css (en caso usemos software para SASS)
supongo q tmbn cositas de como hacemo el code capas algun tipo de codigo para comunicarse entre comments
### 5.1.4. Software Deployment Configuration.
Configuraciones de donde y como deployeamos el proyecto
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.X. Sprint n
#### 5.2.X.1. Sprint Planning n.
Explicar como vamos a plannear el sprint?
#### 5.2.X.2. Sprint Backlog n.
![SprintBacklog n](image.jpg) Nica hago la tabla 
#### 5.2.X.3. Development Evidence for Sprint Review.
![Sprint review development Evidence](image.jpg)
#### 5.2.X.4. Testing Suite Evidence for Sprint Review.
![Sprint review Testing suite Evidence](image.jpg)
#### 5.2.X.5. Execution Evidence for Sprint Review.
![Sprint review Execution Evidence](image.jpg)
#### 5.2.X.6. Services Documentation Evidence for Sprint Review.
![Sprint review Services Documentation Evidence](image.jpg)
#### 5.2.X.7. Software Deployment Evidence for Sprint Review.
![Sprint review Software Deployment Evidence](image.jpg)
#### 5.2.X.8. Team Collaboration Insights during Sprint.
![Sprint review Team Collaboration Insights](image.jpg) imagenes de colaboraciones github

## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 5.3.2. Registro de Entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}
### 5.3.3. Evaluaciones según heurísticas.
| HEURÍSTICA   | EVALUACIÓN ✅❌ | NOTA      |
| --------------------------------------------- | ---------- | --------- |
| Visibilidad del estado del sistema            |            | {texto}   |
| Coincidencia entre el sistema y el mundo real |            | {texto}   |
| Control y libertad del usuario                |            | {texto}   |
| Consistencia y estándares                     |            | {texto}   |
| Prevención de errores                         |            | {texto}   |
| Mostrar antes que recordar                    |            | {texto}   |
| Flexibilidad y eficiencia de uso              |            | {texto}   |
| Diseño estético y minimalista                 |            | {texto}   |
| Comunicar errores con facilidad               |            | {texto}   |
| Ayuda y documentación                         |            | {texto}   |
## 5.4. Video About-the-Product.
[URL del video about the product](https://www.example.com)
# Conclusiones
{texto}
# Conclusiones y recomendaciones.
{texto}
# Video About-the-Team.
[URL del video about the team](https://www.example.com)

# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores

![Imagen de algo no nuestro lol](image.jpg)






