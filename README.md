# cafeLaf-iot-report

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección se brinda la descripción de nuestra startup, nuestro producto y de los miembros del equipo que llevará a cabo el proyecto.

### 1.1.1. Descripción de la Startup

**Café Metrix** es una startup enfocada en desarrollar soluciones tecnológicas para la industria del café de especialidad. Así, nace de la pasión por combinar tecnología accesible con el arte del café para lograr una mejor conservación y preparación del mismo, apuntando a la comodidad tanto de los baristas y demás profecionales como del consumidor final.

De esta manera, llega **Café Lab**, el cual es un sistema integral diseñado para baristas profesionales y cafeterías de especialidad que busca resolver dos problemas fundamentales en la industria: la falta de herramientas integradas para documentar, replicar y compartir procesos clave del café, y la desarticulación entre el tueste del grano y la experiencia final en taza.

La solución consiste en una plataforma dual que combina software y componentes IoT, proporcionando control total sobre el café desde el grano verde hasta la preparación final. Permite documentar perfiles de tueste, controlar el almacenamiento del café verde mientras mantiene un monitoreo de su estado, asegurar su óptima conservación, digitalizar procesos de calibración, conectar la forma en que tuestan el café con cómo sabe finalmente (alineando parámetros técnicos del tostado con el perfil en taza) y reforzar la transparencia de la cadena productiva (mostrando de dónde viene el café y cómo se ha procesado en cada etapa).

Con esto, aseguramos que el proceso será mucho más claro para ambas partes y se logrará tanto facilitar el monitoreo del proceso con registro de acciones y posibles errores como proteger la calidad del grano mediante nuestro sistema de detección de humedad y regulación de tempratura mediante ventilación.

**Misión**: Elevar la calidad y consistencia del café, documentando cada etapa del proceso y gestionando una correcta conservación del grano para garantizar resultados excepcionales y sostenibles.

**Visión**: Ser líder a nivel nacional en el estándar tecnológico que revoluciona la industria del café de especialidad.

#### Logo, isotipo y logotipo de Café Lab:
<img src="public/assets/images/styleGuidelines/Branding.png" alt="Imagen de logo y variaciones" width="7000">

### 1.1.2. Perfiles de integrantes del equipo
<table border="1">
  <tr>
    <td><img src="public/assets/images/integrantes/adriand.jpeg" alt="Adrian Donayre" width="150"></td>
    <td>Mi nombre es <strong>Adrian Donayre</strong>, tengo 19 
    años y actualmente estoy cursando el quinto ciclo de la 
    carrera de Ingeniería de Software en la UPC. Tengo habilidad en los lenguajes C++ y javascript. Así mismo, cuento con experiencia en monitoreo de infraestructura en herramientas como Azure, NR y Kemp. Personalmente, opino que lo que hagamos en la universidad se verá reflejado en nuestra vida profesional. Por ello me esfuerzo en ampliar mis conocimientos y conseguir nuevas experiencias que me sumen para seguir mejorando.</td>
  </tr>
  <tr>
    <td><img src="public/assets/images/integrantes/natalia-roman.png" alt="Guillermo Tantaleán" width="200"> </td>
    <td>Mi nombre es <strong>Natalia Roman</strong>, tengo 20 años y me encuentro cursando el séptimo ciclo de la carrera de ingeniería de software. Desde los primeros ciclos me ha apasionado la programación, siendo los lenguajes que mejor manejo java, javascript, C++ y C#, y me he centrado en aprender lo más posible en cuanto a optimización de procesos y nuevas tecnologías. Me interesa aprender sobre elementos IoT para poder integrarlos en nuevos proyectos.</td>
  </tr>
  <tr>
  <td><img src="public/assets/images/integrantes/jorge_suin_yum_gonzales.png"alt="Jorge Suin Yum Gonzales" width="200"> </td>
    <td>Mi nombre es <strong>Jorge Suin Yum Gonzales</strong>, Soy estudiante del 7° ciclo con 21 años. Tengo experiencia con diferentes lenguajes de programación y desarrollo de aplicaciones web en diversos frameworks ambos en frontend y backend. Soy una persona responsable y puntual, interesado en tecnologias emergentes y sus aplicaciones, cualidades que aplico al trabajar de manera colaborativa con los integrantes de nuestro equipo.
</td>
  </tr>
  <tr> 
    <td> <img src="public/assets/images/integrantes/fredy.png"alt="..." width="200">  </td>
    <td> Mi nombre es <strong>Carlos Fredy Fernandez Camayo</strong>.Soy estudiante de ingenieria de software. Tengo experiencia en desarrollo de proyectos Frontend y Backend con Angular y Spring boot, asimismo considero que cada paso en la universidad contribuye en mi avance como desarollo profesional. Estoy interesado en continuar mi aprendizaje, por lo que estoy dispuesto a participar en la adecuada realizacion de proyectos.  </td>
  </tr>
  <tr> 
    <td> <img src="public/assets/images/integrantes/fredy.jpeg"alt="..." width="200">  </td>
    <td> Mi nombre es <strong>...</strong>, ... </td>
  </tr>
  <tr> 
    <td> <img src="public/assets/images/integrantes/fredy.jpeg"alt="..." width="200">  </td>
    <td> Mi nombre es <strong>...</strong>, ... </td>
  </tr>
</table>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

**Who (¿Quiénes?):** 

Nuestros principales usuarios serán baristas profesionales y dueños de cafeterías de especialidad que manejan procesos desde el tueste hasta la preparación, así como emprendedores del rubro que buscan escalar su operación manteniendo la calidad e integrando elementos tecnológicos.

**What (¿Qué sucede?):**

Actualmente, la mayoría de cafeterías de especialidad utilizan herramientas manuales o genéricas que no permiten documentar ni replicar parámetros técnicos clave, lo que genera inconsistencias en la calidad del café, desconexión entre procesos y pérdida de trazabilidad. Además, al tener que ser controlado manualmente, el café tiende a humedecerse de más, lo que puede provocar la aparición de hongos.

**When (¿Cuándo ocurre?):**

Los problemas detectados suelen surigr cuando se intenta replicar perfiles de tueste, preparar recetas específicas o cumplir con estándares de calidad de forma profesional sin contar con herramientas digitales adaptadas al rubro que faciliten el control y desarrollo de los procesos.

**Where (¿Dónde ocurre?):**

Esto ocurre en laboratorios de café, tostadores pequeños, cafeterías urbanas o rurales y negocios en expansión que buscan formalizar su operación, es decir, cualquier establecimiento en el que se conserve o realiza la preparación de café donde no se cuente con herramientas tecnológicas de apoyo.

**Why (¿Por qué es un problema?):**

Esto es porblema dado que existe una falta de integración entre los procesos técnicos (almacenamiento, tueste, calibración, cata, extracción) que dificulta la estandarización, dificulta la conservación del café, reduce la calidad percibida y limita la posibilidad de crecer o competir en el mercado de cafés de especialidad.

**How (¿Cómo lo solucionan hoy?):**

La solución que se utiliza hoy consiste en registros manuales en cuadernos, hojas de Excel, softwares genéricos no adaptados al café, sin conexión entre lotes, recetas y resultados. En el caso de la conversación, parte del personal debe tomar mediciones de humedad manualmente y alterar la temperatura sin medición, es decir, no se está seguro de si es la adecuada, lo que pone en riesgo la calidad del grano.

**How much (¿Cuánto cuesta no resolverlo?):**

Al no tomar acciones para implementar una solución, se genera pérdida de reputación en las cafeterías, inconsistencias en la calidad, dificultad para cumplir certificaciones y pérdida de clientes exigentes. Además, impide escalar el negocio con eficiencia.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Nuestro sistema para baristas y cafeterías de especialidad fue diseñado para lograr que los usuarios puedan documentar, replicar y mejorar procesos como el tueste, la preparación y la cata, además de asegurar trazabilidad y control desde el grano verde hasta la taza.

Hemos observado que el producto no está cumpliendo completamente con estos objetivos, ya que los procesos están desarticulados, no hay conexión entre etapas como el almacenamiento, el tueste y la extracción, la conservación del grano no se realiza adecuadamente, y muchos datos importantes se pierden o no quedan registrados. Esto provoca errores, variabilidad en la calidad, pérdida de información y poca confianza del cliente final.

¿Cómo podríamos mejorar la plataforma para que los usuarios sean más exitosos mediante una integración real de procesos, alertas en tiempo real sobre el estado del grano, cuidado de la conservación del grano automatizada y herramientas que permitan ver y comparar datos técnicos y sensoriales, basándonos en métricas como consistencia en recetas, reducción de pérdidas y mejora en la trazabilidad?

# Capítulo II:  Requirements Elicitation & Analysis

### 2.1.1. Análisis competitivo

#### Competitive Analysis


<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width: 100%;">

  <!-- Título -->
  <tr>
    <th colspan="6" style="text-align:center; border: 1px solid #000;">
      Competitive Analysis Landscape
    </th>
  </tr>

  <!-- Descripción -->
  <tr>
    <th style="text-align:center; border: 1px solid #000;">
      ¿Por qué llevar a cabo este análisis?
    </th>
    <td colspan="5" style="border: 1px solid #000;">
      Este análisis identifica las capacidades, limitaciones y enfoques estratégicos de soluciones que gestionan el café de especialidad (tueste, trazabilidad, inventario y calidad), con el fin de posicionar CaféLab como una plataforma integral que incorpora monitoreo IoT del estado del grano (verde y tostado), optimizando la calidad y reduciendo pérdidas.
    </td>
  </tr>

  <!-- Encabezados de comparación -->
  <tr>
    <th style="border: 1px solid #000;"></th>
    <th style="text-align:center; border: 1px solid #000;">Criterio</th>
    <th style="text-align:center; border: 1px solid #000;">CaféLab<img src="public\assets\images\styleGuidelines\Logo.jpg" alt="Logo Café Lab" width="150"></th>
    <th style="text-align:center; border: 1px solid #000;">Cropster<img src="public\assets\images\competidores\cropster.jpg" alt="Logo Crospter" width="150"></th>
    <th style="text-align:center; border: 1px solid #000;">Artisan<img src="public\assets\images\competidores\artisan.png" alt="Logo Artisan" width="150"></th>
    <th style="text-align:center; border: 1px solid #000;">RoastLog<img src="public\assets\images\competidores\roastlog.png" alt="Logo Roastlog" width="150"></th>
  </tr>



<!-- PERFIL -->
<tr>
    <th rowspan="3" style="text-align:center; border: 1px solid #000;">Perfil</th>
    <td><strong>Overview</strong></td>
    <td>Plataforma web integral para gestión de café de especialidad con módulos de trazabilidad, tueste, cata, inventario y monitoreo IoT del almacenamiento.</td>
    <td>Software líder en la industria para gestión de tueste, control de calidad y trazabilidad en operaciones de café.</td>
    <td>Software open source para registro y análisis de perfiles de tueste en tiempo real.</td>
    <td>Software especializado en gestión de tostadores pequeños con enfoque en control de producción y perfiles.</td>
</tr>
<tr>
    <td><strong>Ventaja competitiva</strong></td>
    <td>Integración única de software + sensores IoT para monitorear temperatura, humedad y condiciones del grano en almacenamiento.</td>
    <td>Ecosistema robusto, integración con maquinaria industrial y estandarización de procesos.</td>
    <td>Flexibilidad, personalización y comunidad activa de usuarios técnicos.</td>
    <td>Interfaz simple y enfoque accesible para pequeños tostadores.</td>
</tr>
<tr>
    <td><strong>Clientes</strong></td>
    <td>Cafeterías de especialidad, tostadores pequeños/medianos y negocios que buscan control de calidad integral.</td>
    <td>Tostadores industriales, empresas consolidadas y cadenas de café.</td>
    <td>Tostadores técnicos y entusiastas avanzados.</td>
    <td>Pequeños tostadores y negocios en crecimiento.</td>
</tr>

<!-- MARKETING -->
<tr>
    <th rowspan="2">Perfil de Marketing</th>
    <td><strong>Mercado objetivo</strong></td>
    <td>Latinoamérica (inicial), con enfoque en digitalización de cafeterías y tostadores emergentes.</td>
    <td>Mercado global consolidado (Europa, EE.UU.).</td>
    <td>Usuarios técnicos a nivel global.</td>
    <td>Mercado internacional de pequeños tostadores.</td>
</tr>
<tr>
    <td><strong>Estrategias de marketing</strong></td>
    <td>Educación sobre calidad del café, alianzas con cafeterías, enfoque en innovación IoT.</td>
    <td>Eventos internacionales, alianzas industriales, marketing de contenido técnico.</td>
    <td>Comunidad open source, foros y contribuciones técnicas.</td>
    <td>Marketing digital y posicionamiento como solución simple.</td>
</tr>

<!-- PRODUCTO -->
<tr>
    <th rowspan="3">Perfil de Producto</th>
    <td><strong>Productos & Servicios</strong></td>
    <td>Software SaaS + dispositivo IoT (sensores de temperatura/humedad, control de ventilación, alertas).</td>
    <td>Software SaaS con integración a maquinaria de tueste y análisis de datos.</td>
    <td>Software open source de escritorio para monitoreo de tueste.</td>
    <td>Software SaaS para gestión de tueste y producción.</td>
</tr>
<tr>
    <td><strong>Precios & Costos</strong></td>
    <td>Suscripción escalonada + posible costo de hardware IoT.</td>
    <td>Suscripción premium con costos adicionales por integración.</td>
    <td>Gratuito (open source).</td>
    <td>Suscripción accesible para pequeños negocios.</td>
</tr>
<tr>
    <td><strong>Canales de distribución</strong></td>
    <td>Plataforma web + integración con dispositivos físicos.</td>
    <td>Web + integraciones industriales.</td>
    <td>Aplicación de escritorio.</td>
    <td>Plataforma web.</td>
</tr>

<!-- NUEVA FILA CLAVE -->
<tr>
    <th rowspan="2">Gestión de Calidad del Grano</th>
    <td><strong>Monitoreo de almacenamiento</strong></td>
    <td>Monitoreo en tiempo real de temperatura y humedad del grano (verde y tostado).</td>
    <td>No enfocado en almacenamiento físico.</td>
    <td>No disponible.</td>
    <td>No disponible.</td>
</tr>
<tr>
    <td><strong>Control ambiental / IoT</strong></td>
    <td>Control remoto de ventilación y alertas automáticas vía sensores.</td>
    <td>No disponible.</td>
    <td>No disponible.</td>
    <td>No disponible.</td>
</tr>

<!-- SWOT -->
<tr>
    <th rowspan="4">ANÁLISIS SWOT</th>
    <td><strong>Fortalezas</strong></td>
    <td>Diferenciación clara mediante IoT, enfoque en calidad post-tueste y almacenamiento, solución integral.</td>
    <td>Reputación global, integración con maquinaria, robustez del sistema.</td>
    <td>Flexibilidad y costo cero.</td>
    <td>Facilidad de uso y accesibilidad.</td>
</tr>
<tr>
    <td><strong>Debilidades</strong></td>
    <td>Dependencia de adopción de hardware IoT, producto en fase de introducción.</td>
    <td>Alto costo y complejidad.</td>
    <td>Falta de soporte empresarial.</td>
    <td>Funcionalidades limitadas frente a soluciones completas.</td>
</tr>
<tr>
    <td><strong>Oportunidades</strong></td>
    <td>Creciente demanda de trazabilidad y control de calidad en café de especialidad.</td>
    <td>Expansión a mercados emergentes.</td>
    <td>Mejoras mediante comunidad.</td>
    <td>Crecimiento del segmento de pequeños tostadores.</td>
</tr>
<tr>
    <td><strong>Amenazas</strong></td>
    <td>Entrada de grandes plataformas al IoT, resistencia al cambio tecnológico.</td>
    <td>Competencia de soluciones más económicas.</td>
    <td>Limitaciones de escalabilidad.</td>
    <td>Competencia de software más avanzado.</td>
</tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores (CaféLab)

En base al análisis competitivo realizado, se identificaron las principales fortalezas, debilidades, oportunidades y amenazas de plataformas como Cropster, Artisan y RoastLog.

Esta información permite definir estrategias orientadas a posicionar CaféLab como una solución innovadora que integra software de gestión con monitoreo IoT del estado del café.

---

#### Afrontando las fortalezas de nuestros competidores:

**Fortalezas identificadas:**
- Ecosistemas robustos y consolidados en la industria del café.
- Integración con maquinaria de tueste y estandarización de procesos.
- Amplia adopción y reconocimiento global.
- Herramientas avanzadas de análisis de perfiles de tueste.

**Comprendemos que nuestras fortalezas son:**
- Integración de IoT para monitoreo del almacenamiento del grano (temperatura, humedad, ventilación).
- Plataforma integral que conecta trazabilidad, inventario, cata y calidad.
- Enfoque en control post-tueste y post-cosecha, poco abordado por competidores.

#### Estrategias
- Diferenciar la propuesta de valor mediante el enfoque en calidad del grano en tiempo real, más allá del tueste.
- Posicionar CaféLab como una solución integral que cubre toda la cadena: almacenamiento → tueste → taza.

#### Tácticas
- Implementar dashboards visuales con métricas en tiempo real sobre condiciones ambientales del café.
- Desarrollar alertas inteligentes (ej. riesgo de humedad alta o degradación del grano).
- Integrar reportes comparativos entre condiciones de almacenamiento y resultados en taza.
- Crear demostraciones prácticas donde se evidencie la pérdida de calidad sin monitoreo IoT.

---

#### Afrontando las debilidades de nuestros competidores:

**Debilidades identificadas:**
- Alto costo y complejidad de uso (especialmente en plataformas como Cropster).
- Falta de enfoque en almacenamiento físico del café.
- Curva de aprendizaje elevada.
- Dependencia de procesos manuales para registrar condiciones externas.

**Comprendemos que nuestras debilidades son:**
- Dependencia de adopción de hardware IoT.
- Baja presencia en el mercado en etapas iniciales.
- Necesidad de educar al usuario sobre el valor del monitoreo ambiental.

#### Estrategias
- Reducir la barrera de entrada mediante una experiencia de usuario simple y accesible.
- Educar al mercado sobre la importancia del control ambiental en la calidad del café.

#### Tácticas
- Ofrecer un plan gratuito con funcionalidades básicas para captación de usuarios.
- Diseñar una interfaz intuitiva con onboarding guiado para nuevos usuarios.
- Crear tutoriales y contenido educativo sobre almacenamiento del café.
- Implementar soporte técnico accesible y acompañamiento en la instalación del IoT.

---

#### Afrontando las oportunidades de nuestros competidores:

**Oportunidades identificadas:**
- Crecimiento del mercado de café de especialidad.
- Mayor interés en trazabilidad, sostenibilidad y calidad.
- Tendencia hacia la digitalización de procesos productivos.
- Baja adopción de tecnologías IoT en el sector cafetero.

**Comprendemos que nuestras oportunidades son:**
- Posicionarnos como pioneros en IoT aplicado al café.
- Atender el mercado emergente en Latinoamérica.
- Integrar educación + tecnología como propuesta de valor.

#### Estrategias
- Desarrollar una propuesta centrada en la digitalización del control de calidad del café.
- Generar alianzas estratégicas con actores del ecosistema cafetero.

#### Tácticas
- Colaborar con certificadoras como Rainforest Alliance y Fairtrade International para validar trazabilidad.
- Participar en eventos y ferias de café de especialidad.
- Crear contenido educativo (blogs, webinars, redes sociales) sobre buenas prácticas.
- Implementar campañas que demuestren el impacto del almacenamiento en la calidad final.

---

#### Afrontando las amenazas de nuestros competidores:

**Amenazas identificadas:**
- Posible entrada de grandes plataformas al uso de IoT.
- Resistencia al cambio tecnológico en cafeterías tradicionales.
- Existencia de soluciones gratuitas o de bajo costo.
- Limitaciones en adopción tecnológica en mercados emergentes.

**Comprendemos que nuestras amenazas son:**
- Dificultad en demostrar el retorno de inversión del IoT.
- Diversidad de prácticas de almacenamiento entre cafeterías.
- Competencia futura con soluciones más integradas.

#### Estrategias
- Demostrar el valor económico y operativo del uso de IoT en la gestión del café.
- Adaptar la solución a diferentes niveles de madurez tecnológica del cliente.

#### Tácticas
- Desarrollar casos de estudio que evidencien reducción de pérdidas de café.
- Implementar métricas de impacto (ej. mejora en consistencia de taza, reducción de desperdicio).
- Ofrecer versiones modulares del sistema (software sin IoT / con IoT escalable).
- Realizar encuestas y validaciones continuas con usuarios del sector.



## 2.3. Needfinding
### 2.3.1. User Personas
**Administradores y dueños de cafeterias de especialidad**
<td><img src="public\assets\images\userPersonas\UserPersona_FernandoGoijman.png" alt="Fernando Goijman"></td>

**Barista Profesional**
<td><img src="public\assets\images\userPersonas\UserPersona_ValeriaRamos.png" alt="Valeria Ramos"></td>



### 2.3.2. User Task Matrix

En esta sección se presentan los User Task Matrix correspondientes a los segmentos objetivos del proyecto (barista profesional y dueño de cafetería de especialidad).

A continuación, se detallan las tareas que ambos realizan en su rutina profesional, incorporando no solo actividades relacionadas con la preparación y análisis del café, sino también aquellas vinculadas al monitoreo del estado del grano (verde y tostado), condiciones de almacenamiento y toma de decisiones basada en datos, aspectos clave dentro de la propuesta de valor de CaféLab.

---

#### User Task Matrix

| TASK | Barista Profesional (Frecuencia) | Barista Profesional (Importancia) | Dueño de Cafetería (Frecuencia) | Dueño de Cafetería (Importancia) |
|------|--------------------------------|----------------------------------|--------------------------------|----------------------------------|
| Calibrar máquina de espresso | Always | High | Sometimes | Medium |
| Registrar parámetros de extracción | Always | High | Sometimes | Medium |
| Cata sensorial de cafés | Often | High | Often | High |
| Registrar recetas de preparación | Always | High | Sometimes | Medium |
| Recomendar mejoras en recetas | Often | Medium | Often | High |
| Registrar consumo de café molido/tostado | Often | High | Always | High |
| Monitorear condiciones del café (temperatura, humedad) | Rarely | Medium | Often | High |
| Detectar cambios en la calidad del grano almacenado | Sometimes | Medium | Often | High |
| Compartir información con el equipo | Always | Medium | Always | High |
| Documentar perfiles de tueste | Sometimes | Medium | Always | High |
| Supervisar procesos de calidad | Rarely | Medium | Always | High |
| Realizar pedidos o gestionar inventario | Sometimes | Medium | Always | High |
| Analizar datos para mejorar procesos | Sometimes | Medium | Often | High |
| Buscar registros históricos (tueste, cata, almacenamiento) | Sometimes | Medium | Often | High |
| Coordinar con proveedores de café | Never | Low | Often | High |
| Usar herramientas digitales de control y trazabilidad | Often | Medium | Often | High |
| Capacitarse o aprender sobre café | Always | High | Sometimes | Medium |

---

El análisis de las tareas de baristas profesionales y dueños de cafeterías de especialidad evidencia una diferencia clara en el enfoque operativo y estratégico dentro del negocio del café.

Por un lado, los baristas se concentran en tareas técnicas y operativas del día a día, como la calibración de la máquina de espresso, el registro de parámetros de extracción, la preparación de recetas y la evaluación sensorial. Su objetivo principal es garantizar la consistencia y calidad en taza, con un alto interés en la mejora continua y el aprendizaje. Sin embargo, su participación en procesos de monitoreo del estado del grano o control de almacenamiento es limitada, siendo estas actividades menos frecuentes en su rutina.

Por otro lado, los dueños de cafeterías adoptan un rol más estratégico y de control integral del negocio. Sus tareas incluyen la gestión de inventarios, la supervisión de la calidad del café, la documentación de perfiles de tueste, el análisis de datos históricos y la toma de decisiones basadas en información. Además, muestran una mayor preocupación por factores relacionados con la conservación del café, como las condiciones de almacenamiento (temperatura y humedad) y el impacto de estas variables en la calidad final del producto.

Ambos perfiles coinciden en la importancia de las catas sensoriales, el uso de herramientas digitales y el registro de información para mejorar procesos. No obstante, se identifica una oportunidad clave: la falta de monitoreo sistemático y automatizado de las condiciones físicas del café, lo que puede afectar la calidad del grano sin ser detectado a tiempo.

En este contexto, CaféLab se posiciona como una solución que permite integrar las tareas técnicas y estratégicas mediante el uso de software y dispositivos IoT, facilitando el monitoreo en tiempo real, la trazabilidad completa y la toma de decisiones informadas para mejorar la calidad del café desde el almacenamiento hasta la taza.

### 2.3.3 User Journey Mapping
**Administradores y dueños de cafeterias de especialidad**
![Journey Map Fernando](<public/assets/images/journeymapping/Fernando.png>)
**Barista Profesional**
![Journey Map Valeria](<public/assets/images/journeymapping/Valeria.png>)

### 2.3.4. Empathy Mapping.
**Administradores y dueños de cafeterias de especialidad**
![Empathy Map dueño](<public/assets/images/empathymapping/Empathy map Dueños.png>)
**Barista Profesional**
![Barista](<public/assets/images/empathymapping/Empathy Map Barista Professional.png>)

## 2.4. Big Picture EventStorming.

# Capítulo III: Requirements Specification
## 3.1. User Stories.
## 3.2. Impact Mapping.
## 3.3. Product Backlog.
