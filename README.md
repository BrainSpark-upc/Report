<div align = "center">
  <img style="height: 150px" src=/assets/assets/chapter-1/UPC_logo_transparente.png alt="">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
<h1>Facultad de Ingeniería</h1>
  <h2>Carrera de Ingeniería de Software</h2>
  <h2>Periodo 202610</h2>
  <h2>1ASI0729 - Desarrollo de Aplicaciones Open Source </h2>
  <h2>NRC- 2610</h2>
  <br>
  <h2>Profesor - Angel Augusto Velasquez Nuñez </h2>
  <h2>Informe de Trabajo </h2>
  <br>
  <h2 >Startup - Care-Labs </h2>
  <h2 >Producto - PulseReport </h2>
  <br>
  <h2 >Integrantes</h2>
  <ul style="list-style: none; padding: 0;">
      <li><h3>U202417693 - Alexander Auden Aliaga Ocampo</h3></li>
      <li><h3>U202217893 - Adrian Matias Rios Cespedes </h3></li>
      <li><h3>U20221c803 - Anhelo Rodrigo Rocca Leon </h3></li>
  </ul>
  <br>
  <h4>Abril del 2026</h4>
  <br>
  </div>



## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#capítulo-1-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
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
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
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
        - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)


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
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** : La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  </table>




  ## Capítulo 1: Introducción
### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
Somos Care-Labs, una startup creada por estudiantes con el propósito de desarrollar una solución tecnológica para el sector salud. Nuestro proyecto surge a partir de la necesidad de mejorar la gestión de procesos críticos en el área de enfermería cardiovascular, donde es muy importante contar con información clara, segura y disponible en tiempo real para brindar una atención más ordenada y eficiente.

A través de nuestra propuesta, buscamos desarrollar un sistema web que permita apoyar distintos procesos clínicos, como la gestión de citas médicas, la administración básica de pacientes, la digitalización del historial clínico, el registro de traspasos mediante el modelo SBAR, el seguimiento de tratamientos y el monitoreo de signos vitales, como la presión arterial y la frecuencia cardíaca. Además, el sistema también permitirá registrar eventos críticos, generar alertas y mantener un log de auditoría inalterable que ayude a conservar la trazabilidad de la información. De esta manera, se busca mejorar la comunicación entre turnos, la organización del personal de salud y la continuidad del cuidado del paciente.

Misión:
Nuestra misión es desarrollar una solución tecnológica que ayude a mejorar la gestión de procesos críticos en enfermería cardiovascular, facilitando el acceso a información clínica de manera rápida, segura y ordenada. Buscamos contribuir a que los centros de salud puedan brindar una atención más eficiente y confiable mediante el uso de herramientas digitales.

Visión:
Nuestra visión es convertir a Care-Labs en una startup reconocida por ofrecer una solución tecnológica útil e innovadora para el sector salud, aportando a la modernización de hospitales, clínicas y centros especializados. Aspiramos a que nuestra propuesta pueda crecer, adaptarse a las necesidades del mercado y generar un impacto positivo en la atención médica.


#### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th colspan="2"> Alexander Auden Aliaga Ocampo </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/Alex.jpg" width=300px> </td>
    <td> Soy estudiante de ingeniería de software en la UPC, con conocimientos básicos en los lenguajes de programación como c++, python , css, html, javascript también conocimientos básicos en base de datos viendo Mongo DB y creando diagramas relaciones como no relacionales. Además poseo habilidades de empatía y buena comunicación con el equipo esto me permite ser productivo en el ámbito de grupos y en general. </td>
  </tr>
  <tr>
    <th colspan="2"> Adrian Matias Rios Cespedes </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/adrian.jpg" width=300px> </td>
    <td> Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), con conocimientos en lenguajes de programación como C++, Python y JavaScript. Cuento con formación en bases de datos y fundamentos relacionados a su gestión.

Además, poseo habilidades blandas orientadas al trabajo en equipo, comunicación efectiva y liderazgo, lo que me permite organizar y dirigir proyectos de manera eficiente, manteniendo un enfoque estructurado y orientado a resultados. </td>
  </tr>

<tr>
    <th colspan="2"> Anhelo Rodrigo Rocca Leon </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/anhelo.jpg" width=300px > </td>
    <td> Soy estudiante de ingeniería de software en la UPC, con conocimientos básicos en los lenguajes de programación como c++, python , css, html, javascript también conocimientos básicos en base de datos viendo Mongo DB y creando diagramas relaciones como no relacionales. Además poseo habilidades de empatía y buena comunicación con el equipo esto me permite ser productivo en el ámbito de grupos y en general </td>
  </tr>
</table>


### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática

A. **Who**

Los principales actores involucrados son los profesionales de salud del área de enfermería cardiovascular, médicos especialistas, personal asistencial, clínicas privadas, hospitales y centros especializados en cardiología. Todos ellos enfrentan dificultades en la gestión de procesos críticos debido al uso de registros manuales, información dispersa y poca trazabilidad clínica.

B. **What**

Actualmente, muchos procesos dentro del área de enfermería cardiovascular se realizan de manera manual o mediante sistemas poco integrados, lo que genera problemas en la comunicación entre turnos, retrasos en el acceso a la información, errores en el registro de signos vitales, dificultades en el seguimiento de tratamientos y poca trazabilidad de eventos críticos. Además, la falta de un sistema centralizado limita la organización de los historiales clínicos y el control adecuado de la atención brindada al paciente.

C. **When**

Estos problemas se presentan de manera continua durante la atención diaria de los pacientes, especialmente en momentos como el cambio de turno del personal, el monitoreo de signos vitales, el registro de incidencias, la actualización de historiales clínicos y el seguimiento de tratamientos. Los riesgos aumentan en situaciones críticas donde se necesita actuar rápidamente y contar con información precisa en tiempo real.

D. **Where**

La problemática ocurre en hospitales, clínicas privadas, centros de salud especializados en cardiología y otras áreas asistenciales donde se atienden pacientes con condiciones cardiovasculares. En estos entornos, la falta de digitalización y trazabilidad afecta tanto al personal de salud como a la calidad de atención brindada.

E. **Why**

Porque la ausencia de una plataforma digital centralizada genera:

- Dificultades en la comunicación entre turnos y áreas asistenciales.
- Pérdida de trazabilidad en eventos clínicos importantes.
- Mayor probabilidad de errores en el registro de signos vitales y tratamientos.
- Demora en el acceso a información relevante del paciente.
- Menor eficiencia en la organización y seguimiento de los procesos clínicos.

Esto impacta directamente en la continuidad del cuidado, la seguridad del paciente y la eficiencia del personal de salud.

F. **How**

Actualmente, muchos centros de salud utilizan historias en papel, hojas de cálculo o sistemas básicos que no están completamente integrados. Aunque algunas instituciones cuentan con herramientas digitales, estas no siempre permiten registrar traspasos SBAR, monitorear signos vitales en tiempo real, generar alertas de eventos críticos o mantener un log de auditoría inalterable. Como resultado, varios problemas siguen presentes en la gestión clínica diaria.

G. **How much**

El impacto de esta problemática se refleja en:

- Pérdida de tiempo del personal de salud en tareas manuales y repetitivas.
- Riesgo de errores en registros clínicos y en la comunicación entre turnos.
- Dificultades para dar seguimiento oportuno a tratamientos y eventos críticos.
- Menor capacidad de respuesta ante situaciones que requieren atención inmediata.
- Reducción en la eficiencia operativa y en la calidad del servicio brindado al paciente.

#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements

### Segmento — Personal de Enfermería Cardiovascular

**Contexto:** El personal de enfermería cardiovascular se encarga del monitoreo constante de pacientes, del registro de signos vitales, del seguimiento de tratamientos y de la comunicación entre turnos para asegurar la continuidad del cuidado.

**Observación:** Actualmente, muchos de estos procesos se realizan de manera manual o mediante registros dispersos, lo que puede generar errores en la documentación, pérdida de información relevante, retrasos en la atención y dificultades en la comunicación entre áreas asistenciales.

**Problema:** No existe una herramienta centralizada y fácil de usar que permita al personal de enfermería cardiovascular registrar información clínica importante, dar seguimiento a tratamientos, documentar traspasos SBAR y mantener trazabilidad de eventos críticos en tiempo real.

**Pregunta clave:** ¿Cómo diseñar una solución digital que permita al personal de enfermería cardiovascular registrar y consultar información clínica de manera rápida, segura y ordenada, mejorando la comunicación entre turnos, la trazabilidad de eventos críticos y la continuidad del cuidado del paciente?


### Segmento — Clínicas, Hospitales y Centros Especializados en Cardiología

**Contexto:** Las instituciones de salud y centros especializados necesitan optimizar sus procesos clínicos, reducir errores operativos y asegurar una atención de calidad, especialmente en áreas críticas donde se requiere acceso inmediato a información confiable.

**Observación:** La falta de integración entre registros clínicos, seguimiento de pacientes, control de signos vitales y documentación de incidencias dificulta la supervisión de procesos y limita la capacidad de respuesta ante eventos críticos.

**Problema:** No se cuenta con una plataforma web que centralice los procesos esenciales de enfermería cardiovascular, facilite la supervisión de pacientes y permita una gestión más eficiente de la información clínica dentro de hospitales, clínicas y centros especializados.

**Pregunta clave:** ¿Cómo implementar una plataforma digital que permita a las instituciones de salud centralizar información clínica, supervisar procesos críticos, mejorar la trazabilidad y fortalecer la calidad de atención en el área de enfermería cardiovascular?


##### 1.2.2.2. Lean UX Assumptions

###### Supuestos sobre los usuarios de la aplicación:

- El personal de enfermería cardiovascular necesita registrar y consultar información clínica de manera rápida, clara y segura durante su jornada diaria.
- Los profesionales de salud requieren una herramienta que facilite la comunicación entre turnos y reduzca la pérdida de información importante en los traspasos.
- Las clínicas, hospitales y centros especializados necesitan mejorar la organización y supervisión de procesos críticos relacionados con el cuidado del paciente.
- Los usuarios prefieren interfaces simples e intuitivas que les permitan acceder fácilmente a signos vitales, tratamientos, historial clínico y eventos críticos.

###### Supuestos sobre necesidades

- El registro manual de información clínica y signos vitales es un proceso repetitivo y propenso a errores.
- La falta de trazabilidad en eventos críticos y en los traspasos entre turnos puede afectar la continuidad del cuidado del paciente.
- Los profesionales de salud necesitan contar con información actualizada en tiempo real para tomar decisiones oportunas.
- Es importante disponer de un sistema que centralice la información clínica básica y permita un seguimiento más ordenado de pacientes y tratamientos.

###### Supuestos sobre la solución

- Una plataforma web permitirá centralizar la información clínica y facilitar su acceso desde distintos puntos dentro de la institución de salud.
- El registro digital de traspasos SBAR mejorará la comunicación entre turnos y áreas asistenciales.
- El monitoreo y almacenamiento de signos vitales dentro del sistema ayudará a mantener un mejor control del estado del paciente.
- Un log de auditoría inalterable permitirá mantener la trazabilidad de eventos críticos y reforzar la confiabilidad de la información registrada.

###### Supuestos sobre el impacto

- La solución reducirá el tiempo invertido en tareas manuales de registro y seguimiento clínico.
- Disminuirá la probabilidad de errores en la documentación de signos vitales, tratamientos y eventos críticos.
- Mejorará la continuidad del cuidado del paciente al fortalecer la comunicación entre turnos.
- Permitirá a las instituciones de salud tener una gestión más ordenada, trazable y eficiente de sus procesos clínicos en el área de enfermería cardiovascular.

##### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis de Valor**  
Creemos que el *personal de enfermería cardiovascular* y las *instituciones de salud* necesitan una plataforma digital que les permita registrar, consultar y dar seguimiento a información clínica crítica de manera rápida, segura y ordenada.  
Tendrán éxito utilizando PulseReport porque les permitirá mejorar la comunicación entre turnos, fortalecer la trazabilidad clínica y optimizar la continuidad del cuidado del paciente.

**Hipótesis de Funcionalidad**  
Creemos que proporcionar funciones como el registro de traspasos SBAR, monitoreo de signos vitales, gestión básica de pacientes, seguimiento de tratamientos, alertas de eventos críticos y un log de auditoría inalterable permitirá que los usuarios gestionen procesos clínicos de forma más eficiente.  
Sabremos que esta funcionalidad es útil cuando observemos un uso constante de la plataforma, una reducción de errores en los registros y una mejora en la documentación de eventos clínicos importantes.

**Hipótesis de Usabilidad**  
Creemos que los usuarios podrán navegar la interfaz de PulseReport de manera intuitiva, ya que estará diseñada con flujos simples, información clara y acceso rápido a las funciones más importantes del sistema.  
Validaremos esta hipótesis mediante pruebas de usabilidad en las que los usuarios puedan completar tareas como registrar signos vitales, consultar pacientes y documentar traspasos sin ayuda adicional.

**Hipótesis de Crecimiento**  
Creemos que si la plataforma demuestra mejoras en la organización de la información clínica, la trazabilidad y la comunicación entre áreas asistenciales, hospitales, clínicas y centros especializados estarán dispuestos a adoptar la solución de manera progresiva.  
Sabremos que esto es cierto cuando las instituciones muestren interés en ampliar el uso del sistema, incorporar nuevos módulos o mantener el servicio bajo el modelo de suscripción.


##### 1.2.2.4. Lean UX Canvas

| **Sección** | **Descripción** |
|------------|-----------------|
| **1. Problema / Oportunidad** | En el área de enfermería cardiovascular, muchos procesos clínicos aún se realizan de manera manual o con herramientas poco integradas, lo que genera errores en los registros, dificultades en la comunicación entre turnos, poca trazabilidad de eventos críticos y retrasos en la atención. PulseReport busca digitalizar y optimizar estos procesos mediante una plataforma web que centralice la información clínica relevante y mejore la continuidad del cuidado del paciente. |
| **2. Usuarios y Clientes** | **Usuarios:** Personal de enfermería cardiovascular, médicos especialistas, personal asistencial. <br> **Clientes:** Hospitales, clínicas privadas, centros especializados en cardiología y profesionales de salud independientes. |
| **3. Supuestos** | Los usuarios necesitan acceder a información clínica de manera rápida y segura; las instituciones requieren mayor trazabilidad en los procesos asistenciales; la plataforma será adoptada si cuenta con una interfaz simple e intuitiva; la gestión digital de registros clínicos mejorará la comunicación y reducirá errores operativos. |
| **4. Necesidades del Usuario** | Registrar signos vitales, documentar traspasos SBAR, consultar historial clínico, dar seguimiento a tratamientos, registrar eventos críticos, recibir alertas y acceder a la información desde una plataforma segura y ordenada. |
| **5. Solución Propuesta** | Plataforma web orientada a la gestión de procesos críticos en enfermería cardiovascular, desarrollada para centralizar citas médicas, pacientes, historial clínico, tratamientos, signos vitales, eventos críticos y un log de auditoría inalterable, complementada con un dashboard básico para seguimiento clínico. |
| **6. Resultados (Outcomes)** | **Resultados esperados:** Mejor comunicación entre turnos, mayor trazabilidad clínica, menos errores en registros y mejor organización del cuidado del paciente. <br> **KPIs:** Reducción de errores en documentación, tiempo de registro de información clínica, cantidad de eventos críticos correctamente trazados, frecuencia de uso de la plataforma y número de usuarios activos. |
| **7. Experimentos** | Pruebas de usabilidad con usuarios simulados, validación del flujo de registro de signos vitales, simulación de traspasos SBAR, pruebas del registro de eventos críticos y evaluación del dashboard básico para comprobar que el MVP cubre las necesidades esenciales del personal de salud. |
| **8. MVP (Producto Mínimo Viable)** | Registro básico de pacientes, registro de signos vitales, documentación de traspasos SBAR, seguimiento simple de tratamientos, registro de eventos críticos, log de auditoría básico y dashboard inicial con visualización resumida de la información. |

### 1.3 Segmentos Objetivo

### Segmento objetivo #1: Personal de enfermería cardiovascular  
Este grupo está conformado por profesionales de salud que participan directamente en la atención y monitoreo de pacientes con enfermedades cardiovasculares dentro de hospitales, clínicas y centros especializados. Su labor incluye el registro de signos vitales, la documentación de tratamientos, la comunicación entre turnos y el seguimiento constante del estado del paciente para asegurar una atención continua y segura.

**Características clave de este segmento:**  
- Buscan optimizar el registro y consulta de información clínica para reducir errores y ahorrar tiempo.  
- Valoran sistemas que faciliten la comunicación entre turnos y mejoren la continuidad del cuidado del paciente.  
- Requieren herramientas que permitan registrar signos vitales, tratamientos y eventos críticos de forma rápida y ordenada.  
- Se interesan por plataformas intuitivas que les ayuden a trabajar de manera más eficiente en entornos de alta demanda.  

---

### Segmento objetivo #2: Hospitales, clínicas privadas y centros especializados en cardiología  
Este grupo está conformado por instituciones de salud que necesitan optimizar sus procesos clínicos y administrativos relacionados con la atención de pacientes en áreas cardiovasculares. Su interés principal es mejorar la organización, la trazabilidad de la información clínica y la calidad de atención, al mismo tiempo que reducen errores operativos y fortalecen la supervisión de procesos críticos.

**Características clave de este segmento:**  
- Buscan soluciones tecnológicas que centralicen la información clínica y faciliten su acceso en tiempo real.  
- Valoran plataformas que mejoren la trazabilidad de eventos críticos y la supervisión de procesos asistenciales.  
- Necesitan sistemas que contribuyan a una mejor organización del personal y de la atención brindada a los pacientes.  
- Se interesan por herramientas escalables bajo modelo SaaS que puedan adaptarse a las necesidades de su institución.

### 2.1. Competidores
#### 2.1.1. Análisis competitivo

En el sector de soluciones tecnológicas para la gestión clínica, especialmente en entornos hospitalarios, existen diversas plataformas que abordan problemáticas similares a las planteadas por PulseReport. Estas soluciones pueden clasificarse en tres categorías principales: sistemas hospitalarios integrales (HIS/EHR), sistemas de monitoreo clínico y herramientas tradicionales de gestión.

**Competidor 1: Sistemas EHR/HIS (Ej: Epic, Cerner)**

**Descripción:**
Son plataformas integrales utilizadas en hospitales y clínicas para la gestión de historiales clínicos electrónicos, citas médicas, tratamientos, facturación y otros procesos hospitalarios.

**Fortalezas:**

- Alta integración de procesos clínicos y administrativos.
- Escalabilidad a nivel institucional.
- Cumplimiento de estándares de seguridad y normativas.
- Alta confiabilidad y respaldo empresarial.

**Debilidades:**

- Interfaces complejas y poco intuitivas para el personal de enfermería.
- Alto costo de implementación y mantenimiento.
- Baja flexibilidad para adaptaciones rápidas.
- Procesos de registro poco eficientes en entornos críticos.

**Competidor 2: Sistemas de monitoreo clínico (Ej: Philips IntelliVue, GE Healthcare)**

**Descripción:**
Soluciones enfocadas en el monitoreo de signos vitales en tiempo real mediante dispositivos médicos conectados.

**Fortalezas:**

- Alta precisión en la captura de datos biomédicos.
- Monitoreo continuo en tiempo real.
- Integración con hardware especializado.

**Debilidades:**

- No gestionan procesos clínicos completos.
- No incluyen trazabilidad de eventos clínicos.
- Limitada funcionalidad en gestión de pacientes y tratamientos.
- Dependencia de infraestructura médica especializada.

**Competidor 3: Métodos tradicionales (Excel y registros en papel)**

**Descripción:**
Métodos aún utilizados en diversos centros de salud, especialmente donde la digitalización es limitada.

**Fortalezas:**

- Bajo costo.
- Fácil implementación.
- No requiere capacitación técnica avanzada.

**Debilidades:**

- Alta probabilidad de errores humanos.
- Falta de trazabilidad.
- Información dispersa y difícil de consultar.
- No permite acceso en tiempo real.
- Nula automatización.

| Criterio                 | EHR/HIS  | Monitoreo clínico | Métodos tradicionales | PulseReport |
| ------------------------ | -------- | ----------------- | --------------------- | ----------- |
| Facilidad de uso         | Baja     | Media             | Alta                  | Alta        |
| Integración de procesos  | Alta     | Baja              | Nula                  | Media       |
| Monitoreo en tiempo real | Sí       | Sí                | No                    | Parcial     |
| Trazabilidad clínica     | Alta     | Baja              | Nula                  | Alta        |
| Costo                    | Muy alto | Alto              | Bajo                  | Medio       |
| Enfoque en enfermería    | Bajo     | Bajo              | Medio                 | Alto        |

**Posicionamiento de PulseReport**

PulseReport se posiciona como una solución intermedia entre los sistemas hospitalarios complejos y las herramientas tradicionales, enfocándose específicamente en las necesidades del personal de enfermería cardiovascular.

Su propuesta se centra en:

- Simplificar el registro de información clínica.
- Centralizar datos relevantes del paciente.
- Mejorar la comunicación entre turnos mediante el modelo SBAR.
- Garantizar trazabilidad en eventos clínicos.

#### 2.1.2. Estrategias y tácticas frente a competidores

Para competir en este mercado, PulseReport adopta un conjunto de estrategias orientadas a la diferenciación, la especialización y la implementación progresiva.

**Estrategia 1: Enfoque en un nicho específico**

**Descripción:**
PulseReport se enfoca en el área de enfermería cardiovascular en lugar de intentar abarcar todo el sistema hospitalario.

**Tácticas:**

- Diseñar funcionalidades específicas para enfermería.
- Priorizar procesos críticos como registro de signos vitales y traspasos SBAR.
- Adaptar la solución a flujos reales del personal de salud.

**Estrategia 2: Simplicidad y usabilidad**

**Descripción:**
Se prioriza una interfaz intuitiva que permita realizar tareas en el menor tiempo posible.

**Tácticas:**

- Formularios simplificados para registro rápido.
- Reducción de pasos en procesos críticos.
- Diseño centrado en el usuario.

**Estrategia 3: Desarrollo basado en MVP**

**Descripción:**
El desarrollo del sistema se realiza de manera incremental, comenzando con un producto mínimo viable.

**Tácticas:**

- Implementar inicialmente:
  - Registro de signos vitales.
  - Traspasos SBAR.
- Validar funcionalidades con usuarios reales.
- Iterar en base a feedback.

**Estrategia 4: Integración como sistema complementario**

**Descripción:**
PulseReport no busca reemplazar sistemas existentes, sino integrarse como una herramienta complementaria.

**Tácticas:**

- Exportación de datos en formatos estándar.
- Diseño modular para futuras integraciones.
- Compatibilidad con flujos de trabajo existentes.

**Estrategia 5: Modelo SaaS accesible**

**Descripción:**
La solución se ofrece bajo un modelo de suscripción accesible para facilitar su adopción.

**Tácticas:**

- Planes escalables según número de usuarios.
- Bajo costo inicial.
- Implementación rápida sin infraestructura compleja.

**Estrategia 6: Trazabilidad y control de información**

**Descripción:**
Se prioriza la capacidad de auditar y rastrear eventos clínicos.

**Tácticas:**

- Registro de eventos con historial de cambios.
- Control de accesos por roles.
- Almacenamiento estructurado de información clínica.
  
**Ventaja competitiva**

La principal ventaja competitiva de PulseReport radica en su capacidad de ofrecer una solución enfocada, simple y eficiente para la gestión de procesos críticos de enfermería, evitando la complejidad de los sistemas hospitalarios tradicionales.

**Consideración estratégica**

PulseReport no busca competir directamente con sistemas EHR/HIS de gran escala, sino posicionarse como una herramienta especializada que mejora la eficiencia operativa en un área específica del proceso clínico, facilitando su adopción e implementación progresiva.

### 2.2. Entrevistas

Se realizaron entrevistas semiestructuradas con el objetivo de validar los supuestos del proyecto y comprender cómo se gestionan actualmente los procesos clínicos relacionados con el registro de información, comunicación entre turnos y seguimiento de pacientes.

Las entrevistas se enfocaron en identificar problemas reales, necesidades operativas y percepción sobre el uso de herramientas digitales en entornos clínicos.

#### 2.2.1. Diseño de entrevistas

**Objetivo**

**Recopilar información sobre:**

- Registro de información clínica
- Comunicación entre turnos
- Seguimiento de pacientes
- Problemas operativos actuales
- Necesidades frente a una solución digital

**Perfil de entrevistados**
- Personal de enfermería
- Profesionales del sector salud
- Personal vinculado a procesos clínicos o administrativos

**Guía de preguntas**
1. ¿Cuál es tu rol en el entorno de salud?
2. ¿Cómo registran actualmente la información de los pacientes?
3. ¿Qué problemas tienes al registrar signos vitales o datos clínicos?
4. ¿Cómo se comunican entre turnos?
5. ¿Qué errores o dificultades ocurren en esa comunicación?
6. ¿Pierdes tiempo buscando información del paciente?
7. ¿Qué tan importante es la trazabilidad de eventos clínicos?
8. ¿Qué limitaciones tienen las herramientas actuales?
9. ¿Usarías una plataforma que centralice esta información?
10. ¿Qué funcionalidades consideras más importantes?
11. ¿Qué haría que una herramienta sea fácil de usar?
12. ¿Qué preocupaciones tendrías al usar un sistema digital?

**Supuestos a validar**
- El registro actual es ineficiente y propenso a errores
- La comunicación entre turnos es un punto crítico
- Existe necesidad de centralizar la información
- La trazabilidad es importante
- Los usuarios prefieren soluciones simples e intuitivas

#### 2.2.2. Registro de entrevistas

**Entrevista 1 – Enfermera clínica**
<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> XXXXXXXXX <br>
      <b>Edad: </b> XXXXXXX <br>
      <b>Distrito:</b> XXXXXXXXXX <br>
      <b>Ocupacion:</b> XXXXXXXXXXXXX <br>
      <b>Timing:</b> XXXXXX <br>
      <b>Duración:</b> XXXXXXX
    </td>
    <td align=center>
      <img src="XXXXXXX" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="XXXXXXXXXXXXXXXXXXXXX"> Link </a>
      <br>
      <b>Resumen:</b> La entrevistada indicó que su trabajo implica el monitoreo constante de pacientes y el registro de signos vitales. Señaló que, en la práctica, la información se registra primero en papel y luego se transfiere al sistema digital, lo que genera retrasos y posibles omisiones. La comunicación entre turnos se realiza principalmente de forma verbal, lo que ocasiona pérdida de información relevante. Además, mencionó que suele perder tiempo buscando datos debido a que la información está dispersa. Considera fundamental la trazabilidad de eventos clínicos y estaría dispuesta a usar una herramienta digital siempre que sea rápida, simple y reduzca la carga operativa.
    </td>
  </tr>
</table>

**Entrevista 2 – Enfermero en clínica privada**

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> XXXXXXXXX <br>
      <b>Edad: </b> XXXXXXX <br>
      <b>Distrito:</b> XXXXXXXXXX <br>
      <b>Ocupacion:</b> XXXXXXXXXXXXX <br>
      <b>Timing:</b> XXXXXX <br>
      <b>Duración:</b> XXXXXXX
    </td>
    <td align=center>
      <img src="XXXXXXX" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="XXXXXXXXXXXXXXXXXXXXX"> Link </a>
      <br>
      <b>Resumen:</b> El entrevistado explicó que utiliza un sistema digital, pero lo considera complejo y poco eficiente, ya que requiere múltiples pasos para registrar información. Esto provoca que, en momentos de alta carga laboral, se opte por registrar datos de forma parcial o tardía. La comunicación entre turnos depende en gran medida de la interacción verbal, lo que genera omisiones. También señaló que la información está distribuida en distintas secciones del sistema, dificultando su acceso. Valora la trazabilidad y estaría dispuesto a adoptar una solución más simple que permita visualizar rápidamente el estado del paciente.
    </td>
  </tr>
</table>

**Entrevista 3 – Técnico de enfermería**

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> XXXXXXXXX <br>
      <b>Edad: </b> XXXXXXX <br>
      <b>Distrito:</b> XXXXXXXXXX <br>
      <b>Ocupacion:</b> XXXXXXXXXXXXX <br>
      <b>Timing:</b> XXXXXX <br>
      <b>Duración:</b> XXXXXXX
    </td>
    <td align=center>
      <img src="XXXXXXX" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="XXXXXXXXXXXXXXXXXXXXX"> Link </a>
      <br>
      <b>Resumen:</b> El entrevistado mencionó que su labor es principalmente operativa y que el registro de información se realiza inicialmente en papel. Debido a la carga de trabajo, muchos registros no se transfieren al sistema digital, lo que genera información incompleta. La comunicación entre turnos es verbal y carece de estructura, lo que incrementa el riesgo de omitir datos importantes. También indicó que se pierde tiempo buscando información del paciente. Considera importante la trazabilidad y estaría dispuesto a utilizar una herramienta digital siempre que sea simple y no agregue complejidad al proceso.
    </td>
  </tr>
</table>


**Entrevista 4 – Médico general**

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> XXXXXXXXX <br>
      <b>Edad: </b> XXXXXXX <br>
      <b>Distrito:</b> XXXXXXXXXX <br>
      <b>Ocupacion:</b> XXXXXXXXXXXXX <br>
      <b>Timing:</b> XXXXXX <br>
      <b>Duración:</b> XXXXXXX
    </td>
    <td align=center>
      <img src="XXXXXXX" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="XXXXXXXXXXXXXXXXXXXXX"> Link </a>
      <br>
      <b>Resumen:</b> El entrevistado indicó que depende de la información registrada para la toma de decisiones clínicas. Sin embargo, señaló que dicha información suele estar incompleta o desactualizada, lo que representa un riesgo en la atención del paciente. La comunicación entre turnos no siempre es estructurada, lo que dificulta comprender el estado real del paciente. También mencionó que acceder a la información puede tomar tiempo. Considera crítica la trazabilidad de eventos clínicos y valora la existencia de una herramienta que permita acceder a información clara, confiable y actualizada.
    </td>
  </tr>
</table>

**Entrevista 5 – Administrador de clínica**

<table border=1>
  <tr>
    <td>
      <b>Nombres y apellidos:</b> XXXXXXXXX <br>
      <b>Edad: </b> XXXXXXX <br>
      <b>Distrito:</b> XXXXXXXXXX <br>
      <b>Ocupacion:</b> XXXXXXXXXXXXX <br>
      <b>Timing:</b> XXXXXX <br>
      <b>Duración:</b> XXXXXXX
    </td>
    <td align=center>
      <img src="XXXXXXX" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a href="XXXXXXXXXXXXXXXXXXXXX"> Link </a>
      <br>
      <b>Resumen:</b> El entrevistado explicó que su función está relacionada con la supervisión de procesos y control de calidad. Señaló que actualmente existe dificultad para auditar lo que ocurre en cada turno debido a registros incompletos o poco claros. La comunicación entre turnos no siempre está documentada adecuadamente, lo que limita la trazabilidad. También indicó que consolidar información para análisis operativo toma tiempo. Considera fundamental contar con una herramienta que permita registrar eventos de forma clara, auditable y estructurada.
    </td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

A partir de las cinco entrevistas realizadas, se identificaron patrones consistentes en relación con la gestión de información clínica, la comunicación entre turnos y el uso de herramientas digitales en entornos de salud. El análisis permitió validar los principales supuestos del proyecto y delimitar con mayor precisión las necesidades del usuario.

**Hallazgos principales**
**1. Ineficiencia en el registro de información clínica**

Se evidenció que el proceso de registro actual es ineficiente debido al uso combinado de medios físicos y digitales. Los entrevistados indicaron que:

- Se realiza un doble registro (papel y sistema)
- El registro en el sistema suele hacerse de forma tardía
- Existe alta probabilidad de omisión o error

Este problema afecta directamente la calidad y confiabilidad de la información.

**2. Dependencia de la comunicación verbal entre turnos**

La transferencia de información entre turnos se basa principalmente en comunicación verbal, lo que genera:

- Pérdida de información relevante
- Falta de estandarización
- Dependencia de la memoria del personal

Esto impacta negativamente en la continuidad del cuidado del paciente.

**3. Información dispersa y difícil de acceder**

Se identificó que la información clínica se encuentra distribuida en múltiples fuentes, lo que provoca:

- Tiempo elevado en la búsqueda de datos
- Dificultad para obtener una visión completa del paciente
- Retrasos en la toma de decisiones

Este problema afecta tanto al personal operativo como al médico.

**4. Falta de trazabilidad de eventos clínicos**

Todos los perfiles coinciden en la importancia de contar con trazabilidad, pero actualmente existen limitaciones como:

- Registros incompletos
- Falta de claridad sobre quién realizó una acción
- Dificultad para auditar eventos pasados

Esto afecta la supervisión, el control de calidad y la toma de decisiones clínicas.

**5. Limitaciones de las herramientas actuales**

Las herramientas existentes presentan problemas comunes:

- Son complejas y poco intuitivas
- Requieren múltiples pasos para tareas simples
- No están diseñadas para entornos de alta demanda

Esto genera que, en la práctica, se evite su uso o se utilicen de forma incompleta.

**Patrones identificados**

A partir de los hallazgos, se identificaron los siguientes patrones recurrentes:

- Uso frecuente de registros manuales o mixtos
- Registro tardío o incompleto de información clínica
- Comunicación no estructurada entre turnos
- Dificultad para acceder rápidamente a información relevante
- Necesidad de herramientas más simples y rápidas

Estos patrones se repiten en todos los perfiles entrevistados, lo que refuerza la validez del problema identificado.

**Insights clave**

Del análisis se derivan los siguientes insights:

- La rapidez en el registro y acceso a la información es un factor crítico en entornos clínicos.
- La comunicación entre turnos requiere estructura y soporte digital, no solo interacción verbal.
- Los sistemas actuales fallan no por falta de funcionalidad, sino por exceso de complejidad.
- La trazabilidad no solo es importante para el control, sino también para la seguridad del paciente.
- Una solución solo será adoptada si reduce fricción operativa, no si agrega procesos adicionales.
- 
**Validación de supuestos**

Con base en las entrevistas, se validan los siguientes supuestos planteados previamente:

- Existe un problema real en el registro y gestión de información clínica.
- La comunicación entre turnos es un punto crítico del proceso asistencial.
- Los usuarios perciben valor en una herramienta que centralice la información.
- La trazabilidad de eventos clínicos es una necesidad clave.
- La usabilidad y rapidez son factores determinantes para la adopción de una solución.
**Conclusión**

El análisis de entrevistas confirma la existencia de una brecha significativa entre los procesos actuales y las necesidades reales del personal de salud. Los problemas identificados se centran en la ineficiencia del registro, la falta de trazabilidad y las limitaciones de las herramientas existentes. En este contexto, existe una oportunidad clara para el desarrollo de una solución como PulseReport, enfocada en simplificar el registro de información, mejorar la comunicación entre turnos y garantizar la trazabilidad de eventos clínicos mediante una interfaz rápida, intuitiva y adaptada al entorno operativo.
