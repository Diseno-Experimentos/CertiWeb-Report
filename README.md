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
        "🧑‍💻Quiroz Zambrano, Fabrizio Javier - u202213406"",
        "👩‍💻 ,
        "👩‍💻 ,
        "👩‍💻 ,
        "👩‍💻 , 
    };
}
~~~


## Contenido del Informe
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
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.2. Sprint 2](#522-sprint-2)
    - [5.2.3. Sprint 3](#523-sprint-3)
    - [5.2.4. Sprint 4](#524-sprint-4)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Informe Trabajo Final 📙

# Informe Trabajo Final 📙

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
  <img src="resources/Cap-1/Members/Fabrizio1.jpg" alt="imagen Fabrizio" width="120" align="right">
  
~~~txt
Estudiante de 6to ciclo de Ingeniería de Software en la UPC.
Experiencia en C++, Angular, Python y SQL, con énfasis en desarrollo frontend.
Me considero comprometido, adaptable y con mentalidad de aprendizaje constante.
Expectativa: fortalecer habilidades fullstack y crear software útil, escalable y centrado en las personas.
~~~
</div>

---

**> [Nombre del integrante 2] (Código)**  
<div align="center">
  <img src="resources/Cap-1/Members/Integrante2.jpg" alt="imagen Integrante 2" width="120" align="right">
  
~~~txt
XXXXXX
~~~
</div>

---

**> [Nombre del integrante 3] (Código)**  
<div align="center">
  <img src="resources/Cap-1/Members/Integrante3.jpg" alt="imagen Integrante 3" width="120" align="right">
  
~~~txt
XXXXXX
~~~
</div>

---

**> [Nombre del integrante 4] (Código)**  
<div align="center">
  <img src="resources/Cap-1/Members/Integrante4.jpg" alt="imagen Integrante 4" width="120" align="right">
  
~~~txt
XXXXXX
~~~
</div>

---

**> [Nombre del integrante 5] (Código)**  
<div align="center">
  <img src="resources/Cap-1/Members/Integrante5.jpg" alt="imagen Integrante 5" width="120" align="right">
  
~~~txt
XXXXXX
~~~
</div>



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
| **TS01** | Endpoint para crear inspección vehicular | Como developer quiero un endpoint `POST /inspections` para registrar solicitudes. | Escenario 1: **Dado** una solicitud válida, **cuando** se procesa, **entonces** se crea con ID y estado “pendiente”. <br> Escenario 2: **Dado** datos incompletos, **cuando** se envía, **entonces** retorna error con campos faltantes. | EP05 |
| **TS02** | Endpoint para visualizar informe | Como developer quiero `GET /report/:id` que devuelva el informe en JSON. | Escenario 1: **Dado** un ID válido, **cuando** consulto, **entonces** se retorna datos técnicos y estado de certificación. <br> Escenario 2: **Dado** un ID inválido, **cuando** consulto, **entonces** retorna 404. | EP05 |
| **TS03** | Endpoint para validación de informe | Como developer quiero `GET /validate/:code` para comprobar autenticidad. | Escenario 1: **Dado** un código válido, **cuando** valido, **entonces** indica validez, certificación y estado. <br> Escenario 2: **Dado** un código inválido, **cuando** valido, **entonces** devuelve mensaje de error. | EP05 |
| **TS04** | Endpoint para consulta de informes técnicos | Como developer quiero `GET /reports/:vehicleId` para obtener informes por vehículo. | Escenario 1: **Dado** un `vehicleId` existente, **cuando** consulto, **entonces** retorna el informe completo en JSON. <br> Escenario 2: **Dado** un `vehicleId` inexistente, **cuando** consulto, **entonces** retorna 404 “Informe no encontrado”. | EP05 |
| **TS05** | Hashing de contraseñas | Como developer quiero hashing seguro para credenciales. | Escenario 1: **Dado** un registro, **cuando** guardo la contraseña, **entonces** se hashea con algoritmo seguro (bcrypt). <br> Escenario 2: **Dado** un login, **cuando** comparo, **entonces** verifico hash vs contraseña ingresada. | EP05 |
| **TS06** | Autorización con JWT | Como developer quiero JWT para autorización stateless. | Escenario 1: **Dado** login correcto, **cuando** se autentica, **entonces** se genera JWT válido. <br> Escenario 2: **Dado** un token en petición, **cuando** lo valido, **entonces** verifico autenticidad y extraigo claims. | EP05 |
| **TS07** | Anti Corruption Layer (ACL) | Como developer quiero un ACL para proteger el dominio de dependencias externas. | Escenario 1: **Dado** datos externos entrantes, **cuando** ingresan, **entonces** el ACL los transforma al modelo del dominio. <br> Escenario 2: **Dado** que debo llamar servicios externos, **cuando** envío objetos de dominio, **entonces** el ACL los adapta al formato requerido. | EP05 |

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
#### 4.2.4. Searching Systems
#### 4.2.5. Navigation Systems

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams

### 4.5. Web Applications Prototyping

### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Software Architecture Context Diagram
#### 4.6.2. Software Architecture Container Diagrams
#### 4.6.3. Software Architecture Components Diagrams

### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
#### 4.7.2. Class Dictionary

### 4.8. Database Design
#### 4.8.1. Database Diagram

---

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1
##### 5.2.1.2. Aspect Leaders and Collaborators
##### 5.2.1.3. Sprint Backlog 1
##### 5.2.1.4. Development Evidence for Sprint Review
##### 5.2.1.5. Execution Evidence for Sprint Review
##### 5.2.1.6. Services Documentation Evidence for Sprint Review
##### 5.2.1.7. Software Deployment Evidence for Sprint Review
##### 5.2.1.8. Team Collaboration Insights during Sprint

#### 5.2.2. Sprint 2
##### 5.2.2.1. Sprint Planning 2
##### 5.2.2.2. Aspect Leaders and Collaborators
##### 5.2.2.3. Sprint Backlog 2
##### 5.2.2.4. Development Evidence for Sprint Review
##### 5.2.2.5. Execution Evidence for Sprint Review
##### 5.2.2.6. Services Documentation Evidence for Sprint Review
##### 5.2.2.7. Software Deployment Evidence for Sprint Review
##### 5.2.2.8. Team Collaboration Insights during Sprint

#### 5.2.3. Sprint 3
##### 5.2.3.1. Sprint Planning 3
##### 5.2.3.2. Aspect Leaders and Collaborators
##### 5.2.3.3. Sprint Backlog 3
##### 5.2.3.4. Development Evidence for Sprint Review
##### 5.2.3.5. Execution Evidence for Sprint Review
##### 5.2.3.6. Services Documentation Evidence for Sprint Review
##### 5.2.3.7. Software Deployment Evidence for Sprint Review
##### 5.2.3.8. Team Collaboration Insights during Sprint

#### 5.2.4. Sprint 4
##### 5.2.4.1. Sprint Planning 4
##### 5.2.4.2. Aspect Leaders and Collaborators
##### 5.2.4.3. Sprint Backlog 4
##### 5.2.4.4. Development Evidence for Sprint Review
##### 5.2.4.5. Execution Evidence for Sprint Review
##### 5.2.4.6. Services Documentation Evidence for Sprint Review
##### 5.2.4.7. Software Deployment Evidence for Sprint Review
##### 5.2.4.8. Team Collaboration Insights during Sprint

### 5.3. Validation Interviews
#### 5.3.1. Diseño de Entrevistas
#### 5.3.2. Registro de Entrevistas
#### 5.3.3. Evaluaciones según heurísticas

---

## Conclusiones

## Bibliografía

## Anexos
