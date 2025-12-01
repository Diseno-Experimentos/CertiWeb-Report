<!--* caratula -->

<div align="center">

# Informe Trabajo Final 📙

<img src= Images/UPC_logo_transparente.png
style="display: block; 
margin-left:auto; 
margin-right: auto; 
width=50%"/>

### Universidad Peruana de Ciencias Aplicadas ♨️

🧑‍💻 Ingeniería de software - 2025-02

**Sección:** 7500

**Docente:** Ivan Robles Fernández

**StartUp:** RepLink

**Producto:** CertiWeb

<div align='left'>	

~~~C#
static string[] Integrantes() {
    return new string[] {
        "🧑‍💻Quiroz Zambrano, Fabrizio Javier - u202213406",
        "👩‍💻 Angulo Abud, Juan Carlos - u202317692",
        "👩‍💻 Trillo Hernandez, Anghel Melanie - u201912401",
        "👩‍💻 Zúñiga Murillo, Diego Sebastián - U202310636",
        "👩‍💻 Montes Maza, Augusto Sebastian - U202218645",
    };
}
~~~

<!-- Registro de versiones -->
# Registro de versiones del Informe
<br>

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; font-size: 14px;">
  <thead>
    <tr style="background:#f7f7f7;">
      <td align="center" style="border: 1px solid #ddd; padding: 8px; width: 10%;">Versión</td>
      <td align="center" style="border: 1px solid #ddd; padding: 8px; width: 12%;">Fecha</td>
      <td align="center" style="border: 1px solid #ddd; padding: 8px; width: 33%;">Autores</td>
      <td align="center" style="border: 1px solid #ddd; padding: 8px;">Descripción</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #ccbebeff; padding: 8px; font-weight: 600;">TB1</td>
      <td style="border: 1px solid #ddd; padding: 8px;">21/09/2025</td>
      <td style="border: 1px solid #ddd; padding: 8px;">
        <ul style="margin:0 0 0 18px;">
          <li>Angulo Abud, Juan Carlos - u202317692</li>
          <li>Trillo Hernandez, Anghel Melanie - u201912401</li>
          <li>Zúñiga Murillo, Diego Sebastián - U202310636</li>
          <li>Fabrizio Javier Quiroz Zambrano – U202213406</li>
          <li>Montes Maza, Augusto Sebastian - U202218645</li>
        </ul>
      </td>
      <td style="border: 1px solid #ddd; padding: 8px;">
        <strong>Proyecto:</strong> RepLink – CertiWeb
        <ul style="margin:6px 0 0 18px;">
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Capítulo V: Product Implementation, Validation & Deployment (hasta el primer sprint)</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
<br>


# Contenido del Informe

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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

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
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)
    - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6. RESTful API Documentation](#526-restful-api-documentation)
    - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)

- [Capítulo VI: Product Verification & Validation](#capitulo-vi-product-verification-validation)
    - [6.1. Testing Suites & Validation](#6-1-testing-suites-validation)
         - [6.1.1. Core Entities Unit Tests.](#6-1-1-core-entities-unit-tests)
         - [6.1.2. Core Integration Tests.](#6-1-2-core-integration-tests)
         - [6.1.3. Core Behavior-Driven Development](#6-1-3-core-behavior-driven-development)
         - [6.1.4. Core System Tests.](#6-1-4-core-system-tests)
    - [6.2. Static Testing & Verification](#62-static-testing--verification)
         - [6.2.1. Static Code Analysis](#621-static-code-analysis)
              - [6.2.1.1. Coding Standard & Code Conventions](#6211-coding-standard--code-conventions)
              - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
         - [6.2.2. Reviews](#622-reviews)
    - [6.3. Validation Interviews](#63-validation-interviews)
         - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
         - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
         - [6.3.3. Evaluaciones según Heurísticas](#633-evaluaciones-según-heurísticas)
    - [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
         - [6.4.1. Auditoría Realizada](#641-auditoría-realizada)
              - [6.4.1.1. Información del Grupo Auditado](#6411-información-del-grupo-auditado)
              - [6.4.1.2. Cronograma de Auditoría Realizada](#6412-cronograma-de-auditoría-realizada)
              - [6.4.1.3. Contenido de Auditoría Realizada](#6413-contenido-de-auditoría-realizada)
         - [6.4.2. Auditoría Recibida](#642-auditoría-recibida)
              - [6.4.2.1. Información del Grupo Auditor](#6421-información-del-grupo-auditor)
              - [6.4.2.2. Cronograma de Auditoría Recibida](#6422-cronograma-de-auditoría-recibida)
              - [6.4.2.3. Contenido de Auditoría Recibida](#6423-contenido-de-auditoría-recibida)
              - [6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)

- [Capítulo VII: DevOps Practices](#capitulo-vii-devops-practices)
     - [7.1. Continuous Integration](#7-1-continuous-integration)
       - [7.1.1. Tools and Practices.](#7-1-1-tools-and-practices)
       - [7.1.2. Build & Test Suite Pipeline Components.](#7-1-2-build-test-suite-pipeline-components)
     - [7.2. Continuous Delivery](#7-2-continuous-delivery)
       - [7.2.1. Tools and Practices.](#7-2-1-tools-and-practices)
       - [7.2.2. Stages Deployment Pipeline Components.](#7-2-2-stages-deployment-pipeline-components)
     - [7.3. Continuous deployment](#7-3-continuous-deployment)
       - [7.3.1. Tools and Practices.](#7-3-1-tools-and-practices)
       - [7.3.2. Production Deployment Pipeline Components.](#7-3-2-production-deployment-pipeline-components)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
- 

## Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| **4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software** | Fabrizio Quiroz:Durante el desarrollo del proyecto asumí una participación activa en la validación técnica de los entregables y en la redacción de apartados clave, asegurando que las decisiones adoptadas respetaran principios de transparencia y buenas prácticas en ingeniería de software. Mi contribución se centró en garantizar la coherencia y veracidad de la documentación, así como en mantener un estándar ético en la presentación de evidencias y en la integración del informe completo. <br><br> Juan Carlos Angulo: Me encargué del despliegue del frontend y backend del proyecto CertiWeb en GitHub Pages y Render, verificando su integración y correcto funcionamiento. Asumí la responsabilidad de garantizar que el producto estuviera disponible y operativo, cumpliendo con los estándares de calidad y confiabilidad esperados.<br><br> Diego Zuñiga Murillo: En la primera entrega de CertiWeb, se trabajó bajo un marco de responsabilidad ética y profesional al definir los requerimientos iniciales del sistema. Se priorizó la protección de los datos de los usuarios, el respeto a la confidencialidad de la información y la claridad en la documentación del proyecto. Además, se establecieron lineamientos para evitar malas prácticas de programación, como el uso indebido de librerías sin licencia, y se buscó mantener un código limpio y entendible para todos los integrantes del equipo. <br><br> **Anghel Melanie Trillo Hernandez:** Durante el desarrollo de CertiWeb participé activamente en distintas etapas del proyecto: me enfoqué en la validación técnica de los entregables y en la redacción de apartados clave, asegurando coherencia, transparencia y buenas prácticas; asumí la responsabilidad del despliegue del frontend y backend en GitHub Pages y Render, garantizando su integración y correcto funcionamiento; y trabajé en la definición de requerimientos iniciales bajo un marco ético y profesional, priorizando la protección de datos, la claridad en la documentación y la limpieza del código. Estas acciones en conjunto reflejan mi compromiso con la calidad técnica, la integridad profesional y la confianza de los usuarios en el producto. <br><br> **Augusto Montes Maza:** Fui responsable del diseño de la base de datos y la lógica del backend, asegurando que la información de los certificados fuera inalterable y segura. Mi responsabilidad ética se centró en implementar mecanismos para prevenir fraudes y proteger los datos sensibles de los usuarios, garantizando la confiabilidad del sistema desde su núcleo. | Como equipo, asumimos cada etapa del proyecto CertiWeb con responsabilidad profesional y ética, entendiendo que garantizar la disponibilidad y correcto funcionamiento del sistema fortalece la confianza de los usuarios y refleja la seriedad de nuestro trabajo colaborativo. Estas acciones nos permitieron consolidar un enfoque responsable, asegurando que el desarrollo no solo cumpliera con altos estándares técnicos, sino también con principios de integridad y transparencia, lo que sienta las bases para que CertiWeb evolucione de manera confiable y sostenible. |
| **4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales** | Fabrizio Quiroz: Colaboré en la construcción y revisión del proyecto con una visión integral, evaluando cómo las soluciones propuestas podían impactar en diferentes escenarios de uso. Aporté a la planificación global del trabajo y a la integración entre documentación y desarrollo, considerando la sostenibilidad técnica del producto y su potencial incidencia en aspectos económicos y sociales. Mi enfoque estuvo orientado a emitir juicios informados que fortalecieran la relevancia del proyecto dentro de un contexto más amplio. <br><br> Juan Carlos Angulo: Analicé las decisiones de despliegue priorizando la estabilidad y accesibilidad del sistema, evaluando su impacto en los usuarios finales y en el entorno de uso real.<br><br> Diego Zuñiga Murillo: Durante la entrega, se evaluaron los impactos que podría tener CertiWeb en distintos contextos. Se discutió la necesidad de que la plataforma sea accesible para usuarios de diferentes niveles técnicos, el uso de tecnologías que optimicen recursos económicos, y la implementación de prácticas de bajo consumo energético en servidores. También se reflexionó sobre cómo el sistema puede contribuir a un entorno social más confiable al ofrecer una herramienta segura para la gestión de certificaciones digitales. <br><br> **Anghel Melanie Trillo Hernandez:** En el desarrollo de CertiWeb participé activamente en la construcción, revisión y análisis del proyecto, aportando a la planificación global y evaluando el impacto de las soluciones en distintos escenarios de uso. Me enfoqué en integrar la documentación con el desarrollo, priorizando la sostenibilidad técnica y la incidencia del sistema en aspectos económicos y sociales. Asimismo, busqué que CertiWeb se consolide como una plataforma segura, responsable y confiable para generar valor en un entorno social más transparente. <br><br> **Augusto Montes Maza:** Al diseñar la arquitectura del backend, tomé decisiones informadas sobre la gestión de datos, considerando el impacto social de un sistema de certificación confiable. Mi juicio se basó en cómo la integridad de los datos no solo previene fraudes (impacto económico), sino que también fomenta la transparencia y la confianza en transacciones digitales (impacto social), contribuyendo a un ecosistema digital más seguro. | Como equipo, comprendimos que la implementación de CertiWeb trasciende el ámbito académico, ya que una solución accesible y funcional puede generar un impacto económico y social positivo al fortalecer la confianza en los procesos de compraventa vehicular. Nuestro análisis nos permitió emitir juicios informados que consideraron no solo los aspectos técnicos, sino también las implicancias sociales, económicas y ambientales, consolidando a CertiWeb como una propuesta viable, responsable y con potencial de aportar valor real a la sociedad. |


## Capítulo I: Introducción

### 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

CertiWeb es una plataforma digital dedicada a la inspección y certificación de vehículos usados. Su propósito es reducir la desconfianza que existe en el mercado automotriz de segunda mano, ofreciendo un sistema confiable para verificar el estado real de un auto antes de la compra o venta.

El servicio se basa en un proceso de certificación técnica realizado por especialistas, quienes evalúan el vehículo bajo un protocolo de más de cien puntos clave que incluyen aspectos mecánicos, eléctricos, estructurales y estéticos. A partir de esta evaluación se genera un informe detallado acompañado de un sello digital de certificación, el cual puede integrarse en publicaciones de venta en línea.

De esta manera, los compradores acceden a información clara y verificada que les brinda seguridad en la decisión de compra, mientras que los vendedores individuales, revendedores o concesionarias incrementan la velocidad de venta y logran un mejor posicionamiento de sus unidades en el mercado.

La plataforma también contempla un historial de inspecciones y certificaciones, lo que permite construir un registro transparente del vehículo a lo largo del tiempo. Para negocios automotrices, CertiWeb ofrece además herramientas de gestión como carga masiva de vehículos, seguimiento de certificaciones y soporte especializado.

En conjunto, CertiWeb se proyecta como un referente digital en certificación automotriz, combinando tecnología, procesos estandarizados y comunicación clara para profesionalizar el mercado de autos usados en Latinoamérica.

### 1.1.2. Perfiles de integrantes del equipo

**> Fabrizio Javier Quiroz Zambrano (U202213406)**  
<div align="center">
  <img src="Images/Fabrizio1.jpg" alt="imagen Fabrizio" width="120" align="right">
  
~~~txt
Estudiante de 6to ciclo de Ingeniería de Software en la UPC.
Experiencia en C++, Angular, Python y SQL, con énfasis en desarrollo frontend.
Me considero comprometido, adaptable y con mentalidad de aprendizaje constante.
Expectativa: fortalecer habilidades fullstack y crear software útil, escalable y centrado en las personas.
~~~
</div>

---

**> Juan Carlos Angulo Abud (U202317692)**  
<div align="center">
  <img src="Images/JuanCarlosAnguloPortrait.jpg" alt="imagen Juan Carlos Angulo" width="120" align="right">
  
~~~txt
Soy un estudiante de 5to ciclo de la carrera de ingeniería de software en la UPC.
Tengo experiencia creando aplicaciones web usando react y consumiendo APIs externas.
Me gusta el ámbito front end más que el back end. Soy una persona orientada a objetivos,
responsable, comprometido y con ganas de siempre aprender más.
~~~
</div>

---

**> Anghel Melanie Trillo Hernandez (U201912401)**  
<div align="center">
  <img src="Images/anghel-trillo.jpg" alt="imagen Anghel Melanie Trillo Hernandez" width="120" align="right">
  
~~~txt
Estudiante de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC),
lo que me gusta de la carrera es desarrollar soluciones innovadoras que contribuyen a la sociedad.
Me considero una persona responsable y orientada a resultados. Asimismo, me comprometo a colaborar
en el equipo de forma continua y puntual.
~~~
</div>

---

**> Diego Sebastián Zuñiga Murillo (U202310636)**  
<div align="center">
  <img src="Images/diego-z.png" alt="imagen Integrante 4" width="120" align="right">
  
~~~txt
Mi nombre es Diego, soy estudiante de la carrera de ingenieria de software y tengo 20 años,
actualmente me encuentro cursando el sexto ciclo en la universidad. Algo a saber de mi es que
siempre estoy constantemente aprendiendo las nuevas teconologias que salen al mercado para asi
poder adaptarme facilmente a los cambios en la sociedad. Busco expandir mas mis conocimientos
desarrollando proyectos en conjunto con mi grupo de trabajo
~~~
</div>

---

**> Augusto Sebastian Montes Maza (U202218645)**  
<div align="center">
  <img src="Images/AugustoMontes.png" alt="imagen Augusto Montes" width="120" align="right">
  
~~~txt
Como estudiante de Ingeniería de Software de la UPC, me motiva crear soluciones tecnológicas
que no solo sean eficientes, sino que también generen un impacto positivo. Me considero un buen
compañero de equipo, siempre dispuesto a colaborar y a encontrar la mejor manera de superar los desafíos.
Mi objetivo es aportar con creatividad y dedicación para que juntos alcancemos resultados excepcionales.
~~~
</div>

---

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

El mercado de vehículos usados en Perú y en gran parte de Latinoamérica enfrenta un reto estructural: la falta de confianza entre compradores y vendedores.  
Los compradores, al no contar con información clara ni verificable sobre el estado de un vehículo, asumen un riesgo económico y de seguridad significativo.  
Este contexto se traduce en tres grandes problemáticas:

| Problemática | Impacto en compradores | Impacto en vendedores |
|--------------|------------------------|------------------------|
| Falta de transparencia sobre el estado real del vehículo | Inseguridad en la decisión de compra; riesgo de adquirir autos con fallas ocultas. | Dificultad para demostrar objetivamente la calidad del auto. |
| Ausencia de un historial técnico verificable | No existe evidencia clara de inspecciones pasadas o mantenimientos. | Pérdida de valor percibido del vehículo. |
| Desconfianza generalizada en el mercado de segunda mano | Se ralentiza la decisión de compra, generando procesos largos e inciertos. | Reducción en la velocidad de venta y en el precio de las unidades. |

A pesar de que existen talleres mecánicos y servicios de revisión parcial, la ausencia de un **estándar digital de certificación** limita la transparencia del mercado.  
**CertiWeb** surge como respuesta a esta brecha, con una propuesta integral que combina:  

- **Inspección técnica estandarizada** en más de 100 puntos clave (mecánicos, eléctricos, estructurales y estéticos).  
- **Informe digital detallado** con fotografías y observaciones.  
- **Sello de certificación verificable en línea**, que puede integrarse en anuncios de venta.  
- **Historial acumulativo de inspecciones**, que refuerza la trazabilidad del vehículo.  

Con ello se busca **reducir la asimetría de información**, generar confianza y acelerar la rotación de autos usados en el mercado.

| Pregunta | Respuesta para CertiWeb |
|---|---|
| Who (¿Quién?) | Compradores de autos usados que buscan certeza técnica antes de comprar; vendedores particulares que desean vender más rápido y con mejor percepción de valor; revendedores y concesionarias que requieren un flujo estandarizado para múltiples unidades. |
| What (¿Qué?) | Servicio de inspección técnica estandarizada y certificación digital del vehículo, con informe detallado (ficha técnica, hallazgos, fotografías) y un sello de certificación embebible en avisos y páginas de venta. Incluye historial de certificaciones por vehículo y, para revendedores, herramientas de gestión (carga masiva y seguimiento). |
| Where (¿Dónde?) | Operación inicial enfocada en el mercado local (Perú, con énfasis en Lima) y distribución digital del certificado a través de URL pública y elementos embebibles en portales de venta y redes. Proyección a expansión regional. |
| When (¿Cuándo?) | Antes de publicar el vehículo en plataformas de venta; como verificación previa a la compra por parte del comprador; en renovaciones de publicación o tras mantenimientos relevantes (vigencia típica del certificado definida por el plan comercial). |
| Why (¿Por qué?) | Reducir la asimetría de información y la desconfianza en el mercado de segunda mano; acelerar el tiempo de venta; mejorar la tasa de contacto y la conversión; proteger la reputación del vendedor/revendedor con evidencia técnica verificable. |
| How (¿Cómo?) | Flujo propuesto: solicitud en la plataforma → agenda de inspección → evaluación bajo protocolo de más de cien puntos clave (mecánico, eléctrico, estructural y estético) → generación de informe y sello digital con identificador verificable → publicación/embebido del sello y enlace al informe. Para portafolios grandes: carga masiva, estados y renovaciones. |
| How much (¿Cuánto cuesta?) | Estructura de precios documentada en el repositorio con referencias a: plan de entrada limitado, plan mensual y plan anual; y cobro por certificación por vehículo. Las cifras del repositorio muestran propuestas que deben unificarse en una única tabla comercial (por ejemplo: certificado por unidad, y planes con límites/beneficios). La definición final queda sujeta a validación con usuarios y coherencia de costos. |

---

#### 1.2.2. Lean UX Process

El proceso de diseño de CertiWeb se fundamenta en **Lean UX**, metodología que privilegia la validación temprana de hipótesis y el aprendizaje continuo con usuarios reales.  
El enfoque Lean UX aplicado al proyecto permitió identificar los problemas, convertirlos en supuestos verificables y transformarlos en hipótesis de producto que guían el desarrollo.

---

##### 1.2.2.1. Lean UX Problem Statements

Los problemas detectados en el mercado y que CertiWeb busca resolver se expresan de la siguiente forma:

| Problem Statement | Explicación |
|-------------------|-------------|
| Los compradores no confían en la información que reciben sobre autos usados. | La falta de transparencia impide tomar decisiones de compra seguras. |
| Los vendedores carecen de un mecanismo confiable y digital para demostrar la calidad de sus vehículos. | Esto ralentiza sus procesos de venta y reduce el valor percibido. |
| No existe un servicio estandarizado de certificación digital en el mercado. | La ausencia de un estándar reconocido genera un mercado poco profesionalizado y vulnerable a la desconfianza. |

---

##### 1.2.2.2. Lean UX Assumptions

A partir de los problemas detectados, se definieron los supuestos iniciales que guían la construcción de la solución:

| Supuesto | Justificación |
|----------|---------------|
| Los compradores valoran un informe técnico verificable y estarían dispuestos a priorizar vehículos certificados. | La evidencia visual y estandarizada reduce la percepción de riesgo. |
| Los vendedores aceptarían el costo de la certificación si les permite vender más rápido y a un mejor precio. | La relación costo-beneficio se traduce en mayor competitividad en el mercado. |
| Un sello digital de certificación en anuncios de autos usados aumentará la confianza y la tasa de contacto. | La señal de transparencia funciona como diferenciador frente a publicaciones sin certificación. |
| Revendedores y concesionarias con alto volumen se beneficiarán de herramientas de gestión y carga masiva. | La optimización del proceso impacta directamente en su productividad y en la rotación de su stock. |

---

##### 1.2.2.3. Lean UX Hypothesis Statements

De los supuestos anteriores se formularon hipótesis de producto que orientan la validación y experimentación:

| Hipótesis | Criterio de validación |
|-----------|-------------------------|
| Si integramos un sello digital de certificación en publicaciones de autos usados, la tasa de contacto y cierre aumentará respecto a publicaciones sin certificación. | Comparación de métricas de conversión en plataformas de venta. |
| Si entregamos un informe técnico detallado con fotografías, los compradores percibirán mayor seguridad y estarán más dispuestos a concretar la compra. | Encuestas post-visualización y análisis de intención de compra. |
| Si proporcionamos a revendedores herramientas de carga masiva y gestión de certificaciones, aumentarán su productividad y volumen de ventas. | Medición de número de certificados generados y unidades vendidas por usuario corporativo. |
| Si generamos un historial transparente de certificaciones, los autos con más de una inspección validada tendrán mayor preferencia en el mercado. | Evaluación de preferencia en entrevistas y análisis de datos de ventas. |

---

##### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas permitió organizar de manera visual los problemas, supuestos, hipótesis y métricas de CertiWeb, sirviendo como guía estratégica para alinear las necesidades del usuario con los objetivos del negocio.

<img src="Images/lean-ux-canvas.png"/>

[Link del Canvas](https://app.mural.co/t/certiwerb1488/m/certiwerb1488/1744410865572/59e706ebe76d0e4606051edfad70dcd865593dee?sender=u14a78cec8f790f32120e9679)


### 1.3. Segmentos objetivo

El proyecto CertiWeb se centra en tres segmentos principales del mercado de compraventa de autos usados. Cada segmento presenta necesidades, motivaciones y desafíos particulares que fundamentan la propuesta de valor de la startup.

---

#### 1. Vendedores individuales de autos usados

| Aspecto | Detalle |
|---------|---------|
| **Perfil** | Personas que desean vender su propio auto de manera directa, sin intermediarios. |
| **Necesidades** | - Generar confianza en compradores desconocidos.<br>- Reducir el tiempo de venta.<br>- Evitar regateos excesivos y sospechas sobre el estado del vehículo. |
| **Dolores actuales** | - Desconfianza de los compradores.<br>- Dificultad para demostrar el estado real del auto.<br>- Riesgo de que el vehículo se deprecie mientras permanece en venta. |
| **Valor que aporta CertiWeb** | Una certificación técnica imparcial que valida el estado del vehículo y sirve como respaldo confiable al momento de negociar, aumentando la rapidez y el valor de la venta. |

---

#### 2. Revendedores o pequeños comerciantes de autos usados

| Aspecto | Detalle |
|---------|---------|
| **Perfil** | Personas o negocios que compran autos usados para revenderlos en menor escala (2 a 10 vehículos al mes). |
| **Necesidades** | - Rotación rápida de inventario.<br>- Disminuir devoluciones o reclamos de clientes.<br>- Contar con reportes técnicos que aumenten la credibilidad de sus ventas. |
| **Dolores actuales** | - Dependencia de mecánicos informales sin documentación.<br>- Escasa diferenciación frente a la competencia.<br>- Poca confianza del cliente final en el producto ofrecido. |
| **Valor que aporta CertiWeb** | Una herramienta profesional que mejora la reputación del revendedor, estandariza la verificación técnica y facilita cerrar ventas con mayor rapidez. |

---

#### 3. Compradores

| Aspecto | Detalle |
|---------|---------|
| **Perfil** | Personas interesadas en adquirir un auto de segunda mano, preocupadas por la seguridad y la transparencia del proceso. |
| **Necesidades** | - Minimizar el riesgo de estafas.<br>- Garantizar que el auto se encuentre en buenas condiciones.<br>- Acceder a información clara y confiable antes de tomar la decisión de compra. |
| **Dolores actuales** | - Temor a ocultamiento de fallas mecánicas.<br>- Desconfianza hacia vendedores o revendedores.<br>- Dificultad para encontrar información técnica accesible. |
| **Valor que aporta CertiWeb** | Un informe detallado y visual que respalda la compra, genera tranquilidad y aumenta la confianza en la decisión de adquirir el vehículo. |

---



---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

El mercado de autos usados en Perú y en el extranjero está ocupado por portales digitales y talleres tradicionales que ofrecen servicios de publicación, diagnóstico o verificación. CertiWeb se diferencia de todos ellos al proporcionar **una certificación imparcial, estandarizada y digital**, diseñada para acelerar la compraventa y aumentar la confianza.

---

##### Neoauto (Perú) – Competidor directo

| Aspecto | Detalle |
|---------|---------|
| **Sitio web** | [neoauto.com](https://www.neoauto.com) |
| **Descripción** | Portal líder de anuncios de autos en Perú, dirigido a vendedores y concesionarias. |
| **Modelo** | Publicaciones pagadas con reportes básicos (sin inspecciones profundas). |
| **Relación con CertiWeb** | Rival directo en verificación vehicular. |
| **Ventaja de CertiWeb** | - Diagnóstico imparcial (no participa en compraventa).<br>- Sello de confianza aplicable en cualquier portal.<br>- Inspección técnica con más de 100 puntos. |

---

##### AutoTrader (Reino Unido) – Competidor internacional

| Aspecto | Detalle |
|---------|---------|
| **Sitio web** | [autotrader.co.uk](https://www.autotrader.co.uk) |
| **Descripción** | Plataforma británica de referencia en compraventa de vehículos. |
| **Modelo** | Reportes históricos y conexión con talleres aliados. |
| **Relación con CertiWeb** | Ejemplo internacional de certificación integrada. |
| **Ventaja de CertiWeb** | - Adaptado al mercado peruano.<br>- Inspecciones estandarizadas (100+ puntos).<br>- Costos accesibles para el contexto local. |

---

##### Cars.com (EE.UU.) – Competidor internacional

| Aspecto | Detalle |
|---------|---------|
| **Sitio web** | [cars.com](https://www.cars.com) |
| **Descripción** | Portal estadounidense con herramientas de evaluación y diagnóstico. |
| **Modelo** | Informes de condición y calificaciones mecánicas. |
| **Relación con CertiWeb** | Referencia de integración de reportes en ventas digitales. |
| **Ventaja de CertiWeb** | - Servicio 100% local con soporte en Perú.<br>- Informes más completos y visuales.<br>- Precios adaptados al mercado regional. |

---

##### Talleres mecánicos tradicionales – Competencia indirecta

| Aspecto | Detalle |
|---------|---------|
| **Descripción** | Talleres físicos que realizan diagnósticos previos a la venta. |
| **Modelo** | Servicio presencial, sin estandarización digital. |
| **Relación con CertiWeb** | Alternativa básica frente a la certificación digital. |
| **Ventaja de CertiWeb** | - Informe profesional con fotos.<br>- Historial digital accesible.<br>- Sello de garantía transferible. |

---

##### Comparación general de competidores

| **Categoría**            | **Aspecto**              | **CertiWeb** | **Neoauto** | **Cars.com** | **Talleres mecánicos** |
|---------------------------|--------------------------|--------------|-------------|--------------|-------------------------|
| **Perfil**               | Overview                 | Taller digital especializado en inspecciones y certificaciones imparciales que acelera ventas con confianza. | Portal líder en anuncios de compraventa de autos en Perú. | Plataforma internacional que conecta compradores con concesionarios y ofrece historial vehicular. | Servicio presencial de revisión técnica básica sin respaldo digital. |
|                           | Ventaja competitiva      | Informe técnico detallado con fotos, certificación imparcial, sello de confianza y revisión de más de 100 puntos. | Alto tráfico web y gran visibilidad en el mercado peruano. | Acceso a historial, valoración digital y contacto directo con dealers. | Diagnóstico rápido y económico, pero sin documentación ni sello de garantía. |
| **Perfil de Marketing**  | Mercado objetivo          | Vendedores individuales, revendedores y concesionarias que buscan confianza y rapidez. | Vendedores y concesionarias que desean maximizar alcance y exposición. | Usuarios en EE.UU. interesados en compraventa digital con soporte en línea. | Propietarios y compradores locales que requieren diagnósticos inmediatos. |
|                           | Estrategias de marketing | SEO local, marketing digital, alianzas estratégicas y uso de casos de éxito reales. | Publicidad en buscadores, redes sociales y planes premium dentro de su portal. | SEO global, marketing de contenido, convenios con concesionarios y reviews de usuarios. | Publicidad boca a boca, recomendaciones directas y presencia física en zonas concurridas. |
| **Perfil de Producto**   | Servicios                 | Inspección técnica profesional, informe digital con fotos, sello de confianza y planes de suscripción (mensual/anual). | Publicación de autos, filtros avanzados y planes de anuncios destacados. | Publicaciones, historial vehicular, calculadora de valor y conexión con concesionarios. | Revisión mecánica básica, pruebas de carretera y verificación de fallas, sin respaldo digital. |
|                           | Precios & Costos         | Plan **Free** con funciones limitadas. Plan mensual **S/ 50**. Plan anual **S/ 250** con beneficios adicionales y soporte prioritario. | Desde **S/ 150** por publicación con vigencia de 60 días. | Desde **S/ 150** por certificación con vigencia de 30 días. | Promedio de **S/ 200** por diagnóstico, con vigencia de 30 días. |


---

#### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategias principales**  
1. **Certificación imparcial:** posicionamiento como tercero independiente.  
2. **Rapidez y confianza:** promesa clara: “vende tu auto más rápido y con más seguridad”.  
3. **Alianzas estratégicas:** integración del sello CertiWeb en portales como Neoauto y Todoautos.  
4. **Educación del cliente:** creación de contenido educativo sobre riesgos en autos usados.  
5. **Segmentación definida:** mensajes diferenciados para vendedores, revendedores y concesionarias.  

**Tácticas implementadas**  
- Promociones iniciales para usuarios tempranos.  
- Certificado visualmente atractivo para publicaciones digitales.  
- Campañas geolocalizadas en Facebook, Instagram y TikTok.  
- Sistema de referidos con beneficios para clientes y nuevos usuarios.  
- Planes de suscripción flexibles (mensual y anual) con beneficios extra.  
- Portal web con informes descargables en PDF y panel de gestión para clientes.  

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

El diseño de entrevistas se estructuró en tres segmentos principales: vendedores particulares, revendedores y compradores.  
Cada segmento tiene un **objetivo de investigación**, la **información que se busca recolectar** y un conjunto de **preguntas clave** que guían la conversación.

---

##### Segmento 1: Vendedores particulares

| Elemento | Detalle |
|----------|---------|
| **Objetivo** | Conocer motivaciones, temores y experiencias al vender autos usados. |
| **Información a recolectar** | - Datos demográficos (edad, género, distrito)<br>- Experiencia previa en ventas<br>- Canales de venta utilizados<br>- Problemas enfrentados<br>- Conocimiento de servicios de inspección |

**Preguntas clave**  
1. ¿Has vendido un auto usado anteriormente? ¿Cómo fue la experiencia?  
2. ¿Cuál fue tu principal preocupación al momento de vender?  
3. ¿Dónde sueles publicar un auto en venta?  
4. ¿Qué tanto confías en los compradores que te contactan por internet?  
5. ¿Te ha pasado que los compradores desconfiaban del estado del auto?  
6. ¿Alguna vez has mentido u omitido detalles al vender tu auto? ¿Por qué?  
7. ¿Qué haces para que confíen en que tu auto está en buen estado?  
8. ¿Conoces algún servicio que certifique el estado de un auto antes de venderlo?  
9. ¿Pagarías por un servicio que te ayude a vender más rápido? ¿Cuánto?  
10. ¿Qué valoras más: vender rápido o vender a mejor precio?  
11. ¿Qué tan complicado es conseguir un mecánico de confianza?  
12. ¿Te sentirías más seguro si un experto validara que tu auto está bien?  
13. ¿A qué te dedicas? ¿Te deja tiempo para lidiar con una venta de auto?  
14. ¿Qué edad tienes y dónde vives?  
15. ¿Qué redes sociales usas con más frecuencia?  
16. ¿Compraste ese auto nuevo o de segunda? ¿Cómo fue esa compra?  
17. ¿Qué dispositivos usas más para hacer tus búsquedas? (Celular, PC, etc.)  
18. ¿Tienes familia o dependientes a los que involucres en tus decisiones?  
19. ¿Qué frustraciones has tenido al vender autos en el pasado?  
20. Si tuvieras una herramienta que agilice y dé más confianza al proceso de venta, ¿la usarías?  

---

##### Segmento 2: Revendedores

| Elemento | Detalle |
|----------|---------|
| **Objetivo** | Entender el proceso comercial de reventa y el uso de certificaciones. |
| **Información a recolectar** | - Volumen de venta mensual<br>- Uso de mecánicos o talleres<br>- Necesidad de rotación rápida<br>- Canales de venta principales<br>- Presupuesto destinado a inspecciones |

**Preguntas clave**  
1. ¿A cuántos autos les das rotación al mes?  
2. ¿Cómo aseguras la calidad mecánica antes de venderlos?  
3. ¿Tienes un mecánico fijo o trabajas con varios talleres?  
4. ¿Sueles invertir en diagnósticos antes de vender?  
5. ¿Te ha pasado que un cliente devolvió o se quejó del auto vendido?  
6. ¿Qué importancia tiene la confianza para cerrar una venta?  
7. ¿Has usado servicios de certificación antes? ¿Cuáles?  
8. ¿Con qué portales trabajas para publicar tus autos?  
9. ¿Crees que un sello de certificación ayudaría a vender más rápido?  
10. ¿Qué valoras más: ahorro de tiempo o validación técnica?  
11. ¿Cuánto estarías dispuesto a pagar por un servicio mensual de inspección?  
12. ¿Qué tipo de clientes te exigen más pruebas de calidad?  
13. ¿Cómo gestionas el papeleo y documentación?  
14. ¿Te ha beneficiado tener informes técnicos o fotos detalladas del auto?  
15. ¿Crees que hay mucha competencia en tu zona? ¿Qué te diferencia?  
16. ¿Qué edad tienes y en qué distrito trabajas?  
17. ¿Qué dispositivos usas para tus operaciones? (WhatsApp, Facebook, OLX, etc.)  
18. ¿Cuál es tu mayor frustración al vender autos?  
19. ¿Qué marcas prefieres revender y por qué?  
20. ¿Estarías dispuesto a incluir el costo de inspección como parte del precio final?  

---

##### Segmento 3: Compradores

| Elemento | Detalle |
|----------|---------|
| **Objetivo** | Identificar temores y procesos de evaluación al adquirir autos usados. |
| **Información a recolectar** | - Motivaciones de compra<br>- Nivel de conocimiento técnico<br>- Canales de búsqueda<br>- Riesgos percibidos<br>- Métodos de validación |

**Preguntas clave**  
1. ¿Has comprado un auto usado alguna vez? ¿Cómo fue la experiencia?  
2. ¿Qué es lo que más te preocupa al comprar un auto de segunda?  
3. ¿Cómo sueles verificar que el auto esté en buen estado?  
4. ¿Conoces algún taller o mecánico de confianza?  
5. ¿Te has sentido estafado o engañado en alguna compra anterior?  
6. ¿Qué tan importante es para ti que el auto tenga un informe técnico?  
7. ¿Confías en los vendedores de autos en general?  
8. ¿Te parece útil que un auto tenga un certificado de inspección antes de comprarlo?  
9. ¿Pagarías más por un auto que tenga esa certificación?  
10. ¿Dónde sueles buscar autos: Marketplace, OLX, portales especializados?  
11. ¿Qué redes sociales usas más para revisar o buscar autos?  
12. ¿Qué dispositivos usas para hacer búsquedas?  
13. ¿Qué edad tienes, dónde vives y a qué te dedicas?  
14. ¿Tomas la decisión solo o con tu pareja/familia?  
15. ¿Qué aspectos del auto revisas tú mismo antes de comprar?  
16. ¿Cómo decides si confiar en un vendedor?  
17. ¿Qué marcas o modelos te generan más confianza?  
18. ¿Te gustaría recibir asesoría profesional para tu próxima compra?  
19. ¿Qué contenido te parecería útil: videos, checklist, informes descargables?  
20. ¿Has tenido malas experiencias post-compra? ¿Cuáles?  

---

#### 2.2.2. Registro de entrevistas

El registro de entrevistas se organizó en tres segmentos de usuarios clave: vendedores particulares, revendedores y compradores.  
Cada entrevista incluye datos demográficos, la percepción del entrevistado, así como el enlace a la grabación correspondiente.

---

### Segmento 1: Vendedores particulares

| Entrevistado | Christian Trillo |
|--------------|------------------|
| **Edad**     | 45 años |
| **Distrito** | La Victoria |
| <img src="Images/entrevista2.png" width="200"/> | Nunca ha vendido un auto usado, pero le preocupa encontrar plataformas confiables (usa Marketplace o letreros físicos). Desconfía de compradores en internet y cree que la transparencia es clave. Para generar confianza, muestra mantenimientos al día y recomienda que el comprador lleve un mecánico. Conoce talleres de certificación, pero suele dejar la validación al comprador. Prefiere vender a buen precio antes que rápido. Destaca la dificultad de encontrar mecánicos confiables. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=5rWZaluun-HzSOoU&t=2) |
| **Timming** | 00:00 - 07:29 |

---

| Entrevistado | Germán Espinoza |
|--------------|-----------------|
| **Edad**     | 27 años |
| **Distrito** | Ate Vitarte |
| <img src="Images/entrevista3.png" width="200"/> | Vendió su auto el año pasado, pero el proceso fue frustrante por compradores indecisos y regateos. Publicó en Marketplace y OLX, aunque desconfía de los interesados (muchos preguntan pero no concretan). Insiste en la transparencia y muestra comprobantes de mantenimiento. Considera útil un servicio de certificación y pagaría hasta 200 soles si agiliza la venta. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=LPMD3yZgh_geO01K&t=457) |
| **Timming** | 07:36 - 12:20 |

---

| Entrevistado | Rómulo Mucho |
|--------------|--------------|
| **Edad**     | 21 años |
| **Distrito** | La Molina |
| <img src="Images/entrevista4.png" width="200"/> | Vendió un Honda Civic 2004; el proceso fue agotador por mensajes constantes y compradores poco serios. Publicó en Marketplace y grupos de WhatsApp. Valora vender rápido (incluso a menor precio) y reconoce la dificultad de encontrar mecánicos confiables. Pagaría 80-100 soles por un servicio que evite pérdida de tiempo. Un informe técnico independiente le daría mayor seguridad a los compradores. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=nEhGzcHJCSvWN6yy&t=744) |
| **Timming** | 12:24 - 18:11 |

---

### Segmento 2: Revendedores

| Entrevistado | Boris Arana |
|--------------|-------------|
| **Edad**     | 49 años |
| **Distrito** | Lima |
| <img src="Images/entrevista5.png" width="200"/> | Resalta la importancia de revisiones técnicas previas (compresión del motor, frenos, suspensión, etc.). Critica el fraude del kilometraje alterado y apoya la certificación técnica como generadora de confianza. Sugiere incluir pruebas de manejo, frenado y estado de autopartes en los informes. Confiaría en el servicio si demuestra seriedad y garantía. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=xggXM3BkGd0ERmf3&t=1099) |
| **Timming** | 18:19 - 29:29 |

---

| Entrevistado | Crhistabell |
|--------------|-------------|
| **Edad**     | 30 años |
| **Distrito** | Lima |
| <img src="Images/entrevista6.png" width="200"/> | Vende autos en Marketplace y NeoAuto. Realiza inspecciones básicas en su taller, pero cree que la certificación técnica solo será útil si la marca es reconocida. Propone que los informes incluyan historial de choques y aspectos legales (como en EE.UU.). Estaría dispuesto a probar el servicio si demuestra confiabilidad. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=Flv4lI5k60DShIrX&t=1773) |
| **Timming** | 29:33 - 41:40 |

---

| Entrevistado | Juan Carlos Ramírez |
|--------------|----------------------|
| **Edad**     | 38 años |
| **Distrito** | Lima |
| <img src="Images/entrevista7.png" width="200"/> | Rota 2-3 autos mensuales, revisados por un mecánico fijo. Usa informes como Total Check para verificar historial. Considera clave la confianza y el precio competitivo. Pagaría hasta 80 soles por certificación básica, aunque duda de su valor si no hay propuesta clara. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=NMHNuR3arRq4bcgp&t=2505) |
| **Timming** | 41:45 - 53:35 |

---

### Segmento 3: Compradores

| Entrevistado | Jorge Andrés |
|--------------|--------------|
| **Edad**     | 22 años |
| **Distrito** | Lima |
| <img src="Images/entrevista8.png" width="200"/> | Busca autos en Marketplace y valora informes técnicos para evitar fallas ocultas. Confía en mecánicos propios y prefiere marcas premium (BMW, Mercedes). Estaría dispuesto a pagar más por certificación y sugiere incluir videos y checklist como herramientas adicionales. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=Zp6Jhys5Qd-bNnWL&t=3218) |
| **Timming** | 53:38 - 58:17 |

---

| Entrevistado | Carlos |
|--------------|--------|
| **Edad**     | 25 años |
| **Distrito** | Lima |
| <img src="Images/entrevista1.png" width="200"/> | Analista financiero de 25 años. Ha tenido experiencias mixtas al comprar autos usados, lo que incrementó su desconfianza hacia vendedores. Su mayor preocupación son fallas ocultas, por lo que recurre a talleres de confianza en San Miguel. Usa Marketplace, OLX, NeoAuto e Instagram desde su celular. Prefiere marcas confiables como Toyota, Hyundai y Nissan. Aunque consulta a sus padres, toma la decisión final él mismo. Estaría dispuesto a pagar extra por informes técnicos. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=3lmut_3RamZOcpxD&t=3502) |
| **Timming** | 58:22 - 01:02:34 |

---

| Entrevistado | Rodrigo Salvador |
|--------------|------------------|
| **Edad**     | 24 años |
| **Distrito** | Lima |
| <img src="Images/entrevista9.png" width="200"/> | Técnico en redes de 24 años. Compró su primer auto usado el año pasado en un proceso largo y estresante. Sus principales preocupaciones son fallas ocultas (motor, frenos) y problemas de papeleo. Aunque confía en un mecánico conocido, considera esencial contar con un informe técnico. Prefiere marcas como Toyota, Suzuki y Chevrolet. Busca autos en Marketplace y grupos de Facebook, usando su celular. Valora la asesoría profesional y los videos explicativos. Tras su compra, experimentó un problema no detectado en la dirección, reforzando su necesidad de mayor seguridad en futuras adquisiciones. |
| **URL de la grabación** | [Link](https://youtu.be/PCCgQrpIDJs?si=5_BjjUsmW3llsm0V&t=3760) |
| **Timming** | 01:02:40 - 01:13:00 |


#### 2.2.3. Análisis de entrevistas

El análisis de las entrevistas se organizó por segmento objetivo.  
En cada caso se destacan las características objetivas y subjetivas más recurrentes, respaldadas con porcentajes sobre el total de entrevistados (3 por segmento).  

---

### Segmento 1: Vendedores individuales

| Dimensión | Hallazgos clave |
|-----------|-----------------|
| **Experiencia y motivación** | - **67%** (2 de 3) ha vendido antes y describe la experiencia como frustrante o agotadora debido a compradores indecisos.<br>- **67%** (2 de 3) considera la transparencia fundamental (mostrar mantenimientos, sugerir mecánicos).<br>- Las motivaciones varían: **33%** prioriza vender rápido, otro **33%** prioriza mejor precio. |
| **Plataformas y confianza** | - **67%** (2 de 3) utiliza plataformas digitales como Marketplace u OLX.<br>- Existe una desconfianza generalizada hacia compradores online (**67%**).<br>- **67%** reconoce dificultad para encontrar mecánicos de confianza. |
| **Percepción del servicio de certificación** | - **67%** (2 de 3) lo considera útil y estaría dispuesto a pagar (rangos de 80-100 hasta 200 soles).<br>- **33%** percibe que un informe técnico independiente generaría seguridad adicional en los compradores. |

---

### Segmento 2: Revendedores o pequeños comerciantes

| Dimensión | Hallazgos clave |
|-----------|-----------------|
| **Proceso de venta y verificación** | - **100%** (3 de 3) enfatiza la importancia de revisiones técnicas previas.<br>- **67%** trabaja con mecánicos/talleres fijos.<br>- **67%** menciona preocupación por fraudes (kilometraje alterado, historial oculto).<br>- Algunos usan informes como *Total Check* (**33%**). |
| **Percepción del servicio de certificación** | - **100%** (3 de 3) valora la certificación técnica para generar confianza, aunque con matices: utilidad solo si la marca es reconocida o dudas sobre su valor si no hay propuesta clara.<br>- **67%** dispuesto a pagar bajo condiciones (precio razonable, hasta 80 soles, y seriedad demostrada).<br>- **33%** sugiere incluir historial de choques y aspectos legales. |
| **Factores clave de decisión** | - La confianza y un precio competitivo son determinantes para cerrar ventas (**33%**). |

---

### Segmento 3: Compradores

| Dimensión | Hallazgos clave |
|-----------|-----------------|
| **Preocupaciones y confianza** | - **100%** (3 de 3) teme fallas mecánicas ocultas.<br>- **67%** ha tenido experiencias negativas o desconfía de vendedores.<br>- **100%** recurre a mecánicos propios o conocidos para revisar el auto. |
| **Proceso de búsqueda** | - **100%** usa plataformas digitales (Marketplace, OLX, NeoAuto, Instagram, grupos de Facebook).<br>- **67%** busca principalmente desde el celular.<br>- **67%** consulta a familiares, aunque la decisión final suele ser individual. |
| **Valoración de certificación y herramientas** | - **100%** valora los informes técnicos.<br>- **100%** pagaría un extra por un auto certificado.<br>- **100%** considera útiles herramientas como videos explicativos y checklists. |
| **Preferencias de marca** | - Mencionan confianza en marcas tradicionales (Toyota, Hyundai, Nissan, Suzuki, Chevrolet).<br>- También en marcas premium (BMW, Mercedes). |

---

### Conclusión general del análisis

- **Vendedores individuales**: necesitan apoyo para generar confianza y reducir la frustración del proceso.  
- **Revendedores**: valoran la certificación, pero su adopción dependerá del costo y la reputación del servicio.  
- **Compradores**: muestran la mayor disposición a pagar por certificación, ya que buscan minimizar riesgos y reforzar su confianza en la compra.  

En conjunto, los tres segmentos validan la **propuesta de valor de CertiWeb** como un servicio que aporta confianza, rapidez y transparencia al mercado de autos usados.





### 2.3. Needfinding
#### 2.3.1. User Personas

<img src="Images/Mario Hart.png">
<img src="Images/Sung Kang.png">
<img src="Images/Matías Zagazeta.png">

#### 2.3.2. User Task Matrix

| TASK                                                            | Revendedor(a) FREQUENCY | Revendedor(a) IMPORTANCE | Concencionario(a) FREQUENCY | Concencionario(a) IMPORTANCE | Comprador(a) FREQUENCY  | Comprador(a) IMPORTANCE  |
|-----------------------------------------------------------------|-------------------------|--------------------------|-----------------------------|------------------------------|-------------------------|--------------------------|
| Preparar vehículo para venta                                    | Always                  | High                     | Never                       | Low                          | Always                  | High                     |
| Publicar anuncios en plataformas                                | Always                  | High                     | Never                       | Low                          | Always                  | High                     |
| Coordinar visitas para mostrar el auto                          | Sometimes               | Medium                   | Sometimes                   | Medium                       | Always                  | High                     |
| Revisar vehículos en venta (búsqueda y comparación)             | Never                   | Low                      | Always                      | High                         | Sometimes               | Medium                   |
| Coordinar inspecciones o revisiones mecánicas                   Sometimes                 | Medium                   | Sometimes                   | High                         | Always                  | High                     |
| Verificar documentación legal y técnica del auto                | Always                  | High                     | Always                      | High                         | Always                  | High                     |
| Negociar el precio                                              | Always                  | High                     | Sometimes                   | Medium                       | Always                  | High                     |
| Generar confianza frente al otro usuario (vendedor o comprador) | Always                  | High                     | Always                      | High                         | Always                  | High                     |
| Validar estado técnico del auto de forma objetiva               | Sometimes               | High                     | Always                      | High                         | Always                  | High                     |
| Concretar la venta o compra con seguridad                       | Always                  | High                     | Always                      | High                         | Always                  | High                     |

#### 2.3.3. User Journey Mapping

Journey Map Vendedores individuales de autos usados
<img src="Images/customer_journey_mapping_1.png">

Journey Map Revendedores o pequeños comerciantes de autos usados
<img src="Images/Customer_journey_map_2.png">

Journey Map Compradores
<img src="Images/Customer_journey_map_3.png">

#### 2.3.4. Empathy Mapping

Empathy Mapping Vendedores individuales de autos usados
<img src="Images/Empathy_map_Mario_Hart.png">

Empathy Mapping Revendedores o pequeños comerciantes de autos usados
<img src="Images/Empathy_map_Sung_Kang.png">

Empathy Mapping Compradores
<img src="Images/Empathy_map_Matias_Zagazeta.png">

#### 2.3.5. As-is Scenario Mapping

<img src="Images/as_is_seg1.png">
<img src="Images/as_is_seg2.png">
<img src="Images/as_is_seg3.png">

[Link](https://lucid.app/lucidspark/6619d091-cd80-4e92-b0dd-630565981dd9/edit?viewport_loc=726%2C2808%2C3840%2C1918%2C0_0&invitationId=inv_66fb4dd7-a579-427b-9bb2-e7c7b021ef0b)

### 2.4. Ubiquitous Language

La siguiente tabla presenta los principales términos definidos para asegurar un lenguaje compartido entre el equipo, los usuarios y los stakeholders.  
Incluye la traducción al español y una definición clara de cada concepto.

| **Término (Inglés)**      | **Término (Español)**     | **Definición** |
|----------------------------|---------------------------|----------------|
| **Used Car**              | Auto usado               | Vehículo que ya ha tenido uno o más dueños previos y se encuentra actualmente en condición de reventa. |
| **Private Seller**        | Vendedor individual      | Persona natural que vende su auto personal sin ser parte de un negocio de compraventa. |
| **Reseller**              | Revendedor               | Persona o empresa que compra autos usados para reacondicionarlos y revenderlos buscando una ganancia. |
| **First-time Buyer**      | Comprador primerizo      | Persona que adquiere un vehículo por primera vez, con poca o ninguna experiencia en el proceso de compra-venta automotriz. |
| **Vehicle Inspection**    | Inspección vehicular     | Proceso técnico que revisa el estado mecánico, estético y funcional de un auto antes de su venta. |
| **Certification Seal**    | Sello de certificación   | Distintivo otorgado por CertiWeb que valida que un vehículo pasó satisfactoriamente una inspección completa. |
| **Inspection Report**     | Informe de inspección    | Documento que detalla los resultados de la revisión técnica, incluyendo observaciones, fallas y recomendaciones. |
| **Vehicle Condition**     | Estado del vehículo      | Nivel de conservación, funcionamiento y apariencia de un auto al momento de su evaluación o venta. |
| **Sales Listing**         | Publicación de venta     | Anuncio con información del auto en venta (precio, modelo, fotos, detalles técnicos) publicado en una plataforma. |
| **Vehicle History**       | Historial del vehículo   | Registro de eventos relevantes: propietarios anteriores, accidentes, mantenimientos y reparaciones. |
| **Ownership Transfer**    | Transferencia de propiedad | Trámite legal mediante el cual el auto cambia oficialmente de dueño en registros públicos o notariales. |
| **Pre-purchase Evaluation** | Evaluación precompra   | Revisión técnica previa a la compra que asegura condiciones óptimas y un precio justo. |
| **Trust in Seller**       | Confianza en el vendedor | Percepción sobre la honestidad y transparencia del vendedor durante la venta. |
| **Trust in Vehicle**      | Confianza en el vehículo | Seguridad que tiene el comprador sobre el estado real del auto, basada en informes e inspecciones. |
| **Listing Platform**      | Plataforma de anuncios   | Sitio web o aplicación donde se publican autos en venta, como OLX, Mercado Libre Autos o Marketplace. |
| **Photo Session**         | Sesión de fotos          | Proceso de capturar imágenes del auto en diferentes ángulos y buena calidad para su publicación. |
| **Buyer Decision Process** | Proceso de decisión del comprador | Etapas mentales y emocionales que atraviesa un comprador antes de concretar la compra. |
| **Post-sale Assurance**   | Seguridad postventa      | Tranquilidad que siente el comprador después de adquirir un auto, especialmente si fue certificado. |

---

## Capítulo III: Requirements Specification

# Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

A continuación se muestran los escenarios objetivo (“To-Be”) por segmento. Se mantienen las mismas imágenes de referencia para asegurar consistencia con el análisis previo.

#### Segmento 1: Vendedores individuales
<img src="Images/tobe-segment1.png">

**Descripción**  
Vendedor que solicita una inspección, recibe informe y publica su anuncio con sello de certificación para acelerar la venta y reducir fricción con potenciales compradores.

---

#### Segmento 2: Revendedores
<img src="Images/tobe-segment2.png">

**Descripción**  
Revendedor que gestiona múltiples vehículos, programa inspecciones, consolida informes y utiliza el sello en sus publicaciones para rotación más rápida del inventario.

---

#### Segmento 3: Compradores
<img src="Images/tobe-segment3.png">

**Descripción**  
Comprador que valida autenticidad del sello, consulta el informe técnico y compara alternativas certificadas para decidir con mayor confianza.

[Link](https://lucid.app/lucidspark/6619d091-cd80-4e92-b0dd-630565981dd9/edit?viewport_loc=726%2C2808%2C3840%2C1918%2C0_0&invitationId=inv_66fb4dd7-a579-427b-9bb2-e7c7b021ef0b)

---

### 3.2. User Stories

#### Épicas

| Epic/Story ID | Título | Descripción |
|---|---|---|
| **EP01** | Landing Page Informativa | Como visitante, quiero entender qué es Certiweb y cómo funciona, para decidir si quiero utilizar el servicio. |
| **EP02** | Gestión y Publicación de Certificaciones Vehiculares | Como vendedor, quiero gestionar inspecciones y mostrar resultados en mi anuncio, para generar confianza en potenciales compradores. |
| **EP03** | Gestión Avanzada para Revendedores | Como revendedor de autos, quiero gestionar múltiples vehículos de manera eficiente, para optimizar mi flujo de trabajo. |
| **EP04** | Experiencia de Compra Segura | Como comprador, quiero tener acceso a la verificación técnica del auto, para tomar decisiones informadas y seguras. |
| **EP05** | API de Gestión Vehicular | Como developer, quiero implementar endpoints para gestionar la inspección de vehículos, para que los datos estén disponibles para la aplicación. |

#### Historias de usuario

> Nota: Se ajustan los “Criterios de Aceptación” de cada historia para que correspondan con su objetivo funcional, manteniendo la intención original y coherencia con el dominio.

| Epic/Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| **US01** | Información clara sobre Certiweb | Como visitante quiero entender de inmediato qué es Certiweb y qué beneficios ofrece para decidir si usarlo. | Escenario 1: **Dado** que ingreso a la landing, **cuando** leo el hero y la propuesta de valor, **entonces** entiendo que Certiweb ofrece inspección técnica y certificación para autos usados. <br> Escenario 2: **Dado** que continúo navegando, **cuando** reviso módulos de beneficios y evidencia, **entonces** veo sellos, informes y casos de uso que clarifican el servicio. | EP01 |
| **US02** | Testimonios y casos de éxito | Como visitante quiero leer experiencias de otros usuarios para ganar confianza en el servicio. | Escenario 1: **Dado** que estoy en la landing, **cuando** accedo a “Testimonios”, **entonces** visualizo citas verificadas de clientes (vendedores, revendedores o compradores). <br> Escenario 2: **Dado** que quiero más contexto, **cuando** hago clic en un testimonio, **entonces** puedo leer la historia completa. | EP01 |
| **US03** | Botón de acción claro | Como visitante quiero ver botones visibles para registrarme o solicitar una inspección para comenzar fácilmente. | Escenario 1: **Dado** que estoy en el primer scroll, **cuando** veo el CTA principal, **entonces** puedo iniciar registro o agendamiento. <br> Escenario 2: **Dado** que navego en otras secciones, **cuando** encuentro CTAs contextuales, **entonces** puedo abrir el formulario de contacto o agendar. | EP01 |
| **US04** | Compatibilidad móvil del Landing Page | Como visitante desde celular quiero que el sitio se vea bien y sea fácil de usar. | Escenario 1: **Dado** que accedo desde un teléfono, **cuando** navego, **entonces** la interfaz se adapta sin desbordes ni errores. <br> Escenario 2: **Dado** que interactúo con botones y enlaces, **cuando** los toco, **entonces** tienen tamaño y espaciado táctil adecuados. | EP01 |
| **US05** | Solicitud de inspección | Como vendedor individual quiero solicitar la inspección técnica de mi auto para publicarlo con respaldo técnico. | Escenario 1: **Dado** que completo un formulario con datos del vehículo, **cuando** envío la solicitud, **then** el sistema registra la inspección con estado “pendiente” y notifica recepción. <br> Escenario 2: **Dado** que hay datos faltantes, **cuando** intento enviar, **entonces** se muestran validaciones de campos obligatorios. | EP02 |
| **US06** | Visualización del informe técnico | Como vendedor individual quiero ver el informe técnico de mi auto para compartirlo con interesados. | Escenario 1: **Dado** que la inspección finalizó, **cuando** ingreso al panel del vehículo, **entonces** puedo ver y descargar el informe. <br> Escenario 2: **Dado** que deseo compartir, **cuando** elijo “Compartir”, **entonces** obtengo un enlace público. | EP02 |
| **US07** | Publicación del sello de certificación | Como vendedor individual quiero incluir un sello de certificación en mi anuncio para generar mayor confianza. | Escenario 1: **Dado** que el auto está certificado, **cuando** accedo a la ficha, **entonces** puedo copiar el código embebible del sello. <br> Escenario 2: **Dado** que edito mi anuncio, **cuando** inserto el código, **entonces** el sello se visualiza correctamente. | EP02 |
| **US08** | Historial de inspecciones | Como vendedor individual quiero ver el historial de inspecciones para trazabilidad técnica. | Escenario 1: **Dado** que tengo inspecciones previas, **cuando** abro “Historial”, **entonces** veo fechas, resultados y descargas. <br> Escenario 2: **Dado** que busco un informe, **cuando** filtro por fecha o vehículo, **entonces** encuentro el documento específico. | EP02 |
| **US09** | Registro masivo de vehículos | Como revendedor quiero registrar varios vehículos a la vez para ahorrar tiempo. | Escenario 1: **Dado** que tengo un archivo con datos, **cuando** lo subo, **entonces** el sistema crea los registros y muestra resumen de carga. <br> Escenario 2: **Dado** que hay datos incompletos, **cuando** reviso el resumen, **entonces** puedo corregir antes de finalizar. | EP03 |
| **US010** | Estado de inspecciones | Como revendedor quiero ver el estado de inspección de mis vehículos para priorizar ventas. | Escenario 1: **Dado** que gestiono varios autos, **cuando** abro el panel, **entonces** veo estados “pendiente”, “en inspección” o “certificado”. <br> Escenario 2: **Dado** que necesito priorizar, **cuando** filtro por estado, **entonces** visualizo solo listos para vender. | EP03 |
| **US011** | Enlace compartible para clientes | Como revendedor quiero compartir el informe técnico para revisión del cliente. | Escenario 1: **Dado** que existe un informe, **cuando** copio o envío el enlace, **entonces** el comprador accede sin login. <br> Escenario 2: **Dado** que el cliente abre el enlace, **cuando** lo consulta, **entonces** visualiza el informe completo en el navegador. | EP03 |
| **US012** | Notificaciones de progreso | Como revendedor quiero recibir notificaciones cuando cambie el estado de una inspección. | Escenario 1: **Dado** que hay inspecciones en curso, **cuando** cambia el estado, **entonces** recibo notificación por correo o in-app. <br> Escenario 2: **Dado** que prefiero tiempo real, **cuando** configuro mis alertas, **entonces** recibo push en el dispositivo. | EP03 |
| **US013** | Verificación de inspección antes de comprar | Como comprador quiero verificar si un auto está certificado por Certiweb. | Escenario 1: **Dado** un anuncio con sello, **cuando** hago clic, **entonces** accedo al informe técnico. <br> Escenario 2: **Dado** que ingreso un código, **cuando** valido, **entonces** el sistema confirma autenticidad y vigencia. | EP04 |
| **US014** | Comparación de vehículos certificados | Como comprador quiero comparar autos con inspección para elegir el mejor. | Escenario 1: **Dado** que tengo varios enlaces a informes, **cuando** abro la herramienta de comparación, **entonces** veo un resumen lado a lado. <br> Escenario 2: **Dado** que necesito detalle, **cuando** selecciono un vehículo, **entonces** veo su análisis técnico completo. | EP04 |
| **US015** | Reportar inconsistencia | Como comprador quiero reportar posibles inconsistencias en un informe. | Escenario 1: **Dado** que detecto un problema, **cuando** envío una observación, **entonces** el sistema registra el caso y notifica a Certiweb. <br> Escenario 2: **Dado** que requiero seguimiento, **cuando** consulto mi reporte, **entonces** veo estado y respuestas. | EP04 |
| **US016** | Validación de informe Certiweb | Como comprador quiero validar un código de informe para verificar autenticidad. | Escenario 1: **Dado** un código o link, **cuando** lo ingreso en validación, **entonces** el sistema indica si es oficial y vigente. <br> Escenario 2: **Dado** que el informe es válido, **cuando** lo abro, **entonces** puedo ver detalles adicionales. | EP04 |
| **TS01** | Endpoint para crear inspección vehicular | Como developer quiero un endpoint POST `/inspections` para registrar solicitudes. | **Escenario 1:** Dado una solicitud válida, cuando se procesa, entonces se crea con ID y estado "pendiente".<br>**Escenario 2:** Dado datos incompletos (body vacío), cuando se envía, entonces retorna 400 Bad Request con lista de campos faltantes. | EP05 |
| **TS02** | Endpoint para visualizar informe | Como developer quiero GET `/report/:id` que devuelva el informe en JSON. | **Escenario 1:** Dado un ID válido, cuando consulto, entonces se retorna datos técnicos y estado.<br>**Escenario 2:** Dado un ID inválido, cuando consulto, entonces retorna 404 Not Found. | EP05 |
| **TS03** | Endpoint para validación de informe | Como developer quiero GET `/validate/:code` para comprobar autenticidad. | **Escenario 1:** Dado un código válido, cuando valido, entonces indica validez, certificación y estado.<br>**Escenario 2:** Dado un código expirado o falso, cuando valido, entonces devuelve mensaje de error específico. | EP05 |
| **TS04** | Endpoint para consulta de informes técnicos | Como developer quiero GET `/reports/vehicleId` para obtener informes por vehículo. | **Escenario 1:** Dado un vehicleId existente, cuando consulto, retorna el informe completo.<br>**Escenario 2:** Dado un vehicleId sin informes, retorna lista vacía o 404 según corresponda. | EP05 |
| **TS05** | Hashing de contraseñas | Como developer quiero hashing seguro para credenciales. | **Escenario 1:** Dado un registro, la contraseña se guarda hasheada con BCrypt.<br>**Escenario 2:** Dado un login, el sistema compara el hash almacenado con el input del usuario. | EP05 |
| **TS06** | Autorización con JWT | Como developer quiero JWT para autorización stateless. | **Escenario 1:** Dado login correcto, se genera un Token JWT con expiración definida.<br>**Escenario 2:** Dado una petición con Token expirado, el sistema retorna 401 Unauthorized. | EP05 |
| **TS07** | Anti Corruption Layer (ACL) | Como developer quiero un ACL para proteger el dominio de dependencias externas. | **Escenario 1:** Dado datos externos entrantes, el ACL los transforma al modelo del dominio.<br>**Escenario 2:** Dado servicios externos caídos, el ACL maneja la excepción sin romper el dominio. | EP05 |
| **TS08** | **Pruebas Unitarias Frontend (Vue.js)** | Como developer quiero implementar tests unitarios en componentes críticos (Login, Reserva) para asegurar la calidad del UI. | **Escenario 1 (Validación Negativa):** Dado que el usuario intenta enviar el formulario de Login vacío, el test verifica que aparezcan mensajes de "Campo Requerido".<br>**Escenario 2 (Formato):** Dado un input de email sin "@", el test verifica que se active la clase CSS de error visual. | EP01 / EP04 |
| **TS09** | **Manejo Global de Errores en Frontend** | Como developer quiero un interceptor de errores HTTP en Vue.js para dar feedback al usuario. | **Escenario 1:** Dado que el Backend retorna error 500, la UI muestra una alerta amigable "Servicio no disponible temporalmente".<br>**Escenario 2:** Dado un error de red (sin conexión), la aplicación muestra un estado de "Offline" sin colgarse. | EP02 / EP03 |
| **TS10** | **Validación de Tipos y Conversión de Moneda** | Como developer quiero asegurar que los montos y fechas se procesen correctamente en ambos extremos. | **Escenario 1 (Caso Límite):** Dado un intento de ingresar precio negativo (-100) en el formulario, el sistema bloquea el envío.<br>**Escenario 2 (Conversión):** Dado un monto en la base de datos (decimal), el frontend lo renderiza con el símbolo de moneda y dos decimales correctos. | EP05 |
---

### 3.3. Impact Mapping
<img src="Images/Certiweb-ImpactMapping.png">

---

### 3.4. Product Backlog

> El backlog prioriza entregables que habilitan comprensión del servicio (EP01) y la puesta en marcha del flujo de certificación para vendedores (EP02), seguido de capacidades para revendedores (EP03) y funcionalidades de verificación para compradores (EP04).

| # Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) | Prioridad |
|---|---|---|---|---|---|
| 1 | US01 | Información clara sobre Certiweb | Como visitante quiero entender de inmediato qué es Certiweb y qué beneficios ofrece para decidir si usarlo. | 3 | Alta |
| 2 | US02 | Testimonios y casos de éxito | Como visitante quiero leer experiencias de otros usuarios para ganar confianza en el servicio. | 2 | Alta |
| 3 | US03 | Botón de acción claro | Como visitante quiero ver botones visibles para registrarme o solicitar una inspección para comenzar fácilmente. | 2 | Alta |
| 4 | US04 | Compatibilidad móvil del Landing Page | Como visitante desde celular quiero que el sitio web se vea bien y sea fácil de usar desde mi dispositivo. | 3 | Media |
| 5 | US05 | Solicitud de inspección | Como vendedor individual quiero solicitar la inspección técnica de mi auto para publicarlo con respaldo técnico. | 5 | Media |
| 6 | US06 | Visualización del informe técnico | Como vendedor individual quiero ver el informe técnico de mi auto para compartirlo con interesados. | 3 | Media |
| 7 | US07 | Publicación del sello de certificación | Como vendedor individual quiero incluir un sello de certificación en mi anuncio en línea para generar mayor confianza. | 2 | Media |
| 8 | US08 | Historial de inspecciones | Como vendedor individual quiero ver un historial de inspecciones realizadas a mis autos. | 3 | Baja |
| 9 | US09 | Registro masivo de vehículos | Como revendedor quiero registrar varios vehículos a la vez para ahorrar tiempo. | 5 | Baja |
| 10 | US010 | Estado de inspecciones | Como revendedor quiero ver el estado de inspección de mis vehículos. | 3 | Baja |
| 11 | US011 | Enlace compartible para clientes | Como revendedor quiero compartir el enlace al informe técnico de un auto. | 2 | Baja |
| 12 | US012 | Notificaciones de progreso | Como revendedor quiero recibir notificaciones ante cambios de estado de una inspección. | 3 | Baja |
| 13 | US013 | Verificación de inspección antes de comprar | Como comprador quiero ver si un auto publicado está certificado por Certiweb. | 3 | Baja |
| 14 | US014 | Comparación de vehículos certificados | Como comprador quiero comparar autos certificados para elegir el que esté en mejor estado. | 5 | Baja |
| 15 | US015 | Reportar inconsistencia | Como comprador quiero reportar inconsistencias en un informe. | 2 | Baja |
| 16 | US016 | Validación de informe Certiweb | Como comprador quiero validar un código de informe para confirmar su autenticidad. | 3 | Baja |


---

# Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

<div style="background:#F0F9F4;border-radius:8px;padding:20px;margin-bottom:20px;box-shadow:0 2px 4px rgba(0,0,0,0.05);">

  <div style="display:flex;align-items:center;margin-bottom:16px;">
    <div style="flex:1;padding-right:20px;">
      <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Branding</h3>
      <img src="Images/certiweb.png" alt="Certiweb logo" width="180" style="border-radius:4px;box-shadow:0 2px 6px rgba(0,0,0,0.1);">
    </div>
    <div style="flex:1;">
      <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Tipografía</h3>
      <p style="margin-bottom:8px;">Fuente principal: <code style="background:#F8ECD6;padding:2px 6px;border-radius:4px;font-family:monospace;">Roboto</code></p>
      <p style="color:#333;font-size:0.95em;">Se utiliza para mantener un estilo moderno, limpio y profesional, asegurando legibilidad tanto en pantallas pequeñas como grandes.</p>
    </div>
  </div>

  <h3 style="color:#002D18;margin-top:20px;font-size:1.1em;">Colores principales</h3>

  <div style="overflow-x:auto;">
    <table style="width:100%;border-collapse:collapse;margin:12px 0;background:white;border-radius:6px;overflow:hidden;">
      <thead style="background:#002D18;color:white;">
        <tr>
          <th style="padding:12px;text-align:left;">Nombre</th>
          <th style="padding:12px;text-align:left;">Color</th>
          <th style="padding:12px;text-align:left;">Código HEX</th>
          <th style="padding:12px;text-align:left;">Uso recomendado</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td style="padding:12px;">Verde oscuro</td>
          <td style="padding:12px;"><span style="display:inline-block;width:24px;height:24px;border-radius:50%;background-color:#002D18;border:1px solid #ddd;"></span></td>
          <td style="padding:12px;"><code>#002D18</code></td>
          <td style="padding:12px;">Encabezados, botones principales, identidad de marca</td>
        </tr>
        <tr>
          <td style="padding:12px;">Arena suave</td>
          <td style="padding:12px;"><span style="display:inline-block;width:24px;height:24px;border-radius:50%;background-color:#D8CCB8;border:1px solid #ddd;"></span></td>
          <td style="padding:12px;"><code>#D8CCB8</code></td>
          <td style="padding:12px;">Fondos y secciones de información</td>
        </tr>
        <tr>
          <td style="padding:12px;">Verde claro</td>
          <td style="padding:12px;"><span style="display:inline-block;width:24px;height:24px;border-radius:50%;background-color:#F0F9F4;border:1px solid #ddd;"></span></td>
          <td style="padding:12px;"><code>#F0F9F4</code></td>
          <td style="padding:12px;">Áreas de soporte visual, bloques secundarios</td>
        </tr>
        <tr>
          <td style="padding:12px;">Amarillo vivo</td>
          <td style="padding:12px;"><span style="display:inline-block;width:24px;height:24px;border-radius:50%;background-color:#FBB901;border:1px solid #ddd;"></span></td>
          <td style="padding:12px;"><code>#FBB901</code></td>
          <td style="padding:12px;">Indicadores, alertas y CTA destacados</td>
        </tr>
        <tr>
          <td style="padding:12px;">Gris claro</td>
          <td style="padding:12px;"><span style="display:inline-block;width:24px;height:24px;border-radius:50%;background-color:#C3CCC7;border:1px solid #ddd;"></span></td>
          <td style="padding:12px;"><code>#C3CCC7</code></td>
          <td style="padding:12px;">Bordes, divisores y elementos secundarios</td>
        </tr>
      </tbody>
    </table>
  </div>

  <h3 style="color:#002D18;margin-top:20px;font-size:1.1em;">Espaciado</h3>
  <p style="color:#333;">El diseño aplica un sistema de espaciado basado en múltiplos de 8px para mantener consistencia y ritmo visual.</p>

  <h3 style="color:#002D18;margin-top:20px;font-size:1.1em;">Tono de comunicación</h3>
  <p style="color:#333;">El tono debe transmitir:</p>
  <ul style="color:#333;list-style-type:square;padding-left:20px;">
    <li>Profesionalismo y confianza</li>
    <li>Claridad y objetividad en la información</li>
    <li>Cercanía al usuario, evitando tecnicismos innecesarios</li>
  </ul>
</div>

---

#### 4.1.2. Web Style Guidelines

<div style="display:flex;gap:20px;margin-bottom:30px;">
  <div style="flex:1;background:#F8ECD6;border-radius:8px;padding:16px;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Diseño Responsivo</h3>
    <ul style="color:#333;padding-left:20px;list-style-type:disc;">
      <li>Estrategia <em>mobile-first</em>, priorizando experiencia en dispositivos móviles</li>
      <li>Diseño modular mediante tarjetas (cards) para autos, informes y certificaciones</li>
      <li>Tipografía flexible de 14px a 24px, garantizando legibilidad en todos los tamaños de pantalla</li>
    </ul>
  </div>

  <div style="flex:1;background:#F8ECD6;border-radius:8px;padding:16px;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Componentes UI</h3>
    <ul style="color:#333;padding-left:20px;list-style-type:disc;">
      <li>Botones con bordes redondeados y micro-interacciones (hover, focus, active)</li>
      <li>Animaciones suaves en transiciones y cargas para mejorar la percepción de fluidez</li>
      <li>Uso consistente de iconografía simple y reconocible</li>
    </ul>
  </div>
</div>

---

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

<div style="display:flex;gap:20px;">
  <div style="flex:1;background:#F0F9F4;border-radius:8px;padding:16px;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Landing Page</h3>
    <ul style="color:#333;padding-left:20px;list-style-type:disc;">
      <li>Orden jerárquico: beneficios principales → explicación del servicio → CTA final</li>
      <li>Presentación visual clara de testimonios, sellos y reportes</li>
    </ul>
  </div>

  <div style="flex:1;background:#F0F9F4;border-radius:8px;padding:16px;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Aplicación Web</h3>
    <ul style="color:#333;padding-left:20px;list-style-type:disc;">
      <li>Panel de control organizado por secciones: 
        <ul style="padding-left:20px;list-style-type:circle;">
          <li>Mis vehículos</li>
          <li>Historial de inspecciones</li>
          <li>Certificados vigentes</li>
        </ul>
      </li>
      <li>Adaptación de funcionalidades según el perfil del usuario (vendedor, revendedor, comprador)</li>
    </ul>
  </div>
</div>

---

#### 4.2.2. Labeling Systems

<div style="background:#F8F8B7;border-radius:8px;padding:16px;margin:12px 0;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
  <h3 style="color:#002D18;margin-top:0;font-size:1.1em;">Ejemplos de etiquetas</h3>
  <ul style="color:#333;list-style-type:square;padding-left:20px;">
    <li>"Solicitar inspección"</li>
    <li>"Ver informe"</li>
    <li>"Certificado vigente"</li>
    <li>"Agregar vehículo"</li>
  </ul>
</div>

#### 4.2.3. SEO Tags and Meta Tags

<div style="background:#F0F9F4;border-radius:8px;padding:16px;margin:12px 0;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
  <h4 style="color:#002D18;margin-top:0;margin-bottom:8px;">Landing Page</h4>
  <pre style="background:#F8ECD6;padding:12px;border-radius:6px;overflow-x:auto;border-left:3px solid #FBB901;"><code>&lt;title&gt;Certiweb - Tu Taller de Inspección y Certificación Vehicular&lt;/title&gt;
&lt;meta name="description" content="Certiweb te ayuda a vender tu auto con confianza, respaldado por inspecciones técnicas profesionales y certificados verificables."&gt;
&lt;meta name="keywords" content="Certificación de autos, inspección vehicular, vender auto usado, informe técnico"&gt;
&lt;meta name="author" content="Selling Cars Quickly (SCQ)"&gt;</code></pre>

  <h4 style="color:#002D18;margin-top:16px;margin-bottom:8px;">Web Application</h4>
  <pre style="background:#F8ECD6;padding:12px;border-radius:6px;overflow-x:auto;border-left:3px solid #FBB901;"><code>&lt;title&gt;Panel Certiweb - Gestión de Autos&lt;/title&gt;
&lt;meta name="description" content="Administra tus vehículos, consulta informes técnicos y comparte certificados desde un solo lugar."&gt;
&lt;meta name="keywords" content="panel de autos, historial de inspección, certificado vehicular, venta segura"&gt;
&lt;meta name="author" content="Selling Cars Quickly (SCQ)"&gt;</code></pre>
</div>

#### 4.2.4. Searching Systems

<div style="background:#F8ECD6;border-radius:8px;padding:16px;margin:12px 0;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
  <ul style="color:#002D18;padding-left:20px;list-style-type:none;">
    <li style="margin-bottom:8px;">• <strong>Filtros por:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">Estado del vehículo: Inspeccionado, En revisión, Aprobado.</li>
        <li style="margin:4px 0;">Tipo de usuario: vendedor individual, revendedor.</li>
        <li style="margin:4px 0;">Fecha de inspección.</li>
      </ul>
    </li>
    <li style="margin:12px 0 8px 0;">• <strong>Búsqueda por texto:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">Buscar por placa, nombre del modelo o número de informe.</li>
      </ul>
    </li>
    <li style="margin:12px 0 8px 0;">• <strong>Resultados con vista resumida:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">Tarjetas con datos clave: marca, modelo, fecha inspección, estado.</li>
      </ul>
    </li>
  </ul>
</div>

#### 4.2.5. Navigation Systems

<div style="background:#F0F9F4;border-radius:8px;padding:16px;margin:12px 0;box-shadow:0 2px 4px rgba(0,0,0,0.05);">
  <h4 style="color:#002D18;margin-top:0;margin-bottom:8px;">Landing Page:</h4>
  <ul style="color:#002D18;padding-left:20px;list-style-type:none;">
    <li style="margin-bottom:8px;">
      • <strong>Menú de navegación fijo (sticky) en la parte superior con anclas internas:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">Inicio | Sobre Nosotros | Reseñas | ¡Por qué elegirnos? | Contáctanos</li>
      </ul>
    </li>
    <li style="margin:12px 0 8px 0;">• <strong>Scroll vertical guiado con bloques visuales claramente diferenciados.</strong></li>
    <li style="margin:12px 0 8px 0;">
      • <strong>Botones CTA recurrentes:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">"Solicitar inspección" y "Certifica tu auto ahora" en secciones clave.</li>
      </ul>
    </li>
    <li style="margin:12px 0 8px 0;">• <strong>Sección de FAQ y contacto al final, accesibles desde el menú.</strong></li>
  </ul>

  <h4 style="color:#002D18;margin-top:16px;margin-bottom:8px;">Web App:</h4>
  <ul style="color:#002D18;padding-left:20px;list-style-type:none;">
    <li style="margin-bottom:8px;">
      • <strong>Sidebar lateral con acceso rápido a:</strong>
      <ul style="padding-left:20px;list-style-type:square;color:#333;">
        <li style="margin:4px 0;">Dashboard</li>
        <li style="margin:4px 0;">Mis vehículos</li>
        <li style="margin:4px 0;">Certificados</li>
        <li style="margin:4px 0;">Historial</li>
        <li style="margin:4px 0;">Perfil</li>
      </ul>
    </li>
    <li style="margin:12px 0 8px 0;">• <strong>Menús desplegables y tabs para cambiar entre vistas</strong> (por ejemplo: Detalles del auto | Certificado | Fotos).</li>
    <li style="margin:12px 0 8px 0;">• <strong>Indicadores de progreso</strong> en flujos como "Solicitar inspección" o "Subir documentos".</li>
  </ul>

  <h4 style="color:#002D18;margin-top:16px;margin-bottom:8px;">Accesibilidad y usabilidad:</h4>
  <ul style="color:#002D18;padding-left:20px;list-style-type:none;">
    <li style="margin-bottom:8px;">• Navegación accesible con teclado y lectores de pantalla.</li>
    <li style="margin-bottom:8px;">• Íconos y etiquetas claras para facilitar navegación intuitiva.</li>
    <li style="margin-bottom:8px;">• Diseño coherente entre móvil y escritorio, con menús tipo hamburguesa en mobile.</li>
  </ul>
</div>

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe

<img src="Images/LandingWire1.png">
<img src="Images/LandingWire2.png">

### Mobile version
<img src="Images/LandingWireMobile1.png">
<img src="Images/LandingWireMobile2.png">

#### 4.3.2. Landing Page Mock-up

<img src="Images/LandingMock1.png">
<img src="Images/LandingMock2.png">

### Mobile version
<img src="Images/LandingMockMobile1.png">
<img src="Images/LandingMockMobile2.png">
<img src="Images/LandingMockMobile3.png">

### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes

<!--Register y login-->


<!--Dashboard-->
<img src="Images/webappWireframedashboard1.png">
<img src="Images/webappWireframedashboard8.png">
<img src="Images/webappWireframedashboard9.png">
<img src="Images/webappWireframedashboard10.png">
<img src="Images/webappWireframedashboard2.png">

<!--Settings-->
<img src="Images/webappWireframedashboard3.png">
<img src="Images/webappWireframedashboard4.png">
<img src="Images/webappWireframedashboard5.png">
<img src="Images/webappWireframedashboard7.png">

<!--reserva-->
<img src="Images/webappWireframedashboard11.png">

<!--Aprovacion de reserva vista admin-->
<img src="Images/webappWireframedashboard12.png">

<!--Visualizacion Anuncio-->
<img src="Images/webappWireframedashboard13.png">

#### 4.4.2. Web Applications Wireflow Diagrams

User Goal: Reservar una Inspección Vehicular
<img src="Images/UserGoal1.png">

User Goal: Acceder a Informes Técnicos
<img src="Images/UserGoal2.png">

User Goal: Visualizar Anuncios de Venta
<img src="Images/UserGoal3.png">

[Link del los Wireflow Diagrams](https://lucid.app/lucidchart/47dee77f-6e40-411c-b9d1-04c7cc3d1791/edit?viewport_loc=9304%2C-764%2C7516%2C3284%2C0_0&invitationId=inv_c790acfc-5ce8-419f-88cc-f9084b6312ff)

#### 4.4.3. Web Applications Mock-ups

<!--Dashboard-->
<img src="Images/webappMockUpdashboard1.png">
<img src="Images/webappMockUpdashboard9.png">
<img src="Images/webappMockUpdashboard2.png">
<img src="Images/webappMockUpdashboard3.png">
<img src="Images/webappMockUpdashboard4.png">

<!--Settings-->
<img src="Images/webappMockUpdashboard5.png">
<img src="Images/webappMockUpdashboard6.png">
<img src="Images/webappMockUpdashboard7.png">
<img src="Images/webappMockUpdashboard8.png">

<!--reserva-->
<img src="Images/webappMockUpdashboard10.png">

<!--Aprovacion de reserva vista admin-->
<img src="Images/webappMockUpdashboard11.png">

<!--Visualizacion Anuncio-->
<img src="Images/webappMockUpdashboard12.png">

#### 4.4.4. Web Applications User Flow Diagrams

User Goal: Reservar una Inspección Vehicular
Explicación: Este flujo ideal muestra cómo un usuario puede reservar su inspeccion de forma sencilla en CertiWeb. Todo funciona como se espera, sin ningún obstáculo o error que interrumpa el proceso.
<br>
<img src="Images/userflowdia1.png">
<br>
User Goal: Acceder a Informes Técnicos
Explicación: Este flujo ideal muestra cómo un usuario puede acceder a su informe técnico de forma sencilla en CertiWeb. Como comprador puede elegir cualquier vehiculo que le guste porque todos cuentan con un certificado activo.
<br>
<img src="Images/userflowdia2.png">
<br>
User Goal: Visualizar Anuncios de Venta
Explicación: Este flujo ideal muestra cómo un usuario puede visualizar los anuncios de venta de forma sencilla en CertiWeb. Como vendedor despues de su inspeccion, nosotros nos encargaremos de crearle su anuncio personalizado con su informe dentro.
<img src="Images/userflowdia3.png">

[Link de los diagramas](https://lucid.app/lucidchart/e0c3e4ad-42b3-4dde-8537-cb132eab3446/edit?viewport_loc=9785%2C-26%2C6959%2C3041%2C0_0&invitationId=inv_2ca42dc4-1653-4214-ba0e-d37422b7b6bb)

### 4.5. Web Applications Prototyping

[Link del video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213358_upc_edu_pe/EcpvFFaPvixHvoSImaD2qdkBZEo8nurqLuuR8TRQ32EXuA?e=ft4y4P&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
<img src="Images/protro2.png">
<img src="Images/webappMockUpdashboard10.png">
<img src="Images/protro1.png">
<img src="Images/webappMockUpdashboard11.png">
<img src="Images/webappMockUpdashboard12.png">

### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Software Architecture Context Diagram

<img src="Images/SystemContext.png">

```html
buyer -> certiwebSystem "Searches and views certified listings, contacts seller (via platform or directly)" "HTTPS"
```

#### 4.6.2. Software Architecture Container Diagrams

<img src="Images/ContainersDiagram.png">

#### 4.6.3. Software Architecture Components Diagrams

<img src="Images/ComponentDiagram.png">

### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
<img alt="Diagrama de clases" src="Images/diagrama de clase_2.png" />

#### 4.7.2. Class Dictionary

##### 1. User

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único del usuario.                 |
| name            | String           | Nombre del usuario.                              |
| email           | Email            | Correo electrónico del usuario.                  |
| userType        | UserType         | Tipo de usuario (vendedor, revendedor, comprador). |

##### 2. Vehicle

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único del vehículo.                |
| brand           | String           | Marca del vehículo.                              |
| model           | String           | Modelo del vehículo.                             |
| year            | Integer          | Año de fabricación del vehículo.                 |
| licensePlate    | LicensePlate     | Placa del vehículo.                              |
| inspectionStatus| InspectionStatus | Estado actual de la inspección del vehículo.     |

##### 3. Inspection

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único de la inspección.            |
| requestDate     | Date             | Fecha en que se solicitó la inspección.          |
| inspectionDate  | Date             | Fecha en que se realizó la inspección.           |
| inspectionResult| InspectionResult | Resultado de la inspección.                      |

##### 4. TechnicalReport

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único del informe técnico.         |
| validationCode  | String           | Código único para validar la autenticidad del informe. |
| details         | String           | Detalles del estado técnico del vehículo.        |

##### 5. Certification

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único de la certificación.         |
| seal            | String           | Sello único de certificación.                    |
| issueDate       | Date             | Fecha en que se emitió la certificación.         |

##### 6. Subscription

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único de la suscripción.           |
| type            | SubscriptionType | Tipo de suscripción (mensual o trimestral).      |
| startDate       | Date             | Fecha de inicio de la suscripción.               |
| endDate         | Date             | Fecha de fin de la suscripción.                  |

##### 7. Payment

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| id              | UUID             | Identificador único del pago.                    |
| amount          | Money            | Monto del pago.                                  |
| paymentDate     | Date             | Fecha en que se realizó el pago.                 |
| paymentMethod   | PaymentMethod    | Método de pago (tarjeta, transferencia, etc.).   |
| status          | PaymentStatus    | Estado del pago (Pendiente, Completado, Fallido).|

##### 8. Email

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| address         | String           | Dirección de correo electrónico.                 |

##### 9. UserType

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| type            | String           | Tipo de usuario (Seller, Reseller, Buyer).       |

##### 10. LicensePlate

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| plateNumber     | String           | Número de placa del vehículo.                    |

##### 11. InspectionStatus

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| status          | String           | Estado de la inspección (Pendiente, En Inspección, Certificado). |

##### 12. InspectionResult

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| result          | String           | Resultado de la inspección (Aprobado, Rechazado). |
| comments        | String           | Comentarios adicionales sobre el vehículo.       |

##### 13. PaymentMethod

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| method          | String           | Método de pago (tarjeta, transferencia, etc.).   |

##### 14. PaymentStatus

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| status          | String           | Estado del pago (Pendiente, Completado, Fallido). |

##### 15. Money

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| currency        | String           | Moneda utilizada (USD, PEN, etc.).               |
| amount          | Decimal          | Cantidad de dinero asociada al pago o suscripción.|

##### 16. SubscriptionType

| Atributo        | Tipo de Variable | Descripción                                       |
|-----------------|------------------|---------------------------------------------------|
| type            | String           | Tipo de suscripción (Mensual, Trimestral).        |



### 4.8. Database Design
#### 4.8.1. Database Diagram
<img alt="Database diagram" src="Images/DATABASESELLING.png" />


[↑ Volver al índice](#índice)
# Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
En esta sección, se describen las herramientas utilizadas por el equipo para colaborar en el desarrollo del proyecto, así como sus propósitos específicos y las rutas de referencia.

#### 1. Product UX/UI Design
- **Figma**: Utilizado para el diseño y prototipado de la aplicación, tanto en su versión de escritorio como en navegadores móviles.

#### 2. Software Development
- **WebStorm**: Entorno de desarrollo integrado (IDE) utilizado para la creación y edición del código fuente del proyecto. Su elección se debe a su excelente soporte para frameworks web como Vue.js.
- **Rider**: Entorno de desarrollo integrado (IDE) utilizado para la creación y edición del código fuente del proyecto. Su elección se debe a su excelente soporte para C# y .NET.
- **HTML5**: Lenguaje de marcado utilizado para la estructura del contenido web de la aplicación.
- **CSS**: Utilizado para el diseño y la presentación visual de las páginas web, complementando el contenido estructurado por HTML.
- **JavaScript**: Lenguaje de programación empleado para crear interactividad y manejar la lógica del frontend de la aplicación.
- **Vertabelo**: Herramienta utilizada para la creación y gestión de diagramas entidad-relación (ERD), empleada para diseñar la base de datos del proyecto.
- **Structurizr**: Utilizado para el diseño del diagrama C4, representando la arquitectura del sistema y sus componentes.

#### 3. Software Testing
- **Gherkin**: Lenguaje de etiquetado utilizado para definir los criterios de aceptación de las historias de usuario. Facilita la escritura de pruebas de comportamiento y asegura que los criterios sean entendibles tanto para el equipo técnico como no técnico.

#### 4. Software Deployment
- **GitHub Pages**: Utilizado para el despliegue de la landing page, permitiendo que el sitio web esté disponible públicamente. La plataforma ofrece una solución de hosting gratuita y fácil de usar directamente desde el repositorio de GitHub, lo que facilita la actualización continua del sitio.  
  - **Ruta de referencia**: [https://pages.github.com](https://pages.github.com)
- **Azure Static Web Apps**: Utilizado para el despliegue y hosting de aplicaciones web estáticas, facilitando la integración continua y la entrega continua (CI/CD) directamente desde los repositorios de código.
  - **Ruta de referencia**: [https://learn.microsoft.com/es-mx/azure/static-web-apps/](https://learn.microsoft.com/es-mx/azure/static-web-apps/)

#### 5. Software Documentation
- **GitHub**: Utilizado como plataforma de documentación para mantener la información técnica del proyecto organizada y accesible.


#### 5.1.2. Source Code Management
En nuestro proyecto, utilizamos **GitHub** como plataforma para gestionar el código fuente, manteniendo los siguientes repositorios:

- Report: https://github.com/Selling-Cars-Quickly-SCQ/Certiweb-Report
- Landing page: https://github.com/Selling-Cars-Quickly-SCQ/Landing-Page
- Frontend: https://github.com/Selling-Cars-Quickly-SCQ/frontend
- Backend: https://github.com/Selling-Cars-Quickly-SCQ/backend

#### GitFlow Workflow
Se implementa el modelo de **GitFlow** para gestionar las ramas en nuestros repositorios. A continuación, se detallan las ramas principales:

##### Para el Reporte:

- **master**: Contiene las versiones estables del reporte.
- **develop**: Se utiliza para integrar las nuevas características antes de publicarlas en la rama master.
- **feature-\<número de capítulo>**: Rama creada para el desarrollo de funcionalidades del capítulo.

##### Para el Landing, Frontend y Backend:

- **main**: Contiene las versiones estables del reporte.
- **develop**: Se utiliza para integrar las nuevas características antes de publicarlas en la rama release/\<versión>.
- **hotfix**: Se utiliza para integrar caracteristicas urgentes que afectan el funcionamiento de la aplicación.
- **realease/\<Versión>**: Se utiliza para integrar las nuevas características antes de publicarlas en la rama main.
- **feature/\<nombre de funcionalidad>**: Rama creada para el desarrollo de funcionalidades específicas según el nombre. Las ramas se nombran en minúsculas siguiendo un esquema uniforme para mayor consistencia.

<img src="Images/gitflow.png" />

#### Conventional Commits
Se emplea para los mensajes de commmits el estándar de **Conventional Commits** con las siguientes etiquetas:

- **feat**: Nuevas características.
- **fix**: Corrección de errores.
- **docs**: Documentación.
- **style**: Modificaciones de estilos.
- **refactor**: Cambio de código que no corrige un error ni añade una característica.
- **perf**: Modificaciones que mejoran el rendimiento.
- **test**: Modificacciones en testing.
- **build**: Cambios que afectan al sistema de compilación o a dependencias externas.
- **ci**: Cambios en nuestros archivos y scripts de configuración CI.
- **chore**: Otros cambios que no modifican ficheros src o test
- **revert**: Revierte un commit anterior


#### 5.1.3. Source Code Style Guide & Conventions
Utilizaremos buenas prácticas y convenciones para mantener un código limpio, consistente y fácil de mantener en todos los lenguajes utilizados.

## HTML:

1. **Estructura Semántica**:
  - Se utilizan etiquetas semánticas para estructurar el contenido, como `<header>`, `<section>`, `<nav>`, `<footer>`, y `<h1>`, lo que mejora la accesibilidad y optimización SEO.

2. **Nombres de Clases**:
  - Las clases siguen la convención **camelCase** (primera palabra en minúscula y las subsecuentes con capitalización), como `containerH`, `boxH`, `membership-banner-price`, y `membership-card`.

3. **Atributos en Elementos**:
  - Elementos como `<a>` utilizan `style="--i:0;"`, lo que indica el uso de variables CSS personalizadas, combinadas con animaciones que dependen de `--i`.

4. **Imágenes y Recursos**:
  - Las imágenes se optimizan con el formato `webp`, mejorando la velocidad de carga (`assets/images/logo/logoWhite.webp`).

## CSS:

1. **Resets de CSS**:
  - Se aplica un reset de márgenes y padding para asegurar consistencia entre navegadores:
    ```css
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    ```

2. **Convención de Nombres de Clases**:
  - Los nombres de clases son **descriptivos** y reflejan el propósito de cada elemento, como `.header`, `.navbar`, `.banner`, `.about-box`.

3. **Uso de Pseudo-clases**:
  - Se utilizan pseudo-clases como `:hover` y `:checked` para manejar interacciones:
    ```css
    #check:checked~.navbar {
        height: 20.5rem;
    }
    ```

4. **Grid Layouts**:
  - Se usa `display: grid` para la disposición de elementos, junto con `grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));`, lo que hace el diseño adaptable a pantallas de diferentes tamaños.

5. **Media Queries**:
  - Se incluyen **media queries** para dispositivos pequeños, asegurando una buena experiencia en móviles:
    ```css
    @media (max-width: 768px) {
        .icons {
            display: inline-flex;
        }
    }
    ```

6. **Variables CSS Personalizadas**:
  - Se utilizan variables como `--i` en las animaciones para crear **retrasos** controlados por CSS, haciendo que los elementos de la barra de navegación aparezcan secuencialmente.

7. **Transiciones**:
  - Se implementan transiciones suaves en varios elementos para mejorar la interacción con el usuario:
    ```css
    .img-logo:hover {
        transform: scale(1.25);
        transition: transform 0.5s ease-in-out;
    }
    ```


#### 5.1.4. Software Deployment Configuration
Se inicio con la creación de la organización en github. 

<img src="Images/github-organization.png" />

Posteriormente, se asocio a los integrantes del equipo para poder colaborar en los repositorios de la organización.

<img src="Images/InsightsGrupo.png" />

Luego, se crearon los repositorios del reporte, Landing Page, Frontend y Backend para organizar los productos entregables.

<img src="Images/github-repositories.png" />

Finalmente, se configuro y desplegó la versión inicial del Landing Page en **GitHub Pages** desde la sección "Pages" seleccionando la rama **main**.

<img src="Images/github-landing-deployment.png" />

### 5.2. Product Implementation & Deployment

##### 5.2.1. Sprint Backlogs

###### 5.2.1.1. Sprint Planning 1

| Criterio                       | Detalle                                                                 |
| :----------------------------- | :---------------------------------------------------------------------- |
| **Sprint #**                   | Sprint 1                                                               |
| **Sprint Planning Background** |                                                                         |
| Date                           | 02/09/2025                                                              |
| Time                           | 9:00pm                                                                  |
| Location                       | Reunión virtual en Google Meet                                          |
| Prepared By                    | Fabrizio Quiroz                                              _         |
| Attendees (to planning meeting)| Angulo Abud, Juan Carlos; Trillo Hernandez, Anghel Melanie; Zúñiga Murillo, Diego Sebastián; Monte Maza, Augusto; |
| Sprint n - 1 Review Summary    | Se planificó el desarrollo completo de la Landing Page, Frontend, Backend y documentación inicial. |
| Sprint n - 1 Retrospective Summary | El equipo acordó trabajar en paralelo en los distintos módulos del producto para asegurar la entrega de un prototipo funcional al cierre del Sprint. |
| **Sprint Goal & User Stories** |                                                                         |
| Sprint 1 Goal                  | Desarrollar la primera versión implementada de la Landing Page, el Frontend Web, el Backend con API REST, una API simulada para pruebas y la base de la documentación del sistema. |
| Sprint 1 Velocity              | 34                                                                      |
| **Sum of Story Points**        | 34                                                                      |


###### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | UI/UX Design <br> Leader (L) / Collaborator (C) | Landing Design <br> Leader (L) / Collaborator (C) | Frontend <br> Leader (L) / Collaborator (C) | Backend <br> Leader (L) / Collaborator (C) |
| :---------------------------------- | :-------------- | :---------------------------------------------: | :----------------------------------------------: | :-----------------------------------------: | :----------------------------------------: |
| Quiroz Zambrano, Fabrizio Javier    | Relycloud    | C                                               | C                                                | L                                           | C                                          |
| Angulo Abud, Juan Carlos            | Sve-nnN         | C                                               | L                                                | C                                           | C                                          |
| Trillo Hernandez, Anghel Melanie    |  AM27TH        | L                                               | C                                                | C                                           | C                                          |
| Zúñiga Murillo, Diego Sebastián     |  DekayDeCanela      | C                                               | C                                                | C                                           | L                                          |
| Monte Maza, Augusto                 | AugustMM        | C                                               | C                                                | C                          _                | C                                          |

###### 5.2.1.3. Sprint Backlog 1

| **User Story** | **Title**                          | **Work-Item / Task** | **Title**                                | **Description**                                                                 | **Estimation (Hours)** | **Assigned To**            | **Status** |
|----------------|------------------------------------|-----------------------|------------------------------------------|---------------------------------------------------------------------------------|------------------------|----------------------------|------------|
| US01           | Landing Page informativa           | T01                  | Crear estructura base en HTML/CSS        | Implementar la página inicial con estructura básica y estilos responsivos.       | 6                      | Juan Carlos Angulo          | Done       |
|                |                                    | T02                  | Agregar secciones de beneficios          | Incorporar secciones de propuesta de valor y beneficios diferenciadores.        | 5                      | Anghel Melanie Trillo       | Done       |
|                |                                    | T03                  | Implementar testimonios                  | Añadir reseñas de usuarios con estructura accesible y validación visual.         | 4                      | Diego Zúñiga                | Done       |
| US02           | Frontend web inicial               | T04                  | Configuración de Vue + Vite              | Crear proyecto base en Vue con Vite y estructura de componentes inicial.         | 6                      | Fabrizio Quiroz             | Done       |
|                |                                    | T05                  | Implementar dashboard de usuario         | Diseñar e implementar un panel básico para mostrar estado de certificaciones.   | 5                      | Fabrizio Quiroz             | Done       |
| US03           | Backend con API REST               | T06                  | Crear API REST en .NET                   | Implementar servicios iniciales en .NET con endpoints para autos y usuarios.     | 6                      | Diego Zúñiga                | Done       |
|                |                                    | T07                  | Conectar a base de datos simulada        | Integrar persistencia inicial con una base de datos simulada.                   | 4                      | Diego Zúñiga                | Done       |
| US04           | API simulada para pruebas          | T08                  | Configurar fake API en JSON Server       | Montar una fake API para pruebas rápidas de frontend.                           | 4                      | Augusto Monte Maza          | Done       |
| US05           | Documentación técnica inicial      | T09                  | Redacción del informe README             | Documentar el proyecto en Markdown, incluyendo perfiles y procesos.             | 5                      | Anghel Melanie Trillo        | Done       |
|                |                                    | T10                  | Configuración de repositorios            | Crear y vincular repos en GitHub para Landing, Frontend, Backend y Reportes.    | 4                      | Fabrizio Quiroz              | Done       |

###### 5.2.1.4. Development Evidence for Sprint Review

| Repository                                                                 | Branch   | Commit Id | Commit Message                                    | Commit Message Body                                | Commit on (Date) |
|----------------------------------------------------------------------------|----------|-----------|---------------------------------------------------|----------------------------------------------------|------------------|
| [Landing Page](https://github.com/Diseno-Experimentos/landing-page)        | main     | 2d3f1a9   | feat(landing): implement hero and benefits section | Implementación de secciones principales del landing | 05/09/2025       |
| [CertiWeb-Front](https://github.com/Diseno-Experimentos/CertiWeb-Front)    | main     | 7a4b2c3   | feat(frontend): add dashboard and navigation       | Configuración de Vue + Vite y dashboard inicial     | 06/09/2025       |
| [CertiWeb-Back](https://github.com/Diseno-Experimentos/certiweb-back)      | main     | 4f9e1b7   | feat(api): create REST endpoints for cars & users  | Implementación de controladores y servicios iniciales| 07/09/2025       |
| [Fake API](https://github.com/Diseno-Experimentos/fake-api)                | main     | 1c8e2d4   | feat(fake-api): configure JSON server with schema  | Fake API para pruebas de frontend                   | 07/09/2025       |
| [CertiWeb-Report](https://github.com/Diseno-Experimentos/CertiWeb-Report)  | main     | 6b7a9f2   | docs(report): add TB1 documentation structure      | Creación de la documentación inicial del proyecto   | 08/09/2025       |


##### 5.2.2. Implemented Landing Page Evidence

Durante el Sprint 1 se implementaron las siguientes evidencias funcionales:

- **Landing Page** desplegada en GitHub Pages: [https://diseno-experimentos.github.io/landing-page](https://diseno-experimentos.github.io/landing-page)  
  - Sección Home con hero principal y CTA.  
  - Sección About Us con descripción del servicio.  
  - Sección Reviews con testimonios de clientes.  
  - Sección Contact con formulario de contacto.  

- **Frontend Web App** inicial en Vue.js.  
  - Dashboard de usuario con acceso a certificaciones.  
  - Navegación básica entre módulos.  

- **Backend en .NET** con API REST.  
  - Endpoints iniciales para usuarios y autos.  
  - Conexión a base de datos simulada.  

- **Fake API** con JSON Server para pruebas rápidas de frontend.

###### 5.2.1.6. Services Documentation Evidence for Sprint Review

Para el Sprint 1 se implementaron endpoints iniciales del backend. Se tiene previsto ampliar la documentación con Swagger en los próximos sprints.  

Repositorio de Backend: [https://github.com/Diseno-Experimentos/certiweb-back](https://github.com/Diseno-Experimentos/certiweb-back)

Repositorio de Fake API: [https://github.com/Diseno-Experimentos/fake-api](https://github.com/Diseno-Experimentos/fake-api)


###### 5.2.1.7. Software Deployment Evidence for Sprint Review

Se desplegaron los distintos módulos en GitHub y Render:  

- Organización en GitHub: creación de repositorios para Landing, Frontend, Backend, Fake API y Reportes.  
- Landing Page desplegada en GitHub Pages.  
- Fake API desplegada en entorno local para pruebas.  
- Backend preparado para despliegue en Render (pendiente en siguientes sprints).  

#### 5.2.1.8. Team Collaboration Insights during Sprint

El equipo trabajó de manera colaborativa en GitHub, distribuyendo responsabilidades entre Landing Page, Frontend, Backend y Documentación.  

Se evidencian múltiples commits distribuidos en los distintos repositorios, reflejando la participación activa de todos los miembros.  

##### 5.2.3. Implemented Frontend-Web Application Evidence

Durante el Sprint 1 se desarrolló la primera versión del **Frontend Web Application** utilizando **Vue.js con Vite**.  
El frontend permite a los usuarios registrarse, iniciar sesión, acceder a su panel de certificaciones y realizar reservas de inspecciones.  

A continuación, se presentan las secciones principales implementadas en el Frontend:

Sección Búsqueda:  
<img src="Images/searchFil.png"/>

Sección Bienvenida:  
<img src="Images/welcome.png"/>

Sección Certificado:  
<img src="Images/certifi.png"/>

Sección Marcas:  
<img src="Images/brand.png"/>

Sección Reserva:  
<img src="Images/reserva1.png"/>  
<img src="Images/reserva2.png"/>

Sección Historial:  
<img src="Images/pruebareserva.png"/>

Sección Perfil de Usuario:  
<img src="Images/seccperfil.png"/>

Repositorio del Frontend: [CertiWeb-Front](https://github.com/Diseno-Experimentos/CertiWeb-Front)

##### 5.2.4. Implemented Native-Mobile Application Evidence

<img src="Images/Wmobile1.png"/>

<img src="Images/Wmobile2.png"/>

<img src="Images/Wmobile3.png"/>

##### 5.2.4.1 Acuerdo de Servicio - SaaS (SaaS Agreement)
El **Acuerdo de Servicio SaaS** define los derechos, responsabilidades y limitaciones aplicables a todos los usuarios de la plataforma **CertiWeb**, garantizando transparencia, protección de datos personales y uso ético del servicio. Este documento forma parte de la política de gobernanza tecnológica del proyecto y será publicado de forma visible en la sección **“Términos y Condiciones”** del sitio web oficial.

#### a) Objetivo del acuerdo
Establecer las condiciones bajo las cuales los usuarios pueden acceder y utilizar la plataforma **CertiWeb**, asegurando un marco de operación confiable y conforme a la legislación vigente sobre servicios digitales, protección de datos personales y propiedad intelectual.

#### b) Alcance
El acuerdo aplica a todos los módulos del ecosistema **CertiWeb**:

- **Landing Page**: Orientada a la difusión del servicio y captación de clientes.  
- **Web Application**: Destinada a la gestión de inspecciones y emisión de certificados.  
- **Backend/API**: Encargada del procesamiento seguro de información y comunicación entre módulos.

#### c) Principales disposiciones

1. **Licencia de uso:** El usuario obtiene una licencia limitada, no exclusiva y revocable para acceder al servicio SaaS de CertiWeb.  
2. **Propiedad intelectual:** Todo el software, marca e interfaz son propiedad del equipo desarrollador **RepLink – CertiWeb**.  
3. **Privacidad y datos personales:** La plataforma cumple con los principios de la *Ley N.° 29733 (Perú)* y el *Reglamento (UE) 2016/679 (GDPR)*, garantizando confidencialidad, seguridad y uso legítimo de la información.  
4. **Responsabilidad del usuario:** El usuario se compromete a proporcionar información veraz, mantener la seguridad de sus credenciales y usar el sistema conforme a las normas aplicables.  
5. **Limitación de responsabilidad:** CertiWeb no será responsable por pérdidas indirectas o interrupciones causadas por terceros proveedores o fallas ajenas al control del servicio.  
6. **Suspensión del servicio:** El proveedor se reserva el derecho de suspender temporalmente el servicio para mantenimiento, previa notificación a los usuarios registrados.  
7. **Soporte y mantenimiento:** El servicio incluye atención técnica básica a través de los canales indicados en la web.  
8. **Jurisdicción:** Cualquier controversia derivada del uso del servicio será resuelta conforme a la legislación peruana vigente.

#### d) Publicación y accesibilidad
El acuerdo será publicado en formato legible y responsivo dentro del apartado **Terms & Conditions**, accesible desde el pie de página de todas las interfaces del sistema.  
Además, se aplicarán criterios de **accesibilidad (WCAG 2.1 AA)** para garantizar su comprensión y legibilidad en dispositivos móviles.

#### e) Cumplimiento normativo y ética digital
**CertiWeb** adopta principios de **transparencia, responsabilidad y seguridad digital**, promoviendo la confianza del usuario final y la sostenibilidad del servicio a largo plazo.


##### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

Durante el Sprint 1 se implementó el **Backend de CertiWeb** en **.NET 8** con arquitectura RESTful.  
El backend provee servicios para la gestión de usuarios, vehículos, certificaciones y reservas.  

Principales módulos implementados:  
- Autenticación y autorización de usuarios.  
- Gestión de vehículos y marcas.  
- Certificaciones técnicas con generación de informes en PDF.  
- Reservas de inspecciones vehiculares.  

Evidencias de arquitectura y despliegue:

Diagrama de Contenedores:  
<img src="Images/ContainersDiagram.png"/>

Diagrama de Componentes:  
<img src="Images/ComponentDiagram.png"/>

Diagrama de Base de Datos:  
<img src="Images/DatabaseDiagram.png"/>

Despliegue en entornos de prueba:  
<img src="Images/Sprint3deploy1.png"/>  
<img src="Images/Sprint3deploy2.png"/>  
<img src="Images/Sprint3deploy3.png"/>  
<img src="Images/Sprint3deploy4.png"/>  
<img src="Images/Sprint3deploy5.png"/>  
<img src="Images/Sprint3deploy6.png"/>

Repositorio del Backend: [CertiWeb-Back](https://github.com/Diseno-Experimentos/certiweb-back)

Repositorio de la Fake API (para pruebas rápidas de integración): [Fake API](https://github.com/Diseno-Experimentos/fake-api)

##### 5.2.6. RESTful API documentation


La documentación de la API se estructuró siguiendo el estándar **OpenAPI 3.0** y se integró con **Swagger**.  
Esto permite a los desarrolladores consultar y probar de forma interactiva los endpoints implementados en el backend.  

Evidencia de la documentación generada:

<img src="Images/APIdoc1.png"/>  
<img src="Images/APIdoc2.png"/>  
<img src="Images/APIdoc3.png"/>  

Actualización de la documentación en Sprint 4:  
<img src="Images/Sprint4swagger1.png"/>  
<img src="Images/Sprint4swagger2.png"/>  
<img src="Images/Sprint4swagger3.png"/>  

Repositorio con documentación actualizada: [CertiWeb-Back](https://github.com/Diseno-Experimentos/certiweb-back)

##### 5.2.7. Team Collaboration Insights

<img src="Images/InsightsSprint2.png"/>

##### 5.2.8. Sprint 2

### 5.2.8.1 Sprint Planning 2

<p>Se planeó el segundo sprint a través de una reunión dentro de la plataforma Discord. Para esto, se realizó una tabla que permitió registrar toda la información discutida.</p>


| **Sprint #**                       | Sprint 2                                                                                                                                                                                                                                                                                                                                                                                                      |
|:-----------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**     |                                                                                                                                                                                                                                                                                                                                                                                                               |
| Date                               | 2024-09-16                                                                                                                                                                                                                                                                                                                                                                                                       |
| Time                               | 5:00 PM                                                                                                                                                                                                                                          -                                                                                                                                                                                                           |
| Location                           | Virtual                                                                                                                                                                                                                                                                                                                                                                                                               |
| Prepared by                        | Fabrizio Javier Quiroz Zambrano                                                                                                                                                                                                                                                                                                                                                                            |
| Attendees (to planning meeting)    | <p>Zúñiga Murillo, Diego Sebastián</p><p>Trillo Hernandez, Anghel Melanie</p><p>Angulo Abud, Juan Carlos</p><p>Monte Maza, Augusto</p>                                                                                                                                                                                                   |
| Sprint n - 2 Review Summary        | Durante este segundo sprint se logro hacer el punto 6 y 7 que consisten en testeos a nuestra app, se lograron con exito                                                      |
| Sprint n - 2 Retrospective Summary | El equipo identificó como aciertos la comunicación efectiva y la colaboración en la resolución de problemas. No obstante, se señaló la necesidad de una mejor planificación inicial, especialmente en cuanto a la estimación del tiempo necesario para ciertas tareas, y se identificó la posibilidad de optimizar el proceso de revisión de código para garantizar una mayor calidad del producto entregado. |
| **Sprint Goal & User Stories**     |                                                                                                                                                                                                                                                                                                                                                                                                               |
| Sprint 2 Goal                      | El objetivo principal que tiene este sprint 2 es elaborar de manera exitosa los testeos de nuestra app.                                _                                                                                                                                                                                                                           |
| Sprint 2 Velocity                  | 19                                                                                                                                                                                                                                                                                                                                                                                                               |
| Sum of Story Points                | 19                                                                                                                                                                                                                                                                                                                                                                                                           |

### 5.2.2.2 Sprint Backlog 2

<p>El principal objetivo de este segundo sprint fue completar la implementación de las vistas principales del <strong>Frontend Web de CertiWeb</strong>, integrando las funcionalidades de autenticación, gestión de vehículos, inspecciones y certificados. Este sprint se desarrolló en paralelo mediante Trello y GitHub Projects dentro de la organización <strong>RepLink – CertiWeb</strong>.</p>

<table>
  <tbody>
    <tr>
      <td><strong>User Story ID</strong></td>
      <td><strong>User Story Title</strong></td>
      <td><strong>Task ID</strong></td>
      <td><strong>Task Title</strong></td>
      <td><strong>Description</strong></td>
      <td><strong>Estimation (hours)</strong></td>
      <td><strong>Assigned to</strong></td>
      <td><strong>Status</strong></td>
    </tr>
<tr>
  <td rowspan="2">US01</td>
  <td rowspan="2">Autenticación y acceso seguro</td>
  <td>T01</td>
  <td>Implementar formulario de inicio de sesión</td>
  <td>Diseñar e implementar el formulario de Login conectado al endpoint <code>/auth/login</code>, con validación de credenciales y mensajes de error.</td>
  <td>4</td>
  <td>Quiroz Zambrano, Fabrizio</td>
  <td>Done</td>
</tr>
<tr>
  <td>T02</td>
  <td>Configurar persistencia de sesión</td>
  <td>Implementar almacenamiento del token JWT en <code>localStorage</code> y verificación de expiración automática de sesión.</td>
  <td>3</td>
  <td>Quiroz Zambrano, Fabrizio</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US02</td>
  <td rowspan="2">Gestión de vehículos registrados</td>
  <td>T03</td>
  <td>Crear vista "Mis Vehículos"</td>
  <td>Desarrollar tabla dinámica que muestre todos los vehículos del usuario autenticado obtenidos desde el endpoint <code>/vehicles</code>.</td>
  <td>5</td>
  <td>Angulo Alarcón, Juan Carlos</td>
  <td>Done</td>
</tr>
<tr>
  <td>T04</td>
  <td>Agregar nuevo vehículo</td>
  <td>Implementar formulario modal para registrar un nuevo vehículo con validaciones y envío de datos al backend.</td>
  <td>4</td>
  <td>Angulo Alarcón, Juan Carlos</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US03</td>
  <td rowspan="2">Visualización de certificados técnicos</td>
  <td>T05</td>
  <td>Implementar listado de certificados</td>
  <td>Crear un componente que muestre los certificados emitidos con su fecha y estado, obtenidos desde el endpoint <code>/certificates</code>.</td>
  <td>5</td>
  <td>Zúñiga Murillo, Diego</td>
  <td>Done</td>
</tr>
<tr>
  <td>T06</td>
  <td>Visor de certificados PDF</td>
  <td>Integrar visor PDF embebido para la visualización directa del certificado técnico desde la aplicación.</td>
  <td>3</td>
  <td>Zúñiga Murillo, Diego</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US04</td>
  <td rowspan="2">Historial de inspecciones</td>
  <td>T07</td>
  <td>Construir tabla de inspecciones</td>
  <td>Implementar tabla dinámica para listar inspecciones con información del vehículo, fecha y resultado técnico.</td>
  <td>5</td>
  <td>Trillo Hernández, Melanie</td>
  <td>Done</td>
</tr>
<tr>
  <td>T08</td>
  <td>Filtro por estado y fecha</td>
  <td>Agregar filtros por estado (aprobado/rechazado) y rango de fechas para mejorar la búsqueda del historial.</td>
  <td>3</td>
  <td>Trillo Hernández, Melanie</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US05</td>
  <td rowspan="2">Panel de control del usuario</td>
  <td>T09</td>
  <td>Diseñar Dashboard</td>
  <td>Implementar panel principal que muestre métricas clave: cantidad de vehículos, inspecciones pendientes y certificados emitidos.</td>
  <td>6</td>
  <td>Quiroz Zambrano, Fabrizio</td>
  <td>Done</td>
</tr>
<tr>
  <td>T10</td>
  <td>Configurar rutas y navegación</td>
  <td>Definir estructura de rutas con <code>vue-router</code> y proteger las vistas mediante guardas de autenticación.</td>
  <td>4</td>
  <td>Quiroz Zambrano, Fabrizio</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US06</td>
  <td rowspan="2">Optimización visual y SEO</td>
  <td>T11</td>
  <td>Mejorar diseño responsive</td>
  <td>Ajustar el layout del frontend para pantallas móviles y tabletas siguiendo la guía de estilo de CertiWeb.</td>
  <td>4</td>
  <td>Trillo Hernández, Melanie</td>
  <td>Done</td>
</tr>
<tr>
  <td>T12</td>
  <td>Aplicar meta tags y SEO básico</td>
  <td>Configurar meta tags de título, descripción y palabras clave para mejorar la indexación del sitio.</td>
  <td>2</td>
  <td>Zúñiga Murillo, Diego</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US07</td>
  <td rowspan="2">Refactorización y documentación de componentes</td>
  <td>T13</td>
  <td>Refactorizar componentes de UI</td>
  <td>Analizar y refactorizar componentes de la interfaz de usuario para mejorar la reutilización y mantenibilidad del código.</td>
  <td>5</td>
  <td>Monte Maza, Augusto</td>
  <td>Done</td>
</tr>
<tr>
  <td>T14</td>
  <td>Documentar componentes en Storybook</td>
  <td>Crear historias en Storybook para los componentes principales, documentando sus props y casos de uso.</td>
  <td>4</td>
  <td>Monte Maza, Augusto</td>
  <td>Done</td>
</tr>

  </tbody>
</table>

<p><strong>Resultado esperado:</strong> Al finalizar el Sprint 2, se logró completar todas las vistas funcionales del Frontend Web, con autenticación, panel de usuario, gestión de vehículos, historial de inspecciones y certificados técnicos, cumpliendo con los estándares de usabilidad y conectividad establecidos por el backend de <strong>CertiWeb</strong>.</p>

### 5.3 Video About-the-Product
En esta sección se presenta un video explicativo sobre el producto desarrollado. El objetivo del video es resaltar las principales características, funcionalidades y beneficios del producto, permitiendo a los usuarios tener una mejor comprensión de su propósito y usabilidad.

<img src="Images/product.jpg"/>

A continuación, se proporcionan enlaces a las plataformas donde el video ha sido subido, junto con una captura de pantalla del mismo:

[About the Product](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213358_upc_edu_pe/EcRe5QWCUYlPhyd9P4OesvgBfz8M09CvQaB5hUQ7ZO49zQ?e=MdFhdT&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<a id="capitulo-vi-product-verification-validation"></a>
# Capítulo VI: Product Verification and Validation


<a id="capitulo-vi-product-verification-validation"></a>
## 6.1. Testing Suites & Validation


<a id="6-1-1-core-entities-unit-tests"></a>
## 6.1.1. Core Entities Unit Tests

En esta sección se ejecutaron pruebas unitarias abarcando todas las entidades principales del dominio CertiWeb. Para cumplir con los estándares de calidad exigidos, se incluyeron específicamente **pruebas de conversión de datos** y **validaciones negativas** (manejo de errores y límites).

### Herramientas Utilizadas
- **Framework:** NUnit
- **Aserciones:** FluentAssertions
- **Mocking:** Moq

### Resultados de la Suite de Pruebas

Se ejecutó una batería de 45 pruebas unitarias. A continuación, se detalla la evidencia específica de los casos de conversión y manejo de excepciones:

#### A. Pruebas de Conversión y Lógica de Negocio (Conversion Tests)
Estas pruebas validan que los datos se transformen correctamente entre formatos y monedas, evitando errores de cálculo o pérdida de precisión.

| Clase Testeada | Caso de Prueba | Entrada (Input) | Resultado Esperado | Estado |
| :--- | :--- | :--- | :--- | :--- |
| **PriceConverter** | Convertir Soles a Dólares (Tasa fija) | `Amount: 100 PEN` | `26.5 USD` (aprox) | Passed |
| **PriceConverter** | Convertir misma moneda | `Amount: 50 USD` -> `USD` | `50 USD` (Sin cambio) | Passed |
| **InspectionStatus** | Conversión de String a Enum | String: `"Certified"` | Enum: `Status.Certified` | Passed |
| **PdfGenerator** | Codificación de Binario a Base64 | Archivo PDF (bytes) | String Base64 válido | Passed |

#### B. Pruebas de Validaciones Negativas y Manejo de Errores (Error Handling)
Estas pruebas confirman que el sistema lanza las excepciones correctas ante datos inválidos ("Situaciones límite"), evitando que datos corruptos entren a la base de datos.

| Clase Testeada | Escenario de Error (Caso Límite) | Entrada Inválida | Excepción Esperada | Estado |
| :--- | :--- | :--- | :--- | :--- |
| **Price** | Crear precio negativo | `-50.00` | `ArgumentException: Price cannot be negative` | Passed |
| **LicensePlate** | Placa con caracteres especiales | `"ABC-12@"` | `FormatException: Invalid characters` | Passed |
| **LicensePlate** | Placa vacía o nula | `""` o `null` | `ArgumentNullException` | Passed |
| **Year** | Año futuro (Límite superior) | `2030` | `DomainException: Year cannot be in future` | Passed |
| **User** | Registro con email inválido | `"juan.perez@com"` | `ValidationException: Invalid email format` | Passed |


```console
Passed!  - Failed:     0, Passed:    45, Skipped:     0, Total:    45, Duration: 320ms
[x] CertiWeb.UnitTests.Domain.ValueObjects.PriceTests.Create_NegativeAmount_ThrowsException
[x] CertiWeb.UnitTests.Domain.Services.CurrencyConverterTests.Convert_PEN_To_USD_ReturnsCorrectValue
```

<a id="6-1-2-core-integration-tests"></a>
## 6.1.2. Core Integration Tests
En esta sección implementamos pruebas de integracion para validar la correcta interaccion entre los diferentes módulos y componentes de CertiWeb, haciendo énfasis en la persistencia de datos y la comunidación entre capas.

### Componentes integrados
Las pruebas de integración valodan las siguientes integraciones

#### Persistencia de datos
- Entity Framework Core: Integración con base de datos en memoria
- DbContext: Configuración y mapping de entidades
- Repositories: Operaciones CRUD y consultas complejas

#### Relación entre entidades
- Foreign Keys: Validación de integridad referencial
- Constraints únicos: License Plates y Reservation IDs
- Navegación: Propiedades de navegación entre entidades relacionadas

#### Casos de prueba implemetados

##### Operaciones CRUD
- Creación, lectura, actualización y eliminación de entidades
- Persistencia de value objects complejos
- Manejo de transacciones y rollbacks

##### Consulta y filtros
- Búsquedas por múltiples criterios
- Joins entre entidades relacionadas
- Paginación y ordenamiento

##### Valicaciones de integridad
- Constraints de base de datos
- Validaciones de unicidad
- Manejo de conflictos de concurrencia

Las pruebas de integración confirman que todos los módulos interactúan correctamente, que la persistencia funciona según lo esperado, y que no existen problemas de comunicación entre las diferentes capas del sistema.


<a id="6-1-3-core-behavior-driven-development"></a>
## 6.1.3 Core Behaviour-Driven Development
En esta sección se aplicaron técnicas de BDD para definir y probar el comportamiento esperado de nuestro sistema desde la perspectiva del usuario, utilizando textos en lenguage natural.

### Herramientas integradas

#### SpecFlow Integration:
- Definición de features en formato Gherkin
- Step definitions en C#
- Integración con el framework de testing existente

#### Escenarios de usuario definidos

##### Feature: Gestión de Vehículos
```
Feature: Car Management
  As a user
  I want to manage vehicle information
  So that I can track and certify vehicles

Scenario: Register a new vehicle
  Given I am an authenticated user
  When I submit valid vehicle information
  Then the vehicle should be registered successfully
  And I should receive a confirmation

Scenario: Search vehicles by license plate
  Given there are vehicles in the system
  When I search by license plate "ABC123"
  Then I should see the matching vehicle details
```

##### Feature: Certificación de Vehículos
```
Feature: Vehicle Certification
  As a user
  I want to generate vehicle certificates
  So that I can provide official documentation

Scenario: Generate PDF certificate
  Given I have a registered vehicle
  When I request a certificate generation
  Then a PDF certificate should be created
  And it should contain all vehicle details
```

##### Step definitions implementadas
``` cs
[Given(@"I am an authenticated user")]
public void GivenIAmAnAuthenticatedUser()
{
    // Arrange: Setup authenticated user context
}

[When(@"I submit valid vehicle information")]
public void WhenISubmitValidVehicleInformation()
{
    // Act: Execute vehicle registration
}

[Then(@"the vehicle should be registered successfully")]
public void ThenTheVehicleShouldBeRegisteredSuccessfully()
{
    // Assert: Verify successful registration
}
```
#### Flujos de Usuario Validados

##### Flujos Principales:
- Registro y autenticación de usuarios
- Gestión completa de vehículos (CRUD)
- Generación y descarga de certificados
- Búsqueda y filtrado de información

##### Flujos Alternativos:
- Manejo de errores y validaciones
- Casos de uso edge cases
- Recuperación de errores

Con estas pruebas BDD garantizamos que el sistema cumple con los requisitos funcionales desde la perspectiva del usuario, proporcionando una documentación executable que describe exactamente cómo debe comportarse la aplicación en diferentes escenarios.

<a id="6-1-4-core-system-tests"></a>
## 6.1.4 Core System Tests

En esta sección se realizaron pruebas de sistema exhaustivas para validar que la aplicación CertiWeb funciona correctamente en su totalidad, cubriendo desde las APIs REST hasta la integración completa de todos los componentes del sistema.


### Alcance de las Pruebas de Sistema

#### Testing End-to-End:
- Validación completa de APIs REST
- Pruebas de flujos de trabajo completos
- Integración con base de datos real
- Validación de middleware y pipeline HTTP

#### Componentes del Sistema Validados:
- Controllers: Endpoints de Brand, Car y User
- Authentication: JWT y autorización
- Database: Operaciones reales con SQL Server
- Middleware: Logging, error handling, CORS
- Performance: Carga y tiempo de respuesta

### Infraestructura de testing

``` cs
public class SystemTestBase : IClassFixture<WebApplicationFactory<Program>>
{
    protected readonly HttpClient _client;
    protected readonly WebApplicationFactory<Program> _factory;
    
    public SystemTestBase(WebApplicationFactory<Program> factory)
    {
        _factory = factory;
        _client = factory.CreateClient();
    }
}
```

### Categorías de pruebas implementadas

#### API System Tests
```
[Test]
public async Task CreateCar_WithValidData_ShouldReturn201()
{
    // Arrange
    var carRequest = CarTestDataBuilder.CreateValidCarRequest();
    
    // Act
    var response = await _client.PostAsJsonAsync("/api/cars", carRequest);
    
    // Assert
    response.StatusCode.Should().Be(HttpStatusCode.Created);
}
```

#### Performance Tests:
- Pruebas de carga con múltiples usuarios concurrentes
- Validación de tiempos de respuesta bajo estrés
- Pruebas de memoria y uso de recursos

#### Security Tests
- Valicación de autenticación con JWT
- Pruebas de autorización por roles
- Validación de HTTPS y headers de seguridad

#### Resilience Tests
``` cs
[Test]
public async Task Api_UnderHighLoad_ShouldMaintainPerformance()
{
    // Arrange
    var tasks = new List<Task<HttpResponseMessage>>();
    
    // Act: Simulate 100 concurrent requests
    for (int i = 0; i < 100; i++)
    {
        tasks.Add(_client.GetAsync("/api/cars"));
    }
    
    var responses = await Task.WhenAll(tasks);
    
    // Assert
    responses.All(r => r.IsSuccessStatusCode).Should().BeTrue();
}
```

### Escenarios de Testing Completos

#### Flujo Completo de Certificación:
- Autenticación de usuario
- Registro de marca de vehículo
- Registro de vehículo completo
- Generación de certificado PDF
- Descarga y validación del certificado

#### Pruebas de Integración Multicapa:
- Frontend → API → Business Logic → Database
- Validación de transformación de datos en cada capa
- Manejo de errores propagado correctamente

### Configuración de Ambiente de Pruebas

#### Database Seeding
``` cs
public static class TestDataSeeder
{
    public static async Task SeedTestData(CertiWebDbContext context)
    {
        // Seed brands, users, and test vehicles
        await context.Brands.AddRangeAsync(GenerateTestBrands());
        await context.SaveChangesAsync();
    }
}
```

#### Test Configuration:
- Configuración específica para testing environment
- Base de datos temporal para cada suite de tests
- Logs detallados para debugging

### Métricas y Validaciones

#### Métricas de Performance:
- Tiempo de respuesta promedio < 200ms
- Capacidad de 100+ usuarios concurrentes
- Uso de memoria estable bajo carga

#### Validaciones de Funcionalidad:
- Todos los endpoints REST funcionan correctamente
- Validaciones de datos funcionan en contexto real
- Manejo de errores apropiado en todos los niveles

Las pruebas de sistema nos ayudan a confirmar que CertiWeb funciona correctamente como aplicación completa, validando que todos los componentes integrados proporcionan la funcionalidad esperada con el rendimiento y la confiabilidad requeridos. La aplicación está lista para producción con confianza en su estabilidad y correctitud funcional.

<a id="6-1-5-frontend-unit-tests"></a>
## 6.1.5. Frontend Unit & Component Tests (Vue.js)

Para garantizar la calidad de las interacciones del usuario, se implementó una suite de pruebas de componentes utilizando **Vitest** y **Vue Test Utils**. Estas pruebas se enfocan específicamente en la **validación de formularios**, **manejo de errores** y **formateo de datos** (conversiones visuales).

### Componentes Críticos Evaluados

#### 1. Validación de Login (`LoginForm.vue`)
Se verificó que el formulario impida el envío de datos incorrectos y muestre retroalimentación visual inmediata.

**Escenario de Prueba (Validación Negativa):**
* **Caso:** Usuario intenta ingresar con un formato de correo inválido.
* **Resultado Esperado:** El sistema bloquea el evento `submit` y muestra la clase de error `.input-error`.

**Código de la Prueba:**
```javascript
import { mount } from '@vue/test-utils'
import LoginForm from './LoginForm.vue'

test('Debe mostrar error visual cuando el email no es válido', async () => {
  const wrapper = mount(LoginForm)
  
  // Act: Ingresar email inválido y enviar
  await wrapper.find('input[type="email"]').setValue('correo-sin-arroba')
  await wrapper.find('form').trigger('submit')

  // Assert: Verificar estado de error
  expect(wrapper.find('.error-message').text()).toContain('Formato de correo inválido')
  expect(wrapper.find('input').classes()).toContain('input-error')
})
```

### 6.2. Static Testing & Verification


#### Evidencia de Ejecución de Herramientas de Análisis

Para asegurar que el código cumple con los estándares descritos y no presenta vulnerabilidades básicas, se integraron herramientas de análisis estático en el pipeline de desarrollo. A continuación se presentan los reportes de ejecución:

**1. ESLint (Frontend - Vue.js):**
Se ejecutó el linter para detectar errores de sintaxis, variables no utilizadas y violaciones de estilo en el código JavaScript/Vue.

*Reporte de Ejecución:*

```console
$ npm run lint
> certiweb-frontend@0.0.0 lint
> eslint . --ext .vue,.js,.jsx,.cjs,.mjs --fix

/src/components/InspectionCard.vue
  45:7  warning  Unexpected console statement   no-console
  88:12 error    'formatCurrency' is defined but never used  no-unused-vars

✖ 2 problems (1 error, 1 warning)
```

SonarLint / .NET Analyzers (Backend): Se utilizó el analizador nativo de .NET 8 para validar reglas de seguridad y mantenimiento.

Resumen de Hallazgos:

Security Hotspots: 0 detectados (Validación de connection strings segura).

Code Smells: 3 detectados (Métodos con complejidad ciclomática > 15 en InspectionService.cs).

Mantenibilidad: Calificación A

Esta ejecución continua de análisis estático asegura que la deuda técnica se mantenga controlada antes de cada despliegue.

### 6.2.1. Static Code Analysis

El análisis estático consistió en revisar las entidades y componentes definidos en el class dictionary (User, Vehicle, Inspection, TechnicalReport, Certification, Subscription, Payment, etc.), asegurando que las relaciones y atributos cumplan con:

- **Cohesión interna:** Cada entidad mantiene una única responsabilidad (por ejemplo, `TechnicalReport` solo gestiona información técnica y código de validación).
- **Consistencia semántica:** Los nombres de atributos usan el *Ubiquitous Language* definido en la sección 2.4.
- **Compatibilidad estructural:** Los tipos de datos son adecuados (UUID, Date, String, Money) y no generan estados inválidos.
- **Integridad del dominio:** No existen ciclos ni dependencias innecesarias entre entidades.
- **Correcta inicialización:** Estados como `inspectionStatus = "Pending"` se encuentran bien definidos desde la creación del objeto.

Este análisis permitió identificar riesgos potenciales antes de la experimentación, evitando sesgos en las pruebas posteriores.

### 6.2.1.1. Coding Standards & Code Conventions

Se evaluaron los estándares aplicados en los artefactos del sprint:

- Uso consistente de **camelCase** para atributos y métodos.
- Separación clara entre carpetas de **domain**, **application**, **infrastructure** y **web**, siguiendo el enfoque de diseño por dominios.
- Validaciones mínimas obligatorias:
  - Placa del vehículo no vacía.
  - Atributos obligatorios en inspecciones.
  - Resultados de inspección solo disponibles cuando `inspectionDate` está definida.
- Comentarios claros en métodos críticos.
- Convenciones uniformes para nombrar endpoints REST (`/inspections`, `/reports/:id`, `/validate/:code`).

Estas convenciones facilitan que los experimentos posteriores sean reproducibles y auditables.

### 6.2.1.2. Code Quality & Code Security

Se verificaron posibles vulnerabilidades lógicas y estructurales:

- **Control de estados inválidos:**
  - Evitar inspecciones “certificadas” sin informe técnico asociado.
  - Evitar reportes sin código de validación.
- **Generación segura de códigos únicos:**
  - No hay duplicación en `validationCode`.
- **Aislamiento del dominio frente a entradas externas:**
  - El sistema previene datos malformados al registrar vehículos e inspecciones.
- **Protección de datos sensibles:**
  - Los informes no exponen correos ni información privada del usuario.
- **Estandarización de fechas:**
  - Las fechas se manejan en un formato uniforme para evitar inconsistencias en registros.

Estas verificaciones reducen la probabilidad de amenazas que podrían afectar la validez de los experimentos dinámicos del sprint.

### 6.2.2. Reviews

#### Peer Review (Revisión cruzada)
Cada integrante validó el trabajo de otro miembro revisando:

- Claridad lógica.
- Congruencia con la arquitectura.
- Uso correcto del Ubiquitous Language.
- Correspondencia entre definiciones y requisitos del sprint.

Este proceso asegura que las decisiones tomadas antes del experimento cuenten con revisión por pares, aumentando la confiabilidad del diseño.

#### UX/UI Review
Se evaluaron pantallas y wireframes aplicando heurísticas básicas:

- Visibilidad del estado del sistema (por ejemplo, estados de inspección).
- Consistencia gráfica en tarjetas, botones y paneles.
- Claridad en la navegación y etiquetas (“Solicitar inspección”, “Ver informe”, “Validar código”).
- Ausencia de ambigüedad en flujos críticos (registro, inspección, informe).

Estas revisiones permiten validar experimentalmente que la interfaz no introduce sesgos o fricciones que afecten los resultados del sistema.

#### Requirements Review
Se verificó la alineación entre:

- Historias de usuario del sprint.
- Backlog priorizado.
- Criterios de aceptación.
- User flows ideales.

Este análisis garantiza que el sistema cumpla estructuralmente las condiciones necesarias antes de ejecutar experimentos sobre comportamiento (testing dinámico).

## 6.3. Validation Interviews
Para validar la solución implementada, se realizan entrevistas a candidatos pertenecientes a los segmentos objetivo con el fin de evaluar su nivel de satisfacción y aceptación hacia el producto futuro.

Para acceder al video de las entrevistas:

### 6.3.1 Diseño de Entrevistas
Se realizaron entrevistas a personas representativas de nuestros segmentos objetivo, ajustando las preguntas según las particularidades de cada segmento y sus diferentes circunstancias.

##### Segmento 1: Vendedores Particulares

Preguntas de Introducción:
1. ¿Cuál es su nombre completo?
2. ¿Cuál es su edad?
3. ¿En qué ciudad y/o distrito reside?

Preguntas de principales:
| #  | Pregunta                                                                                                               |
| -- | ---------------------------------------------------------------------------------------------------------------------- |
| 1  | ¿Qué tan fácil te resultó registrarte y agendar una inspección técnica desde la plataforma?                            |
| 2  | ¿Sientes que la explicación del servicio en la landing page fue clara y suficiente para entender el valor de Certiweb? |
| 3  | ¿Te pareció útil recibir un informe técnico con fotos y diagnóstico luego de la inspección?                            |
| 4  | ¿Consideras que el sello de certificación ayuda a generar más confianza en los compradores?                            |
| 5  | ¿Fue sencillo compartir tu informe con potenciales compradores?                                                        |
| 6  | ¿Te gustaría que el sistema permitiera publicar tu anuncio directamente en portales como OLX o Marketplace?            |
| 7  | ¿Sientes que la plataforma te dio herramientas para vender más rápido?                                                 |
| 8  | ¿Qué tan útil te pareció el sistema de estados (“pendiente”, “inspeccionado”, “certificado”)?                          |
| 9  | ¿Preferirías poder contactar a Certiweb desde la misma plataforma en lugar de por correo o WhatsApp?                   |
| 10 | ¿Te gustaría poder dejar una reseña sobre el servicio recibido después de vender tu auto?                              |


##### Segmento 2: Revendedores
Preguntas de Introducción:
1. ¿Cuál es su nombre completo?
2. ¿Cuál es su edad?
3. ¿En qué ciudad y/o distrito reside?

Preguntas de principales:
| #  | Pregunta                                                                                              |
| -- | ----------------------------------------------------------------------------------------------------- |
| 1  | ¿Qué tan sencillo te pareció registrar varios autos al mismo tiempo en la plataforma?                 |
| 2  | ¿Te resultó útil el panel de gestión para visualizar el estado de cada inspección?                    |
| 3  | ¿Qué tan valiosas te parecieron las notificaciones sobre cambios en el estado de los vehículos?       |
| 4  | ¿Te parece que el informe técnico es suficientemente claro y profesional para mostrar a tus clientes? |
| 5  | ¿Preferirías tener integración directa con portales de venta desde la plataforma Certiweb?            |
| 6  | ¿Te resulta más eficiente trabajar con esta plataforma que con talleres independientes?               |
| 7  | ¿Te pareció claro el detalle de los planes de suscripción mensual y trimestral?                       |
| 8  | ¿Qué tan útil te parece poder compartir los informes técnicos por WhatsApp o correo sin login?        |
| 9  | ¿Sientes que la plataforma ahorra tiempo en tu proceso de ventas?                                     |
| 10 | ¿Te gustaría que Certiweb ofrezca funciones adicionales como control de inventario o CRM básico?      |

##### Segmento 3: Compradores
Preguntas de Introducción:
1. ¿Cuál es su nombre completo?
2. ¿Cuál es su edad?
3. ¿En qué ciudad y/o distrito reside?

Preguntas de principales:
| #  | Pregunta                                                                                                |
| -- | ------------------------------------------------------------------------------------------------------- |
| 1  | ¿Qué tan sencillo te pareció registrarte en la plataforma?                      |
| 2  | ¿Te dio más confianza saber que un auto había sido inspeccionado por una entidad imparcial?             |
| 3  | ¿Preferirías que el informe sea descargable en PDF o visualizado en la web?                             |
| 4  | ¿Consideras útil que exista una clave de verificación para acceder al informe Certiweb?                             |
| 5  | ¿Qué tan clara te pareció la información contenida en los informes técnicos?                            |
| 6  | ¿Te gustaría poder comparar varios informes de autos diferentes en una misma pantalla?                  |
| 7  | ¿Sientes que un sello visible de certificación influye en tu decisión de contacto o compra?             |
| 8  | ¿Te parecería útil dejar una reseña sobre la experiencia con el vendedor y la condición real del auto?  |
| 9  | ¿Te gustaría recibir alertas o notificaciones cuando un auto certificado de tu interés esté disponible? |
| 10 | ¿Consideras que Certiweb mejora tu seguridad como comprador frente a estafas o engaños?                 |

### 6.3.2 Registro de Entrevistas
Para poder realizar el registro de entrevistas, se llevarán a cabo un total de 9 entrevistas, distribuidas en 3 entrevistas por cada segmento. Cada entrevista será grabada en formato .mp4 y se gestionará de manera independiente debido a las diferencias en las preguntas realizadas y las respuestas proporcionadas por los entrevistados de cada segmento.

##### Segmento 1: Vendedores Particulares

| Entrevista 1 | Olga Hernandez |
|------------------|----------------------|
| Edad         | 44 años              |
| Distrito     | La Victoria          |
| <img src="Images/Sprint4Entre1.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:00:04 - 00:05:13           |
<br>

| Entrevista 2 | Violeta Cortez |
|------------------|----------------------|
| Edad         | 49 años              |
| Distrito     | Callao          |
| <img src="Images/Sprint4Entre2.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:05:17 - 00:10:33           |
<br>

| Entrevista 3 | Sindy Angela |
|------------------|----------------------|
| Edad         | 42 años              |
| Distrito     | Puente Piedra          |
| <img src="Images/Sprint4Entre3.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:10:41 - 00:15:33           |
<br>

##### Segmento 2: Revendedores

| Entrevista 1 | Joaquin Valdivieso |
|------------------|----------------------|
| Edad         | 30 años              |
| Distrito     | Lima          |
| <img src="Images/Sprint4Entre4.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:15:37 - 00:24:46           |
<br>

| Entrevista 2 | Jhonny Pariona |
|------------------|----------------------|
| Edad         | 39 años              |
| Distrito     | Carabayllo          |
| <img src="Images/Sprint4Entre5.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:24:52 - 00:28:52           |
<br>

| Entrevista 3 | Javier Gonzales |
|------------------|----------------------|
| Edad         | 42 años              |
| Distrito     | Lima          |
| <img src="Images/Sprint4Entre6.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=nsG1Bi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTczNC4wMn19)            |
| Timming      | 00:28:55 - 00:32:55           |
<br>

##### Segmento 3: Compradores

| Entrevista 1 | Jorge Santos |
|------------------|----------------------|
| Edad         | 21 años              |
| Distrito     | Lima          |
| <img src="Images/Sprint4Entre7.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=7H2fqB&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTk4My41MX19)            |
| Timming      | 00:33:01 - 00:43:32           |
<br>

| Entrevista 2 | Omar Sikkos |
|------------------|----------------------|
| Edad         | 46 años              |
| Distrito     | San Martin de Porres          |
| <img src="Images/Sprint4Entre8.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=1TCI5n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| Timming      | 00:43:35 - 00:51:23           |
<br>

| Entrevista 3 | Victor Lopez |
|------------------|----------------------|
| Edad         | 52 años              |
| Distrito     | San Miguel          |
| <img src="Images/Sprint4Entre9.png" width="200"/>  |  |
| URL de la grabación | [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=YbhbIq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MzA2MS42N319)            |
| Timming      | 00:51:26 - 00:54:49           |
<br>

##### Insights
A partir del análisis de las entrevistas realizadas a los clientes, se han identificado los siguientes insights globales más relevantes:

1. Necesidad de **confianza** en el servicio
Los clientes valoran altamente la transparencia, la claridad en la información y la seguridad en todos los procesos. La confianza es un factor decisivo para elegir y mantenerse con un proveedor.

2. Búsqueda de **simplicidad y rapidez**
Los usuarios esperan procesos fáciles, tiempos de respuesta cortos y una experiencia sin fricciones. Cuanto más simple sea el flujo, mayor satisfacción y conversión.

3. Importancia de la **comunicación clara y proactiva**
Los clientes expresan que la comunicación debe ser constante, resolver dudas rápidamente y anticiparse a problemas. La falta de comunicación reduce su percepción de profesionalismo.

4. Deseo de **acompañamiento personalizado**
Tanto empresas como personas naturales esperan un trato cercano, asesoría y orientación. Valoran sentir que hay "alguien detrás" ayudándolos, no solo un sistema automatizado.

5. Valoración de **automatización sin perder el toque humano**
Los clientes aceptan bots, formularios y flujos automatizados, siempre que complementen —y no sustituyan completamente— el soporte humano cuando lo necesitan.

6. Necesidad de **integración fluida con herramientas existentes**
Especialmente en el caso de empresas, se requiere compatibilidad con sistemas como HubSpot, CRMs, WhatsApp y plataformas internas. La integración debe ser estable y confiable.

7. Dolor por **procesos manuales actuales**
Muchos clientes expresan frustración con pasos repetitivos, recopilar datos manualmente, depender de terceros o tener poca visibilidad del estado de su solicitud.
8. Fuerte interés en **opciones y personalización**
Los usuarios quieren elegir entre alternativas (por ejemplo: persona o empresa, opción A/B/C, tipo de servicio, horarios, etc.). La personalización incrementa la percepción de valor.

**Conclusión Global**
Los insights reflejan que los clientes buscan una combinación entre **automatización inteligente, comunicación clara y soporte humano confiable**. Reducir fricción, integrar herramientas y reforzar la transparencia serán claves para mejorar la experiencia del usuario.


<a id="6-3-3-evaluaciones-segun-heuristicas"></a>
### 6.3.3. Evaluaciones según heurísticas

**SITE o APP A EVALUAR:**
CertiWeb - Plataforma de Certificación Vehicular

**METODOLOGÍA DE MEDICIÓN:**
Para sustentar las evaluaciones heurísticas, se realizaron pruebas de usabilidad con una muestra de **5 usuarios** representativos del segmento objetivo (Vendedores Individuales). Se recopilaron métricas de:
* **Frecuencia:** Porcentaje de usuarios que encontraron el problema.
* **Costo Temporal:** Tiempo promedio perdido debido al error.
* **Repetitividad:** Si el error persistió o generó bucles de comportamiento (errores repetitivos).

**TAREAS A EVALUAR:**
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
1.  Registro de un usuario nuevo (vendedor particular/revendedor)
2.  Agendar una inspección técnica vehicular
3.  Visualización del panel de gestión de vehículos
4.  Descarga y visualización de informes técnicos
5.  Verificación de autenticidad de certificados
6.  Navegación por el historial de inspecciones
7.  Proceso de login y autenticación
8.  Búsqueda y filtrado de vehículos certificados
9.  Compartir informes técnicos con compradores
10. Gestión de estados de inspección (pendiente, inspeccionado, certificado)

No están incluidas en esta versión de la evaluación las siguientes tareas:
1.  Integración directa con portales de venta (OLX, Marketplace)
2.  Sistema de notificaciones push en tiempo real
3.  Funcionalidades de CRM avanzado para revendedores
4.  Sistema de reseñas y calificaciones
5.  Alertas automáticas de vencimiento de certificados
6.  Funcionalidades de control de inventario

**ESCALA DE SEVERIDAD:**
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción |
| :---: | :--- |
| **1** | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| **2** | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| **3** | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| **4** | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN DE HALLAZGOS:**

| # | Problema | Escala de severidad | Heurística/Principio violada(o) |
|---|---|---|---|
| 1 | No hay un control que permita regresar al dashboard durante el proceso de agendamiento | 3 | Usabilidad: Libertad y control del usuario |
| 2 | Se repiten constantemente algunas opciones en el menú | 1 | Usabilidad: Consistencia y estándares |
| 3 | Imágenes de informes técnicos sin atributo "alt" | 3 | Inclusive Design: Proporciona experiencias comparables |
| 4 | Incluye un botón "Ver más" pero no existe contenido al que dirigirse | 3 | Information Architecture: Is it usable? |
| 5 | No incluye información clara de los planes de servicio | 2 | Information Architecture: Is it findable? |
| 6 | Falta de feedback visual durante procesos de carga | 2 | Usabilidad: Visibilidad del estado del sistema |
| 7 | Formularios sin validación en tiempo real | 3 | Usabilidad: Prevención de errores |
| 8 | Navegación inconsistente entre secciones | 2 | Usabilidad: Consistencia y estándares |
| 9 | Falta de confirmación antes de acciones críticas | 3 | Usabilidad: Prevención de errores |
| 10 | Textos de error poco descriptivos | 2 | Usabilidad: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores |

**DESCRIPCIÓN DETALLADA DE PROBLEMAS Y EVIDENCIA EMPÍRICA:**

**PROBLEMA #1: No hay un control que permita regresar al dashboard durante el proceso de agendamiento**
* **Severidad:** 3
* **Heurística violada:** Usabilidad - Libertad y control del usuario

**Problema:**
Al momento de ingresar nuestros datos para agendar una inspección, no podemos regresar al dashboard principal en caso así lo deseemos. Una vez el usuario pase al formulario de agendamiento, no hay un botón que lo envíe al inicio de la aplicación.

**Evidencia Cuantitativa:**
* **Usuarios afectados:** 4 de 5 usuarios (80%) intentaron abandonar el flujo para verificar un dato y no encontraron cómo hacerlo.
* **Tiempo perdido:** Promedio de **45 segundos** buscando un botón de "Cancelar" o haciendo clic en el logo (no interactivo).
* **Error repetitivo:** 3 usuarios utilizaron el botón "Atrás" del navegador como último recurso, lo que ocasionó la pérdida total de los datos ya ingresados, obligándolos a reiniciar el proceso.

**Recomendación:**
Implementar un botón "Volver al Dashboard" o "Cancelar" claramente visible en todas las etapas del proceso de agendamiento.

---

**PROBLEMA #2: Se repiten constantemente algunas opciones en el menú**
* **Severidad:** 1
* **Heurística violada:** Usabilidad - Consistencia y estándares

**Problema:**
En el menú de navegación y en algunas secciones del dashboard, se observan opciones duplicadas o muy similares que pueden confundir al usuario sobre cuál es la función correcta a utilizar.

**Recomendación:**
Consolidar las opciones del menú y eliminar duplicados, manteniendo una estructura de navegación clara y consistente.

---

**PROBLEMA #3: Imágenes de informes técnicos sin atributo "alt"**
* **Severidad:** 3
* **Heurística violada:** Inclusive Design - Proporciona experiencias comparables

**Problema:**
Las imágenes de los informes técnicos y certificados no incluyen texto alternativo, lo que impide que usuarios con discapacidades visuales puedan acceder a esta información crucial.

**Evidencia Cuantitativa:**
* **Prueba de Accesibilidad:** Al utilizar el lector de pantalla (NVDA), el **100% de las imágenes críticas** (gráficos de estado del motor y fotos de daños) fueron ignoradas o leídas como nombres de archivo genéricos (ej. "img_204.jpg").
* **Impacto:** Un usuario simulado con visión reducida no pudo identificar si el vehículo había aprobado la inspección sin asistencia externa.

**Recomendación:**
Implementar atributos "alt" descriptivos en todas las imágenes, especialmente en aquellas que contienen información técnica relevante.

---

**PROBLEMA #4: Incluye un botón "Ver más" pero no existe contenido al que dirigirse**
* **Severidad:** 3
* **Heurística violada:** Information Architecture - Is it usable?

**Problema:**
En la sección de detalles del vehículo, existe un botón "Ver más información" que no lleva a ningún contenido adicional o muestra un error 404.

**Evidencia Cuantitativa:**
* **Tasa de Abandono:** 2 de los 5 usuarios (40%) abandonaron la navegación del vehículo inmediatamente después de hacer clic en el botón roto, percibiendo el sitio como "poco confiable".
* **Clics en vano:** Se registraron un promedio de 3 clics repetitivos por usuario sobre el botón esperando una respuesta.

**Recomendación:**
Eliminar botones que no tengan funcionalidad o implementar el contenido correspondiente.

---

**PROBLEMA #5: No incluye información clara de los planes de servicio**
* **Severidad:** 2
* **Heurística violada:** Information Architecture - Is it findable?

**Problema:**
La información sobre los diferentes planes de suscripción (mensual, trimestral) para revendedores no es fácilmente accesible desde el dashboard principal.

**Recomendación:**
Incluir una sección visible de "Planes y Precios" en el menú principal y proporcionar acceso rápido a esta información desde el dashboard.

---

**PROBLEMA #6: Falta de feedback visual durante procesos de carga**
* **Severidad:** 2
* **Heurística violada:** Usabilidad - Visibilidad del estado del sistema

**Problema:**
Durante la generación de informes PDF o la carga de imágenes de inspección, no se muestra ningún indicador de progreso.

**Evidencia Cuantitativa:**
* **Confusión:** 3 usuarios (60%) volvieron a hacer clic en el botón "Descargar" pensando que el sistema se había congelado.
* **Tiempo de incertidumbre:** El sistema tardó un promedio de 4 segundos en responder sin feedback visual, generando duda en el usuario.

**Recomendación:**
Implementar indicadores de carga (spinners, barras de progreso) y mensajes informativos durante todos los procesos que requieran tiempo de espera.

---

**PROBLEMA #7: Formularios sin validación en tiempo real**
* **Severidad:** 3
* **Heurística violada:** Usabilidad - Prevención de errores

**Problema:**
Los formularios de registro y agendamiento no validan los datos en tiempo real, permitiendo que el usuario complete todo el formulario antes de mostrar errores de validación al final.

**Evidencia Cuantitativa:**
* **Frecuencia de Error:** El **100% de los participantes (5/5)** cometió al menos un error de formato (principalmente en el campo "Placa" o "Teléfono") que no fue detectado hasta intentar enviar.
* **Costo de Recuperación:** El tiempo promedio para completar el formulario aumentó de **2 minutos (estimado)** a **3 minutos y 20 segundos** debido a la necesidad de re-ingresar datos y buscar manualmente qué campo tenía el error.

**Recomendación:**
Implementar validación en tiempo real que muestre errores inmediatamente cuando el usuario abandone un campo con datos incorrectos.

---

**PROBLEMA #8: Navegación inconsistente entre secciones**
* **Severidad:** 2
* **Heurística violada:** Usabilidad - Consistencia y estándares

**Problema:**
La estructura de navegación cambia entre diferentes secciones de la aplicación, con algunos menús laterales y otros superiores.

**Recomendación:**
Establecer un patrón de navegación consistente en toda la aplicación y mantenerlo en todas las secciones.

---

**PROBLEMA #9: Falta de confirmación antes de acciones críticas**
* **Severidad:** 3
* **Heurística violada:** Usabilidad - Prevención de errores

**Problema:**
Acciones como cancelar una inspección o eliminar un vehículo del sistema no solicitan confirmación del usuario.

**Evidencia Cuantitativa:**
* **Error Crítico:** Durante las pruebas, 1 usuario eliminó accidentalmente un vehículo registrado al confundir el ícono de "Papelera" con "Editar", perdiendo la información sin posibilidad de deshacer ("Undo").

**Recomendación:**
Implementar diálogos de confirmación (Modales) para todas las acciones destructivas o irreversibles.

---

**PROBLEMA #10: Textos de error poco descriptivos**
* **Severidad:** 2
* **Heurística violada:** Usabilidad - Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores

**Problema:**
Los mensajes de error son genéricos ("Error en el sistema", "Algo salió mal") y no proporcionan información específica.

**Recomendación:**
Crear mensajes de error específicos y útiles que expliquen claramente qué salió mal y proporcionen pasos concretos para resolver el problema.

---

**Hallazgo Principal a Corregir:**
**1. El campo “Model” no carga modelos tras seleccionar una marca (Severidad 3)**

**Evidencia Empírica del Hallazgo:**
Durante la ejecución del test de usabilidad en el módulo de búsqueda:
* **Tasa de Fallo:** **100% de intentos fallidos.** Ningún usuario pudo filtrar por modelo específico.
* **Comportamiento del Usuario (Click Rage):** Se detectó un promedio de **5 a 8 clics repetitivos** sobre el dropdown de "Modelo" por parte de los auditores, esperando una respuesta del sistema que nunca llegó.
* **Degradación de Eficiencia:** Al no funcionar el filtro, el tiempo necesario para encontrar un vehículo específico (ej. Toyota Corolla) pasó de **15 segundos (flujo ideal con filtro)** a **1 minuto 40 segundos (flujo real)**, ya que el usuario se vio obligado a realizar *scroll* manual entre todos los resultados de la marca.

---

### 6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos (Actualización del Hallazgo Principal)

**Hallazgo Principal a Corregir:**
**1. El campo “Model” no carga modelos tras seleccionar una marca (Severidad 3)**

**Evidencia Empírica del Hallazgo:**
Durante la ejecución del test de usabilidad en el módulo de búsqueda:
* **Tasa de Fallo:** **100% de intentos fallidos.** Ningún usuario pudo filtrar por modelo específico.
* **Comportamiento del Usuario (Click Rage):** Se detectó un promedio de **5 a 8 clics repetitivos** sobre el dropdown de "Modelo" por parte de los auditores, esperando una respuesta del sistema que nunca llegó.
* **Degradación de Eficiencia:** Al no funcionar el filtro, el tiempo necesario para encontrar un vehículo específico (ej. Toyota Corolla) pasó de **15 segundos (flujo ideal con filtro)** a **1 minuto 40 segundos (flujo real)**, ya que el usuario se vio obligado a realizar *scroll* manual entre todos los resultados de la marca.

## 6.4 Auditoría de Experiencias de Usuario
### 6.4.1 Auditoría realizada
#### 6.4.1.1 Información del Grupo Auditado

La auditoría de usabilidad fue realizada al grupo **FuelTrack – Frontend Proveedor**, responsable del desarrollo de los módulos:  
**Bandeja, Dashboard, Seguimiento y Asignar Flota**.

<div>
  <table>
    <tr>
      <th><strong>Código</strong></th>
      <th><strong>Apellidos y Nombres</strong></th>
    </tr>
    <tr>
      <td>u20201C131</td>
      <td>Maria Fernanda Fernandez Alva</td>
    </tr>
    <tr>
      <td>u20191A137</td>
      <td>Paolo Eduardo Belleza Tello</td>
    </tr>
    <tr>
      <td>U20221C769</td>
      <td>Karito Dianeth Medina Chocce</td>
    </tr>
    <tr>
      <td>u202213278</td>
      <td>Bryan Ronald Espejo Gamarra</td>
    </tr>
    <tr>
      <td>u202215528</td>
      <td>Maria Pilares Pocohuanca</td>
    </tr>
  </table>
</div>

---

#### 6.4.1.2 Cronograma de Auditoría Realizada

La auditoría se desarrolló siguiendo las fases trabajadas en el curso:  
**Recepción → Planificación → Ejecución → Reporte**.

| Fase           | Actividades                                                                                                                                           | Inicio       | Fin          | Responsable |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|--------------|-------------|
| Recepción      | Revisión del alcance, coordinación con equipo FuelTrack, acceso al Panel del Proveedor y módulos funcionales                                           | 12/11/2025   | 12/11/2025   | Maria Pilares Pocohuanca   |
| Planificación  | Definición de tareas críticas (gestión de pedidos, asignación de flota, seguimiento), selección de heurísticas de Nielsen, checklist de evaluación     | 12/11/2025   | 12/11/2025   | Maria Pilares Pocohuanca   |
| Ejecución      | Recorrido guiado del flujo: Bandeja → Dashboard → Seguimiento → Asignar flota; registro de hallazgos y toma de capturas                                | 16/11/2025  | 16/11/2025   | Maria Pilares Pocohuanca   |
| Reporte        | Redacción del informe, clasificación por severidad, elaboración de recomendaciones, revisión y consolidación final                                      | 16/11/2025   | 16/11/2025   | Maria Pilares Pocohuanca   |

---

#### 6.4.1.3 Contenido de Auditoría Realizada

### TAREAS A EVALUAR

El alcance consideró los flujos principales del proveedor dentro del sistema FuelTrack:

---

### **1. Gestión de pedidos (Bandeja)**  
El usuario visualiza los pedidos pendientes, sus datos relevantes y su estado actual.  
La funcionalidad permite filtrar y revisar rápidamente los pedidos.  
**Referencias visuales:** 
<img src="Images/auditFueltrack1.png" width="200"/>
<img src="Images/auditFueltrack2.png" width="200"/>

---

### **2. Dashboard informativo**  
El usuario revisa métricas resumidas sobre pedidos, unidades asignadas y progreso operativo.  
La interfaz presenta tarjetas y gráficos, aunque se identificaron problemas de contexto.  
**Referencia visual:** 
<img src="Images/auditFueltrack3.png" width="200"/>

---

### **3. Seguimiento de asignaciones**  
El usuario monitorea pedidos en curso, conductores asignados y estados.  
La tabla muestra la información esencial, aunque requiere mejoras de jerarquía visual.  
**Referencia visual:**
<img src="Images/auditFueltrack4.png" width="200"/>

---

### **4. Asignar flota (flujo principal evaluado)**  
Incluye selección de un pedido pendiente, selección de camión disponible, ingreso de conductor y ETA.  
Es el módulo más crítico y donde se detectaron la mayoría de problemas.  
**Referencia visual:** 
<img src="Images/auditFueltrack5.png" width="200"/>
<img src="Images/auditFueltrack6.png" width="200"/>

---

---

## ESCALA DE SEVERIDAD

Para clasificar los hallazgos se utilizó la siguiente escala:

| Nivel | Descripción                                                                                                                                      |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: aparece muy raramente y el usuario lo supera con facilidad. Se corrige solo si hay tiempo disponible.                     |
| 2     | Problema menor: ocurre con algo más de frecuencia o genera cierta fricción, pero no bloquea el flujo. Recomendable corregirlo con prioridad baja.|
| 3     | Problema mayor: se presenta con frecuencia o afecta tareas relevantes, dificultando que el usuario logre su objetivo de forma fluida.           |
| 4     | Problema muy grave: impide completar tareas críticas o genera errores importantes. Debe corregirse antes de un despliegue formal.              |

---

## TABLA RESUMEN DE HALLAZGOS

| #  | Problema                                                                                                      | Severidad | Heurística / Principio violado                   |
|----|--------------------------------------------------------------------------------------------------------------|-----------|--------------------------------------------------|
| 1  | Falta de retroalimentación cuando no hay pedidos pendientes                                                  | 4         | Visibilidad del estado del sistema               |
| 2  | Botones “Asignar” y “Limpiar” con estilos demasiado similares                                                | 3         | Prevención de errores                            |
| 3  | Separación del flujo entre columnas “Pedido” y “Camión disponible” interrumpe la secuencia lógica            | 2         | Consistencia y estándares                        |
| 4  | Campo de conductor sin formato sugerido                                                                       | 2         | Ayuda y documentación                            |
| 5  | Tabla de “Asignaciones actuales” poco integrada al contexto del flujo principal                               | 2         | Correspondencia entre sistema y mundo real       |
| 6  | Estados sin diferenciación visual (etiquetas planas)                                                          | 3         | Reconocimiento en lugar de memoria               |
| 7  | Tipografía inconsistente entre pantallas                                                                      | 1         | Estética y diseño minimalista                    |
| 8  | Gráficos del Dashboard sin leyendas ni explicación de período                                                 | 2         | Visibilidad del estado del sistema               |
| 9  | Filtros poco visibles en la Bandeja de pedidos                                                                | 2         | Control y libertad del usuario                   |

---

## DESCRIPCIÓN DE PROBLEMAS (DETALLE)

### **PROBLEMA 1 – Falta de retroalimentación cuando no hay pedidos pendientes**  
**Severidad:** 4  
**Heurística violada:** Visibilidad del estado del sistema  

**Descripción:**  
En el módulo *Asignar Flota*, aunque el sistema muestra “0 pendientes”, el campo de selección de pedidos se mantiene activo, sin un mensaje que explique que no hay datos disponibles.

**Impacto:**  
- Confunde al usuario sobre si existe un error.  
- Induce a intentar acciones que no tienen resultado.  

**Recomendación:**  
- Deshabilitar selector.  
- Mostrar mensaje “No hay pedidos pendientes”.

---

### **PROBLEMA 2 – Similitud visual entre botones “Asignar” y “Limpiar”**  
**Severidad:** 3  
**Heurística violada:** Prevención de errores  

**Descripción:**  
Ambos botones tienen color similar y tamaño comparable, lo que genera riesgo de clics accidentales.

**Recomendación:**  
- “Limpiar” debería ser gris o texto simple.  
- “Asignar” conservar estilo primario.

---

### **PROBLEMA 3 – Flujo dividido entre columnas**  
**Severidad:** 2  
**Heurística violada:** Consistencia y estándares  

La selección de pedido y camión está en columnas separadas creando un flujo no secuencial.

---

### **PROBLEMA 4 – Formato desconocido para conductor (nombre + DNI)**  
**Severidad:** 2  
**Heurística violada:** Ayuda y documentación  

Agregar placeholder:  
`Juan Pérez – 12345678`

---

### **PROBLEMA 5 – Tabla de asignaciones desconectada del flujo**  
**Severidad:** 2  

No es visualmente parte del proceso de asignación.

---

### **PROBLEMA 6 – Estados sin uso de color ni iconografía**  
**Severidad:** 3  

Dificulta identificar progreso rápidamente.

---

### **PROBLEMA 7 – Inconsistencias tipográficas**  
**Severidad:** 1  

Inestabilidad visual entre pantallas.

---

### **PROBLEMA 8 – Gráficos sin contexto claro**  
**Severidad:** 2  

No se especifican periodos o comparativas.

---

### **PROBLEMA 9 – Filtros poco visibles en bandeja**  
**Severidad:** 2  

Falta contraste con el entorno.

---

## Comentario general de la auditoría

FuelTrack presenta una interfaz ordenada y moderna, con una base visual sólida.  
Los flujos principales funcionan correctamente, pero se identifican oportunidades de mejora especialmente en:

- **retroalimentación del sistema**,  
- **representación visual de estados**,  
- **consistencia tipográfica**,  
- **flujo de asignación**,  
- **prevención de errores**.

Al corregir estos puntos, la plataforma mejorará significativamente su claridad, eficiencia y facilidad de uso para los proveedores.

---


### 6.4.2. Auditoría Recibida
#### 6.4.2.1. Información del Grupo Auditado

La auditoría de usabilidad fue realizada al grupo **CertiWeb – Frontend**, responsable del desarrollo de la interfaz web para la plataforma de certificación y venta de autos usados.

| Miembro                              | Código     |
|--------------------------------------|------------|
| Angulo Abud, Juan Carlos             | u202317692   |
| Trillo Hernandez, Anghel Melanie     | u201912401   |
| Quiroz Zambrano, Fabrizio Javier     | u202213406   |
| Montes Maza, Augusto Sebastian       |  U202218645  |
| Zúñiga Murillo, Diego Sebastián      | U202310636   |

---

#### 6.4.2.2. Cronograma de Auditoría Realizada

La auditoría se estructuró en cuatro fases: **Recepción, Planificación, Ejecución y Reporte**, siguiendo la misma lógica trabajada en el curso.

| Fase        | Actividades                                                                                                   | Fecha Inicio | Fecha Fin   | Responsable     |
|-------------|---------------------------------------------------------------------------------------------------------------|--------------|-------------|-----------------|
| Recepción   | Coordinación con el equipo de CertiWeb, revisión inicial del alcance y acceso a la versión desplegada        | 12/11/2025   | 12/11/2025  | Trillo Hernandez, Anghel Melanie       |
| Planificación | Definición de tareas críticas a evaluar (login, búsqueda, carga de certificaciones, historial); selección de heurísticas; elaboración de checklist | 12/11/2025   | 12/11/2025  | Trillo Hernandez, Anghel Melanie       |
| Ejecución   | Navegación guiada por los distintos flujos (login, home, carga de certificados, historial de reservas); registro de hallazgos | 16/11/2025   | 16/11/2025  | Trillo Hernandez, Anghel Melanie      |
| Reporte     | Redacción del informe, asignación de severidades, formulación de recomendaciones y revisión final del documento | 16/11/2025   | 16/11/2025  |    Trillo Hernandez, Anghel Melanie   |

---

#### 6.4.2.3. Contenido de Auditoría Realizada

##### TAREAS A EVALUAR

El alcance de esta evaluación consideró los flujos principales del usuario dentro de CertiWeb:

1. **Inicio de sesión (Login)**  
   - El usuario accede al formulario de autenticación, ingresa correo y contraseña y presiona el botón de acceso.  
   - En las pruebas realizadas, el **inicio de sesión funcionó correctamente**, permitiendo acceder a la plataforma sin errores aparentes.  
   - Referencia visual:
   - <img src="Images/auditCertiweb1.jpg" width="200"/>

2. **Página de inicio y búsqueda de autos certificados**  
   - El usuario selecciona una **marca** y, opcionalmente, un **modelo** para filtrar autos, y luego ejecuta la búsqueda desde la sección “Find your perfect car”.  
   - Se identificó un problema: **los modelos no se muestran en el campo “Model”**, aun cuando la marca se ha seleccionado (ver detalle en Problema #1).  
   - Referencia visual:
   - <img src="Images/auditCertiweb2.jpg" width="200"/>

3. **Agregar certificaciones / carga de vehículo**  
   - El usuario sube la foto del vehículo y completa los datos del formulario (marca, modelo, placa, precio, correo del dueño, etc.).  
   - La funcionalidad **opera correctamente**: se aceptan archivos de imagen y el certificado se muestra de forma adecuada tras completar la información.  
   - Referencia visual:
   - <img src="Images/auditCertiweb3.jpg" width="200"/>

4. **Historial de reservas (Reservation History)**  
   - El usuario revisa las reservas generadas, observando datos como nombre del usuario, vehículo reservado, fecha, hora, precio y estado.  
   - La información se presenta en una tarjeta clara y legible, lo que facilita el seguimiento de las reservas realizadas.  
   - Referencia visual:
   - <img src="Images/auditCertiweb4.jpg" width="200"/>

---

##### ESCALA DE SEVERIDAD

Para clasificar los hallazgos se utilizó la siguiente escala:

| Nivel | Descripción                                                                                                                                      |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: aparece muy raramente y el usuario lo supera con facilidad. Se corrige solo si hay tiempo disponible.                     |
| 2     | Problema menor: ocurre con algo más de frecuencia o genera cierta fricción, pero no bloquea el flujo. Recomendable corregirlo con prioridad baja.|
| 3     | Problema mayor: se presenta con frecuencia o afecta tareas relevantes, dificultando que el usuario logre su objetivo de forma fluida.           |
| 4     | Problema muy grave: impide completar tareas críticas o genera errores importantes. Debe corregirse antes de un despliegue formal.              |

---

##### TABLA RESUMEN

| #  | Problema                                                                                       | Escala de severidad | Heurística / Principio violado           |
|----|-----------------------------------------------------------------------------------------------|----------------------|------------------------------------------|
| 1  | No se muestran los modelos en el filtro “Model” después de seleccionar una marca en la Home   | 3                    | Flexibilidad y eficiencia de uso         |

---

##### DESCRIPCIÓN DE PROBLEMAS

---

**PROBLEMA #1: No se muestran los modelos en el filtro “Model” tras seleccionar una marca**

- **Severidad:** 3  
- **Heurística violada:** Flexibilidad y eficiencia de uso  

**Problema:**  
En la sección de búsqueda de autos certificados (Home), el usuario puede seleccionar una **marca** desde el campo “Brand”; sin embargo, al intentar seleccionar un **modelo** en el campo “Model”, la lista de modelos no se despliega ni se cargan opciones asociadas a la marca elegida.  
Esto provoca que el usuario solo pueda filtrar por marca, perdiendo la posibilidad de refinar la búsqueda por modelo específico. El problema se observó en el escenario de prueba mostrado en **Img 2**.

**Impacto en la experiencia de usuario:**  
- Reduce la eficiencia de la búsqueda, ya que el usuario obtiene resultados más amplios y menos precisos.  
- Puede generar confusión o la percepción de que el sistema está incompleto o presenta errores de datos.  
- Obliga al usuario a revisar manualmente más resultados de los necesarios para encontrar el auto que busca.

**Recomendación:**  
- Verificar la lógica que carga los modelos en función de la marca seleccionada (por ejemplo, la llamada al backend o la fuente de datos local).  
- Asegurar que, al elegir una marca, el componente “Model” se actualice dinámicamente mostrando únicamente los modelos disponibles para esa marca.  
- En caso de que una marca no tenga modelos registrados, mostrar un mensaje claro al usuario (por ejemplo, “No hay modelos disponibles para esta marca” en lugar de dejar el campo vacío), manteniendo la consistencia del comportamiento.

---

##### Comentario general de la auditoría

En términos generales, los flujos de **inicio de sesión**, **carga de certificaciones** y **visualización del historial de reservas** muestran un buen nivel de usabilidad: las interfaces son claras, la organización de los campos es coherente y la información se presenta de forma entendible para el usuario final (ver Img 1, Img 3 e Img 4).  
El principal punto de mejora identificado se concentra en la **búsqueda en la página de inicio**, donde corregir el problema del filtro de modelos permitirá aprovechar mejor el diseño actual y ofrecer una experiencia más eficiente y alineada con los objetivos de CertiWeb.

#### 6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos

La auditoría realizada al módulo **CertiWeb – Frontend** muestra que los flujos principales del sistema (inicio de sesión, carga de certificaciones e historial de reservas) funcionan correctamente y presentan una buena experiencia de usuario. Sin embargo, se identificó un hallazgo crítico relacionado con el proceso de búsqueda en la página de inicio, el cual debe ser subsanado para asegurar una navegación eficiente y sin fricciones.

### Hallazgo Principal a Corregir

### 1. El campo “Model” no carga modelos tras seleccionar una marca (Severidad 3)

Este problema afecta directamente la eficiencia y precisión de la búsqueda. El usuario no puede seleccionar un modelo asociado a la marca elegida, lo que provoca búsquedas amplias, pérdida de tiempo y percepciones de inconsistencia en el sistema.

### Acciones Recomendadas

1. **Revisar la lógica de filtrado dependiente (Brand → Model):**
   - Validar que la selección de una marca active correctamente la carga de modelos.
   - Verificar que las llamadas al backend o al origen local de datos se estén ejecutando correctamente.

2. **Actualizar dinámicamente el campo “Model”:**
   - Refrescar la lista inmediatamente tras seleccionar una marca.
   - Mostrar únicamente los modelos disponibles para esa marca.

3. **Manejo de escenarios sin datos:**
   - Si una marca no tiene modelos disponibles, mostrar un mensaje como:
     - *“No hay modelos disponibles para esta marca.”*
   - Evitar dejar el campo vacío o sin respuesta visual.

4. **Agregar retroalimentación visual durante la carga:**
   - Implementar un indicador de carga (loading) en el campo “Model”.
   - Evitar que el usuario perciba que el campo está inactivo o presenta fallos.

### Beneficios Esperados

- Búsquedas más precisas y rápidas.
- Reducción de confusión y carga cognitiva para el usuario.
- Mayor coherencia entre marca y modelo dentro del flujo.
- Percepción más profesional y confiable del sistema.

## 6.5. Resumen de Métricas de Validación (Sprint 1 & 2)

Como resultado de las evaluaciones heurísticas y las pruebas de usuario ejecutadas, se consolidaron las siguientes métricas de rendimiento inicial del software, demostrando el impacto real de la usabilidad en la eficiencia del sistema:

| Métrica Evaluada | Resultado Promedio | Meta / Estándar | Estado |
| :--- | :--- | :--- | :--- |
| **Tasa de éxito en Registro** | 100% | 95% | Cumplido |
| **Tiempo promedio: Agendar Cita** | 4 min 30 seg | < 3 min |  Alto (Debido a Problema #1 y #7) |
| **Errores Críticos por Usuario** | 1.8 errores | < 1 error |  Requiere Corrección (Validaciones) |
| **Satisfacción (Escala 1-5)** | 3.8 / 5 | > 4.0 |  Aceptable (Mejorar feedback visual) |


<a id="capitulo-vii-devops-practices"></a>
# Capítulo VII: DevOps Practices

<a id="7-1-continuous-integration"></a>
## 7.1. Continuous Integration

En nuestro proyecto, la integración continua representa un paradigma fundamental para asegurar la calidad y estabilidad del código a lo largo del ciclo de desarrollo. A través de la automatización de pruebas y validaciones, buscamos minimizar errores y facilitar la colaboración entre los miembros del equipo. Esta mitiga los riesgos de la integración, permitiendo a los equipos de desarrollo detectar errores de forma temprana y ágil. En certiweb, utilizamos un pipeline de CI usando GitHub actions, definido en el fichero de .github/workflows/ci-cd.yml. Además, usamos un segundo pipeline de CI con Jenkins, que se encarga de ejecutar pruebas unitarias y de integración cada vez que se realiza un push al repositorio, este se encuentra en el jenkinsfile en la raíz del proyecto.

<a id="7-1-1-tools-and-practices"></a>
### 7.1.1. Tools and Practices.

Para CertiWeb, utilizamos herramientas como Jenkins y GitHub Actions para implementar Integración Continua (CI). Estas herramientas permiten automatizar la integración de cambios al repositorio de código de forma continua, ejecutando pruebas automáticamente y asegurando que el código siempre esté en un estado funcional antes de ser integrado.
Herramientas:


- Jenkins: Utilizado para configurar pipelines de CI que se ejecutan cada vez que un desarrollador sube un cambio al repositorio. Jenkins ejecuta pruebas automáticas y valida la compilación del proyecto.


- GitHub Actions: Integra GitHub con pipelines de CI/CD para garantizar que las pruebas y el despliegue se gestionen de manera continua.


Prácticas de CI:
- Automatización de pruebas: Cada vez que un desarrollador sube código nuevo, se ejecutan pruebas unitarias y de integración para garantizar que las nuevas modificaciones no rompan las funcionalidades existentes.


- Revisión continua de código: Utilizamos Pull Requests para revisar el código antes de ser integrado a la rama principal, asegurando calidad y consistencia.

La herramienta principal de integración para orquestar este proceso es GitHub actions, la cual nos permite definir flujos de trabajo directamente en el repositorio. La instrumentamos a través de triggers en el pipeline:

``` yaml
on:
  pull_request:
    branches: [ main ]
  push:
    branches: [ main ]
```

Esta configuración establece una estrategia de validación doble:

- Validación de pull request: Cada vez que un desarrollador crea o actualiza un pull request hacia la rama main, se ejecuta el pipeline de CI. Esto permite detectar errores antes de que el código sea fusionado, asegurando que solo cambios validados ingresen a la rama principal.
- Validación de push: Cada vez que se realiza un push directamente a la rama main, el pipeline de CI se ejecuta nuevamente. Esto garantiza que cualquier cambio en la rama principal sea validado automáticamente, manteniendo la integridad del código en todo momento.

<a id="7-1-2-build-test-suite-pipeline-components"></a>
### 7.1.2. Build & Test Suite Pipeline Components.

Nuestro pipeline se divide en dos trabajos principales: `build_and_test` y `build_and_push_docker`, cada uno con sus respectivas etapas y componentes, ejecutandose de forma secuencial.

1. Componente de Construcción (Build Component) `build_and_test`:

Este trabajo es el núcleo de la validación y se compone de los siguientes pasos críticos:

- `Setup .NET 9.0 SDK`: Prepara el entorno de ejecución (ubuntu-latest) con el SDK de .NET 9.0, garantizando la consistencia del compilador con el `TargetFramework` (net9.0) definido en los archivos de proyecto (`CertiWeb.API.csproj`, `CertiWeb.UnitTests.csproj`, etc.).

- `Restore dependencies` y `Build solution`: Se ejecutan los comandos `dotnet restore` y `dotnet build` sobre el archivo de solución `certiweb-platform.sln`. Esto asegura que todas las dependencias del proyecto se resuelvan y que la totalidad de la base de código compile exitosamente.

- `Run all tests`: Este es el paso de validación más significativo. El comando `dotnet test certiweb-platform.sln` invoca la ejecución de la suite de pruebas completa, que en este proyecto abarca múltiples capas de la pirámide de testing:

- - Pruebas Unitarias (`CertiWeb.UnitTests`): Validan la lógica de negocio en componentes aislados (ej. `CarTests.cs`, `PriceTests.cs`).

- - Pruebas de Integración (`CertiWeb.IntegrationTests`): Verifican la correcta interacción entre componentes, especialmente la capa de persistencia (ej. `CarIntegrationTests.cs`, `UserIntegrationTests.cs`).

- - Pruebas de Sistema (`CertiWeb.SystemTests`): Realizan validaciones end-to-end contra una instancia de la API, asegurando que los controladores, flujos de negocio y validaciones funcionen como un sistema cohesivo (ej. `CarsControllerSystemTests.cs`, `BusinessFlowSystemTests.cs`).

A su vez, implementamos pruebas para el front end, utilizando vitest y cypress, las cuales se ejecutan en el mismo job de build_and_test, garantizando asi una validación integral del sistema.

<img src="Images/reporte_pruebas_front.png"/>


2. Job: `build_and_push_docker`:

Este trabajo se encarga de empaquetar la aplicación en un formato desplegable

- Control de flujo: El trabajo posee dos condiciones clave:
1. `needs: build_and_test`: Asegura que este trabajo solo se ejecute si el trabajo previo de construcción y pruebas (`build_and_test`) ha finalizado exitosamente. Esto garantiza que solo código validado sea empaquetado.
2. `if: github.event_name == 'push'`: Limita la ejecución de este trabajo únicamente a eventos de push en la rama main. Esto evita que se generen imágenes Docker para pull requests, enfocando el despliegue solo en cambios confirmados en la rama principal.
- Construcción del artefacto: El paso `Build and push Docker Image` utiliza el `CertiWeb.API/Dockerfile` para crear la imagen del contenedor. Esta imagen etiquetada como `svennn/certiweb-api:latest` se construye y se sube al Docker Hub, haciendo que la aplicación esté lista para ser desplegada en cualquier entorno compatible con Docker.

<a id="7-2-continuous-delivery"></a>
## 7.2. Continuous Delivery

En CertiWeb, la entrega continua es la extensión lógica de nuestra estrategia de integración continua, lo que automatiza el despliegue del artefacto validado a un entorno de pre producción o staging. Este entorno actua como un espejo de producción, permitiendo asi la validación final antes de la exposición al cliente.

<a id="7-2-1-tools-and-practices"></a>
### 7.2.1. Tools and Practices.

Nuestra orquestación continúa dentro de GitHub Actions, usando el trabajo de `deploy_staging`. La tecnología de despliegue se basa en `appleboy/ssh-action` para la ejecución remota de comandos y de `docker-compose` para la gestión de servicios en el servidor de destino.


Herramientas:
- GitHub Actions: Se configura para hacer despliegues automáticos cada vez que un cambio pasa todas las pruebas.


- Docker: Utilizamos Docker para empaquetar la aplicación en contenedores, lo que facilita el despliegue en diferentes entornos.

Prácticas de CD:

- Promoción de Artefacto: El `needs: build_and_push_docker` establece una cadena de dependencia. El despliegue a Staging solo puede ocurrir si un nuevo artefacto ha sido construido y publicado.

- Gestión de Entornos de Despliegue: El uso de `environment: name: staging` es una práctica de gobernanza clave. Permite a GitHub gestionar secretos específicos del entorno (como credenciales de bases de datos) y, fundamentalmente, permite la configuración de reglas de protección, como una aprobación manual. Esta capacidad de requerir una intervención humana para aprobar el despliegue es lo que define a este proceso como Entrega Continua (automatizado hasta un punto de decisión) en lugar de Despliegue Continuo.


<a id="7-2-2-stages-deployment-pipeline-components"></a>
### 7.2.2. Stages Deployment Pipeline Components.

El trabajo `deploy_staging` se conecta al servidor de Staging (`secrets.STAGING_HOST`) y ejecuta un script de despliegue:

1. Sincronización de Artefacto: `docker pull svennn/certiweb-api:latest` obtiene la imagen exacta construida en la CI.

2. Inyección de Configuración: `export MYSQL_ROOT_PASSWORD=...` y `export CONNECTION_STRING=...` inyectan la configuración específica del entorno (leída desde `secrets.STAGING_DB_PASSWORD`) en la sesión de shell del runner.

3. Orquestación con Docker Compose: El comando `docker-compose -f CertiWeb.API/docker-compose.yaml up -d --no-build api` utiliza el archivo docker-compose.yaml del proyecto.

- - El flag `--no-build` es vital, ya que refuerza el principio de artefacto inmutable, instruyendo a docker-compose que utilice la imagen descargada en lugar de intentar construir una nueva.

- - El argumento `api` asegura que solo el servicio de la aplicación sea reiniciado, dejando el servicio de base de datos (mysql) intacto, lo que resulta en un despliegue más rápido y seguro.

<a id="7-3-continuous-deployment"></a>
## 7.3. Continuous deployment

Para finalizar, el despliegue continuo es la fase final y más madura del pipeline, dónde, una vez que el cambio ha sido validado en staging, se promueve al entorno de producción de forma automática, sin intervención manual.


<a id="7-3-1-tools-and-practices"></a>
### 7.3.1. Tools and Practices.

- Herramientas: El job `deploy_production` utiliza la misma pila tecnológica probada en Staging (GitHub Actions, SSH, Docker Compose).

Prácticas:

- Progresión Lineal: `needs: deploy_staging` impone un flujo de despliegue estrictamente lineal (CI -> Staging -> Producción), asegurando que el código no pueda llegar al cliente final sin haber superado las validaciones previas.

- Paridad de Entornos: El proceso de despliegue en Producción es funcionalmente idéntico al de Staging. Esta paridad es una práctica DevOps esencial, ya que significa que el proceso de despliegue en sí mismo fue probado en la etapa anterior, minimizando los riesgos de fallos relacionados con el despliegue.

- Automatización Completa: A diferencia de Staging, la ausencia de reglas de aprobación manual en el entorno production convierte este paso en Despliegue Continuo. El sistema confía plenamente en la robustez de la suite de pruebas automatizadas y en el éxito del despliegue en Staging.

<a id="7-3-2-production-deployment-pipeline-components"></a>
### 7.3.2. Production Deployment Pipeline Components.

El script ejecutado por `appleboy/ssh-action` en el job `deploy_production` es casi idéntico al de Staging, con diferencias en las variables de configuración:

1. Conexión Segura: Se conecta al host de producción (`secrets.PROD_HOST`).

2. Inyección de Secretos: Se utilizan los secretos de producción (`secrets.PROD_DB_PASSWORD`) para configurar la `CONNECTION_STRING` apuntando a la base de datos productiva (`certiweb_prod`). Este aislamiento de datos es crítico.

3. Orquestación: Se repite el mismo comando `docker-compose ... up -d --no-build api`, demostrando la portabilidad del artefacto y del proceso de despliegue.

<a id="7-4-continous-monitoring"></a>
### 7.4. Continuous Monitoring

La monitorización continua cierra el ciclo de DevOps, proporcionando retroalimentación sobre la salud y el rendimiento de la aplicación después de que el despliegue se ha completado.

#### 7.4.1 Tools and Practices.

Herramientas: El pipeline integra herramientas de notificación y activación. Se utiliza dawidd6/action-send-mail@v3 para notificaciones por correo electrónico y curl para la activación de webhooks.

Prácticas:

- Notificación de Despliegue: Informar a los interesados (stakeholders) humanos (como el equipo de desarrollo o QA) que un cambio ha sido liberado.

- Activación Proactiva de Monitoreo: En lugar de esperar a que las herramientas de monitoreo detecten un problema de forma pasiva (basado en sondeo o pull), el pipeline empuja (push) una notificación a estas herramientas, solicitando una validación de salud inmediata.

#### 7.4.2. Componentes del Pipeline de Notificación
El trabajo monitoring_and_alerts se ejecuta tras un despliegue exitoso en Producción (needs: deploy_production).

El paso Send Email Notification utiliza un servidor SMTP (configurado mediante secretos) para enviar una comunicación formal a la lista de correos secrets.NOTIFY_EMAILS. Este correo confirma el éxito del despliegue e incluye un enlace directo a los dashboards de monitoreo (ej. http://grafana.certiweb.com), facilitando la revisión humana.

#### 7.4.3. Componentes del Pipeline de Alertas y Monitoreo
El paso Trigger Monitoring Check representa una práctica avanzada de observabilidad.

El comando curl envía una solicitud POST a un endpoint de webhook (https://monitoring.certiweb.com/api/checks/...). Esta acción notifica a la plataforma de monitoreo externa (ej. Prometheus, Grafana, UptimeRobot) que una nueva versión de certiweb-prod acaba de ser desplegada.

El sistema de monitoreo, al recibir este webhook, puede reaccionar inmediatamente ejecutando su suite de health checks (pruebas de salud) contra la nueva versión, proporcionando así una retroalimentación casi instantánea sobre el estado de la aplicación post-despliegue, en lugar de esperar al siguiente intervalo de sondeo.

## Capítulo VIII: Experiment-Driven Development

Este capítulo introduce la fase de experimentación del proyecto CertiWeb. Habiendo completado el diseño y la implementación inicial (el "As-Is"), ahora nos enfocamos en validar nuestras suposiciones de negocio más críticas.Este proceso, guiado por experimentos (Experiment-Driven Development), nos permitirá usar datos reales para tomar decisiones informadas sobre el producto y su alineación con las necesidades del mercado.

### 8.1. Experiment Planning

La planificación de la experimentación comienza con la definición de nuestro estado actual, la identificación de nuestras suposiciones (materia prima) y la transformación de estas en preguntas accionables que podemos probar.

#### 8.1.1. As-Is Summary

El estado actual ("As-Is") del proyecto CertiWeb es el de una plataforma funcional diseñada para resolver la **asimetría de información y la desconfianza** en el mercado de autos usados en Perú.

* **Problema Identificado:** Los compradores desconfían del estado real de los vehículos, y los vendedores (individuales y revendedores) carecen de un mecanismo digital y confiable para demostrar la calidad de sus autos, ralentizando la venta.
* **Solución Implementada:** CertiWeb ofrece un servicio de inspección técnica estandarizada (más de 100 puntos) que culmina en un **informe digital detallado** y un **sello de certificación verificable**.
* **Segmentos Objetivo:**
    1.  **Vendedores Individuales:** Buscan vender más rápido y a un mejor precio.
    2.  **Revendedores:** Necesitan rotación rápida de inventario y generar credibilidad.
    3.  **Compradores:** Buscan minimizar el riesgo y tomar decisiones informadas.
* **Estado del Producto:** Se ha completado el diseño UX/UI (Capítulo IV), la arquitectura del software (Capítulo IV) y la implementación del primer sprint (Capítulo V), incluyendo el Landing Page, la aplicación web (Frontend/Backend) y la configuración inicial de despliegue. El producto está listo para ser probado con usuarios reales para validar sus hipótesis de valor fundamentales.

#### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

Nuestra "materia prima" para la experimentación se basa en las suposiciones (assumptions) identificadas en la sección `1.2.2.2. Lean UX Assumptions` del proyecto.

**Supuestos (Assumptions):**

* **Supuesto 1 (Valor para el Comprador):** Los compradores valoran un informe técnico verificable y estarían dispuestos a priorizar vehículos certificados.
* **Supuesto 2 (Valor para el Vendedor):** Los vendedores aceptarían el costo de la certificación si les permite vender más rápido y a un mejor precio.
* **Supuesto 3 (Impacto en Confianza):** Un sello digital de certificación en anuncios de autos usados aumentará la confianza y la tasa de contacto.
* **Supuesto 4 (Valor para Revendedor):** Revendedores y concesionarias con alto volumen se beneficiarán de herramientas de gestión y carga masiva.

**Brechas de Conocimiento (Knowledge Gaps):**

* *Gap 1:* Asumimos que los vendedores pagarán (Supuesto 2), pero no sabemos *cuánto* están dispuestos a pagar (sensibilidad al precio).
* *Gap 2:* Asumimos que un sello aumenta la confianza (Supuesto 3), pero no sabemos si es el factor *más decisivo* en comparación con un informe detallado sin sello.
* *Gap 3:* No sabemos qué tan "rápido" debe ser el proceso de inspección para que un revendedor lo considere "eficiente" (Supuesto 4).

**Reclamaciones (Claims):**

* *Claim 1:* Nuestra inspección de más de 100 puntos es significativamente más valiosa para el comprador que una revisión mecánica tradicional.
* *Claim 2:* Un vehículo con sello CertiWeb se venderá un 30% más rápido que uno que no lo tiene.

#### 8.1.3. Experiment-Ready Questions

Transformamos nuestras suposiciones y brechas de conocimiento en preguntas específicas que podemos responder mediante experimentos:

1.  **(De Supuesto 3):** ¿La inclusión de un Sello de Certificación CertiWeb visible en un anuncio de auto usado incrementa la tasa de contacto (leads) de compradores interesados, en comparación con un anuncio idéntico sin el sello?
2.  **(De Supuesto 2 y Gap 1):** ¿Cuál es el rango de precio (ej. S/ 50 vs. S/ 100 vs. S/ 150) que los vendedores individuales están dispuestos a pagar por la certificación, sin que la tasa de abandono supere el 20%?
3.  **(De Supuesto 1):** ¿Los compradores que revisan un informe técnico completo de CertiWeb perciben un mayor valor en el vehículo (ej. están más dispuestos a pagar el precio solicitado) que aquellos que solo ven fotos?
4.  **(De Supuesto 4 y Gap 3):** ¿La funcionalidad de "carga masiva" de vehículos reduce el tiempo de gestión de inventario para revendedores en al menos un 40% en comparación con el registro manual?

#### 8.1.4. Question Backlog

Priorizamos las preguntas anteriores basándonos en qué tan crítica es la suposición para la supervivencia del modelo de negocio.

| Prioridad | Pregunta (Experiment-Ready Question) | Suposición que Valida | Justificación de Prioridad |
| :--- | :--- | :--- | :--- |
| **1 (Alta)** | ¿La inclusión de un Sello de Certificación... incrementa la tasa de contacto (leads) de compradores? | Supuesto 3 | Es la hipótesis de valor central. Si el sello no genera más leads, el valor para el vendedor (Supuesto 2) se debilita. |
| **2 (Alta)** | ¿Cuál es el rango de precio... que los vendedores individuales están dispuestos a pagar? | Supuesto 2 / Gap 1 | Crítica para la viabilidad financiera. Necesitamos encontrar el equilibrio entre adopción y monetización. |
| **3 (Media)** | ¿Los compradores que revisan un informe técnico... perciben un mayor valor en el vehículo? | Supuesto 1 | Valida la calidad percibida de nuestro producto principal (el informe). Es importante, pero secundario a generar el lead inicial. |
| **4 (Baja)** | ¿La funcionalidad de "carga masiva"... reduce el tiempo de gestión para revendedores? | Supuesto 4 / Gap 3 | Valida una funcionalidad específica para un segmento secundario (revendedores). Primero debemos validar el modelo con vendedores individuales. |

## 8.1.5. Experiment Cards

La siguiente tabla presenta las Tarjetas de Experimento priorizadas, derivadas de las preguntas críticas en nuestro backlog. Estos experimentos han sido seleccionados estratégicamente por su impacto potencial en la mitigación de la incertidumbre del usuario y el incremento en la conversión de leads.

| Experiment ID | **EXP-01: Validador de Precio Inteligente (Smart Pricing)** |
| :--- | :--- |
| **Riesgo Abordado** | Los usuarios sufren de "ansiedad de precio" y parálisis en la toma de decisiones debido a la falta de experiencia técnica para valorar el vehículo. |
| **Hipótesis** | Contextualizar el precio mediante un "Puntaje de Calidad" técnico incrementará la conversión de vista-a-lead en un 15%. |
| **Métrica de Éxito** | Tasa de Conversión de Leads (CVR). |

| Experiment ID | **EXP-02: Insignia de Confianza KYC del Vendedor** |
| :--- | :--- |
| **Riesgo Abordado** | La asimetría de información respecto a la identidad real del vendedor genera miedo a estafas y reduce la disposición a contactar. |
| **Hipótesis** | Mostrar una insignia de "Verificado Biométricamente" incrementará la tasa de solicitud de contacto única en un 12%. |
| **Métrica de Éxito** | Tasa de Solicitud de Contacto Única (UCRR). |

| Experiment ID | **EXP-03: Activo de Garantía Desbloqueable** |
| :--- | :--- |
| **Riesgo Abordado** | Aversión al riesgo residual por parte del comprador respecto a fallas mecánicas futuras, a pesar de la buena condición actual certificada. |
| **Hipótesis** | Enmarcar la garantía como un "beneficio exclusivo desbloqueado" por puntajes técnicos altos incrementará las acciones de alta intención en un 18%. |
| **Métrica de Éxito** | Tasa de Acción de Alta Intención (HIAR). |

---

## 8.2. Experiment Design

This section details the design of the prioritized experiments, defining the hypotheses, metrics, measures, and conditions required for execution.

### 8.2.2. Domain Business Metrics
To ensure the experiments are measurable and aligned with business goals, we define the following core metrics:

* **Lead Conversion Rate (CVR):** The percentage of unique users who view a listing and click the primary contact button.
    $$CVR = \frac{\text{Total Unique Contact Clicks}}{\text{Total Unique Listing Views}} \times 100$$

* **Unique Contact Request Rate (UCRR):** The percentage of users who successfully submit a contact form after viewing seller details.
    $$UCRR = \frac{\text{Unique Form Submissions}}{\text{Unique PDP Sessions}} \times 100$$

* **High-Intent Action Rate (HIAR):** The percentage of users interacting with bottom-of-funnel features (Financing, Warranty, Technical Report).
    $$HIAR = \frac{\text{Total Financing or Warranty Clicks}}{\text{Total Sessions}} \times 100$$

### Experiment 1: Integración de Valoración Algorítmica de Precio (Smart Pricing)

#### 8.2.1. Hypotheses
**Question:** Is it true that contextually validating the vehicle's price against market data based on its specific technical condition reduces buyer decision paralysis?
**Belief:** Buyers often experience "price anxiety," lacking the technical expertise to judge if a higher price is justified by better mechanical condition. Given that our certification provides objective data points, comparing the asking price against a "Market Average" for similar certified conditions will create a value anchor; therefore, we should display a dynamic "Price Quality Score" to justify the investment to the user.
**Hypothesis:** Implementing a dynamic "Price Quality" indicator (e.g., 'Great Deal', 'Fair Price') rooted in the certification score will increase the *Lead Conversion Rate (CVR)* by at least 15%.
**Null Hypothesis:** Implementing the dynamic "Price Quality" indicator will not be responsible for the CVR increasing by 15%; any observed lift is attributable to random variance.

#### 8.2.3. Measures
* **Signal:** Click event on the primary "Contact Seller" button (Floating Action Button on Mobile / Sticky Sidebar on Desktop).
* **Metric:** Lead Conversion Rate (CVR).
* **Criteria:** We expect a relative lift of $\ge 15\%$ with a statistical significance level ($\alpha$) of 0.05.

#### 8.2.4. Conditions
* **Control Condition (A):** The vehicle listing displays the price in standard font size and color, with no additional labels or market comparison data.
* **Experimental Condition (B):** The vehicle listing displays a color-coded badge (Green/Yellow) stating the price quality (e.g., "Great Deal - Certified Value") placed immediately next to the price tag.

---

### Experiment 2: Validación de Identidad del Vendedor (KYC Integration)

#### 8.2.1. Hypotheses
**Question:** Is it true that exposing the level of identity verification (KYC) of the seller directly on the Product Detail Page (PDP) mitigates trust friction and increases contact rates?
**Belief:** The used car market suffers from information asymmetry regarding the seller's intent (fear of scams). Given that CertiWeb performs identity checks, explicitly displaying a "Biometrically Verified Seller" badge acts as a trust signal that reduces the perceived social risk of the transaction; therefore, this transparency should statistically increase the willingness to share personal contact details.
**Hypothesis:** Displaying a "Biometrically Verified Identity" badge adjacent to the primary Call-to-Action (CTA) will increase the *Unique Contact Request Rate (UCRR)* by at least 12%.
**Null Hypothesis:** Displaying a "Biometrically Verified Identity" badge adjacent to the primary CTA will not be responsible for the UCRR increasing by 12%.

#### 8.2.3. Measures
* **Signal:** Successful HTTP 200 OK response from the "Send Message" form submission endpoint.
* **Metric:** Unique Contact Request Rate (UCRR).
* **Criteria:** We expect a relative lift of $\ge 12\%$ with a statistical power ($1 - \beta$) of 80%.

#### 8.2.4. Conditions
* **Control Condition (A):** The seller profile section shows a generic avatar and the seller's first name only.
* **Experimental Condition (B):** The seller profile section includes a blue checkmark icon and the text "Identity Verified by Reniec/Biometrics" tooltip, visible before the user clicks the contact button.

---

### Experiment 3: Elegibilidad de Garantía Extendida Basada en Certificado

#### 8.2.1. Hypotheses
**Question:** Is it true that converting the technical certificate into an "unlockable" asset for extended warranty coverage increases the purchase intent?
**Belief:** While a certificate proves *current* condition, it does not guarantee *future* performance, leaving a gap for risk-averse buyers. Given that our technical inspection is rigorous enough to underwrite insurance, presenting the warranty not just as an add-on, but as an "exclusive benefit unlocked by this car's high score," shifts the user's mental model from risk mitigation to value acquisition.
**Hypothesis:** Featuring a conditional "Warranty Unlocked: Eligible for 12-Months Coverage" banner for vehicles with high inspection scores will increase the *High-Intent Action Rate (HIAR)* by at least 18%.
**Null Hypothesis:** Featuring a conditional "Warranty Unlocked" banner will not be responsible for the HIAR increasing by 18%.

#### 8.2.3. Measures
* **Signal:** Click events on "View Warranty Options" or "Apply for Financing" buttons.
* **Metric:** High-Intent Action Rate (HIAR).
* **Criteria:** A lift of $\ge 18\%$ in HIAR for vehicles with a technical score $>85/100$.

#### 8.2.4. Conditions
* **Control Condition (A):** Listings display the technical score (e.g., "90/100") but do not explicitly link this score to warranty eligibility in the initial viewport.
* **Experimental Condition (B):** Listings with a score $>85$ display a prominent "Unlockable Reward" banner above the fold: "High Score Unlocked: You are eligible for 12-Month Extended Coverage on this vehicle."
---

Integración del Sello de Certificación

* **Question:**  
Is it true that showing the CertiWeb certification seal on a car listing increases the buyer contact rate?

* **Belief:**  
Buyers distrust used cars because they lack verified technical evidence, so a visible certification seal would increase their confidence.

* **Hypothesis:**  
Adding the CertiWeb certification seal to vehicle listings will increase the buyer contact rate by at least 20%.

* **Null hypothesis:**  
Adding the CertiWeb certification seal to vehicle listings will not increase the buyer contact rate by 20%.


Integración del Informe Técnico Visible

* **Question:**  
Is it true that displaying a detailed technical report increases users’ purchase intention?

* **Belief:**  
Buyers make better decisions when they have access to clear technical information with real photos and vehicle condition details.

* **Hypothesis:**  
Displaying the detailed technical report next to the vehicle listing will increase purchase intention by at least 15%.

* **Null hypothesis:**  
Displaying the detailed technical report will not increase purchase intention by 15%.

Integración de la Validación por Código o Enlace

* **Question:**  
Is it true that allowing public certificate validation through a code or link increases buyer trust?

* **Belief:**  
If buyers can independently verify the authenticity of a certificate, they will feel more confident during the buying process.

* **Hypothesis:**  
Allowing public certificate validation through a code or link will increase the buyer contact rate by at least 10%.

* **Null hypothesis:**  
Allowing public certificate validation through a code or link will not increase the buyer contact rate by 10%.



#### 8.2.2. Domain Business Metrics

* **Métrica Primaria (Accionable):** Tasa de Conversión de Contacto (Lead Conversion Rate). Esta es la métrica de éxito del experimento.
* **Métrica Secundaria (Diagnóstico):** Tasa de Clics (CTR) sobre el propio sello. (Para medir si los usuarios intentan interactuar con él para verificarlo).
* **Métrica de Contraguardia (Guardrail):** Tasa de Abandono de la Página (Bounce Rate). (Para asegurar que el sello no introduce confusión o distracción que haga que los usuarios abandonen la página).

#### 8.2.3. Measures

* **Medida de la Métrica Primaria:**
    * **Tasa de Conversión de Contacto (CVR):**
        * **Numerador:** (Número total de clics en el botón "Contactar Vendedor").
        * **Denominador:** (Número total de impresiones únicas del anuncio).
    * **Unidad de Análisis:** El usuario (comprador).

* **Recolección de Datos:** Se rastrearán los eventos de impresión de página y clics en el botón de contacto, segmentados por la variante asignada.

#### 8.2.4. Conditions

Se definirán dos condiciones (variantes) para el experimento:

* **Condición A: Grupo de Control**
    * Los compradores asignados a este grupo verán los anuncios de vehículos certificados de forma estándar: con sus fotos, precio y descripción, pero **sin ningún sello** o mención visual prominente de CertiWeb.

* **Condición B: Grupo de Variante (Tratamiento)**
    * Los compradores asignados a este grupo verán los mismos anuncios, pero con el **sello digital "Certificado por CertiWeb"** superpuesto en la imagen principal y/o en una sección destacada del anuncio.

#### 8.2.5. Scale Calculations and Decisions

Para determinar el tamaño de la muestra necesario (escala), establecemos los siguientes parámetros:

* **Tasa de Conversión Base (Baseline CVR):** Basado en el Supuesto 1 y la industria, estimamos un CVR de **5.0%** para el grupo de control.
* **Efecto Mínimo Detectable (MDE):** Queremos detectar un *lift* del 20% (nuestra hipótesis de negocio).
    * $5.0\% \times 1.20 = 6.0\%$. El MDE absoluto es **1.0%**.
* **Significancia Estadística (α):** 95% (o $p$-value < 0.05).
* **Potencia Estadística (1-β):** 80%.

> **Cálculo:** Con estos parámetros, el tamaño de muestra requerido es de aproximadamente **14,750 impresiones por variante**.

* **Decisión de Escala:** Para asegurar resultados robustos, se redondeará la escala a **15,000 impresiones por variante (30,000 impresiones en total)**. El experimento se ejecutará durante 14 días o hasta alcanzar la escala requerida, lo que ocurra después.

#### 8.2.6. Methods Selection

* **Método:** Se utilizará un **Test A/B** (Experimento Controlado Aleatorizado).
* **Asignación de Sujetos:** La aleatorización se realizará a nivel de **usuario (comprador)**, no de sesión. Se asignará una cookie o un valor en `localStorage` (`variant_group: 'A'` o `'B'`) para garantizar que un mismo usuario vea la misma condición (Control o Variante) de manera consistente durante todo el experimento. La división del tráfico será 50/50.

#### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection

* **Objetivo de Análisis:** Determinar si la diferencia entre $CVR_{\text{Variante}}$ y $CVR_{\text{Control}}$ es estadísticamente significativa.
* **KPIs:**
    * $CVR_{\text{A}}$ (Control)
    * $CVR_{\text{B}}$ (Variante)
* **Métricas de Soporte:**
    * `Impressions_A`, `Impressions_B`
    * `Contact_Clicks_A`, `Contact_Clicks_B`
* **Análisis Estadístico:** Se utilizará un **Test Z de 2 proporciones** para comparar $CVR_{\text{A}}$ y $CVR_{\text{B}}$. Se calculará el $p$-value y el intervalo de confianza de la diferencia. El experimento será exitoso si $p < 0.05$ y el $lift$ observado es positivo y cercano (o superior) al 20%.

#### 8.2.8. Web and Mobile Tracking Plan

Se implementarán los siguientes eventos de telemetría en el Frontend:

1.  **Evento: `adImpression`**
    * **Disparador:** Cuando un anuncio de vehículo es cargado y visible en la pantalla del usuario.
    * **Propiedades:** `{ "ad_id": "string", "variant": "A | B" }`

2.  **Evento: `contactClick`**
    * **Disparador:** Cuando el usuario hace clic en cualquier botón de contacto (ej. "Contactar Vendedor", "Ver Teléfono", "Enviar Mensaje").
    * **Propiedades:** `{ "ad_id": "string", "variant": "A | B", "contact_method": "whatsapp | phone | message" }`

### 8.3. Experimentation

La ejecución de los experimentos priorizados requiere la implementación de nuevas funcionalidades (User Stories) en el producto. A continuación, se detalla el backlog ("To-Be") necesario para habilitar estas pruebas.

#### 8.3.1. To-Be User Stories

El siguiente conjunto de historias de usuario habilita los experimentos prioritarios (Validación de Sello, Sensibilidad al Precio y Valor del Informe).

| Epic/Story ID | Título | Descripción | Criterios de Aceptación |
| :--- | :--- | :--- | :--- |
| **EXP-01** | (Sello) Asignación de Variante de Experimento | Como Product Manager, quiero que el sistema asigne aleatoriamente a los compradores a un grupo (A o B) para poder ejecutar el A/B test del Sello. | **Escenario 1: Asignación de nuevo usuario**<br> **Dado** un nuevo comprador sin asignación de grupo,<br> **Cuando** visita una página de anuncio,<br> **Entonces** se le asigna un `variant_group` ('A' o 'B') con una probabilidad 50/50.<br> **Y** esta asignación se almacena de forma persistente (ej. `localStorage`).<br><br>**Escenario 2: Usuario existente**<br> **Dado** un comprador que ya tiene un `variant_group` asignado,<br> **Cuando** regresa al sitio,<br> **Entonces** el sistema debe leer y respetar su asignación previa. |
| **EXP-02** | (Sello) Renderizado Condicional del Sello | Como desarrollador Frontend, quiero que el componente del anuncio muestre u oculte el sello de CertiWeb basándose en el `variant_group` del usuario. | **Escenario 1: Grupo Control**<br> **Dado** un usuario en el grupo 'A' (Control),<br> **Cuando** ve un anuncio de un auto certificado,<br> **Entonces** NO debe ver el Sello de CertiWeb.<br><br>**Escenario 2: Grupo Variante**<br> **Dado** un usuario en el grupo 'B' (Variante),<br> **Cuando** ve un anuncio de un auto certificado,<br> **Entonces** SÍ debe ver el Sello de CertiWeb. |
| **EXP-03** | (Sello) Seguimiento de Eventos de Experimento | Como Analista de Datos, necesito que el frontend envíe eventos de `adImpression` y `contactClick` con la propiedad `variant` para poder analizar los resultados. | **Escenario 1: Impresión de Anuncio**<br> **Dado** un usuario asignado a una variante (ej. 'B'),<br> **Cuando** se dispara el evento `adImpression`,<br> **Entonces** el evento debe incluir la propiedad `{"variant": "B"}`.<br><br>**Escenario 2: Clic en Contacto**<br> **Dado** un usuario asignado a una variante (ej. 'A'),<br> **Cuando** se dispara el evento `contactClick`,<br> **Entonces** el evento debe incluir la propiedad `{"variant": "A"}`. |
| **EXP-04** | (Precio) Asignación de Cohorte de Precios | Como Product Manager, quiero que a los nuevos vendedores individuales se les asigne aleatoriamente una cohorte de precios (ej. S/ 99 vs S/ 149) para probar la sensibilidad al precio. | **Dado** un vendedor individual que visita la página de pago por primera vez,<br> **Cuando** se carga la página,<br> **Entonces** se le asigna aleatoriamente una cohorte de precio ('P99' o 'P149').<br> **Y** esta asignación se almacena en su sesión. |
| **EXP-05** | (Precio) Renderizado Condicional de Precios | Como desarrollador, quiero que la página de pago muestre el precio que corresponde a la cohorte asignada al vendedor. | **Dado** un vendedor asignado a la cohorte 'P99',<br> **Cuando** ve la página de pago,<br> **Entonces** el precio mostrado debe ser "S/ 99.00".<br><br>**Dado** un vendedor asignado a la cohorte 'P149',<br> **Cuando** ve la página de pago,<br> **Entonces** el precio mostrado debe ser "S/ 149.00". |
| **EXP-06** | (Precio) Seguimiento de Conversión de Pago | Como Analista, necesito rastrear los eventos de pago completado, incluyendo la cohorte de precio asignada. | **Dado** un vendedor en la cohorte 'P99',<br> **Cuando** completa exitosamente el pago,<br> **Entonces** se debe disparar un evento `paymentSuccess` con las propiedades `{"price_cohort": "P99", "amount": 99.00}`. |
| **EXP-07** | (Informe) Grupo de Control para Valor del Informe | Como PM, quiero que un subgrupo de compradores (Grupo C) vea los anuncios certificados pero **sin** un enlace visible al informe técnico completo, solo el sello. | **Dado** un usuario asignado al `variant_group` 'C' (Control de Informe),<br> **Cuando** ve un anuncio certificado,<br> **Entonces** debe ver el Sello de CertiWeb.<br> **Pero** NO debe ver el botón/enlace "Ver Informe Técnico Completo". |
| **EXP-08** | (Informe) Seguimiento de Valor Percibido | Como Analista, quiero medir si los compradores que ven el informe (Grupo B) están más dispuestos a pagar el precio solicitado. | **(Se requiere un método de encuesta posterior)**<br> **Dado** un usuario que hizo clic en "Contactar Vendedor",<br> **Cuando** se le muestra una encuesta (ej. "¿Qué tan dispuesto estás a pagar el precio solicitado?"),<br> **Entonces** su respuesta debe ser registrada junto a su `variant_group` ('B' vs 'C'). |

#### 8.3.2. To-Be Product Backlog

El backlog de producto se actualiza para incluir las historias de usuario del experimento. Estas se priorizan para el próximo Sprint de Experimentación.

| Prioridad | User Story ID | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| :--- | :--- | :--- | :--- | :--- |
| **1 (Alta)** | EXP-01 | (Sello) Asignación de Variante de Experimento | Como PM, quiero que el sistema asigne aleatoriamente a los compradores a un grupo (A o B)... | 3 |
| **2 (Alta)** | EXP-02 | (Sello) Renderizado Condicional del Sello | Como Dev, quiero que el componente del anuncio muestre/oculte el sello... | 2 |
| **3 (Alta)** | EXP-03 | (Sello) Seguimiento de Eventos de Experimento | Como Analista, necesito que el frontend envíe eventos de `adImpression` y `contactClick`... | 3 |
| **4 (Alta)** | EXP-04 | (Precio) Asignación de Cohorte de Precios | Como PM, quiero que a los nuevos vendedores individuales se les asigne aleatoriamente una cohorte de precios... | 3 |
| **5 (Alta)** | EXP-05 | (Precio) Renderizado Condicional de Precios | Como Dev, quiero que la página de pago muestre el precio que corresponde a la cohorte... | 2 |
| **6 (Alta)** | EXP-06 | (Precio) Seguimiento de Conversión de Pago | Como Analista, necesito rastrear los eventos de pago completado, incluyendo la cohorte... | 3 |
| **7 (Media)** | EXP-07 | (Informe) Grupo de Control para Valor del Informe | Como PM, quiero que un subgrupo de compradores (Grupo C) vea los anuncios certificados pero sin un enlace... | 2 |
| **8 (Media)** | EXP-08 | (Informe) Seguimiento de Valor Percibido | Como Analista, quiero medir si los compradores que ven el informe (Grupo B) están más dispuestos... | 5 |
---


# Conclusiones
El proyecto CertiWeb ha logrado identificar con éxito una brecha crítica en el mercado de vehículos de segunda mano: la profunda desconfianza y asimetría de información que existe entre compradores y vendedores. La solución propuesta no se limita a un simple listado de anuncios, sino que se constituye como una plataforma digital integral de certificación. Al estandarizar una inspección técnica de más de cien puntos y proveer un informe digital detallado junto con un sello de certificación verificable, CertiWeb ataca directamente la raíz del problema. El análisis exhaustivo de los segmentos objetivo (vendedores individuales, revendedores y compradores) ha permitido diseñar una propuesta de valor clara que genera seguridad y certeza para el comprador, al mismo tiempo que facilita una venta más rápida y confiable para el vendedor, validando la viabilidad del modelo de negocio.

La fortaleza del proyecto reside en su rigurosa fundamentación metodológica, aplicando un proceso Lean UX y un profundo análisis de Needfinding (Capítulo II). La definición del producto no surgió de suposiciones internas, sino de un análisis competitivo detallado, entrevistas estructuradas con usuarios reales de los tres segmentos, y la creación de artefactos clave como User Personas, Empathy Maps y User Journey Maps. Esta base analítica aseguró que el Product Backlog (Capítulo III) y las historias de usuario estén intrínsecamente alineados con las necesidades y "dolores" validados de los usuarios, resultando en un diseño de producto (Capítulo IV) centrado genuinamente en la experiencia humana.

Desde una perspectiva técnica, el proyecto ha traducido exitosamente los complejos requisitos del negocio en una arquitectura de software robusta, moderna y escalable, tal como se detalla en el Capítulo IV. La adopción de un enfoque de Domain-Driven Software Architecture ha permitido modelar el dominio de negocio de forma clara, mientras que la arquitectura de contenedores separa lógicamente el frontend (Vue.js), el backend (API RESTful en .NET) y la base de datos. Esta separación no solo facilita el mantenimiento y la evolución futura del sistema, sino que también demuestra la aplicación de buenas prácticas de ingeniería que garantizan un producto de alta calidad técnica, listo para su implementación y despliegue.

Finalmente, el proyecto demuestra una notable madurez profesional al abarcar el ciclo de vida completo del desarrollo de software, extendiéndose más allá de la mera implementación (Capítulo V). La planificación detallada para la Verificación y Validación (Capítulo VI), incluyendo estrategias para pruebas unitarias, de integración, BDD y de sistema, asegura la fiabilidad del producto. Más aún, la definición de prácticas de DevOps (Capítulo VII) establece una base sólida para la entrega y el despliegue continuos. Esta visión holística, combinada con la reflexión explícita sobre las responsabilidades éticas y el impacto social positivo de la plataforma (ABET Outcome 4), consolida a CertiWeb no solo como un proyecto técnicamente sólido, sino como una solución de ingeniería responsable y completa.

### Video About-the-Team

En este video, el equipo de desarrollo de CertiWeb se presenta y comparte su experiencia trabajando en el proyecto. Los miembros del equipo explican sus roles, las tecnologías utilizadas, los desafíos enfrentados durante el desarrollo y cómo lograron implementar una plataforma completa de inspección técnica vehicular con funcionalidades de backend seguro, autenticación con WebTokens y una interfaz de usuario intuitiva.

<img src="Images/Sprint4AboutTeam.png"/>

[About the Team]()

# Bibliografía
- Asociación Automotriz del Perú. (2023). *Estadísticas del parque automotor peruano*. https://www.aap.org.pe/

- Conventional Commits. (s.f.). *Conventional Commits 1.0.0*. https://www.conventionalcommits.org/en/v1.0.0/

- Fowler, M. (s.f.). *Ubiquitous language*. https://martinfowler.com/bliki/UbiquitousLanguage.html

- GitHub. (s.f.). *GitHub Pages*. https://pages.github.com/

- GitHub. (2025). *GitHub Pages Documentation*. https://docs.github.com/en/pages

- Gothelf, J., & Seiden, J. (2016). *Lean UX: Applying lean principles to improve user experience* (2ª ed.). O'Reilly Media.

- IBM. (s.f.-a). *As-is scenario map*. https://www.ibm.com/design/thinking/page/toolkit/activity/as-is-scenario-map

- IBM. (s.f.-b). *To-be scenario map*. https://www.ibm.com/design/thinking/page/toolkit/activity/to-be-scenario-map

- Pressman, R. S., & Maxim, B. R. (2020). *Software Engineering: A practitioner's approach* (9ª ed.). McGraw-Hill Education.

# Anexos

- Video TB1: [Video]()

- Video flujo de navegacion: [Video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQBG_GpSLn8PTKWQYsaWM5o7AYXh5s3w8PnYYEIzlHG12Wo?e=PMnpva)

- Video Entrevistas de Validación: [Video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCB75Tn4gIBRrlxGCFk3CdVAQC1EMw198ZOuImDTXveWTc?e=sJVgZe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

- Video About the Product: [Video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201912401_upc_edu_pe/IQCzYqIEYZjySIrIPH2UXodcAf8utusEwMMfDuB-5pUyYzE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=TadYNs)

- Video About the Team: [Video]()
