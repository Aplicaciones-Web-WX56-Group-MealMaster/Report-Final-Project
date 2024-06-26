<hr> 

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2024-1</strong><br>
    <strong>Aplicaciones Web - WX56</strong><br>
    <strong>Profesor: Alex Humberto Sánchez Ponce</strong><br>
    <br>Informe de Trabajo Final - TF1
</p>

<p align="center">
    <strong>Startup: MealMaster</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Cortés Casas, Joaquin Marcelo</td>
            <td>U202114545</td>
        </tr>
        <tr>
            <td>Diaz Silva, Fernando Josué</td>
            <td>U202112722</td>
        </tr>
        <tr>
            <td>Chávez Rojas, Carlos Raúl Guillermo</td>
            <td>U201910317</td>
        </tr>
        <tr>
            <td>Ruiz Blas, Luciano</td>
            <td>U20211F978</td>
        </tr>
	<tr>
            <td>Becerra Llempen, Fabiola</td>
            <td>U20171A518</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Junio, 2024</strong>
</p>
<br>

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
| TP1     | 02/05/2024 |MealMaster |Documentación y código del Sprint N°2, desplegando la primera versión del aplicativo web.|
| TB2     | 17/05/2024 |MealMaster |Documentación y código del Sprint N°3, desplegando la primera versión del aplicativo web.|
| TF1     | 27/06/24 |MealMaster |Documentación y código del Sprint N°4, desplegando las versiones del aplicativo web, conclusiones, bibliografías y anexos.|

# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.| Joaquín Marcelo Cortés Casas <br> TB1: <li>He contribuido con la codificación de la primera versión del landing page y a la documentación de distintos capítulos del informe<br>TP: <li>He contribuido con la codificación de la primera versión del aplicativo web, además de realizar correcciones de la landing page<br>TB2: <li>He realizado la primera versión del backend, definiendo los distintos endpoints<br>TF:<li>Me he encargado de realizar la segunga versión del backend, actualizando las entidades utilizadas en base a bounded contexts específicos.<br><br>** Fabiola Becerra**<br> **TB1:** <li>Durante el desarrollo de nuestro prototipo he logrado comprender la importancia de las necesidades que requieren los usuarios. También, he obtenido un grado satisfactorio de comprensión al momento de reunirme con mis compañeros para poder realizar el trabajo con la finalidad de brindar una satisfacción a los usuarios.<br>**TP:** <li>En el transcurso del desarrollo de nuestro prototipo, he llegado a entender profundamente las necesidades de los usuarios y las características fundamentales que debe tener la interfaz de nuestra aplicación. Este entendimiento se ha enriquecido gracias a numerosas reuniones y debates con mi equipo, orientados a crear una solución innovadora y efectiva para nuestros usuarios.<br>**TB2:** <li>A lo largo del desarrollo de nuestro prototipo, he comprendido claramente los componentes que debe incluir nuestro backend y la importancia de las relaciones entre las tablas en nuestra base de datos. Este entendimiento se ha profundizado mediante diversas reuniones y discusiones con mi equipo, centradas en asegurar que nuestra solución sea robusta y eficiente para satisfacer las necesidades de los usuarios.<br>**TF:** <li>Durante el desarrollo de nuestro prototipo, he comprendido cómo conectar eficazmente el frontend con el backend y la importancia de crear aplicaciones bien integradas. Este conocimiento se ha fortalecido mediante numerosas reuniones y discusiones con mi equipo, enfocadas en desarrollar una solución cohesiva y funcional que cumpla con las expectativas de nuestros usuarios.<br><br>FernandoJosue Diaz Silva<br> TB1: <li>Participé en la programación de la versión inicial de la página de aterrizaje y en la redacción de varios capítulos del informe.<br>TP: <li>Colaboré en la programación de la versión inicial de la aplicación web, además de corregir la página de aterrizaje.<br>TB2: <li>Desarrollé la primera versión del backend, definiendo los distintos endpoints.<br>TF: <li>Me encargué de la segunda versión del backend, actualizando las entidades basadas en contextos delimitados específicos. <br><br>Carlos Raúl Guillermo Chávez Rojas<br> TB1: <li>Contribuí en la codificación de la primera versión del landing page y en la elaboración de diversos capítulos del informe.<br>TP: <li>Colaboré en la codificación de la primera versión de la aplicación web y realicé correcciones en el landing page.<br>TB2: <li>Implementé la primera versión del backend, definiendo los endpoints necesarios.<br>TF: <li>Me encargué de la segunda versión del backend, actualizando las entidades de acuerdo a contextos específicos delimitados.<br>Luciano Ruiz Blas <br> TB1: <li>Aporté en la codificación de la primera versión de la página de inicio y en la redacción de distintos capítulos del informe.<br>TP: <li>Contribuí en la codificación de la primera versión de la aplicación web, además de hacer correcciones en la página de inicio.<br>TB2: <li>Realicé la primera versión del backend, definiendo los endpoints.<br>TF: <li>Desarrollé la segunda versión del backend, actualizando las entidades utilizadas basadas en contextos delimitados específicos.|<br>**Conclusión número uno:** Durante el proceso de creación de nuestro prototipo para nuestros futuros clientes, me di cuenta de cuán importantes son sus necesidades y deseos.Además, las charlas y reuniones que he tenido con mis compañeros de trabajo con el objetivo de presentar una solución innovadora para los clientes han mejorado esta comprensión.<br><br>**Conclusión 2:** Comprendí las necesidades de los usuarios durante el desarrollo de nuestro prototipo. Además, al reunirme con mis compañeros para poder completar el trabajo con el objetivo de brindar satisfacción a los usuarios, he obtenido un grado satisfactorio de comprensión.<br><br>**Conclusión 3:**<br>La comunicación oral dentro del equipo ha sido efectiva, lo que ha permitido un intercambio fluido de ideas y una comprensión compartida de los objetivos del proyecto. Para mantener la colaboración y el progreso del trabajo, se continuará fomentando esta comunicación.|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.| **Joaquín Marcelo Cortés Casas **<br> TB1: <li>He contribuido con la codificación de la primera versión del landing page y a la documentación de distintos capítulos del informe<br>TP: <li>He contribuido con la codificación de la primera versión del aplicativo web, además de realizar correcciones de la landing page<br>TB2: <li>He realizado la primera versión del backend, definiendo los distintos endpoints<br>TF:<li>Me he encargado de realizar la segunga versión del backend, actualizando las entidades utilizadas en base a bounded contexts específicos.<br>** Fabiola Becerra**<br> **TB1:** <li>Mediante la realización del trabajo en equipo hemos logrado crear un prototipo de manera asertiva en el aspecto de superar las expectativas de nuestros clientes, ya que nuestro prototipo ofrece soluciones de una manera eficaz e innovadora para los usuarios.<br>**TP:** <li>Gracias al trabajo colaborativo, hemos desarrollado un prototipo sólido en el ámbito del frontend, superando las expectativas de nuestros clientes. Nuestro prototipo proporciona soluciones de manera eficiente e innovadora para los usuarios, demostrando nuestro compromiso con la excelencia y la funcionalidad.<br>**TB2:** <li>A través del esfuerzo conjunto, hemos creado un prototipo robusto en el desarrollo del backend, excediendo las expectativas de nuestros clientes. Nuestro prototipo ofrece soluciones de manera eficiente e innovadora para los usuarios, garantizando un rendimiento sólido y fiable del sistema.<br>**TF:** <li>Mediante la colaboración efectiva, hemos desarrollado un prototipo cohesivo que integra de manera óptima el frontend con el backend, superando las expectativas de nuestros clientes. Nuestro prototipo ofrece soluciones de manera eficiente e innovadora para los usuarios, subrayando la importancia de una aplicación bien conectada y operativa en todos sus aspectos.<br><br>FernandoJosue Diaz Silva<br> TB1: <li>Participé en la programación de la versión inicial de la página de aterrizaje y en la redacción de varios capítulos del informe.<br>TP: <li>Colaboré en la programación de la versión inicial de la aplicación web, además de corregir la página de aterrizaje.<br>TB2: <li>Desarrollé la primera versión del backend, definiendo los distintos endpoints.<br>TF: <li>Me encargué de la segunda versión del backend, actualizando las entidades basadas en contextos delimitados específicos.<br><br>Carlos Raúl Guillermo Chávez Rojas<br> TB1: <li>Contribuí en la codificación de la primera versión del landing page y en la elaboración de diversos capítulos del informe.<br>TP: <li>Colaboré en la codificación de la primera versión de la aplicación web y realicé correcciones en el landing page.<br>TB2: <li>Implementé la primera versión del backend, definiendo los endpoints necesarios.<br>TF: <li>Me encargué de la segunda versión del backend, actualizando las entidades de acuerdo a contextos específicos delimitados.<br>**Luciano Ruiz Blas **<br> TB1: <li>Aporté en la codificación de la primera versión de la página de inicio y en la redacción de distintos capítulos del informe.<br>TP: <li>Contribuí en la codificación de la primera versión de la aplicación web, además de hacer correcciones en la página de inicio.<br>TB2: <li>Realicé la primera versión del backend, definiendo los endpoints.<br>TF: <li>Desarrollé la segunda versión del backend, actualizando las entidades utilizadas basadas en contextos delimitados específicos.|<br><br>**Conclusión 1:**<br> Podemos crear un prototipo que supera las expectativas de nuestros clientes gracias al trabajo en equipo correcto que hemos realizado; ofrecemos soluciones innovadoras que resuelven problemas que son evidenciados en la actualidad.<br><br>**Conclusión 2:** Hemos logrado crear un prototipo que supera las expectativas de nuestros clientes porque ofrece soluciones efectivas e innovadoras para los usuarios mediante el trabajo en equipo.<br><br>**Conclusión 3:**La comunicación escrita ha sido fundamental para registrar el progreso del proyecto y garantizar que los miembros del equipo comprendan los entregables. Para garantizar la eficacia y la calidad del trabajo, se seguirá manteniendo un enfoque claro y conciso en la comunicación escrita.|

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

MealMaster es una plataforma web diseñada para ayudar a cocineros inexpertos y entusiastas de la nutrición a seleccionar y organizar sus recetas de comida para alcanzar sus objetivos culinarios y mejorar su salud, transformando la planificación de comidas con una interfaz intuitiva y fácil de utilizar. Al ingresar sus ingredientes, los usuarios reciben recomendaciones adaptadas a sus necesidades específicas, garantizando una experiencia culinaria saludable y eficiente.

Misión: Brindar una plataforma de planificación de comidas fácil de utilizar, que simplifique la preparación diaria de alimentos, ofreciendo opciones saludables y económicas que se ajusten a diferentes estilos de vida.

Visión: Convertirnos en la plataforma líder en organización y planificación de comidas, empoderando a las personas para tomar decisiones alimenticias más saludables y conscientes.

#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Cortés Casas, Joaquin Marcelo ![Integrante](images/joaquin.png)|U202114545 |Ingenieria de software|Mi edad es de 20 años, soy un estudiante de la carrera de Ingeniería de Software en la UPC. Desde una edad temprana, he tenido un interés por el manejo de la tecnología y la interacción con los videojuegos. Tengo un fuerte sentido de liderazgo al asumir la responsabilidad de coordinar y motivar a los equipos de trabajo en momentos clave. Siempre estoy dispuesto a enfrentar nuevos desafíos y desarrollar mis conocimientos en el entorno del Software.|
| Diaz Silva, Fernando Josué ![Integrante](images/fernando.png)|U202112722|Ingenieria de software|Soy Fernando Diaz, tengo 20 años, me apasiona la tecnología, actualmente estudio la carrera de  ingeniería de software en la Universidad Peruana de Ciencias Aplicadas(UPC). A lo largo de la carrera he desarrollado distintas habilidades, mi principal enfoque en esta carrera parte del software como tal y el ámbito empresarial, para lo cual planeo realizar un MBA. Soy una persona proactiva, responsable y disciplinada. Estoy preparado para desarrollar un buen trabajo junto a mi equipo y aplicar todo el conocimiento adquirido a lo largo de mi carrera.|
|Chávez Rojas, Carlos Raúl Guillermo ![Integrante](images/carlos.png)|U201910317|Ingenieria de software|Tengo 22 años y estudió la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me apasiona el mundo digital y la capacidad de la tecnología para solucionar problemas y crear nuevas experiencias. Soy una persona proactiva, responsable y con gran capacidad de aprendizaje. Tengo un fuerte interés por la investigación y la innovación, y estoy siempre buscando nuevas formas de mejorar mis habilidades y conocimientos.|
|Ruiz Blas, Luciano Stefano ![Integrante](images/luciano.png)|U20211F978|Ingenieria de software|Soy Luciano Ruiz, tengo 20 años y estudió la carrera de Ingeniería de Software. Soy un apasionado de la tecnología y la creación de software. Además, cuento con conocimiento de diferentes lenguajes de programación como C++, C#, Java, Python, etc. Me gusta aprender intensamente temas de mi interés como la inteligencia artificial y el desarrollo de aplicaciones móviles. Finalmente, me considero una persona con cualidades aptas para trabajar en equipo y aprender rápidamente conocimientos.|
|Becerra Llempen, Fabiola Dayane ![Integrante](images/fabiola1.png)|U20171a518|Ingenieria de software|Soy Fabiola Becerra, actualmente estudio la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una apasionada de la tecnología e innovación, utilizando todas las herramientas de software disponibles. Me considero una persona dinámica, responsable y con muchas ganas de enfrentar nuevos retos y experiencias. Mis temas de interés son la inteligencia artificial y la innovación en estos campos. Siempre estoy al tanto de los temas actuales para reforzar mis conocimientos y mejorar mis habilidades blandas. Por último, me siento capacitada para colaborar en equipo y asimilar con rapidez nuevos aprendizajes.|

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En la actualidad, el ritmo de vida acelerado y las múltiples responsabilidades han llevado a muchas personas a descuidar la planificación de sus comidas. Esto ha resultado en un aumento del consumo de alimentos preparados fuera de casa, como comidas rápidas o restaurantes. El no planificar las comidas y el consumir alimentos fuera de casa se encuentra relacionado a un mayor consumo de calorías, grasas, sodio y menor consumo de alimentos ricos en fibra y micronutrientes (Lindley, Benavides, 2022). Otro factor importante es la poca evidencia que existe sobre esta práctica a nivel nacional y la poca diversificación de esta.

|What (Qué)|El problema que abordamos en Meal Master es la carencia de tiempo y conocimientos gastronómicos para poder realizar comidas nutritivas para mejorar su salud y alcanzar objetivos culinarios. Este limitante desanima a los interesados a adquirir artículos interesantes y de obtener una buena nutrición. Por ello, tenemos como objetivo proporcionar una solución que ofrezca una experiencia de conocimientos sin restricciones y cumpliendo con los estándares de calidad.|
|When (Cuándo)|Cuando los amantes de la comida rápida o para las personas ocupadas que no cuentan con tiempo suficiente para realizar un plato de comida en el Perú se enfrentan a dificultades para encontrar aquellas recetas de interés, debido a la falta de opciones confiables en las escasas plataformas existentes dentro del mercado peruano.
Todo eso genera que la comunidad de clientes no puedan satisfacer sus deseos de adquirir recetas de platos saludables, o deba gastar una cantidad exorbitante de dinero para lograr conseguirlo.|
|Where (Dónde)|Al ser un servicio virtual, el usuario se encontrará en cualquier dispositivo móvil que le permita ingresar a la página web para poder obtener una receta o posibles recomendaciones. Este dispositivo debe contar con una conexión a internet y debe ser compatible con navegadores web como Chrome, Safari, Firefox o Microsoft Edge, respectivamente con sus versiones actualizadas.|
|Who (Quién) |Tenemos como principales involucrados a los participantes de la startup Meal Master, los cuales se encargarán de las creaciones de las plataformas de las dietas y su correcta gestión, nuestros clientes, que nos apoyaran con las recomendaciones de dietas o platos gastronómicos, los cuales se encuentran interesados por la realización de estos desde la comodidad de sus hogares, en Perú.|
|Why (Por qué)| La causa del problema es a  raíz de las preocupaciones por la falta de información nutritiva y falta de conocimientos de recetas saludables y beneficios para la salud, ya que en el mercado existen productos de calidad inferior, generando dudas o desconfío en los consumidores sobre su uso para una vida saludable.
Por otro lado, este mercado aún no ha sido explotado a fondo, lo que significa que es una oportunidad para Meal Master de promocionar tipos de comidas en tendencia y auténticas de una manera segura y de interés para los usuarios.|
|How (Cómo)|Nuestros clientes utilizan nuestra plataforma cuando deseen adquirir una dieta o un plato gastronómico para cocinar. En nuestro país, los lugares en donde se pueden adquirir este tipo de mercancía son muy limitados, siendo usualmente algunas páginas de redes sociales como Facebook o Instagram, librerías o por último, tiendas virtuales del extranjero. Ellos acceden a Meal Master cuando nos toman en cuenta como una opción confiable, segura y cómoda para realizar las recetas.|
|How much (Cuánto)| Alrededor del mundo, la industria de las recetas gastronómicas virtuales ha experimentado un crecimiento significativo. Para ello nuestra app contará con las herramientas de acompañamiento, que les ayudarán a elegir una mejor manera de realizar sus comidas.|

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.


Hemos detectado el gran limitante de recetas disponibles en línea que enfrentan los usuarios que les gusta la gastronomía o novatos que quieren aprender. En cuanto a la adquisición de recetas recomendadas dependiendo de los diferentes tipos de comidas. Esta falta de variedad y acceso a artículos en línea que no cuenten con dificultad al realizarlo es de satisfacción  por estos contenidos y limita su capacidad de obtener recetas exclusivas.

Hemos notado que las opciones de pago de estas aplicaciones no se encuentran en rangos de precio asequibles para los compradores regulares, problemática que limita el acceso a la adquisición de dichos servicios y afecta negativamente a la experiencia de compra. Este alto costo se debe a la escasez de tiendas especializadas en el rubro de enseñanza online en el Perú, por lo que la falta de competencia y gran demanda genera un aumento en los precios. En consecuencia, los clientes se encuentran obligados a pagar precios excesivos o tienen que renunciar a los deseos de obtener esta aplicación.


Hemos observado que en el mercado peruano actual existen carencias en cuanto a la diversidad de enseñanza en la cocina. Esta carencia de variedad se hace evidente a través de la repetición de platos gastronómicos que realizan en su día a día. Por ende, esta repetitividad de productos genera limitantes opciones a los consumidores y también esto desencadena un desinterés progresivo debido a la falta de novedades de las recetas de comida. 


Hemos notado que las tiendas tienden a enfocarse en solo un segmento del mercado oriental, como por ejemplo, la venta de recetas gastronómicas por segmentos. Esta limitación en la variedad de productos es notoria tanto en las tiendas físicas como en las tiendas virtuales. Por lo que esta restricción puede llevar a los consumidores a explorar nuevas alternativas como las tiendas internacionales, y existe la posibilidad de que las tiendas locales pierdan clientes. 

Al realizar compras en línea en tiendas virtuales enfocadas en el mercado oriental que no ofrecen una gran variedad de opciones de pago seguras y confiables, hemos observado que muchos usuarios se sienten inseguros. En la actualidad, las pocas tiendas presentes en el mercado peruano de este sector ofrecen una variedad limitada de métodos de pago, limitando los pagos con efectivo, Yape o Plin, y rechazando los pagos con tarjetas de crédito, débito o PayPal. La exclusión de métodos de pago populares y comunes limita la comodidad y la flexibilidad que esperan los usuarios al realizar compras en línea, e incluso llega a limitar su crecimiento, reduciendo oportunidades comerciales.


Hemos observado que los clientes de este sector en Perú tienen dificultades para encontrar información detallada sobre las recetas gastronómicas en las tiendas ya existentes, como ingredientes, sugerencias de uso dependiendo el utensilio y calificaciones de ventas, lo que les dificulta tomar decisiones de compra informadas. Muchos de estos clientes buscan conocer detalles específicos de los productos, como el tamaño de la figura coleccionable, cuántas personas han comprado un plan específico en la plataforma, cuál es el rango de calificación de los compradores del sector, entre otras características, porque esta amplitud de información los hace sentir más seguros al hacer una compra. 

Hemos detectado que el prolongado tiempo de espera asociado a la entrega de un libro adquirido virtualmente de librerías conocidas, genera incomodidad y un sentimiento de impaciencia en los consumidores. Además, afecta negativamente la experiencia de compra ya que desgasta la confianza que tiene el cliente. Por ende, una plataforma de recetas de comida es capaz de solventar este desafío y más, a través de la implementación de recetas actualizadas dentro del país es una opción innovadora.


#### 1.2.2.2. Lean UX Assumptions.

Business Assumptions
1. Los usuarios valoran la personalización y precisión en las recomendaciones de recetas basadas en sus ingredientes disponibles y preferencias alimenticias.
2. Proporcionar información nutricional precisa y detallada aumentará la confianza del usuario en nuestro servicio y mejorará su experiencia general.
3. Una base de datos de recetas amplia y constantemente actualizada mantendrá a los usuarios comprometidos y fomentará el uso repetido del servicio.
4. Un sistema de filtrado avanzado y una interfaz de usuario intuitiva e interactiva aumentarán la satisfacción del usuario y la adopción del servicio.
5. Al satisfacer las necesidades de los usuarios de manera efectiva, podemos aumentar la retención de usuarios y expandir nuestra base de usuarios.
6. Al mejorar continuamente nuestras características y servicios basados en los comentarios de los usuarios, podemos mantenernos competitivos en el mercado.

User Assumptions
¿Quién es el usuario? 
Una persona con poca experiencia en la cocina que busca recomendaciones de recetas en base a los ingredientes disponibles y tener un mayor control de los alimentos que consume.
 
¿Dónde encaja nuestro servicio en su trabajo o vida? 
MealMaster se integra en la vida diaria, proporcionando diferentes opciones para los desayunos, almuerzos, cenas y/o comidas del usuario.

¿Qué problema tiene nuestro servicio y cómo se resuelve?
Resuelve la dificultad que conlleva encontrar recetas de comida que se ajusten a los ingredientes del usuario y tener un mayor control de los alimentos que consuman.

¿Cuándo y cómo es usado nuestro servicio?
Se utiliza principalmente durante la planificación de comidas, momento donde el usuario necesita ideas de platos de comida en base a los que dispone y las preferencias que tiene.

Users outcomes
Los usuarios pueden encontrar recetas que se ajusten a sus ingredientes disponibles y preferencias alimenticias de manera eficiente.
Los usuarios tienen un mayor control sobre los alimentos que consumen gracias a la información nutricional precisa proporcionada. 
Los usuarios pueden explorar una amplia variedad de recetas, lo que les permite diversificar sus comidas y experimentar con nuevos platos.

Business outcomes
Aumento de la satisfacción del usuario debido a las recomendaciones de recetas personalizadas y precisas, lo que puede llevar a un mayor uso del servicio.
Mejora de la reputación del servicio debido a la precisión de la información nutricional proporcionada.
Expansión de la base de usuarios a medida que el servicio se vuelve más útil y relevante para una variedad de preferencias dietéticas y disponibilidad de ingredientes.

Features
¿Qué características son importantes? 
Sistema de filtrado avanzado, que se adapte en base a los ingredientes que dispone el usuario y a diferentes preferencias.
Información nutritiva precisa y detallada para cada receta recomendada. Esta puede incluir calorías, proteínas, carbohidratos, grasas, vitaminas y minerales.
Base de datos de recetas amplia que logre garantizar una alta variedad de opciones alimenticias, la cual se actualiza constantemente.
¿Cómo debería verse y comportarse nuestro servicio?
Debe tener un aspecto visualmente atractivo, contar con una facilidad de uso y utilizar una interfaz intuitiva e interactiva. El ingreso de preferencias e ingredientes de los usuarios debe realizarse de forma sencilla y las recomendaciones que surjan deben presentarse de manera atractiva, utilizando imágenes e información nutricional visibles de forma rápida y eficiente.


#### 1.2.2.3. Lean UX Hypothesis Statements.
Hypothesis 1

Creemos que si mejoramos el sistema de filtrado para que las recomendaciones de recetas se ajusten más precisamente a los ingredientes disponibles y preferencias alimenticias de los usuarios, entonces esperamos ver un aumento en la satisfacción del usuario y un mayor uso del servicio.

Hypothesis 2

Creemos que si proporcionamos información nutricional precisa y detallada para cada receta recomendada, entonces esperamos que los usuarios tengan un mayor control sobre los alimentos que consumen, lo que puede llevar a una mejora en la reputación del servicio y una expansión de la base de usuarios.

Hypothesis 3

Creemos que si mantenemos una base de datos de recetas amplia y constantemente actualizada, entonces esperamos que los usuarios se mantengan comprometidos y fomenten el uso repetido del servicio.

Hypothesis 4

Creemos que si implementamos un sistema de filtrado avanzado y una interfaz de usuario intuitiva e interactiva, entonces esperamos ver un aumento en la satisfacción del usuario y la adopción del servicio.

Hypothesis 5

Creemos que si satisfacemos las necesidades de los usuarios de manera efectiva, entonces podemos esperar un aumento en la retención de usuarios y una expansión de nuestra base de usuarios.
Si mejoramos continuamente nuestras características y servicios basados en los comentarios de los usuarios, entonces podemos esperar mantenernos competitivos en el mercado.

#### 1.2.2.4. Lean UX Canvas.
![leanUx](images/leanUx1.png)
![leanUx](images/leanUx2.png)

## 1.3. Segmentos objetivo.
Nuestro segmento objetivo está compuesto por 2 tipos de usuarios principalmente:
Cocinero Inexperto:
Para el desarrollo de MealMaster se consideró a cocineros inexpertos que buscan mejorar sus habilidades culinarias y disfrutar de una alimentación más saludable sin la necesidad de experiencia previa en la cocina. Nuestra plataforma brinda una interfaz amigable y muy fácil de usar, donde los cocineros inexpertos  pueden aprender a preparar comidas sencillas y nutritivas, utilizando recetas adaptadas a sus preferencias y disponibilidad de ingredientes. Con tutoriales paso a paso y consejos personalizados, ayudamos a estos cocineros novatos a ganar confianza en la cocina, fomentando un estilo de vida más saludable y autosuficiente.Además, nuestra plataforma presenta un apartado para organizar y diseñar planes alimenticios, los cuales un cocinero inexperto podría aprovechar para cocinar su propio plan.

![segmento](images/cocineroexperto.png)


Entusiasta de la Nutrición:
Para los entusiastas de la nutrición que están comprometidos con una alimentación saludable y buscan optimizar su dieta, MealMaster ofrece una solución perfecta. Nuestra plataforma permite a los entusiastas de la nutrición a acceder a recetas nutritivas personalizadas según sus objetivos de salud específicos, preferencias dietéticas y necesidades calóricas. Con información detallada sobre el contenido nutricional de cada plato. MealMaster se convierte en un aliado indispensable para aquellos que desean tomar decisiones informadas sobre su alimentación y mejorar continuamente su bienestar. De igual manera en el apartado de organizar y diseñar plan alimenticio, el entusiasta de la nutrición  puede visualizar el contenido nutricional y su progreso.

![segmento](images/nutricion.png)


# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
En el mercado de recetas en línea enfocadas en productos relacionados con la comida saludable, Meal Master se encuentra en un entorno competitivo. A continuación, se presentan los principales competidores directos: 

### 2.1.1. Análisis competitivo.
![competitivo](images/competitivo1.png)
![competitivo](images/competitivo2.png)
![competitivo](images/competitivo3.png)
![competitivo](images/competitivo4.png)
2.1.2. Estrategias y tácticas frente a competidores: 

Liderazgo en costes:
Tenemos la capacidad de producir y ofrecer nuestro producto de manera gratuita, sin agregar limitaciones a sus funciones principales. Asimismo, para las membresías de pago, podemos ofrecer un precio inferior al de nuestros competidores, con la intención de hacer de nuestra aplicación una opción más atractiva. Y también, orientándose a satisfacer las necesidades de nuestros clientes que enfocan su decisión de compra en el precio.
Estrategia de diferenciación:
Tenemos la capacidad de producir y ofrecer nuestro producto de manera gratuita, sin agregar limitaciones a sus funciones principales. Asimismo, para las membresías de pago, podemos ofrecer un precio inferior al de nuestros competidores, con la intención de hacer de nuestra aplicación una opción más atractiva. Y también, orientándose a satisfacer las necesidades de nuestros clientes que enfocan su decisión de compra en el precio.


Estrategia de enfoque:
Somos conscientes que el crecimiento de la tecnología y el incremento en el uso de computadoras y smartphones, han generado una gran demanda en los servicios de gestión y guías gastronómicas. Por ello, nos enfocamos en toda aquella persona que se dedique o quiera dedicarse a la cocina y que requiera un software que le ayude con el correcto uso de sus productos para realizar recetas. 


Táctica de expansión:
A pesar de que la aplicación funciona de manera gratuita. No planeamos saturar de anuncios por cada operación que se realice con ella. Planeamos expandir su uso a través de buenas calificaciones y anuncios.


## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

Preguntas Generales
¿Cuál es su nombre completo?
¿Dónde vive actualmente?
¿Cuál es su fecha de nacimiento?
¿Cuál es su ocupación actual?
¿Tiene experiencia en la cocina? ¿Suele prepararse sus propias comidas?
¿Se encuentra interesado en realizar un seguimiento del valor nutricional de los alimentos que consume?

Preguntas para ambos segmentos
¿Cuáles son los desafíos más comunes que encuentras al planificar tus comidas diarias?
¿Cómo decides qué recetas preparar con los ingredientes que tienes a mano?
¿Qué tipo de información nutricional consideras más importante al elegir una receta?
¿Podrías contarme sobre una experiencia reciente en la que hayas cocinado algo nuevo?
¿Cómo afecta tu rutina diaria la planificación y preparación de tus comidas?
¿Qué te motiva a seguir un plan de alimentación o a cocinar por ti mismo?
¿Qué características valorarías en una aplicación que te ayude a organizar tus comidas?
¿Cómo te gustaría que una aplicación web te asistiera en el seguimiento de tus objetivos nutricionales?
¿Qué te impulsa a buscar nuevas recetas o cambiar tu dieta actual?
¿Cómo evalúas el éxito de tu plan de comidas y nutrición?
Preguntas para el Cocinero Inexperto:
¿Qué tipo de recetas te gustaría ver recomendadas cuando no estás seguro de qué cocinar?
¿Cómo te sientes al probar técnicas de cocina nuevas y cómo te gustaría que una aplicación te guiará en ese proceso?
¿Qué ingredientes sueles tener en tu despensa y cómo decides utilizarlos?
¿Qué factores consideras más intimidantes o desafiantes al momento de cocinar?
Preguntas para la Persona Interesada en el Seguimiento Nutricional:
¿Qué metas específicas tienes en mente al buscar un seguimiento nutricional detallado?
¿Qué herramientas o métodos has utilizado anteriormente para hacer seguimiento de tu dieta y qué te gustaría mejorar?
¿Cómo te mantienes informado sobre nutrición y qué tipo de información buscas regularmente?
¿Qué aspectos de tu salud o bienestar esperas mejorar al tener un mayor control sobre lo que consumes?

### 2.2.2. Registro de entrevistas.
**URL del video completo:** https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing 
**Cocinero Inexperto**  
![Imagen de entrevista](images/entrevista1.png)  

**Timing: 10:35 min**
**Resumen**
El entrevistado de nombre Daniel, comenta que reside en lima, nació en 2002 y estudia la carrera de Ing. de Sistemas. 
No tiene ningún tipo de experiencia en la cocina. Está muy interesado en aprender y nuestra solución le parece bastante interesante, se considera un amante 
de la tecnología y resalta su gusto por la sazón peruana, por lo que quisiera poder aprender a preparar platillos nacionales. En definitiva sería un usuario de Meal Master.

**Entrevista2**
**URL del video completo:** https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing 

![Imagen de entrevista](images/entrevista2.png)  
**Timing: 10:46 min**
**Resumen**
El entrevistado de nombre Augusto, reside en Lima, nació en 2005, es estudiante de Ing. de Software.Por lo general no suele cocinar, sin embargo, cuando lo hace, suelen ser cosas muy sencillas. Menciona también la importancia para él, de llevar una buena alimentación. 
Le parece genial la idea de una herramienta digital que le permita no solo aprender a cocinar, sino también elaborar un plan nutricional. Resalta que la complementación 
de las 2 características de la solución, hace que sea mucho mejor y de todas maneras sería un usuario.

**Entrevista3**
**URL del video completo:** https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing 

![Imagen de entrevista](images/entrevista3.png)  
**Timing: 12:29 min**
**Resumen**

El entrevistado de nombre Fritz, es un joven Piurano de 20 años, estudiante de Derecho. 
La cocina no es su punto fuerte, pese a eso, es capaz de preparar recetas únicamente viendo tutoriales. Le parece muy importante seguir una buena alimentación y que mejor, que poder uno mismo cocinarse. Al mencionarle que en nuestra solución también 
puede llevar un control de su alimentación, le pareció un increíble plus. Indica que si o si será un usuario.

**Entrevista4**
**URL del video completo:**  https://youtu.be/5sxKK-3rASc 

![Imagen de entrevista](images/entrevista4.png)  
**Timing: 09:34 min**
**Resumen**
La entrevista fue realizada a Diego Servan. Es ingeniero Industrial, trabaja en el banco . Durante estos años ha logrado combatir con la falta de conocimiento al momento de llevar su comida al trabajo, ya que no conoce muchos platos por cocinar y no tiene muchas ideas de recetas diarias para lograr realizarlo. Sin embargo, Diego se ha ido apoyando de algunas recetas saludables que lograba encontrar en internet , pero no logra realizarlo bien. De hecho, nos comenta que no le gusta cocinar mucho porque no conoce un buen recetario que él pueda realizar.Por último, nos comenta que una aplicación que ayude a conocer distintas recetas le parece una idea excelente y muy interesante.

**Segmento objetivo 2: Entusiasta de la nutrición**

**Entrevista5**
**URL del video completo:**  https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing 
![Imagen de entrevista](images/entrevista5.png)  
**Timing: 6:44 min**
**Resumen**
El entrevistado de nombre Cesar, reside en Lima, tiene 19 años y estudia Ing de Software. 
Es un amante de la cocina, suele cocinar en su hogar. Sin embargo, Cesar está muy interesado en controlar y llevar un correcto plan alimenticio. Con el cual, logre su objetivo. Lo ideal para él, es algo que sea práctico, sin muchas complicaciones, y con lo cual pueda cumplir su objetivo. Una vez explicado el funcionamiento y determinadas funcionalidades específicas de nuestra solución, Cesar menciona lo entusiasmado que se encuentra por  poder usar una herramienta de este tipo. 

**Entrevista6**
**URL del video completo:**  https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing 
![Imagen de entrevista](images/entrevista6.png)  
**Timing:  7:39 min**
**Resumen**
El entrevistado de nombre Bruno, reside en Lima , tiene 21 años. 
Menciona que tiene experiencia en la cocina, pero se encuentra muy interesado en mejorar su alimentación en cuanto a calidad y organización de sus alimentos.
Hace ejercicio y parte de su objetivo es hacer un plan nutricional detallado. 
El cual pueda planear sus alimentos para complementarlo con la actividad física que realiza. Hace referencia a que prefiere cocinar en casa, por temas de ahorro, higiene y rapidez.Finalmente, luego de haber expuesto el plan de Meal Master, afirmó que utilizaría y recomendaría nuestra solución. 

**Entrevista7**
**URL del video completo:**  https://youtu.be/Lc20DusLN_c 
![Imagen de entrevista](images/entrevista7.png)  
**Timing:  11:34 min**
**Resumen**
La entrevista fue realizada a Andrea Estrada. Es administradora de empresas desde hace 2 años, trabaja en una empresa de venta de etiquetas evaluando los requerimientos de la empresa en la cual trabaja, brinda prioridad al crecimiento de la empresa.
Durante estos años ha logrado combatir con la falta de conocimiento al momento de llevar su comida al trabajo, ya que no conoce muchos platos por cocinar y no tiene muchas ideas de recetas diarias para lograr realizarlo. Sin embargo, Andrea se ha ido apoyando de algunas recetas saludables que lograba encontrar en internet y le salen deliciosas, pero sin alguna indicación de cómo realizarlo no podría lograrlo. De hecho, nos comenta que no le gusta comer siempre lo mismo, ya que se aburre rápido y siempre le gusta probar cosas nuevas.
Por último, nos comenta que una aplicación que ayude a conocer distintas recetas y que sean saludables le parece una idea excelente y muy interesante, ya que ella cuida mucho su salud y le gustaría saber la cantidad de calorías que consume para lograr su objetivo que es bajar de peso.



### 2.2.3. Análisis de entrevistas.

Segmento 1: Cocinero Inexperto 
Interés Común: Todos desean aprender a cocinar.
Necesidad Clave: Requieren videotutoriales sencillos.
Solución Potencial: Implementar guías paso a paso y videos interactivos.

Sugerencias Específicas:
Introducir una función de tutoriales en video para platillos básicos.
Incluir sugerencias de recetas basadas en ingredientes fáciles de encontrar.
Añadir una función de planificador de comidas que genere listas de compras automáticamente.


Segmento 2: Entusiasta de la Nutrición
Interés Común: Mejorar la nutrición y el control alimenticio.
Necesidad Clave: Herramientas para la gestión y el seguimiento nutricional.
Solución Potencial: Integrar funciones de personalización y seguimiento de dietas.

Sugerencias Concretas:
Implementar un sistema de configuración de objetivos nutricionales con recomendaciones personalizadas.
Desarrollar un contador de calorías y macros para cada receta.
Crear opciones de planificación de menús semanales con listas de compras automatizadas.

## 2.3. Needfinding.
### 2.3.1. User Personas.
2.3.1. User Personas

Para garantizar una comprensión profunda de nuestros segmentos objetivo, hemos llevado a cabo un exhaustivo proceso de elaboración de User Personas. Hemos creado un User Persona para cada uno de los segmentos clave que hemos identificado

**User Persona 1: Cocinero Inexperto**
![Imagen User Persona 1](images/user1.png)
**User Persona 2: Entusiasta de la nutrición**
![Imagen User Persona 1](images/user2.png)


### 2.3.2. User Task Matrix.
En esta sección se presenta el user task matrix, herramienta centrada en los segmentos objetivos, que nos permitirá identificar las tareas y objetivos claves de los usuarios. Además, nos permitirá priorizar características y funcionalidades al momento de realizar el product backlog. Para la frecuencia se han considerado cinco opciones: never, rarely, sometimes, often, always; y para la importancia tres opciones: low, medium, high.

![UserTax](images/usertax.png)

### 2.3.4. Empathy Mapping.
En esta sección se presenta el Empathy Mapping, herramienta para crear un perfil detallado de los user persona y desarrollar una comprensión profunda de su perspectiva y experiencia.

**Empathy Mapping 1: Cocinero Inexperto**
![Empathy Map Segmento1](images/mapping1.png)

**Empathy Mapping 2: Entusiasta de la nutrición**
![Empathy Map Segmento1](images/mapping2.png)


### 2.3.5. As-is Scenario Mapping.

**As-is Scenario Mapping 1: Cocinero Inexperto**  
|Fases| Investigar páginas web de nutrición y para aprender a cocinar |Analizar los planes de cada una de las páginas encontradas | Escoger la página web más confiable|Empezar a estructurar un plan alimenticio en la web| Filtrar mis preferencias alimenticias|
|-|-|-|-|-|-|
| Doing  | Investigo en internet páginas web de confianza para aprender a cocinar y revisar el valor nutricional de mis platos de comida |Analizar los planes que veo recomendable para lo que busco.|En base a mi previo análisis, escojo la página web más prometedora.|Dentro de la página web, busco realizar la organización de mi plan de alimentos según mis preferencias.|Busco aplicar ciertos filtros para disfrutar del plan alimentario organizado.|
| Thinking  |Espero que existan múltiples plataformas web que ayuden al proceso de cocina. |Ojalá los planes ofrecidos tengan un valor adicional.|Espero haber elegido la página web más confiable de las disponibles.|Espero organizar de forma rápida y efectiva un plan de alimentos.|Espero que el plan alimenticio sea suficientemente efectivo.|
|Feeling|Tengo dudas al momento de investigar y conocer cuál es la opción más conveniente.|Miedo por escoger un plan con información desactualizada.|Siento dudas sobre la seguridad de la página web, pudiendo no ser confiable.|Siento dudas al momento de pensar en los detalles del plan alimenticio por generar, pudiendo ser impráctico.|Me siento aliviado, sabiendo que mis necesidades van a ser saciadas en base a mi correcta elección.|

**To-Be Scenario Mapping 2: Entusiasta de la nutrición**  
|Fases|Investigar páginas web que puedan medir lo que consumo (kcl)|Analizar los planes de cada una de las páginas encontradas.|Escoger la página web más confiable|Ponerme en contacto con un especialista |Filtrar mis preferencias alimenticias |
|-|-|-|-|-|-|
|Doing|Investigo en internet páginas web de confianza para medir los alimentos que consumo|Analizar los planes que veo recomendable para lo que busco.|En base a mi previo análisis, escojo la página web más prometedora.|Dentro de la página web, busco contactarme con un especialista ideal|Busco aplicar ciertos filtros para disfrutar del plan alimentario organizado.|
|Thinking|Espero que existan múltiples plataformas web que ayuden al proceso de cocina.|Ojalá los planes ofrecidos tengan un valor adicional.|Espero haber elegido la página web más confiable de las disponibles.|Espero dialogar con el especialista para organizar de forma rápida y efectiva un plan de alimentos.|Espero que el plan alimenticio sea suficientemente efectivo.|
|Feeling|Tengo dudas al momento de investigar y conocer cuál es la opción más conveniente.|Miedo por escoger un plan con información desactualizada.|Siento dudas sobre la seguridad de la página web, pudiendo no ser confiable.|Siento dudas al momento de esperar contactarme con el especialista.|Me siento aliviado, sabiendo que mis necesidades van a ser saciadas en base a mi correcta elección.|


# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

**To-Be Scenario Mapping 1: Cocinero Inexperto**  

|Fases|Investigar páginas web de nutrición y para aprender a cocinar|Analizar los planes de cada una de las páginas encontradas.|Escoger la página web más confiable|Empezar a estructurar un plan alimenticio en la web|Filtrar mis preferencias alimenticias |
|-|-|-|-|-|-|
|Doing|Investigó páginas web con la finalidad de mejorar mi alimentación y aprender a cocinar con los ingredientes que tengo|Analizar los planes de cada uno de las posibles opciones, teniendo en cuenta la calidad y el precio del servicio|Inclinarse por la nueva app innovadora “Meal Master” que he visto que es muy buena entre el público|Busco organizar adecuadamente un plan para mi alimentación sana, con una dieta equilibrada.|Poder agregar tus preferencias alimenticias para no tener inconvenientes con mi plan.|
|Thinking|Ojalá pueda encontrar de preferencia una app que sea eficiente para  organizar mi alimentación y aprender a cocinar |Espero que el plan de la aplicación valga la pena y cubra todas mis necesidades, para aprender a cocinar con lo que tengo. |Espero que no sea demasiado tedioso tener que usar la aplicación web y no tener problemas.|Espero que la app pueda organizar un buen plan y enseñarme cómo cocinar el plan organizado.|Espero que la app pueda buscar buenos resultados según mis filtros.|
|Feeling|Curiosidad por las nuevas apps para aprender a cocinar con lo que tengo y que organice mi alimentación.|Siento que los planes valen la pena, porque me ayudarán en mi objetivo y espero no sea muy costoso.|Siento confianza de que mis datos personales no sean utilizados de mala manera|Curiosidad por ver como organiza y estructura un plan , y me ayuda a aprender a cocinar con lo que dispongo.|Felicidad porque puedo filtrar mis gustos, y así, no tener problemas para cumplir mi meta.|

**To-Be Scenario Mapping 2: Clientes que buscan medir las calorías que consumen y llevar un control más detallado, de igual manera con el contacto de un profesional a su disposición.**  
|Fases|Investigar páginas web que puedan medir lo que consumo (kcl)|Analizar los planes de cada una de las páginas encontradas.|Escoger la página web más confiable|Ponerme en contacto con un especialista |Filtrar mis preferencias alimenticias |
|-|-|-|-|-|-|
|Doing|Investigó páginas web con la finalidad de medir las calorías que consumo y llevar un control. |Analizar los planes de cada uno de las posibles opciones, teniendo en cuenta la calidad y el precio del servicio|Inclinarse por la nueva app innovadora “Meal Master” que he visto que es muy buena entre el público, y dispone de profesionales para consultas.|Busco en la app web, el apartado para ponerme en contacto con un especialista.|Poder agregar tus preferencias alimenticias para no tener inconvenientes con mi plan.|
|Thinking|Ojalá pueda encontrar de preferencia una app que sea eficiente para  llevar el control de mi alimentación, y así llegar a mi objetivo más rápido.|Espero que el plan de la aplicación valga la pena y cubra todas mis necesidades.|Espero que no sea demasiado tedioso tener que usar la aplicación web y no tener problemas.|Espero que el especialista pueda brindarme tips o recomendaciones en base a mi progreso, de igual manera responder mis dudas.|Espero que la app pueda buscar buenos resultados según mis filtros.|
|Feeling|Curiosidad por las nuevas apps que te permiten medir y controlar las calorías que consumes.|Siento que los planes valen la pena, porque me ayudarán en mi objetivo y espero no sea muy costoso.|Siento confianza de que mis datos personales no sean utilizados de mala manera|Siento tranquilidad al saber que un especialista me puede asesorar y responder dudas..|Felicidad porque puedo filtrar mis gustos, y así, no tener problemas para cumplir mi meta.|

## 3.2. User Stories.

# User Stories

## 01 Implementación de landing page responsive

**Título:** Implementación de landing page responsive  
**Descripción:** Como visitante, quiero interactuar con un landing page responsive, que se adapte a mi pantalla.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso exitoso a la landing page responsive**  
Dado que un visitante accede a la landing page desde cualquier dispositivo con conexión a internet  
Cuando carga la landing page en su dispositivo  
Entonces la landing page se adapta de manera fluida y eficiente a la pantalla del dispositivo del visitante, garantizando una experiencia de usuario óptima y fácil navegación.  

**Scenario 02: Problemas de adaptación en la landing page responsive**  
Dado que un visitante accede a la landing page desde cualquier dispositivo con conexión a internet  
Cuando carga la landing page en su dispositivo  
Entonces la landing page presenta problemas de visualización o funcionalidad en ciertos dispositivos, lo que dificulta la experiencia del visitante y puede llevar a una percepción negativa de la marca.  

## 02 Visualizar redes sociales de MealMaster

**Título:** Visualizar redes sociales de MealMaster  
**Descripción:** Como visitante, quiero visualizar las redes sociales de MealMaster.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a las redes sociales de MealMaster**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca las redes sociales de la marca  
Entonces encuentra fácilmente enlaces visibles y accesibles a las redes sociales de MealMaster, como Facebook, Twitter, Instagram, etc., lo que le permite seguir la marca y estar al tanto de sus novedades y actividades.  

**Scenario 02: Dificultad para encontrar las redes sociales de MealMaster**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca las redes sociales de la marca  
Entonces tiene problemas para encontrar enlaces a las redes sociales de MealMaster, lo que le dificulta seguir la marca en sus plataformas sociales y puede afectar su percepción de la presencia en línea de la empresa.  

## 03 Ver ejemplos de planes de alimentación en la página de inicio

**Título:** Ver ejemplos de planes de alimentación en la página de inicio  
**Descripción:** Como visitante, quiero ver ejemplos de planes de alimentación en la página de inicio para tener una idea de lo que puedo lograr con la aplicación.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a ejemplos de planes de alimentación en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca ejemplos de planes de alimentación  
Entonces encuentra fácilmente una sección dedicada que presenta ejemplos de planes de alimentación elaborados con la aplicación, mostrando variedad de opciones y ejemplos de comidas para inspirar y ayudar al visitante a comprender el potencial de la aplicación.  

**Scenario 02: Dificultad para encontrar ejemplos de planes de alimentación en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca ejemplos de planes de alimentación  
Entonces tiene problemas para encontrar ejemplos de planes de alimentación, lo que dificulta su comprensión del potencial de la aplicación y puede afectar su interés en explorar más a fondo.  

## 04 Ver una página de inicio atractiva con beneficios clave de MealMaster

**Título:** Ver una página de inicio atractiva con beneficios clave de MealMaster  
**Descripción:** Como visitante, quiero ver una página de inicio atractiva que me muestre rápidamente los beneficios clave de MealMaster para que pueda decidir si quiero registrarme.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso a una página de inicio atractiva con beneficios clave de MealMaster**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre los beneficios de la aplicación  
Entonces encuentra una página de inicio atractiva y bien diseñada que destaca rápidamente los beneficios clave de MealMaster, como planificación de comidas personalizadas, seguimiento de nutrientes, recetas saludables, etc., lo que le permite tomar una decisión informada sobre si quiere registrarse o no.  

**Scenario 02: Dificultad para encontrar beneficios clave en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre los beneficios de la aplicación  
Entonces tiene problemas para identificar rápidamente los beneficios clave de MealMaster, lo que dificulta su toma de decisiones sobre si quiere registrarse o no.  

## 05 Ver testimonios y reseñas de otros usuarios satisfechos en la página de inicio

**Título:** Ver testimonios y reseñas de otros usuarios satisfechos en la página de inicio  
**Descripción:** Como visitante, quiero ver testimonios y reseñas de otros usuarios satisfechos en la página de inicio para ganar confianza en la aplicación.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a testimonios y reseñas en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca testimonios y reseñas de otros usuarios  
Entonces encuentra fácilmente una sección dedicada que muestra testimonios y reseñas auténticas de otros usuarios satisfechos con la aplicación, lo que le proporciona confianza en la calidad y efectividad de MealMaster.  

**Scenario 02: Dificultad para encontrar testimonios y reseñas en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca testimonios y reseñas de otros usuarios  
Entonces tiene problemas para encontrar una sección que muestre testimonios y reseñas, lo que afecta su confianza en la aplicación y puede disminuir su interés en registrarse.  

## 06 Navegar fácilmente por las características clave de MealMaster

**Título:** Navegar fácilmente por las características clave de MealMaster  
**Descripción:** Como visitante, quiero poder navegar fácilmente por las características clave de MealMaster, como la creación de platillos y planes alimenticios, para comprender rápidamente cómo la aplicación puede ayudarme.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a características clave de MealMaster**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre las características clave de la aplicación  
Entonces encuentra fácilmente una navegación clara y organizada que le permite explorar las características clave de MealMaster, como la creación de platillos, la planificación de planes alimenticios, el seguimiento de nutrientes, entre otros, lo que le ayuda a comprender rápidamente cómo la aplicación puede beneficiarlo.  

**Scenario 02: Dificultad para navegar por las características clave de MealMaster**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre las características clave de la aplicación  
Entonces tiene problemas para encontrar una navegación clara y organizada que le permita explorar las características clave de MealMaster, lo que dificulta su comprensión sobre cómo la aplicación puede beneficiarlo y puede disminuir su interés en registrarse.  

## 07 Encontrar fácilmente información sobre precios y planes en la página de inicio

**Título:** Encontrar fácilmente información sobre precios y planes en la página de inicio  
**Descripción:** Como visitante, quiero encontrar fácilmente información sobre precios y planes disponibles en la página de inicio, para evaluar si el producto se ajusta a mis necesidades y presupuesto.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a información sobre precios y planes en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre precios y planes disponibles  
Entonces encuentra fácilmente una sección dedicada que presenta de manera clara y detallada los precios y planes disponibles de MealMaster, lo que le permite evaluar si el producto se ajusta a sus necesidades y presupuesto.  

**Scenario 02: Dificultad para encontrar información sobre precios y planes en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca información sobre precios y planes disponibles  
Entonces tiene problemas para encontrar una sección que presente claramente los precios y planes disponibles, lo que dificulta su evaluación del producto y puede disminuir su interés en registrarse.  

## 08 Ver información sobre el servicio premium y beneficios extras en la landing page

**Título:** Ver información sobre el servicio premium y beneficios extras en la landing page  
**Descripción:** Como visitante, quiero ver información sobre el servicio premium de MealMaster y sus beneficios extras en la landing page, para decidir si quiero suscribirme.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a información sobre el servicio premium y beneficios extras en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca información sobre el servicio premium y beneficios extras  
Entonces encuentra fácilmente una sección dedicada que presenta de manera clara y detallada los beneficios del servicio premium de MealMaster, así como los extras que ofrece en comparación con la versión gratuita, lo que le permite tomar una decisión informada sobre si suscribirse o no.  

**Scenario 02: Dificultad para encontrar información sobre el servicio premium y beneficios extras en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca información sobre el servicio premium y beneficios extras  
Entonces tiene problemas para encontrar una sección que presente claramente los beneficios del servicio premium y los extras, lo que dificulta su toma de decisiones sobre si suscribirse o no.  

## 09 Encontrar información sobre los colaboradores del proyecto en la landing page

**Título:** Encontrar información sobre los colaboradores del proyecto en la landing page  
**Descripción:** Como visitante, quiero encontrar información sobre los colaboradores del proyecto en la landing page, para saber quiénes están detrás de la aplicación y qué experiencia tienen.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a información sobre los colaboradores del proyecto en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca información sobre los colaboradores del proyecto  
Entonces encuentra fácilmente una sección dedicada que presenta información sobre los colaboradores del proyecto, incluyendo sus nombres, roles, experiencia relevante y contribuciones al desarrollo de la aplicación, lo que le brinda confianza y transparencia sobre quiénes están detrás de la aplicación.  

**Scenario 02: Dificultad para encontrar información sobre los colaboradores del proyecto en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca información sobre los colaboradores del proyecto  
Entonces tiene problemas para encontrar una sección que presente claramente información sobre los colaboradores del proyecto, lo que puede generar dudas sobre la transparencia y credibilidad de la aplicación.  

## 10 Encontrar fácilmente la información de contacto de la empresa en la página de inicio

**Título:** Encontrar fácilmente la información de contacto de la empresa en la página de inicio  
**Descripción:** Como visitante, quiero encontrar fácilmente la información de contacto de la empresa en la página de inicio, para saber quiénes están detrás.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a la información de contacto de la empresa en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca la información de contacto de la empresa  
Entonces encuentra fácilmente una sección dedicada que presenta información de contacto clara y visible, como dirección de correo electrónico, número de teléfono y dirección física de la empresa, lo que le permite saber quiénes están detrás de la aplicación y cómo pueden ser contactados.  

**Scenario 02: Dificultad para encontrar la información de contacto de la empresa en la página de inicio**  
Dado que un visitante carga la página de inicio de MealMaster  
Cuando busca la información de contacto de la empresa  
Entonces tiene problemas para encontrar una sección que presente claramente la información de contacto de la empresa, lo que dificulta su comprensión sobre quiénes están detrás de la aplicación y cómo pueden ser contactados.  

## 11 Ver ejemplos visuales de platillos variados y atractivos en la landing page

**Título:** Ver ejemplos visuales de platillos variados y atractivos en la landing page  
**Descripción:** Como visitante, deseo ver ejemplos visuales de platillos variados y atractivos en la landing page, para sentirme motivado en probar la aplicación web.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a ejemplos visuales de platillos en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca ejemplos visuales de platillos  
Entonces encuentra fácilmente una sección que presenta imágenes atractivas y variadas de platillos elaborados con la aplicación, mostrando su aspecto visualmente atractivo y apetitoso, lo que le motiva a probar la aplicación web.  

**Scenario 02: Dificultad para encontrar ejemplos visuales de platillos en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca ejemplos visuales de platillos  
Entonces tiene problemas para encontrar una sección que presente claramente ejemplos visuales de platillos, lo que disminuye su motivación para probar la aplicación web.  

## 12 Ver ejemplos de planes semanales adaptados a diferentes objetivos en la landing page

**Título:** Ver ejemplos de planes semanales adaptados a diferentes objetivos en la landing page  
**Descripción:** Como visitante, deseo ver en la landing page ejemplos de planes semanales adaptados a diferentes objetivos (perder grasa, ganar masa muscular, etc.), para comprender cómo MealMaster puede ayudarme a alcanzar mis metas.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a ejemplos de planes semanales adaptados a diferentes objetivos en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca ejemplos de planes semanales  
Entonces encuentra fácilmente una sección que presenta ejemplos de planes semanales adaptados a diferentes objetivos, como perder grasa, ganar masa muscular, mantener el peso, etc., lo que le ayuda a comprender cómo MealMaster puede ayudarlo a alcanzar sus metas de forma personalizada.  

**Scenario 02: Dificultad para encontrar ejemplos de planes semanales en la landing page**  
Dado que un visitante carga la landing page de MealMaster  
Cuando busca ejemplos de planes semanales  
Entonces tiene problemas para encontrar una sección que presente claramente ejemplos de planes semanales adaptados a diferentes objetivos, lo que dificulta su comprensión sobre cómo MealMaster puede ayudarlo a alcanzar sus metas de forma personalizada.  

## 13 Cambio de contraseña en MealMaster

**Título:** Cambio de contraseña en MealMaster  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder cambiar mi contraseña por si deseo añadirle mayor seguridad a mi cuenta.  
**Criterios de Aceptación:**  

**Scenario 01: Cambio exitoso de contraseña**  
Dado que un usuario interesado en alimentación saludable desea cambiar su contraseña en MealMaster  
Cuando accede a la configuración de su cuenta y selecciona la opción de cambiar contraseña  
Entonces se le solicita ingresar su contraseña actual y luego ingresar y confirmar la nueva contraseña, y una vez completado el proceso, la contraseña se actualiza satisfactoriamente.  

**Scenario 02: Error al cambiar la contraseña**  
Dado que un usuario interesado en alimentación saludable desea cambiar su contraseña en MealMaster  
Cuando intenta cambiar la contraseña, pero ingresa incorrectamente su contraseña actual o no cumple con los criterios de seguridad  
Entonces se le muestra un mensaje de error indicando la razón por la cual no se pudo completar el cambio de contraseña, y se le brinda la oportunidad de intentarlo nuevamente.  

## 14 Filtrado de preferencias alimenticias

**Título:** Filtrado de preferencias alimenticias  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder filtrar mis preferencias para poder evitar que dentro de mi dieta haya algún alimento al que soy alérgico o no me gusta.  
**Criterios de Aceptación:**  

**Scenario 01: Filtrado exitoso de preferencias alimenticias**  
Dado que un usuario interesado en alimentación saludable desea filtrar sus preferencias alimenticias en MealMaster  
Cuando accede a la configuración de su cuenta y selecciona la opción de preferencias alimenticias  
Entonces puede especificar sus alergias alimenticias y alimentos que desea evitar, y una vez guardados los cambios, la aplicación filtra automáticamente los alimentos que no cumplen con estas preferencias en las recomendaciones y planes alimenticios.  

**Scenario 02: Dificultad para filtrar preferencias alimenticias**  
Dado que un usuario interesado en alimentación saludable desea filtrar sus preferencias alimenticias en MealMaster  
Cuando intenta acceder a la opción de preferencias alimenticias pero no encuentra la funcionalidad o el proceso es confuso  
Entonces se siente frustrado y puede abandonar el proceso de configuración, lo que limita su capacidad de personalizar su experiencia en la aplicación.  

## 15 Visualización de planes de alimentación personalizados

**Título:** Visualización de planes de alimentación personalizados  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder visualizar planes de alimentación personalizados en MealMaster, para tener una guía clara de mis comidas diarias.  
**Criterios de Aceptación:**  

**Scenario 01: Visualización exitosa de planes de alimentación personalizados**  
Dado que un usuario interesado en alimentación saludable desea visualizar planes de alimentación personalizados en MealMaster  
Cuando accede a la sección de planes alimenticios y selecciona su plan personalizado  
Entonces puede ver claramente las comidas recomendadas para cada día, incluyendo desayuno, almuerzo, cena y refrigerios, así como las recetas y cantidades de ingredientes necesarios, lo que le proporciona una guía clara para sus comidas diarias.  

**Scenario 02: Problemas al visualizar planes de alimentación personalizados**  
Dado que un usuario interesado en alimentación saludable desea visualizar planes de alimentación personalizados en MealMaster  
Cuando intenta acceder a su plan personalizado pero la información no se muestra correctamente o hay errores en las recetas o cantidades de ingredientes  
Entonces se siente frustrado y confundido, lo que puede afectar su experiencia y confianza en la aplicación.  

## 16 Modificar el método de pago en la aplicación

**Título:** Modificar el método de pago en la aplicación  
**Descripción:** Como usuario interesado en alimentación saludable, quiero tener la opción de modificar mi método de pago, por si deseo realizar compras con otra tarjeta.  
**Criterios de Aceptación:**  

**Scenario 01: Modificación exitosa del método de pago**  
Dado que un usuario interesado en alimentación saludable desea modificar su método de pago en MealMaster  
Cuando accede a la configuración de su cuenta y selecciona la opción de métodos de pago  
Entonces puede agregar una nueva tarjeta de crédito o débito, eliminar o editar las tarjetas existentes, y una vez guardados los cambios, el nuevo método de pago queda registrado para futuras transacciones.  

**Scenario 02: Dificultad para modificar el método de pago**  
Dado que un usuario interesado en alimentación saludable desea modificar su método de pago en MealMaster  
Cuando intenta acceder a la opción de métodos de pago pero encuentra dificultades técnicas o no encuentra la funcionalidad  
Entonces se siente frustrado y puede abandonar el proceso de modificación del método de pago, lo que limita su capacidad de gestionar sus opciones de pago en la aplicación.  

## 17 Eliminar permanentemente la cuenta de MealMaster

**Título:** Eliminar permanentemente la cuenta de MealMaster  
**Descripción:** Como usuario interesado en alimentación saludable, quiero tener la opción de eliminar permanentemente mi cuenta de MealMaster.  
**Criterios de Aceptación:**  

**Scenario 01: Eliminación exitosa de la cuenta de MealMaster**  
Dado que un usuario interesado en alimentación saludable desea eliminar permanentemente su cuenta de MealMaster  
Cuando accede a la configuración de su cuenta y selecciona la opción de eliminar cuenta  
Entonces se le solicita confirmar la eliminación de su cuenta y después de confirmar, su cuenta y todos los datos asociados se eliminan permanentemente del sistema.  

**Scenario 02: Dificultad para eliminar la cuenta de MealMaster**  
Dado que un usuario interesado en alimentación saludable desea eliminar permanentemente su cuenta de MealMaster  
Cuando intenta acceder a la opción de eliminar cuenta pero no encuentra la funcionalidad o encuentra dificultades técnicas  
Entonces se siente frustrado y puede abandonar el proceso de eliminación de cuenta, lo que limita su capacidad de gestionar su presencia en la aplicación.  

## 18 Observar en la plataforma las reseñas de recetas

**Título:** Observar en la plataforma las reseñas de recetas  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder observar las reseñas de los platos para tener mayor confianza en lo que prepararé.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a las reseñas de recetas**  
Dado que un usuario interesado en alimentación saludable desea ver las reseñas de recetas en MealMaster  
Cuando busca una receta específica o navega por las opciones de recetas  
Entonces encuentra fácilmente las reseñas de otros usuarios debajo de cada receta, mostrando sus comentarios y valoraciones, lo que le proporciona una mayor confianza en la calidad y gusto de los platos.  

**Scenario 02: Dificultad para encontrar las reseñas de recetas**  
Dado que un usuario interesado en alimentación saludable desea ver las reseñas de recetas en MealMaster  
Cuando busca las reseñas pero no encuentra la funcionalidad o no están disponibles para algunas recetas  
Entonces se siente frustrado y puede dudar sobre la calidad de los platos, lo que puede afectar su experiencia en la aplicación.  

## 19 Visualización de platos más destacados

**Título:** Visualización de platos más destacados  
**Descripción:** Como usuario interesado en alimentación saludable, quiero ver ejemplos de platos más destacados en la página de inicio para tener una idea de lo que puedo cocinar con la aplicación.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a platos más destacados en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca ejemplos de platos más destacados  
Entonces encuentra fácilmente una sección dedicada que presenta imágenes y descripciones de platos populares y bien valorados, lo que le proporciona inspiración y le ayuda a decidir qué cocinar con la aplicación.  

**Scenario 02: Dificultad para encontrar platos más destacados en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca ejemplos de platos más destacados pero la sección no está claramente visible o no está presente  
Entonces se siente frustrado y puede perderse de descubrir nuevas recetas y funcionalidades de la aplicación.  

## 20 Acceso a la calculadora de calorías

**Título:** Acceso a la calculadora de calorías  
**Descripción:** Como usuario interesado en alimentación saludable, quiero tener acceso a una calculadora de calorías en la página de inicio para poder estimar rápidamente mis necesidades calóricas diarias.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a la calculadora de calorías en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca acceso a una calculadora de calorías  
Entonces encuentra una sección claramente visible que ofrece una calculadora de calorías, donde puede ingresar información personalizada y obtener rápidamente estimaciones de sus necesidades calóricas diarias.  

**Scenario 02: Dificultad para encontrar la calculadora de calorías en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca acceso a una calculadora de calorías pero la funcionalidad no está visible o no está presente  
Entonces se siente frustrado y puede perderse de utilizar esta herramienta útil para su planificación dietética.  

## 21 Acceso a la sección de soporte al cliente

**Título:** Acceso a la sección de soporte al cliente  
**Descripción:** Como usuario interesado en alimentación saludable, quiero encontrar fácilmente la sección de soporte al cliente en la página de inicio para poder hacer preguntas o reportar problemas.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a la sección de soporte al cliente en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca la sección de soporte al cliente  
Entonces encuentra un enlace visible o un botón dedicado que lo dirige rápidamente a la sección de soporte al cliente, donde puede hacer preguntas, encontrar respuestas a problemas comunes y reportar cualquier problema que encuentre.  

**Scenario 02: Dificultad para encontrar la sección de soporte al cliente en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca la sección de soporte al cliente pero no la encuentra o está oculta  
Entonces se siente frustrado y puede tener dificultades para obtener ayuda o resolver problemas con la aplicación.  

## 22 Acceso a la sección de precios y planes

**Título:** Acceso a la sección de precios y planes  
**Descripción:** Como usuario interesado en alimentación saludable, quiero encontrar fácilmente la sección de precios y planes en la página de inicio para entender los costos asociados con el uso de la aplicación.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a la sección de precios y planes en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca la sección de precios y planes  
Entonces encuentra un enlace visible o un botón dedicado que lo lleva directamente a la sección de precios y planes, donde puede ver claramente las opciones disponibles, los costos asociados y los beneficios de cada plan de suscripción.  

**Scenario 02: Dificultad para encontrar la sección de precios y planes en la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster  
Cuando busca la sección de precios y planes pero no la encuentra o está oculta  
Entonces se siente frustrado y puede tener dificultades para entender los costos asociados con el uso de la aplicación, lo que puede afectar su decisión de suscribirse.  

## 23 Acceso a un tour guiado

**Título:** Acceso a un tour guiado  
**Descripción:** Como usuario interesado en alimentación saludable, quiero tener la opción de realizar un tour guiado por la aplicación desde la página de inicio para familiarizarme rápidamente con sus características.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil al tour guiado desde la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster por primera vez  
Cuando busca una manera de familiarizarse con las características de la aplicación  
Entonces encuentra un enlace o botón claramente visible que le permite acceder a un tour guiado, donde puede aprender rápidamente sobre las funcionalidades y cómo utilizar la aplicación de manera efectiva.  

**Scenario 02: Dificultad para acceder al tour guiado desde la página de inicio**  
Dado que un usuario interesado en alimentación saludable carga la página de inicio de MealMaster por primera vez  
Cuando busca una manera de familiarizarse con las características de la aplicación pero no encuentra el tour guiado o está oculto  
Entonces se siente frustrado y puede tener dificultades para comprender cómo utilizar la aplicación de manera efectiva.  

## 24 Registro de Ingredientes

**Título:** Registro de Ingredientes  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder registrar los ingredientes que tengo a la mano, para que la aplicación pueda sugerirme platillos que pueda preparar con ellos.  
**Criterios de Aceptación:**  

**Scenario 01: Registro exitoso de ingredientes**  
Dado que un usuario interesado en alimentación saludable desea registrar ingredientes en MealMaster  
Cuando accede a la sección de registro de ingredientes y agrega los ingredientes disponibles en su despensa  
Entonces la aplicación guarda los ingredientes registrados y utiliza esta información para sugerirle recetas que pueda preparar con los ingredientes disponibles.  

**Scenario 02: Dificultad para registrar ingredientes**  
Dado que un usuario interesado en alimentación saludable desea registrar ingredientes en MealMaster  
Cuando intenta registrar ingredientes pero encuentra dificultades técnicas o la funcionalidad no está clara  
Entonces se siente frustrado y puede abandonar el proceso, limitando su capacidad de recibir recomendaciones personalizadas de recetas.  

## 25 Filtros de Platillos

**Título:** Filtros de Platillos  
**Descripción:** Como usuario interesado en alimentación saludable, quiero poder aplicar filtros a las sugerencias de platillos, para que pueda elegir si quiero que sean saludables o no.  
**Criterios de Aceptación:**  

**Scenario 01: Aplicación exitosa de filtros a las sugerencias de platillos**  
Dado que un usuario interesado en alimentación saludable desea aplicar filtros en MealMaster  
Cuando busca la opción de aplicar filtros y selecciona criterios como saludable, vegetariano, bajo en carbohidratos, etc.  
Entonces la aplicación filtra las sugerencias de platillos según los criterios seleccionados, permitiéndole encontrar opciones que se ajusten a sus preferencias y necesidades dietéticas.  

**Scenario 02: Dificultad para aplicar filtros a las sugerencias de platillos**  
Dado que un usuario interesado en alimentación saludable desea aplicar filtros en MealMaster  
Cuando intenta aplicar filtros pero no encuentra la opción o la funcionalidad no está clara  
Entonces se siente frustrado y puede abandonar el proceso, limitando su capacidad de recibir recomendaciones personalizadas de recetas.  

## 26 Instrucciones de Cocina

**Título:** Instrucciones de Cocina  
**Descripción:** Como usuario interesado en alimentación saludable con habilidades de cocina baja, quiero que la aplicación me proporcione instrucciones paso a paso para preparar los platillos sugeridos, para que pueda aprender y mejorar mis habilidades de cocina.  
**Criterios de Aceptación:**  

**Scenario 01: Instrucciones claras y detalladas para preparar platillos**  
Dado que un usuario interesado en alimentación saludable con habilidades de cocina baja accede a la receta de un platillo sugerido  
Cuando busca las instrucciones de preparación  
Entonces encuentra instrucciones paso a paso que son claras, concisas y fáciles de seguir, lo que le permite preparar el platillo con confianza y mejorar sus habilidades culinarias.  

**Scenario 02: Dificultad para comprender las instrucciones de cocina**  
Dado que un usuario interesado en alimentación saludable con habilidades de cocina baja accede a la receta de un platillo sugerido  
Cuando las instrucciones de preparación son confusas o incompletas  
Entonces se siente frustrado y puede tener dificultades para preparar el platillo correctamente, lo que afecta su experiencia con la aplicación.  

## 27 Creación de Planes Alimenticios (Premium)

**Título:** Creación de Planes Alimenticios (Premium)  
**Descripción:** Como usuario premium, quiero poder crear planes alimenticios semanales basados en mis objetivos (perder grasa, ganar masa muscular, mantener un peso saludable), para que pueda seguir una dieta personalizada y alcanzar mis metas de salud.  
**Criterios de Aceptación:**  

**Scenario 01: Creación exitosa de planes alimenticios personalizados**  
Dado que un usuario premium accede a la funcionalidad de creación de planes alimenticios  
Cuando selecciona sus objetivos de salud y preferencias dietéticas  
Entonces puede crear fácilmente un plan alimenticio semanal personalizado que se ajuste a sus necesidades y metas, lo que le permite seguir una dieta estructurada y alcanzar sus objetivos de salud.  

**Scenario 02: Dificultades técnicas al crear planes alimenticios**  
Dado que un usuario premium accede a la funcionalidad de creación de planes alimenticios  
Cuando encuentra errores técnicos o la funcionalidad no está disponible  
Entonces se siente frustrado y no puede crear el plan alimenticio deseado, lo que limita su capacidad de seguir una dieta personalizada.  

## 28 Detalles de la Dieta (Premium)

**Título:** Detalles de la Dieta (Premium)  
**Descripción:** Como usuario premium, quiero que la aplicación me proporcione todos los detalles específicos (calorías, grasas, etc.) de la dieta que voy a consumir en mi día a día, para que pueda monitorear mi ingesta nutricional.  
**Criterios de Aceptación:**  

**Scenario 01: Acceso fácil a los detalles de la dieta diaria**  
Dado que un usuario premium accede a su plan alimenticio diario  
Cuando busca información detallada sobre calorías, grasas, proteínas, etc.  
Entonces encuentra fácilmente todos los detalles específicos de la dieta diaria, lo que le permite monitorear su ingesta nutricional y realizar ajustes según sea necesario.  

**Scenario 02: Información incompleta o difícil de encontrar sobre la dieta diaria**  
Dado que un usuario premium accede a su plan alimenticio diario  
Cuando la información detallada no está disponible o es difícil de encontrar  
Entonces se siente frustrado y no puede monitorear adecuadamente su ingesta nutricional, lo que afecta su experiencia con la aplicación.  

## 29 Personalización de Planes Alimenticios (Premium)

**Título:** Personalización de Planes Alimenticios (Premium)  
**Descripción:** Como usuario premium, quiero poder personalizar mi plan alimentario semanal con diferentes filtros (dinero, preferencia de alimentos), para que se ajuste a mis necesidades y preferencias.  
**Criterios de Aceptación:**  

**Scenario 01: Personalización exitosa de planes alimenticios con diferentes filtros**  
Dado que un usuario premium accede a la funcionalidad de personalización de planes alimenticios  
Cuando selecciona diferentes filtros como presupuesto, preferencia de alimentos, etc.  
Entonces puede personalizar fácilmente su plan alimentario semanal para que se ajuste a sus necesidades y preferencias específicas, lo que mejora su experiencia con la aplicación y su capacidad para seguir una dieta personalizada.  

**Scenario 02: Dificultades técnicas al personalizar planes alimenticios**  
Dado que un usuario premium accede a la funcionalidad de personalización de planes alimenticios  
Cuando encuentra errores técnicos o la funcionalidad no está disponible  
Entonces se siente frustrado y no puede personalizar su plan alimenticio según sus necesidades, lo que limita su capacidad de seguir una dieta personalizada.  

## 30 Sugerencias de Reemplazo (Premium)

**Título:** Sugerencias de Reemplazo (Premium)  
**Descripción:** Como usuario premium, quiero que la aplicación me sugiera platos o comidas equivalentes para reemplazar en mi plan alimentario semanal, para que pueda mantener la variedad en mi dieta.  
**Criterios de Aceptación:**  

**Scenario 01: Sugerencias de reemplazo útiles y variadas**  
Dado que un usuario premium accede a su plan alimentario semanal  
Cuando busca sugerencias de reemplazo para ciertos platos o ingredientes  
Entonces la aplicación le proporciona sugerencias útiles y variadas de platos o comidas equivalentes que puede incluir en su plan alimenticio, lo que le permite mantener la variedad en su dieta y explorar nuevas opciones culinarias.  

**Scenario 02: Falta de sugerencias de reemplazo en el plan alimenticio**  
Dado que un usuario premium accede a su plan alimentario semanal  
Cuando busca sugerencias de reemplazo pero la funcionalidad no está disponible o las sugerencias son limitadas  
Entonces se siente frustrado y puede tener dificultades para mantener la variedad en su dieta, lo que afecta su experiencia con la aplicación.  


## 3.3. Impact Mapping.
**Link del miro:  https://miro.com/app/board/uXjVKNP7IR4=/?share_link_id=521254084234**
![Impact Mapping](images/impactmapping.png)

## 3.4. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 01|US-LP-01|Implementación de Landing Page Responsive|Como usuario interesado en alimentación saludable, quiero interactuar con una landing page responsive que se adapte a mi pantalla.|5|
|02|US-LP-02|Visualización de Redes Sociales de MealMaster|Como usuario interesado en alimentación saludable, quiero visualizar las redes sociales de MealMaster.|3|
|03|US-LP-03|Visualización de Planes de Alimentación Destacados|Como usuario interesado en alimentación saludable, quiero ver ejemplos de planes de alimentación en la página de inicio para tener una idea de lo que puedo lograr con la aplicación.|3|
|04|US-01|Página de Inicio Atractiva|Como visitante, quiero ver una página de inicio atractiva que me muestre rápidamente los beneficios clave de MealMaster para poder decidir si quiero registrarme.|5|
|05|US-05|Testimonios y Reseñas en la Página de Inicio|Como visitante, quiero ver testimonios y reseñas de otros usuarios satisfechos en la página de inicio para ganar confianza en la aplicación.|3|
|06|US-06|Navegación por Características Clave|Como visitante, quiero poder navegar fácilmente por las características clave de MealMaster, como la creación de platillos y planes alimenticios, para comprender rápidamente cómo la aplicación puede ayudarme.|5|
|07|US-07|Información sobre Precios y Planes Disponibles|Como visitante, quiero encontrar fácilmente información sobre precios y planes disponibles en la página de inicio, para evaluar si el producto se ajusta a mis necesidades y presupuesto.|5|
|09|US-09|Información sobre Servicio Premium de MealMaster|Como visitante, quiero ver información sobre el servicio premium de MealMaster y sus beneficios extras en la landing page, para decidir si quiero suscribirme.|3|
|02|US-LP-02|Ejemplos Visuales de Platillos|Como visitante, deseo ver ejemplos visuales de platillos variados y atractivos en la landing page, para sentirme motivado en probar la aplicación web.|5|
|01|US-AW-01|Cambio de Contraseña|Como usuario interesado en alimentación saludable, quiero poder cambiar mi contraseña por si deseas añadirle mayor seguridad a mi cuenta.|3|
|02|US-AW-02|Filtrado de Preferencias Alimenticias|Como usuario interesado en alimentación saludable, quiero poder filtrar mis preferencias para evitar que dentro de mi dieta haya algún alimento al que soy alérgico o no me gusta.|5|
|03|US-AW-03|Modificar Método de Pago|Como usuario interesado en alimentación saludable, quiero tener la opción de modificar mi método de pago por si deseo realizar compras con otra tarjeta.|3|
|04|US-AW-04|Eliminar Cuenta Permanentemente|Como usuario interesado en alimentación saludable, quiero tener la opción de eliminar permanentemente mi cuenta de MealMaster.|5|
|05|US-AW-05|Observar Reseñas de Recetas|Como usuario interesado en alimentación saludable, quiero poder observar las reseñas de los platos para tener mayor confianza en lo que prepararé.|3|
|06|US-AW-06|Visualización de Platos Destacados|Como usuario interesado en alimentación saludable, quiero ver ejemplos de platos más destacados en la página de inicio para tener una idea de lo que puedo cocinar con la aplicación.|5|
|07|US-AW-07|Acceso a la Calculadora de Calorías|Como usuario interesado en alimentación saludable, quiero tener acceso a una calculadora de calorías en la página de inicio para poder estimar rápidamente mis necesidades calóricas diarias.|3|
|08|US-AW-08|Acceso a la Sección de Soporte al Cliente|Como usuario interesado en alimentación saludable, quiero encontrar fácilmente la sección de soporte al cliente en la página de inicio para poder hacer preguntas o reportar problemas.|3|
|09|US-AW-09|Acceso a la Sección de Precios y Planes|Como usuario interesado en alimentación saludable, quiero encontrar fácilmente la sección de precios y planes en la página de inicio para entender los costos asociados con el uso de la aplicación.|3|
|11|US-AW-11|Registro de Ingredientes|Como usuario interesado en alimentación saludable, quiero poder registrar los ingredientes que tengo a la mano, para que la aplicación pueda sugerirme platillos que pueda preparar con ellos.|3|
|12|US-AW-12|Filtros de Platillos|Como usuario interesado en alimentación saludable, quiero poder aplicar filtros a las sugerencias de platillos, para que pueda elegir si quiero que sean saludables o no.|3|
|13|US-AW-13|Instrucciones de Cocina|Como usuario interesado en alimentación saludable con habilidades de cocina baja, quiero que la aplicación me proporciona instrucciones paso a paso para preparar los platillos sugeridos, para que pueda aprender y mejorar mis habilidades de cocina.|5|
|14|US-AW-14|Creación de Planes Alimenticios (Premium)|Como usuario premium, quiero poder crear planes alimenticios semanales basados en mis objetivos (perder grasa, ganar masa muscular, mantener un peso saludable), para que pueda seguir una dieta personalizada y alcanzar mis metas de salud.|8|
|15|US-AW-15|Detalles de la Dieta (Premium)|Como usuario premium, quiero que la aplicación me proporcione todos los detalles específicos (calorías, grasas, etc.) de la dieta que voy a consumir en mi día a día, para que pueda monitorear mi ingesta nutricional.|5|
|16|US-AW-16|Personalización de Planes Alimenticios (Premium)|Como usuario premium, quiero poder personalizar mi plan alimentario semanal con diferentes filtros (dinero, preferencia de alimentos), para que se ajuste a mis necesidades y preferencias.|8|
|17|US-AW-17|Sugerencias de Reemplazo (Premium)|Como usuario premium, quiero que la aplicación me sugiera platos o comidas equivalentes para reemplazar en mi plan alimentario semanal, para que pueda mantener la variedad en mi dieta.|5|
|01|US-WS-01|Desarrollo de una API RESTful|Como desarrollador, quiero desarrollar una API RESTful para la aplicación, para permitir la integración con otras aplicaciones y servicios.|8|
|02|US-WS-02|Integración de APIs de información nutricional|Como desarrollador, quiero integrar APIs de información nutricional de fuentes confiables, para proporcionar a los usuarios datos precisos y actualizados sobre los alimentos que consumen.|5|
|03|US-WS-03|Implementación de pruebas automatizadas|Como desarrollador, quiero implementar pruebas automatizadas para todas las funcionalidades de la aplicación, para detectar y corregir errores de manera eficiente y garantizar la calidad del software.|8|
|04|US-WS-04|Desarrollo de un sistema de notificaciones en tiempo real|Como desarrollador, quiero desarrollar un sistema de notificaciones en tiempo real, para enviar recordatorios y actualizaciones a los usuarios de manera oportuna.|5|
|05|US-WS-05|Integración de API de información nutricional|Como desarrollador, quiero integrar una API de información nutricional confiable, para proporcionar a los usuarios datos precisos y actualizados sobre los alimentos que consumen.|5|
|06|US-WS-06|Documentación de la API|Como desarrollador, quiero documentar la API de manera completa y precisa, para facilitar su uso por parte de otros desarrolladores.|3|
|07|US-WS-07|Seguridad de la API|Como desarrollador, quiero implementar medidas de seguridad en la API, como la encriptación de las comunicaciones y la protección contra ataques de inyección SQL, para proteger los datos de los usuarios.|8|
|08|US-WS-08|Implementación de autenticación en la API|Como desarrollador, quiero implementar la autenticación en la API utilizando tokens JWT, para proteger los endpoints y asegurar que solo los usuarios autorizados puedan acceder a ellos.|5|
|09|US-WS-09|Manejo de errores en la API|Como desarrollador, quiero implementar un manejo de errores robusto en la API, para proporcionar respuestas útiles cuando ocurran errores y facilitar la depuración.|5|

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

#### Branding
Con el propósito de dar estilo y reconocimiento a nuestra aplicación web que posee una variedad de ajustes en los temas de colores, fuentes tipográficas y en el aspecto de diseño estructural, para el desarrollo correcto de nuestro banding hemos tomado en cuenta cada una de las características de nuestra solución .

#### Typography
El tipo de tipografía escogida es Raleway, resalta elegancia y modernidad. Ofreciendo así, una visión amigable y fácil de leer para nuestra plataforma.

#### Logotipo
![Imgur](https://imgur.com/01ZzG81.png)

![Imgur](https://imgur.com/pzpkb3P.png)

#### Colors

![Imgur](https://imgur.com/oLdpYAb.png)

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

![Imgur](https://imgur.com/LqIUOY3.png)

### 4.3.2. Landing Page Mock-up
 Link Figma Landing Page Mock-Up: https://www.figma.com/proto/nEypHPwCcG8EhmtVhJOvJr/MealMaster?page-id=0%3A1&type=design&node-id=54-332&viewport=4399%2C734%2C0.39&t=otNJnnSFIW0hXd45-1&scaling=min-zoom&starting-point-node-id=54%3A332&show-proto-sidebar=1&mode=design 

![Imgur](https://imgur.com/C3EdZp9.png)
![Imgur](https://imgur.com/xlHjv7e.png)
![Imgur](https://imgur.com/IACnVKM.png)

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
En primer lugar, se presentarán los wireframes de la aplicación, que luego serán usados como plantilla.
![Imgur](https://imgur.com/0DR3Qvn.png)
![Imgur](https://imgur.com/YegBn2H.png)
![Imgur](https://imgur.com/TRj2sp9.png)
![Imgur](https://imgur.com/3xRzXAw.png)
![Imgur](https://imgur.com/3F5UWrr.png)
![Imgur](https://imgur.com/ssa7pBB.jpg)

### 4.4.2. Web Applications Wireflow Diagrams.
En esta sección, se presentan los wireflows de la aplicación, guiándose de las historias de usuario respectivas.

User Goal: El usuario se registra, recupera su contraseña o inicia sesión


![webapp](images/webapp.JPG)

Descripción:
Al ingresar a la aplicación el usuario se encuentra con un formulario para inicio de sesión. Además, tiene también la opción de registrarse en caso no posea una cuenta y la opción de cambiar su contraseña en caso de que la haya olvidado. Dentro del formulario de registro podrá llenar todos sus datos y el mismo formulario le confirmará que su registro fue exitoso. Cuando el usuario ingrese correctamente sus credenciales podrá ingresar a su página de inicio.
User Goal: Perfil de usuario
![webapp](images/webapp2.JPG)

Descripción:
Si el usuario desea acceder a su perfil. Desde la página de inicio puede hacer click en el menú “Hamburger” ubicado en la esquina superior izquierda, lo que desplegará un “Sidebar” donde se mostrarán todas las opciones disponibles, entre ellas el “Perfil”. Haciendo click en la opción “Perfil” el usuario podrá acceder a su perfil y visualizar toda su información.


### 4.4.3. Web Applications Mock-Ups

![Imgur](images/mocksups.JPG)

link: https://www.figma.com/proto/nEypHPwCcG8EhmtVhJOvJr/MealMaster?page-id=0%3A1&type=design&node-id=52-1044&viewport=2279%2C660%2C0.24&t=d8bNesaa3lxnFw7a-1&scaling=min-zoom&starting-point-node-id=52%3A1044&show-proto-sidebar=1&mode=design 

### 4.4.4. Web Applications User Flow Diagrams
Para esta sección, se presentan los user flow diagrams, los cuales son diagramas que ayudan a presenciar de mejor manera el flujo por el cual pasará el usuario al momento de realizar cierta acción.

![Imgur](images/usergol.JPG)
![Imgur](images/usergol1.JPG)
![Imgur](images/usergol2.JPG)
![Imgur](images/usergo3.JPG)

## 4.5. Web Applications Prototyping.

En esta sección se compartirán los prototipos relacionados a la aplicación web, donde se presentan el alcance de los user goals en ambos segmentos objetivos. 

![Imgur](images/prototyping.JPG)

link: https://www.figma.com/proto/CdgFvnlG3KaH8i1DkzBdPS/Landing-Page-Mock-up?page-id=0%3A1&type=design&node-id=44-1166&viewport=-625%2C-929%2C0.16&t=eDwh3NJDNQ9cpKtd-1&scaling=contain&starting-point-node-id=44%3A1166&mode=design 

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
![Imgur](images/contextdiagram.JPG)
1. System Context Diagram: Diagrama que muestra la relacion del aplicativo con los usuarios
se incluyen servicios externos.
   
### 4.6.2. Software Architecture Container Diagrams.
![Imgur](images/containerdiagram.JPG)

 Container Diagrams. Sirve para entender cómo funciona y el proceso, Se especifican DB's, indexers, Search engine, las Apis que usen los bounded context y se conectan por flechas, las cuales tienen como objetivo explicar la dirección y relación junto a que se está enviando/comunicando (TCP) 
 
### 4.6.3. Software Architecture Components Diagrams.
![Imgur](images/componentsdiagram.JPG)

Component diagrams: Estos van a mostrar las ordenes, procesos, mensajes y componentes utilizados en el uso del aplicativo, claro se deben hacer diferentes de estos para cada bounded o USER GOALS
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
Link:  https://lucid.app/lucidchart/16233ba4-2e87-4655-b479-e883196ddf2a/edit?viewport_loc=-3294%2C-1036%2C7700%2C3775%2C0_0&invitationId=inv_331dbcfa-612c-48d8-8356-f7308a4a82d6
![Imgur](images/classdiagram.JPG)

### 4.7.2. Class Dictionary.
![Imgur](images/classdictionary.jpg)

## 4.8. Database Design.
### 4.8.1. Database Diagram.
![Database Diagram](https://raw.githubusercontent.com/Aplicaciones-Web-WX56-Group-MealMaster/ingredients-images/main/ingredients-images/Database%20diagram.jpg)

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
A continuación se listará los productos software externos que se han utilizado para el desarrollo del proyecto:
Project Management
Discord y WhatsApp (https://discord.com/) (https://www.whatsapp.com/?lang=es)
Discord y WhatsApp han sido los medios principales de comunicación entre los miembros del grupo, donde Discord ha destacado ya que contiene funcionalidades adicionales para organizar grupos de estudio y de trabajo.

Requirements Management
Trello (https://trello.com/es)
Trello ha permitido la organización de tareas a realizar en el proyecto, además del desarrollo del product backlog.

Product UX/UI Design
UXPressia (https://uxpressia.com/)
Se utilizó UXPressia para el desarrollo de los diagramas user personas, user journey mapping, empathy mapping e impact map.
Color Space (https://mycolor.space/)
Color Space ha apoyado en la selección de la paleta de colores para el desarrollo del diseño de la web.
Figma (https://www.figma.com/)
Se ha utilizado Figma para el desarrollo de los wireframes y prototipos del landing page y aplicación web, tanto en dispositivos de escritorio como de móvil.
Miro (https://miro.com/es/)
Miro ha sido empleado en el desarrollo de los escenarios mapping y escenario mapping para ambos segmentos objetivos.

Software Development
Visual Studio Code, Visual Studio Code Community, IntelliJ IDEA (https://code.visualstudio.com/) (https://visualstudio.microsoft.com/es/vs/community/) (https://www.jetbrains.com/idea/)
Visual Studio Code, Visual Studio Code Community e IntelliJ IDEA fueron las IDEs que emplearemos para el desarrollo del código del proyecto. Hemos desarrollado el landing page con Visual Studio Code, luego Visual Studio Code Community para el diagrama C4 y emplearemos IntelliJ IDEA para la aplicación web.
Github y Git bash (https://github.com/) (https://git-scm.com/downloads)
Github y Git bash nos permitirán el control de versiones del código y el desarrollo colaborativo del proyecto.

Software Testing
Google Chrome Developer (https://www.google.com/intl/es-419/chrome/dev/)
Se utilizó Google Chrome en la versión developer para visualizar la interfaz que desarrollamos del landing page.

Software Deployment
Github Pages (https://github.com/)
Se utilizó Github Pages para el deploy del landing page.

Software Documentation
Google Drive (https://www.google.com/intl/es-419_pe/drive/)
Se ha utilizado Google Drive para subir archivos de documentos y presentación. Además se han utilizado herramientas como Google Docs y Google Slides que permiten el desarrollo colaborativo de los informes a entregar.
Google Meets y Zoom (https://meet.google.com/) (https://zoom.us/)
Se ha utilizado software para videoconferencias para realizar las entrevistas de segmentos objetivos. Las plataformas tienen herramientas de grabación, por lo que simplifica el procesamiento de los videos.
Microsoft Stream (https://www.microsoft.com/es-ww/microsoft-365/microsoft-stream) (https://zoom.us/)
Se ha utilizado el servicio de Microsoft Stream para subir el video completo de las entrevistas. La cuenta que ha subido el video está vinculada a la organización de la universidad, por lo que se tuvo suficiente espacio de memoria para mantenerlo en la nube.
LucidChart (https://www.lucidchart.com/pages/es)
LucidChart ha sido empleado en el desarrollo de diagramas de flujo para asegurar los user goals y guiar en el diseño de los prototipos de la aplicación web. Además, se ha utilizado para el diagrama de clases.
Structurizr (https://structurizr.com/)
Para el desarrollo del diagrama C4 en los tres niveles: diagrama de contexto, contenedores y componentes se empleó Structurizr junto a Visual Studio Code Community.
Vertabelo (https://vertabelo.com/)
Para el desarrollo del diagrama del diseño de base de datos se ha empleado Vertabelo, software que se especializa en diagramas de base de datos.

Link de repositorio de GitHub del proyecto: https://github.com/Aplicaciones-Web-WX56-Group-MealMaster/Report-Final-Project
Link de repositorio de Github del Landing Page: https://github.com/Aplicaciones-Web-WX56-Group-MealMaster/landing-page
Link de repositorio de GitHub del aplicativo web: https://github.com/Aplicaciones-Web-WX56-Group-MealMaster/frontend-app

### 5.1.2. Source Code Management.
Se ha creado una organización en Github con los miembros del grupo y un repositorio para el landing page.
Organización:Aplicaciones-Web-WX56-Group-MealMaster/Report-Final-Project (github.com)
Las ramas principales en el Gitflow serán las ramas developer y master, donde developer será la principal rama de trabajo, mientras que la rama master tendrá la versión final de la web desplegada en Github pages. Por otro lado, se utilizarán ramas secundarias con el nombre de los features que se estén trabajando (hero, navbar branches por ejemplo). Asimismo, se incluyen el branches para release (branch release) y hotfix (branch hotfix).

Commit Conventions
Para los commits en Github se han utilizado los estándares convencionales versión 1.1.0 (https://www.conventionalcommits.org/en/v1.0.0/) según la estructura:
<type>[optional scope]: <description>
Type: representa el tipo de commit, sea tipo feature (feat), fix (fix) o docs (docs).
Optional scope: es opcional y representa el alcance del commit.
Description: descripción detallada del commit y acciones realizadas.

Semantic Versioning
Los releases se realizan según los estándares de Semantinc Versioning 2.0 (https://semver.org/), según el formato MAJOR.MINOR.PATCH.
MAJOR: versión mayor cuando se implementa cambios de APIs incompatibles.
MINOR: versión menor cuando se añaden features y funcionalidades nuevas.
PATCH versión de parche de bug fixes y hotfixes.

### 5.1.3. Source Code Style Guide & Conventions

#### HTML Style Guide and Coding Conventions

Es necesario seguir convenciones estandarizadas de HTML como estructura de la web. Entre las principales de W3 Schools [aquí](https://www.w3schools.com/html/html5_syntax.asp) podemos mencionar:

- Siempre declarar el tipo de documento con `<!DOCTYPE html>`.
- Usar siempre letras en minúsculas para los nombres de los elementos (como `<p>`, `<h1>`, `<section>`, entre otros).
- Cerrar siempre con los elementos de HTML (por ejemplo `<p></p>`).
- Siempre poner entre comillas los atributos dentro de un elemento HTML (`<p class="name"></p>`).
- Especificar `alt`, `width`, y `height` para imágenes.
- Espaciado y signo igual estandarizados.
- Evitar líneas de código extensas.
- No olvidar el `<title></title>` al principio.
- Es posible evitar el `<head></head>`.
- Utilizar meta tags al inicio.

#### Google HTML/CSS Style Guide

Algunas de las convenciones de Google en cuanto a HTML y CSS [aquí](https://google.github.io/styleguide/htmlcssguide.html) podemos mencionar:

- Usar la sintaxis y semántica de HTML5.
- Usar minúsculas para los nombres de elementos y atributos.
- Usar comillas dobles para los valores de atributos.
- Usar una nueva línea para cada elemento.
- Usar un espacio después de los dos puntos del nombre de cada propiedad.
- Usar códigos de color hexadecimal (`#000000`) en vez de nombres propios.
- Usar códigos de color hexadecimales abreviados siempre que sea posible.
- Evitar especificar unidades para valores 0. Por ejemplo, `margin: 0px` se incluye la unidad de píxeles.

#### Gherkin Conventions for Readable Specifications

Entre las convenciones para Gherkin sobre las pruebas de aceptación se deben considerar convenciones, entre algunas de Specflow [aquí](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/) están:

- Escribir las especificaciones en un lenguaje simple y fácil de entender por todos los miembros del equipo de desarrollo.
- Utilizar las palabras "Given", "When" y "Then" y “And” para los pasos del escenario.
- Usar verbos finitos y en tiempo presente para las acciones del escenario.
- Evitar redundancias en la descripción de los pasos en el escenario.
- Utilizar formato y estilo consistente en toda la especificación, para todos los escenarios.

#### Angular Coding Style Guide

Algunas convenciones de código en Angular se encuentran en su guía oficial [aquí](https://angular.io/guide/styleguide). Podemos rescatar algunas:

- Respetar el principio de single responsibility de componentes en cada componente de Angular.
- Utilizar la nomenclatura recomendada de componentes “feature.type.ts”. Por ejemplo “feature.component.ts”. Además, los nombres de archivos deben estar con minúsculas.
- Declarar variables con `const` o `let` según el valor sea mutable o inmutable.
- Utilizar los decoradoras correctamente como `@Injectable()`.
- Nunca importar lazy load components directamente porque estaría cargando el componente que debería cargarse según necesidad.
- Toda la aplicación va en la carpeta `src`, donde cada feature tiene su propia carpeta denominada como dominio.
- Utilizar el módulo compartido (shared domain) entre dominios de manera correcta.

#### Google Java Style Guide

A continuación se presentan algunas guías de estilo de Java de la guía de Google [aquí](https://google.github.io/styleguide/javaguide.html):

- Las variables y los métodos deben tener nombres descriptivos y seguir la convención de nombres de Java. Los nombres de variables deben comenzar con minúsculas y usar camelcase (por ejemplo `prepareOneOrTwo()`).
- Las variables constantes deben definirse en mayúsculas y separarse con guiones bajos.
- Los corchetes deben comenzar en la misma línea que la declaración del bloque de código y terminar en una línea separada.
- Los nombres de los paquetes deben ser en minúsculas y seguir la convención de nombres de dominio invertido.
- Usar interfaces para definir tipos, en lugar de clases abstractas.
- Los métodos deben hacer una sola función y respetar el principio de single responsibility.

#### Google TypeScript Style Guide

Se presentarán algunas convenciones de TypeScript según Google [aquí](https://google.github.io/styleguide/tsguide.html):

- Parecido a Java, las variables y los métodos deben tener nombres descriptivos y seguir la convención de nombres de TypeScript. Los nombres de variables deben comenzar con minúsculas y usar camel case.
- Los corchetes deben comenzar en la misma línea que la declaración del bloque de código y terminar en una línea separada `{ }`.
- Como recomendación, las variables deben declararse lo más cerca posible de donde se utilizan y tener el ámbito más pequeño posible.
- Las constantes deben definirse en mayúsculas y separarse con guiones bajos.
- Los nombres de las interfaces deben seguir la convención de camelcase.
- Usar el modificador `readonly` para indicar que una variable no va a cambiar después de ejecutarlo.
- Al igual que Java, los métodos deben hacer una sola función y respetar el principio de single responsibility.

#### Spring Boot Features

Se mencionarán los core features de Sprint Boot según la documentación oficial de Sprint [aquí](https://docs.spring.io/spring-boot/docs/current/reference/html/features.html):

- **Clase de aplicación Sprint**: empieza con el método `main()` y inicializa la aplicación con el método `SpringApplication.run`.
- **Configuración externalizada**: permite realizar cambios en configuración para trabajar en distintos entornos de desarrollo.
- **Perfiles**: segrega funciones según ambiente con `@Profile`.
- **Logging**: tiene funciones predeterminadas de logging, pero se pueden configurar según necesidad.
- **Testing**: Sprint ofrece varios módulos que facilitan el testing de las funcionalidades.
- **Soporte con Kotlin**.

### 5.1.4. Software Deployment Configuration

**En este caso usaremos Git y GitHub**

**Git**: En el desarrollo de software, Git es un sistema de control de versiones distribuido. Fue desarrollado por Linus Torvalds en 2005 y se ha convertido en una herramienta vital para trabajar juntos y monitorear los cambios en proyectos de código abierto y privados. La capacidad de realizar un seguimiento de los cambios en los archivos de un proyecto a lo largo del tiempo es una de las principales ventajas de Git. Los desarrolladores pueden crear ramas, hacer cambios y fusionarlas con Git. Esto permite que varios desarrolladores trabajen simultáneamente en varios aspectos del proyecto sin interferir entre sí.

Como Git usa un modelo de sistema distribuido, cada desarrollador tiene una copia del repositorio completa, que incluye todo el historial de cambios. Esto aumenta la flexibilidad y la seguridad porque cada desarrollador puede trabajar de manera independiente y modificar su propia copia local sin afectar el trabajo de los demás. Los repositorios remotos, como GitHub, facilitan la colaboración en equipo y permiten el intercambio y la sincronización de cambios. Además, Git proporciona una amplia gama de características y comandos que facilitan la gestión de versiones. Se pueden crear ramas para trabajar en nuevas funcionalidades o corregir errores sin afectar el proyecto principal. Las fusiones también se pueden realizar para combinar los cambios de varias ramas y mantener un flujo de trabajo coherente. La capacidad de revertir cambios y realizar seguimiento de versiones anteriores es otra característica importante de Git. Esto permite a los desarrolladores retroceder en el tiempo y recuperar versiones de código anteriores, lo que es útil en caso de errores o necesidad de cambios retrospectivos. A través de su usabilidad, podremos controlar las herramientas de nuestro software y guardar varios archivos o versiones a lo largo de las diferentes etapas de un proyecto. Esto nos permite a nosotros, como desarrolladores, monitorear lo que ya hemos hecho y resolver problemas o cambios que se decidan a lo largo del proyecto.

![Imgur](images/github.png)

**GitHub**: Es una plataforma basada en Git que permite el alojamiento y la colaboración de código fuente. Fue lanzado en 2008 y se ha convertido en uno de los servicios más populares para desarrolladores de todo el mundo. Los desarrolladores pueden crear repositorios en GitHub para almacenar y administrar su código fuente. Estos repositorios pueden ser públicos, lo que significa que cualquiera puede ver y contribuir al código, o privados, que son más apropiados para proyectos comerciales o privados.

La capacidad de permitir la colaboración en equipo es uno de los aspectos más destacados de GitHub. Varios desarrolladores pueden trabajar en el mismo repositorio al mismo tiempo, realizar modificaciones en varias ramas y fusionarlos fácilmente. Esto facilita que los equipos trabajen juntos y gestionan las diversas contribuciones. GitHub ofrece una variedad de herramientas adicionales además de la gestión de código fuente. Los "problemas" permiten un seguimiento de las tareas, errores o mejoras del proyecto. Se pueden solicitar revisiones y fusionar los cambios realizados por colaboradores externos antes de incorporarlos al repositorio principal mediante "requerimientos de salida". Las "acciones" de GitHub son una característica importante que permite automatizar tareas y flujos de trabajo dentro del proyecto. La ejecución de pruebas, la creación de documentación o la implementación continua son ejemplos de esto. GitHub es conocido por su enfoque en el código abierto y su comunidad activa. GitHub aloja una gran cantidad de proyectos de código abierto, lo que facilita la colaboración y promueve la transparencia en el desarrollo de software. Esta herramienta nos ayudará a colaborar con Git, es una plataforma que puede mantener un repositorio de código en la nube y permite que varios trabajadores trabajen en un solo proyecto, viendo las ediciones propias de cada integrante, mejorando el trabajo en equipo para los trabajos por hacer.

![Imgur](images/git.png)

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 1</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td>2024-04-26</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>6 días</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>(Presencial) en la propia universidad</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td>Cortés Casas, Joaquín Marcelo / Díaz Silva, Fernando Josué / Chávez Rojas, Carlos Raúl Guillermo / Ruiz Blas, Luciano / Becerra Llempen, Fabiola</td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>Cortés Casas, Joaquín Marcelo / Díaz Silva, Fernando Josué / Chávez Rojas, Carlos Raúl Guillermo / Ruiz Blas, Luciano / Becerra Llempen, Fabiola</td>
  </tr>
  <tr>
    <th>Sprint n – 0 Review Summary</th>
    <td>
      <ul>
        <li>En este sprint se implementó un landing page visualmente atractivo y profesional.</li>
        <li>Se aseguró una interfaz intuitiva y fácil de utilizar para los usuarios.</li>
        <li>Se hizo responsive el landing page para adaptarse a diversas resoluciones de pantalla.</li>
        <li>Se incorporó una sección de planes de servicio en el landing page.</li>
        <li>Se añadió un botón de registro visible en la página principal.</li>
        <li>Se creó una sección "Acerca de nosotros" para presentar la historia, misión y valores de Meal Master.</li>
        <li>Se implementó una sección de recomendaciones de aliados y redes sociales en la landing page.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 1 Retrospective Summary</th>
    <td>Se identificó la necesidad de mejorar la calidad y consistencia del landing page y asegurar una integración fluida con futuras versiones del aplicativo web.</td>
  </tr>
  <tr>
    <th>Sprint Goal & User Stories</th>
    <td>
      <ul>
        <li>Desplegar una versión mejorada del landing page.</li>
        <li>Integrar nuevas funcionalidades según el feedback del sprint anterior.</li>
        <li>Preparar la base para la implementación del backend en futuros sprints.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>16 Puntos</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>16 Puntos</td>
  </tr>
</table>

#### 5.2.1.2. Sprint Backlog 1

Link de board en Trello: [Enlace](#)

*Sprint #* | Sprint 1

*User Story* | *Work Item / Task* | *Id* | *Title* | *Description* | *Estimation (Hours)* | *Assigned To* | *Status*
--- | --- | --- | --- | --- | --- | --- | ---
EP-01 | US-01 | #185942721 | Accesibilidad de la página | Creación de landing page atractiva. Como usuario, quiero ver un landing page visualmente atractiva y profesional para obtener una buena primera impresión de la empresa. | 5 hours | Fabiola Becerra | Done
EP-01 | US-02 | #185942721 | Accesibilidad de la página | Interfaz intuitiva para comprender la propuesta de valor de Meal Master. Como usuario, quiero una interfaz intuitiva y fácil de utilizar para comprender rápidamente qué hace la empresa y qué es lo que me ofrece. | 5 hours | Joaquin Casas | Done
EP-01 | US-03 | #185942721 | Accesibilidad de la página | Implementación de landing page responsive. Como usuario, quiero interactuar con un landing page responsive, para que se adapte a mi resolución de pantalla. | 3 hours | Fernando Silva | Done
EP-01 | US-04 | #185942721 | Accesibilidad de la página | Sección sobre los planes de servicio de Meal Master en la landing page. Como usuario, quiero que la landing page de Meal Master me muestra una sección de los servicios que brinda como sus planes de Meal Master, para así poder generar mi atención y curiosidad hacia este. | 2 hours | Carlos Rojas | Done
EP-01 | US-05 | #185942721 | Accesibilidad de la página | Creación del botón de “registro” para poder ser un usuario de la aplicación. Como usuario, quiero que la landing page de Meal Master me muestre el botón de “registro” en la landing page para poder ser un usuario de la aplicación. | 2 hours | Fernando Silva | Done
EP-01 | US-06 | #185942721 | Accesibilidad de la página | Sección "Acerca de nosotros" en landing page. Como usuario, quiero que la landing page de Meal Master tenga una sección de "Acerca de nosotros" que presente la historia de la empresa, su misión y valores, para entender mejor su propósito y generar confianza en la marca. | 2 hours | Luciano Blas | Done
EP-01 | US-07 | #185942721 | Accesibilidad de la página | Sección de recomendaciones en landing page. Como usuario, quiero que la landing page de Meal Master tenga una sección que me muestre a todos sus aliados en cuanto a recomendaciones para que me inspire confianza. | 2 hours | Joaquin Casas | Done
EP-01 | US-08 | #185942721 | Accesibilidad de la página | Sección de redes sociales de Meal Master en landing page. Como usuario, quiero que la landing page de Meal Master tenga una sección de redes sociales claramente visible, para que me brinde más confianza al saber que es una aplicación conocida y actualizada. | 2 hours | Luciano Blas | Done

#### 5.2.1.3. Development Evidence for Sprint Review
![Sprint review development Evidence](images/execution.png)
![Sprint review development Evidence](images/execution1.png)
![Sprint review development Evidence](images/execution1.png)

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 2</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td></td>
  </tr>
  <tr>
    <th>Date</th>
    <td>2024-04-24</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>7 días</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>(Presencial) en la propia universidad</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td></td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>
      <ul>
        <li>Cortés Casas, Joaquín Marcelo</li>
        <li>Díaz Silva, Fernando Josué</li>
        <li>Chávez Rojas, Carlos Raúl Guillermo</li>
        <li>Ruiz Blas, Luciano</li>
        <li>Becerra Llempen, Fabiola</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 0 Review Summary</th>
    <td>
      <ul>
        <li>US-14: Como usuario interesado en alimentación saludable, quiero poder filtrar mis preferencias para poder evitar que dentro de mi dieta haya algún alimento al que soy alérgico o no me gusta.</li>
        <li>US-15: Como usuario interesado en alimentación saludable, quiero poder visualizar planes de alimentación personalizados en MealMaster, para tener una guía clara de mis comidas diarias.</li>
        <li>US-24: Como usuario interesado en alimentación saludable, quiero poder registrar los ingredientes que tengo a la mano, para que la aplicación pueda sugerirme platillos que pueda preparar con ellos.</li>
        <li>US-25: Como usuario interesado en alimentación saludable, quiero poder aplicar filtros a las sugerencias de platillos, para que pueda elegir si quiero que sean saludables o no.</li>
        <li>US-26: Como usuario interesado en alimentación saludable con habilidades de cocina baja, quiero que la aplicación me proporcione instrucciones paso a paso para preparar los platillos sugeridos, para que pueda aprender y mejorar mis habilidades de cocina.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 1 Retrospective Summary</th>
    <td>
      <ul>
        <li>Meta principal: X</li>
        <li>Metas específicas: X</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Goal & User Stories</th>
    <td>
      <ul>
        <li>Desplegar una versión mejorada del landing page.</li>
        <li>Integrar nuevas funcionalidades según el feedback del sprint anterior.</li>
        <li>Preparar la base para la implementación del backend en futuros sprints.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>X Puntos</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>X Puntos</td>
  </tr>
</table>

#### 5.2.2.2. Sprint Backlog 2

Link de board en Trello: [Enlace](#)

*Sprint #* | Sprint 2

*User Story* | *Work Item / Task* | *Id* | *Title* | *Description* | *Estimation (Hours)* | *Assigned To* | *Status*
--- | --- | --- | --- | --- | --- | --- | ---
US-14 | Filtrado de preferencias alimenticias | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-15 | Visualización de planes de alimentación personalizados | #185942721 | En base a platos previamente filtrados y operaciones CRUD, mostrar en un apartado los platos de comida. | 5 hours | x | Done
US-24 | Registro de Ingredientes | #185942721 | Listar los ingredientes de comida para generar un plan de comida en base a estos. | 5 hours | x | Done
US-25 | Filtro de Platillos | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-26 | Instrucciones de Cocina | #185942721 | Interfaz del detallado de un plato de cocina seleccionado, con el tutorial de cómo prepararlo. | 5 hours | x | Done

#### 5.2.2.3. Development Evidence for Sprint Review
![Sprint review development Evidence](images/evidence2.png)
![Sprint review development Evidence](images/evidence2.2.png)
![Sprint review development Evidence](images/evidence2.3.png)

#### 5.2.2.4. Testing Suite Evidence for Sprint Review
![Sprint review Testing suite Evidence](image.jpg)

#### 5.2.2.5. Execution Evidence for Sprint Review
![Sprint review Execution Evidence](image.jpg)

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
![Sprint review Software Deployment Evidence](image.jpg)

#### 5.2.2.8. Team Collaboration Insights during Sprint
Cada integrante del grupo ha subido su commit en su respectivo branch, enfocándose en completar su funcionalidad asignada.
![Sprint review Team Collaboration Insights](team2.png)

### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 2</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td></td>
  </tr>
  <tr>
    <th>Date</th>
    <td>2024-04-24</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>7 días</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>(Presencial) en la propia universidad</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td></td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>
      <ul>
        <li>Cortés Casas, Joaquín Marcelo</li>
        <li>Díaz Silva, Fernando Josué</li>
        <li>Chávez Rojas, Carlos Raúl Guillermo</li>
        <li>Ruiz Blas, Luciano</li>
        <li>Becerra Llempen, Fabiola</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 0 Review Summary</th>
    <td>
      <ul>

      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 1 Retrospective Summary</th>
    <td>
      <ul>
        <li>Meta principal: X</li>
        <li>Metas específicas: X</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Goal & User Stories</th>
    <td>
      <ul>
        <li>Desplegar una versión mejorada del landing page.</li>
        <li>Integrar nuevas funcionalidades según el feedback del sprint anterior.</li>
        <li>Preparar la base para la implementación del backend en futuros sprints.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>X Puntos</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>X Puntos</td>
  </tr>
</table>

#### 5.2.3.2. Sprint Backlog 3

Link de board en Trello: [Enlace](#)

*User Story* | *Work Item / Task* | *Id* | *Title* | *Description* | *Estimation (Hours)* | *Assigned To* | *Status*
--- | --- | --- | --- | --- | --- | --- | ---
US-14 | Filtrado de preferencias alimenticias | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-15 | Visualización de planes de alimentación personalizados | #185942721 | En base a platos previamente filtrados y operaciones CRUD, mostrar en un apartado los platos de comida. | 5 hours | x | Done
US-24 | Registro de Ingredientes | #185942721 | Listar los ingredientes de comida para generar un plan de comida en base a estos. | 5 hours | x | Done
US-25 | Filtro de Platillos | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-26 | Instrucciones de Cocina | #185942721 | Interfaz del detallado de un plato de cocina seleccionado, con el tutorial de cómo prepararlo. | 5 hours | x | Done

#### 5.2.3.3. Development Evidence for Sprint Review
![Sprint review development Evidence](images/evidence2.png)
![Sprint review development Evidence](images/evidence2.2.png)
![Sprint review development Evidence](images/evidence2.3.png)

#### 5.2.3.5. Execution Evidence for Sprint Review
![Sprint review Execution Evidence](image.jpg)

#### 5.2.3.7. Software Deployment Evidence for Sprint Review
![Sprint review Software Deployment Evidence](image.jpg)

#### 5.2.3.8. Team Collaboration Insights during Sprint
Cada integrante del grupo ha subido su commit en su respectivo branch, enfocándose en completar su funcionalidad asignada.
![Sprint review Team Collaboration Insights](team2.png)

### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 2</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td></td>
  </tr>
  <tr>
    <th>Date</th>
    <td>2024-04-24</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>7 días</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>(Presencial) en la propia universidad</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td></td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>
      <ul>
        <li>Cortés Casas, Joaquín Marcelo</li>
        <li>Díaz Silva, Fernando Josué</li>
        <li>Chávez Rojas, Carlos Raúl Guillermo</li>
        <li>Ruiz Blas, Luciano</li>
        <li>Becerra Llempen, Fabiola</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 0 Review Summary</th>
    <td>
      <ul>

      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint n – 1 Retrospective Summary</th>
    <td>
      <ul>
        <li>Meta principal: X</li>
        <li>Metas específicas: X</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Goal & User Stories</th>
    <td>
      <ul>
        <li>La última versión del Landing Page, la tercera versión del aplicativo web y segunda versión del backend.</li>
        <li>Integrar nuevas funcionalidades según el feedback del sprint anterior.</li>
        <li>Preparar la base para la implementación del backend en futuros sprints.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>X Puntos</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>X Puntos</td>
  </tr>
</table>

#### 5.2.4.2. Sprint Backlog 4

Link de board en Trello: [Enlace](#)


*User Story* | *Work Item / Task* | *Id* | *Title* | *Description* | *Estimation (Hours)* | *Assigned To* | *Status*
--- | --- | --- | --- | --- | --- | --- | ---
US-14 | Filtrado de preferencias alimenticias | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-15 | Visualización de planes de alimentación personalizados | #185942721 | En base a platos previamente filtrados y operaciones CRUD, mostrar en un apartado los platos de comida. | 5 hours | x | Done
US-24 | Registro de Ingredientes | #185942721 | Listar los ingredientes de comida para generar un plan de comida en base a estos. | 5 hours | x | Done
US-25 | Filtro de Platillos | #185942721 | Filtrar los platos de comida recuperados de un API. | 5 hours | x | Done
US-26 | Instrucciones de Cocina | #185942721 | Interfaz del detallado de un plato de cocina seleccionado, con el tutorial de cómo prepararlo. | 5 hours | x | Done

#### 5.2.4.3. Development Evidence for Sprint Review
![Sprint review development Evidence](images/evidence2.png)
![Sprint review development Evidence](images/evidence2.2.png)
![Sprint review development Evidence](images/evidence2.3.png)

#### 5.2.4.5. Execution Evidence for Sprint Review
![Sprint review Execution Evidence](image.jpg)

#### 5.2.4.6. Services Documentation Evidence for Sprint Review

Se ha realizado la documentación completa de los Endpoints para `MealPlan` y `User`, implementado acciones HTTP: GET, POST, PUT, DELETE.

| Endpoint              | Acción HTTP | Sintaxis de Llamada          | Parámetros              | Ejemplo de Llamada                          | Ejemplo de Response                                                                                                      |
|-----------------------|-------------|------------------------------|-------------------------|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| `/api/meal-plan`      | GET         | `/api/meal-plan`             | Ninguno                 | `GET /api/meal-plan`                        | `[{"id":1,"name":"Plan A"},{"id":2,"name":"Plan B"}]`                                                                     |
| `/api/meal-plan`      | POST        | `/api/meal-plan`             | `name: string`          | `POST /api/meal-plan {"name": "Plan A"}`    | `{"id":1,"name":"Plan A"}`                                                                                               |
| `/api/meal-plan/{id}` | GET         | `/api/meal-plan/{id}`        | `id: int`               | `GET /api/meal-plan/1`                      | `{"id":1,"name":"Plan A"}`                                                                                               |
| `/api/meal-plan/{id}` | PUT         | `/api/meal-plan/{id}`        | `id: int, name: string` | `PUT /api/meal-plan/1 {"name": "Plan B"}`   | `{"id":1,"name":"Plan B"}`                                                                                               |
| `/api/meal-plan/{id}` | DELETE      | `/api/meal-plan/{id}`        | `id: int`               | `DELETE /api/meal-plan/1`                   | `{"message": "Meal plan deleted"}`                                                                                       |
| `/api/user`           | GET         | `/api/user`                  | Ninguno                 | `GET /api/user`                             | `[{"id":1,"name":"User A"},{"id":2,"name":"User B"}]`                                                                     |
| `/api/user`           | POST        | `/api/user`                  | `name: string`          | `POST /api/user {"name": "User A"}`         | `{"id":1,"name":"User A"}`                                                                                               |
| `/api/user/{id}`      | GET         | `/api/user/{id}`             | `id: int`               | `GET /api/user/1`                           | `{"id":1,"name":"User A"}`                                                                                               |
| `/api/user/{id}`      | PUT         | `/api/user/{id}`             | `id: int, name: string` | `PUT /api/user/1 {"name": "User B"}`        | `{"id":1,"name":"User B"}`                                                                                               |
| `/api/user/{id}`      | DELETE      | `/api/user/{id}`             | `id: int`               | `DELETE /api/user/1`                        | `{"message": "User deleted"}`                                                                                           |


#### 5.2.4.7. Software Deployment Evidence for Sprint Review
![Sprint review Software Deployment Evidence](image.jpg)

#### 5.2.4.8. Team Collaboration Insights during Sprint
Cada integrante del grupo ha subido su commit en su respectivo branch, enfocándose en completar su funcionalidad asignada.
![Sprint review Team Collaboration Insights](team2.png)


## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

**Preguntas generales:**

1. ¿Cuál es su nombre?
2. ¿Qué edad tiene?
3. ¿A qué se dedica?
4. ¿[Opinión de idea de propuesta]?

**Entrevistas usuario segmento 2**

1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?

**Entrevistas usuario segmento 3**

1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?

### 5.3.2. Registro de Entrevistas

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

### 5.3.3. Evaluaciones según heurísticas

| HEURÍSTICA                                        | EVALUACIÓN ✅❌ | NOTA                                                                                                                                                 |
|---------------------------------------------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Visibilidad del estado del sistema                | ✅              | Funcionalidades referentes a la visibilidad del estado del sistema aún se encuentran en proceso de desarrollo, por lo que no hubieron observaciones.   |
| Coincidencia entre el sistema y el mundo real     | ✅              | El idioma que utiliza la aplicación se acerca al lenguaje común de los segmentos objetivos, brindando un entorno familiar y sencillo de utilizar.     |
| Libertad y control por parte del usuario          | ✅              | El usuario es libre de navegar por la aplicación sin problemas o restricciones, por lo que se cumple la libertad y control del usuario al usarla.     |
| Consistencia y estándares                         | ✅              | Los entrevistados mencionan la facilidad de utilizar la aplicación, por lo que no se presentan errores de consistencia o estándares de diseño.        |
| Prevención de errores                             | ✅              | Funciones relacionadas a la prevención de errores se siguen trabajando en el desarrollo de la aplicación.                                             |
| Reconocimiento antes que recuerdo                 | ✅              | El usuario no debe recordar funciones de la aplicación para realizar funciones comunes al navegar por la aplicación.                                   |
| Flexibilidad y eficiencia de uso                  | ✅              | Se cumple la flexibilidad del usuario al otorgar las funciones más relevantes al ingresar a la aplicación.                                            |
| Estética y diseño minimalista                     | ✅              | Se prioriza el contenido relevante al mostrar información y sus características antes que los elementos adicionales.                                   |
| Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de los errores | ✅ | Los mensajes de ayuda aún están en proceso de desarrollo, por lo que no se ha considerado este ítem en la evaluación.                                  |
| Ayuda y documentación                             | ✅              | De igual manera, los mensajes de ayuda aún están en proceso de desarrollo. Sin embargo, se proyecta tener un apartado de preguntas frecuentes.         |

## 5.4. Video About-the-Product

[URL del video about the product](https://www.example.com)

Aquí tienes el texto corregido y formateado en Markdown:

# Conclusiones y recomendaciones

## Conclusiones (TB1)

Como principal conclusión de esta etapa del proyecto Meal Master, logramos alcanzar los siguientes hitos:

- Nos permitió desarrollar una solución enfocada y relevante después de realizar una investigación previa exhaustiva para comprender a fondo la problemática a abordar, identificando los segmentos objetivos involucrados y sus necesidades específicas.
- Al aplicar el proceso Lean UX, que incluye ciclos de construcción, medición y aprendizaje, pudimos refinar y mejorar nuestras ideas del proyecto para optimizar la experiencia del usuario y garantizar que nuestras soluciones fueran efectivas y satisfactorias.
- La realización de entrevistas con los segmentos objetivo nos permitió obtener una comprensión profunda y empática de sus necesidades, deseos y preferencias, algo fundamental para el desarrollo de una solución adecuada.
- La elección de las herramientas, lenguajes de programación, marcos y marcadores hipertextuales más apropiados para nuestro proyecto garantizó la eficiencia y efectividad de la implementación de la solución.
- Utilizar las herramientas Git y GitHub para organizar las bases del repositorio nos permitió tener un control preciso de las versiones del proyecto, facilitar el trabajo colaborativo y garantizar la integridad del código fuente.
- El uso de Git Flow como flujo de trabajo ha demostrado ser útil para la gestión del desarrollo del proyecto, ya que nos permite trabajar en equipo, integrar nuevas funciones y realizar cambios de manera segura.
- El diseño del ciclo de vida del producto basado en el marco de trabajo SCRUM nos dio una estructura clara para la planificación, el desarrollo, la revisión y la entrega del producto, lo que permitió una gestión ágil y eficiente del proyecto.
- La realización de entrevistas con ambos grupos objetivo nos permitió obtener una visión más amplia y sólida de los usuarios interesados en dietas nutritivas, especialmente en lo que respecta al consumo de calorías, así como a la compra de productos relacionados.
- El servicio enfrenta desafíos significativos en términos de eficiencia del filtrado de recetas y precisión acerca de la información nutricional. La atención personalizada a través de suscripciones premium y la consulta con profesionales en nutrición logran mostrar un enfoque alto a la plataforma, ofreciendo un valor agregado a los usuarios que buscan una ayuda personalizada para sus necesidades dietéticas.
- La segmentación de usuarios en cocineros inexpertos y entusiastas de la nutrición proporciona una buena base para la estrategia de marketing y desarrollo de los productos. Meal Master se enfoca en proporcionar una experiencia al usuario adaptada a las necesidades y habilidades específicas en cada segmento, ofreciendo tutoriales con sus respectivos pasos para usuarios sin experiencia y herramientas de planificación de dietas para los que prefieren la nutrición.

## Conclusiones (TP1)

Se desarrollaron las siguientes conclusiones relacionadas a esta segunda entrega:

- La adopción de Pivotal Tracker como herramienta de gestión de sprints demuestra una buena práctica en la metodología ágil, ya que el uso de esta herramienta ayudó mucho a organizar y priorizar las User Stories, facilitando la planificación y seguimiento del progreso del proyecto.
- La asignación de puntos de historia y la correcta estructuración de las historias de los usuarios demuestran un enfoque sólido hacia la estimación del esfuerzo requerido para completar cada tarea, lo que permite una mejor planificación y asignación de recursos en sprints posteriores.
- El desarrollo y despliegue exitoso de una aplicación web frontend con vueJS es un logro significativo porque demuestra las habilidades técnicas del equipo de desarrollo y su capacidad para implementar soluciones funcionales utilizando tecnologías modernas.
- La evidencia de la implementación de todas las historias de los usuarios indica un cumplimiento exitoso de los requisitos planteados en el inventario de productos, ya que el equipo ha logrado abordar y completar todas las tareas planificadas para la ronda.
- La utilización de una nomenclatura clara y consistente para los commits en el repositorio de GitHub es una buena práctica de desarrollo colaborativo que facilita bastante la comprensión y el seguimiento de los cambios realizados en el código fuente y mejora la colaboración entre los miembros del equipo.
- El uso de vueJS como tecnología principal en la aplicación web frontend muestra la capacidad del equipo para utilizar tecnologías modernas, lo que puede mejorar la experiencia del usuario final.
- En comparación con entregas anteriores, el cumplimiento exitoso de las tareas planificadas y la implementación de todas las historias de usuario muestran un aumento en la productividad del equipo.
- La competencia en el mercado de aplicaciones de recetas y planificación de comidas es de un nivel elevado, por eso es importante tener estrategias de diferenciación claras y tácticas de expansión efectivas. Meal Master logra realizarlo enfocándose en la calidad y la precisión de sus servicios, manteniendo una interfaz de usuario atractiva y fácil de usar, y evitando la cantidad masiva de anuncios que podría afectar de una manera negativa la experiencia del usuario.
- Finalmente, Meal Master tendrá que innovar continuamente y adaptarse a las necesidades cambiantes de los usuarios para que logre el éxito a largo plazo en un mercado competitivo y en evolución.

## Conclusiones (TB2)

- Validación de Prototipos: Realizamos pruebas de usuario con prototipos de alta fidelidad, lo que nos permitió identificar áreas de mejora y validar nuestras suposiciones iniciales.
- Integración de comentarios de los usuarios: recopilamos y analizamos los comentarios de los usuarios para realizar las modificaciones necesarias y mejorar la usabilidad y funcionalidad de nuestra solución.
- Optimización del Sistema de Recomendación: Adaptamos el algoritmo de recomendación de recetas a las preferencias y necesidades dietéticas de los usuarios para ofrecer opciones más precisas y personalizadas.
- Construir funcionalidades Clave: aumentamos el valor para los usuarios agregando funcionalidades importantes como el seguimiento de la ingesta calórica, planes de comidas personalizados y listas de compras automáticas.
- Mejoras en la interfaz de usuario: Basándonos en las mejores prácticas de diseño UX/UI, actualizamos y optimizamos la interfaz de usuario para garantizar una experiencia más intuitiva y agradable.
- Gestión Eficiente del Proyecto: Organizamos y priorizamos tareas utilizando herramientas ágiles de gestión de proyectos, lo que resultó en una ejecución eficiente y resultados de alta calidad.

## Conclusiones (TF)

- Producto Finalizado y Funcional: Terminamos el desarrollo del producto, creando una aplicación que cumple con los objetivos iniciales. La plataforma ofrece una amplia gama de servicios para el seguimiento nutricional y la planificación de comidas.
- Antes del lanzamiento oficial, realizamos pruebas exhaustivas con usuarios reales, lo que nos permitió identificar y corregir problemas y mejorar funcionalidades importantes.
- Optimización del algoritmo de recomendación de recetas: refinamos y mejoramos el algoritmo para garantizar que las recomendaciones sean precisas y personalizadas, mejorando significativamente la experiencia del usuario.
- Interfaz de usuario mejorada: Basándonos en los comentarios y las pruebas de usuarios, implementamos mejoras significativas en la interfaz de usuario para garantizar que sea fácil de entender, atractiva y fácil de usar.
- Implementación de Características Avanzadas: Añadimos características avanzadas como la integración con dispositivos de seguimiento de actividad física, opciones de dieta específicas y sugerencias de compra basadas en recetas seleccionadas.
- Estrategia de Mercado y Lanzamiento: Creamos una estrategia de marketing sólida y un plan de lanzamiento. Esto incluye colaboraciones con influencers en nutrición y salud, campañas en redes sociales y ofertas promocionales para los primeros usuarios.

## Video About-the-Team

[URL del video about the team](https://www.example.com)

## Bibliografía

- Vue.js. (s.f.). Recuperado de https://vuejs.org/
- W3Schools. (s.f.). HTML5 Syntax. Recuperado de https://www.w3schools.com/html/html5_syntax.asp
- Google. (s.f.). HTML/CSS Style Guide. Recuperado de https://google.github.io/styleguide/htmlcssguide.html
- SpecFlow. (s.f.). Gherkin - Conventions for Readable Specifications. Recuperado de https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/
- Angular. (s.f.). Angular Style Guide. Recuperado de https://angular.io/guide/styleguide
- Google. (s.f.). Google Java Style Guide. Recuperado de https://google.github.io/styleguide/javaguide.html
- Google. (s.f.). TypeScript Style Guide. Recuperado de https://google.github.io/styleguide/tsguide.html
- Spring Boot. (s.f.). Spring Boot Features. Recuperado de https://docs.spring.io/spring-boot/docs/current/reference/html/features.html

## Anexos

| Sección                | Descripción del video                                           | URL del video                                                                                                                                   |
|------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Needfinding Interviews | Video de Entrevistas a segmentos objetivos (Sprint 1)           | [Link](https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing)                                                    |
| Needfinding Interviews | Video de Entrevistas a segmentos objetivos (Sprint 3)           | [Link](https://drive.google.com/drive/folders/146cf9m54FSZ_IvdMyef8TgF4WLe-uAjj?usp=sharing)                                                    |
| About the Product      | Promoción del Meal Master (Sprint 4)                            | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114545_upc_edu_pe/ESh7geU66DZInkBY_Ry5dp4B2wtxCDu1eJW8dgBy4cDEUA?e=0lulFh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| About the Team         | Video del equipo y trabajo realizado (Sprint 3)                 | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114545_upc_edu_pe/EVqG6kPDjURKhwIRSbYjDuMBvwZlgWxIOyZ34_O9rjPl8A?e=882AG3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| Exposición             | Video Exposición TB2 (Sprint 3)                                 | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114545_upc_edu_peEaDbIHfP62hHv28spthCJK8B8_KdpiD8_kgVFjpmblPH1Ae=D9VJg7&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

