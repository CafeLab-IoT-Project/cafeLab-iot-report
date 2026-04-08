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
  <td><img src="public/assets/images/integrantes/Henry.jpg"alt="..." width="200"> </td>
    <td>Mi nombre es <strong>...</strong>, ...</td>
  </tr>
  <tr> 
    <td> <img src="public/assets/images/integrantes/fredy.jpeg"alt="..." width="200">  </td>
    <td> Mi nombre es <strong>...</strong>, ... </td>
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

