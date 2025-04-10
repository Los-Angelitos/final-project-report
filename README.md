<hr>

# <center>Informe del Trabajo Final</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Desarrollo de Soluciones IoT - 2971</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez </strong><br>
    <br>INFORME
</p>

<center>

#### Startup: **Sweet Manager**

#### Product: **Sweet Manager**

</center>

## Team  Members:

<div align="center">

|               Member                |    Code    |
| :---------------------------------: | :--------: |
| Mauricio Abraham Rivo Rojas Sánchez | U202211572 |
| Giacomo Zoppi Rodriguez | U202210029 |
| Omar Andrew Morales Montalvo | U202212383 |
| Ramón Alejandro Jorge Arévalo | U20221D126 |
| Fabia Alejandra Herrera Aguirre | U202219422 |
| Arian Martín Rodriguez Vargas | U202212096 |

</div>

# Registro de Versiones del Informe

<table>
    <thead>
    <tr>
        <th>Version</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td>Mauricio Abraham Rivo Rojas Sánchez</td>
        <td>
        <ul>
        <li> Antecedentes y Problemática </li>
        <li> User stories </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td>Giacomo Zoppi Rodriguez</td>
        <td>
        <ul>
        <li> Lean UX Process</li>
        <li> Product Backlog</li>
        <li> Ubiquitous Language </li>
        </ul>
        </td>
    </tr>
    <tr>  
    </tr>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td>Omar Andrew Morales Montalvo</td>
        <td>
        <ul>
        <li> User Journey Mapping </li>
        <li> Impact Mapping </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td> Ramón Alejandro Jorge Arévalo </td>
        <td>
        <ul>
        <li> As-is Scenario Mapping </li>
        <li> To-Be Scenario Mapping </li>
        <li> User Task Matrix </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td> Fabia Alejandra Herrera Aguirre </td>
        <td>
        <ul>
        <li> Segmentos Objetivos </li>
        <li> User Persona </li>
        <li> Analisis Entrevistas </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>TB1</td>
        <td>29/03/2024</td>
        <td> Arian Martín Rodriguez Vargas </td>
        <td>
        <ul>
        <li> Analisis Competitivo </li>
        <li> Estrategias Frente a Competidores </li>
        <li> Empathy Mapping </li>
        </ul>
        </td>
    </tr>
    </tbody>
</table>

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
El proyecto escogido es Sweet Manager, una solución tecnológica enfocada en la gestión eficiente de hoteles, diseñada para facilitar el trabajo administrativo y operativo, así como, modernizar los procesos administrativos.

Nuestro objetivo es brindar a los hoteles una plataforma integral que centralice la administración de reservas y habitaciones, incorporando además tecnologías IoT para mejorar el confort, la seguridad y la eficiencia energética de los espacios.

Para la monetización, utilizamos un modelo de negocio basado en suscripción escalable, el cual se adapta al tamaño y necesidades de cada hotel, e incorpora la gestión de dispositivos IoT como valor agregado. Es decir, cada nivel de suscripción incluye funcionalidades básicas del sistema (gestión de reservas, finanzas, etc.), además de una cantidad determinada de dispositivos IoT preconfigurados para su uso inmediato. Para el aprovisionamiento de hardware, pensamos usar un modelo de Partner Reseller: el partner instala y mantiene el hardware, y Sweet Manager comparte ingresos por suscripción.

VISION: 

MISION: 

### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo                             | Codigo Estudiante | Carrera                | Conocimientos / Habilidades |
| ----------------------------------------------- | ----------------- | ---------------------- | --------------------------- |
| Mauricio Abraham Rivo Rojas Sánchez	![Imagen del compañero](https://i.imgur.com/qQ6neUi.png) | U202211572            | Ingenieria de software | C++, C#, javascript y java            |


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Siguiendo la estructura propuesta

-   **What?**
    Sweet Manager es una solución integral diseñada para abordar las complejidades de la gestión hotelera, proporcionando una plataforma única para gestionar los aspectos más importantes de un hotel.

-   **When?**
    ¿Cuando estamos viendo el problema?
    El problema puede surgir en cualquier momento, ya sea diariamente con la gestión de reservas o de manera imprevista con problemas de recursos esenciales como comida, agua, o luz.

    ¿En que momento del día y/o del proceso en cuestión?
    El problema puede presentarse en distintos momentos del día, por ejemplo cuando el personal necesite herramientas adecuadas para atender las reservas y/o comunicarse con su superior.

-   **Where?**
    ¿Donde estamos viendo los problemas?
    Estamos viendo los problemas en hoteles y establecimientos de alojamiento en todas partes, desde pequeñas posadas hasta grandes cadenas hoteleras.

    ¿En que parte/lugar del producto/proceso estamos viendo el problema?
    Los problemas se presentan en la gestión de operaciones diarias, como el seguimiento de ingresos, administración de inventarios, y coordinación del personal.

-   **Who?**
    ¿A quien le sucede?
    Los problemas afectan a propietarios, gerentes de hoteles y personal de trabajo en establecimientos de alojamiento.

    ¿El problema está relacionado con las habilitades de las personas?
    El problema no solo está relacionado con las habilidades, sino también con la complejidad y carga de trabajo asociada a la gestión hotelera, lo que puede ser abrumador sin herramientas adecuadas.

-  **Why?**
    ¿Por qué sucede el problema? ¿Cual es la causa?

    El problema surge debido a la gestión ineficiente, que puede resultar en pérdidas financieras, escasez de inventario, falta de coordinación del personal, y en última instancia, una experiencia insatisfactoria para los huéspedes. Esto afecta tanto la reputación como la rentabilidad del hotel.

-   **How?**
    ¿Como se diferencia el problema del estado normal(optimo)? ¿La tendencia en la que aparece el problema es aleatoria o sigue un patrón?
    El estado óptimo se caracteriza por una operación hotelera fluida y bien coordinada. El problema se diferencia del estado óptimo en que causa interrupciones en la operación, con un impacto negativo en la eficiencia y la satisfacción del cliente. La aparición del problema puede seguir un patrón debido a la falta de automatización o puede ser aleatoria por la falta de previsión.

    ¿Como se utilizará el producto?
    Sweet Manager se utilizará como una plataforma centralizada y fácil de usar que permite a los hoteles gestionar los aspectos principales de su negocio de manera eficiente y efectiva, mejorando la coordinación, el control y la toma de decisiones.

-   **How much?**
    ¿Cuantos problemas se dan en un dia? ¿En una semana? ¿En un mes?
    La frecuencia de los problemas puede variar según la eficiencia del hotel antes de implementar Sweet Manager. Sin embargo, sin una solución adecuada, problemas como la falta de coordinación del personal o la escasez de inventario pueden ocurrir a diario, semanalmente o mensualmente.

    ¿Cuanto dinero están implicando?
    Los problemas de gestión ineficiente pueden implicar pérdidas financieras significativas debido a la mala gestión de inventarios, la insatisfacción de los huéspedes y la disminución de la rentabilidad, lo que puede traducirse en miles de dólares perdidos al mes.

### 1.2.2. Lean UX Process
---
#### 1.2.2.1. Lean UX Problem Statements
---
**Problem Statement:**

Siguiendo la estructura propuesta por Jeff Gothelf y Josh Seiden, en su libro "Lean Ux 3rd Edition":

**El estado actual de** la gestión hotelera en hoteles pequeños y medianos se ha centrado principalmente en procesos manuales, soluciones de software fragmentadas y una adopción limitada de tecnologías innovadoras. La mayoría de los sistemas existentes solo abordan funciones básicas como las reservas y la facturación, sin ofrecer una integración integral e inteligente en toda la operación del hotel.

**Los productos y servicios actuales no abordan adecuadamente** la necesidad de integrar tecnologías IoT que mejoren el confort y la experiencia de los huéspedes, ni brindan una plataforma administrativa centralizada, fácil de usar y escalable según el tamaño y las necesidades del hotel.

Sweet Manager **busca cerrar esta brecha mediante** el desarrollo de una solución tecnológica, que integre dispositivos IoT para el control inteligente de habitaciones, al mismo tiempo que simplifica la gestión administrativa y agiliza los procesos de reseva de habitaciones a los huéspedes. 

**Nuestro enfoque inicial estará dirigido** a hoteles pequeños y medianos ubicados en zonas urbanas de América Latina, que buscan modernizar sus operaciones y reducir costos a través de la transformación digital, así como, futuros huespedes interesados en hacer una reserva personalizada rapidamente. 

**Sabremos que hemos tenido éxito cuando observemos** una mayor tasa de adopción de la plataforma, una reducción comprobada de los costos operativos en los hoteles clientes y un aumento en los índices de satisfacción de los huéspedes.

**Dominio:**

La solución se encuentra en el dominio de la gestión hotelera inteligente, donde convergen operaciones administrativas, experiencia del huésped y tecnologías emergentes como el Internet de las Cosas (IoT). Apunta a digitalizar y optimizar la operación diaria de hoteles, combinando eficiencia operativa, automatización y personalización de servicios.

**Segmentos de Clientes:**

Nos dirigimos a los propietarios y administradores de hoteles de tamaños pequeño y mediano, así como a clientes interesados en una agil gestión de reservas. 

**Puntos de Dolor:**

Administradores: uso excesivo de hojas de cálculo, falta de visibilidad en tiempo real, herramientas desconectadas y procesos manuales que consumen tiempo.

Dueños: dificultad para monitorear operaciones desde fuera del hotel, falta de indicadores claros sobre rentabilidad y ocupación.

Huéspedes: procesos de reserva tediosos, comunicación poco eficiente, escasa personalización del servicio.

**Visión/Estrategia:**

Nuestra visión es proporcionar una solución integral y fácil de usar que aborde todas las necesidades de gestión de un hotel, así como mejorar la experiencia del cliente al ofrecer una plataforma dinamica y sencilla para poder gestionar y realizar sus reservas. 

**Segmento Inicial:**

Nos enfocamos inicialmente en hoteles independientes y pequeñas cadenas hoteleras que buscan soluciones accesibles y eficientes para optimizar sus operaciones. Este segmento ofrece la oportunidad de validar rápidamente el producto en contextos reales, generar casos de éxito locales y escalar hacia otras regiones.

---

#### 1.2.2.2. Lean UX Assumptions
---
#### Features
---
**Para el administrador del hotel:**

- Gestión de habitaciones, incluyendo un control de ocupación en tiempo real.

- Visualización de  reservas hechas por huéspedes. También puede registrar manualmente la llegada (check-in) y salida (check-out),

- Integración con dispositivos IoT, que permitan automaticamente adecuarse a las necesidades de sus Huéspedes. 
  
- Comunicación directa por correo dentro del sistema entre personal del hotel

- Gestión de proveedores y suministros necesarios dentro de la aplicación. 

**Para el Huésped del hotel (huésped):**

- Interfaz intuitiva para que el huésped pueda seleccionar fechas, tipo de habitación, servicios adicionales

- Personalización de la habitación, pudiendo determinar valores como la temperatura de la misma. 

- El usuario puede consultar sus estadías anteriores.

**Para el dueño del hotel (owner):**

- Posibilidad de monitorear los indicadores clave del hotel en tiempo real.

- Indicadores clave de rentabilidad y ocupación.

- En caso de que el dueño tenga más de un hotel, podrá ver datos agrupados y comparativos entre ellos.

- El propietario puede gestionar los servicios contratados con Sweet Manager, actualizar su plan, etc. 

---
#### Business Outcomes
---
 ¿Cómo sabremos que resolvimos el problema de negocio? ¿Qué mediremos?

Los siguientes indicadores nos permitirán evaluar si la solución propuesta está generando el impacto esperado en el negocio hotelero:

- **Reducción de costos operativos**: Esperamos que al implementar Sweet Manager, se reduzca al menos un 20% en los primeros 6 meses, gracias a una gestión más efectiva de ingresos y recursos que optimiza los costos operativos y maximiza los ingresos.
- **Incremento en la eficiencia del personal administrativo**: 30% de reducción de tiempo en el tiempo dedicado a tareas administrativas como la gestión de reservas o de habitaciones, lo que se traducirá en una mejora tangible en la eficiencia operativa del hotel.
- **Retención de los Huéspedes**: Mediante el uso de Sweet Manager, esperamos un aumento del 20% en el número de Huéspedes que realizan reservas repetidas dentro de un año, lo que indica una mayor fidelización gracias a una gestión más efectiva y una experiencia de calidad para los huéspedes.
- **Aumento en la adopción del sistema**: Con Sweet Manager, esperamos un 60% de uso diario del sistema en los primeros 3 meses, con tanto los administradores como los Huéspedes estando al tanto de sus reservas y de datos importantes en la aplicación. 
- **Mayor Satisfacción del Huésped**: Gracias a Sweet Manager, esperamos ver un aumento de 0.5 puntos en la calificación promedio de satisfacción del Huésped en las reseñas en línea (fuera de Sweet Manager, refiriendose a servicios externos como las calificaciones de Google Maps, etc) , lo que reflejaría la mejora en la experiencia del Huésped, gracias a una gestión más eficiente y una atención más personalizada.

---
#### Users
---
> **Referencia metodológica:**  
> Según *Lean UX, 3rd edition*, se recomienda crear proto-personas basadas en suposiciones iniciales del equipo, las cuales deben validarse y actualizarse continuamente mediante investigación y observación directa.

Administradores: Los administradores son responsables de garantizar el correcto funcionamiento del hotel en el día a día. Entre sus principales responsabilidades se encuentran la gestión de reservas, control financiero, coordinación del personal, supervisión del inventario y análisis de indicadores clave

Huéspedes: Los Huéspedes representan a los usuarios externos que buscan alojamiento por motivos turísticos, laborales o personales. Este perfil incluye tanto a familias como a viajeros individuales o de negocios.

Dueños: Los dueños de hotel representan a los creadores de la organización y jefes de los administradores. Se encargan de monitorear la correcta gestión del hotel asi como del rendimiento financiero y operativo del mismo. 

##### Proto-persona 1 – Carla, Administradora de Hotel

- **Behavioral demographic information**  
  Administradora de un hotel. Mujer de jornada completa (9:00 a.m. - 5:00 p.m.) encargada de la gestión operativa y financiera del establecimiento. Coordina con un equipo administrativo para mantener el funcionamiento del hotel.

- **Pain points and needs**  
    - **Metas**  
      - Optimizar el tiempo invertido en tareas administrativas.  
      - Aumentar la ocupación del hotel mediante una mejor gestión.  

    - **Necesidades**  
      - Automatizar tareas repetitivas y procesos manuales.  
      - Acceder fácilmente a datos e indicadores clave para la toma de decisiones.  

    - **Frustraciones**  
      - Uso excesivo de hojas de cálculo.  
      - Pérdida de tiempo con proveedores de tecnología poco claros o soluciones poco intuitivas.
        
- **Potential Solutions**
    - Una herramienta que permita gestionar mejor los procesos administrativos y operativos a su cargo.
  
---

##### Proto-persona 2 – José, Huésped del Hotel

- **Behavioral demographic information**  
  Hombre casado que viaja temporalmente con su familia por motivos turísticos. Representa al Huésped típico que busca hospedaje cómodo y sin complicaciones para disfrutar de su viaje familiar.

- **Pain points and needs**  
    - **Metas**   
      - Disfrutar tiempo de calidad con su familia.  
      - Garantizar bienestar y educación a sus hijos.  
      - Aprovechar sus vacaciones sin estrés ni contratiempos.  

    - **Necesidades**  
      - Reservar habitaciones de forma sencilla y rápida.  
      - Contar con servicios que le permitan relajarse y enfocarse en su familia.  

    - **Frustraciones**  
      - Exceso de trámites y procesos al elegir y reservar alojamiento, lo que vuelve mas tediosas sus vacaciones.
     
  - **Potential Solutions**
          - Una herramienta que permita agilizar los tramites y procesos tediosos al reserver alojamiento
---

##### Proto-persona 3 – Lucía, Dueña del Hotel

- **Behavioral demographic information**
- Dueña de dos hoteles en Lima. Supervisa KPIs y busca inversiones rentables. Tiene conocimientos financieros y experiencia en administración.

- **Pain points and needs**

    - **Metas:**
        -  Rentabilizar la operación y asegurar crecimiento sostenible.

    - **Necesidades:**
        - Gestionar un correcto funcionamiento del hotel, asi como su generación de ingresos. 

    - **Frustraciones:**
        - Falta de visibilidad consolidada y herramientas de análisis.

- **Potential Solutions**
    - Dashboard financiero con indicadores de ROI y performance general.
---
##### User Outcomes & Benefits
---
> **Referencia metodológica:**  
> Según *Lean UX, 3rd edition*, usando los proto personas como base , podemos hacernos esta serie de preguntas: What is the user trying to accomplish?, How does the user want to feel during and after this process?, How does our product or service get the user closer to a life goal or dream?, Why would your user seek out your product? y What behavior change can we observe that tells they’ve achieved their goal?

###### Carla, Administradora de Hotel
- **¿Qué quiere lograr?** Mayor control y organización sobre los procesos operativos con el panel de control centralizado. 
- **¿Cómo quiere sentirse?** Tranquila, organizada y en control.
- **¿Cómo la ayuda Sweet Manager?** Centraliza información, automatiza flujos y muestra reportes en tiempo real.
- **¿Por qué lo buscaría?** Necesita herramientas modernas que reemplacen las hojas de cálculo.
- **¿Qué cambio observaríamos?** Disminuye el uso de Excel y usa el panel de control de Sweet Manager a diario.

###### José, Huésped del Hotel
- **¿Qué quiere lograr?** Alcanzar una experiencia de reserva sencilla, rapida y personalizada. 
- **¿Cómo quiere sentirse?** Relajado y satisfecho. 
- **¿Cómo la ayuda Sweet Manager?** Visualiza habitaciones de hotel, hace la reserva y las personaliza. 
- **¿Por qué lo buscaría?** Quiere reservar habitaciones de forma sencilla y agil. 
- **¿Qué cambio observaríamos?** Usaria Sweet Manager para personalizar y escoger la mejor experiencia hotelera.

###### Lucía, CEO del Hotel

- **¿Qué quiere lograr?** Mayor control y organización sobre el rendimiento financiero y operativo de un hotel.  
- **¿Cómo quiere sentirse?** Segura de sus decisiones de inversión.
- **¿Cómo la ayuda Sweet Manager?** Le entrega insights estratégicos y le permite controlar la gestión hotelera. 
- **¿Por qué lo buscaría?** Para supervisar operaciones sin depender de terceros.
- **¿Qué cambio observaríamos?** Toma de decisiones mas rapidas y una mejor gestión. 
---
#### User Assumptions
---
1. ¿Quién es el usuario?

Administrador: Responsable de la operación y administración del hotel.

Huésped: Persona que desea hospedarse con comodidad y sin complicaciones en un hotel.

Dueño: Supervisa la rentabilidad del hotel.

2. ¿Dónde entra nuestro producto en su trabajo o vida?
   
Administrador: En su rutina diaria laboral. Le permitirá agilizar procesos.

Huésped: En la planificación y reserva de su estadía.

Dueño: Al revisar resultados del negocio.

3. ¿Cuál es el problema que nuestro producto soluciona?
   
Administrador: Procesos manuales, desorden y problemas de organización. 

Huésped: Reservas complejas y procesos tediosos.

Dueño: Falta de visibilidad financiera.

4. ¿Cómo y cuándo nuestro producto es usado?
Administrador: A diario, desde el trabajo, para gestionar el hotel.

Huésped: Antes y durante su viaje, para reservar y consultar servicios.

Dueño: Semanalmente o en momentos clave.

5. ¿Qué características son importantes?
Administrador: Automatización, una buena administración y una interfaz intuitiva.

Huésped: Reservas rápidas, interfaz clara, confirmaciones inmediatas.

Dueño: Indicadores estratégicos. 

6. ¿Cómo debería nuestro producto verse o comportarse?
    
Administrador: Profesional, organizado y confiable.

Huésped: Simple, amigable y rápido.

Dueño: Profesional, confiable y accesible.

---
#### Business Assumptions
---
> *Extraído y adaptado del modelo propuesto en **Lean UX Sampler** de Jeff Gothelf*

1. **Creo que mis Huéspedes tienen la necesidad de:**  
   Administrador: Mejorar la eficiencia operativa de sus hoteles mediante automatización y control energético.
   Huésped: Tener una experiencia mas satisfactoria y sencilla a la hora de hacer y gestionar sus reservas de habitaciones en un hotel. 

2. **Estas necesidades pueden resolverse con:**  
   Administrador: Una plataforma integral que centralice gestión de reservas, finanzas y dispositivos IoT.
   Huéspedes: Una plataforma digital de gestión de reservas, con opciones de personalización.
   Dueño: Una plataforma que le permita visualizar la gestión de reservas y habitaciones de su hotel. 

4. **Mis Huéspedes iniciales son (o serán):**  
   Hoteles pequeños y medianos en Lima y sus Huéspedes.

5. **El valor principal que un Huésped desea obtener de mi servicio es:**  
   Administracion y Dueños: Reducción del tiempo y costo operativos y administrativos.
   Huésped: Reducción del tiempo y de cantida de tramites para efectuar una reserva en un hotel. Así como, una mejor experiencia en su reserva. 

6. **Adquiriré a la mayoría de mis Huéspedes a través de:**  
   Administradores y Dueños: Partners tecnológicos, asociaciones hoteleras y marketing digital.
   Huéspedes: Marketing digital. 

7. **Ganaré dinero mediante:**  
   Un modelo de suscripción escalable con funcionalidades básicas e IoT incluidos.

8. **Mi competencia principal en el mercado será:**  
   Sistemas tradicionales de gestión hotelera, gestión empresarial o CRMs
   **Nos diferenciaremos por:**  
   - Innovación tecnológica  
   - Interfaz amigable  
   - Soporte mediante partners

9. **Mi mayor riesgo de producto es:**  
   Poca adopción de funcionalidades IoT por desconocimiento, 
   **Lo resolveremos mediante:**  
   Capacitación, asistentes y soporte técnico.

10. **Que otros supuestos tenemos, que si probados falsos, pueden causar que nuestro proyecto falle**  
   - Que los hoteles pequeños estén dispuestos a pagar por tecnología.
   - Que los administradores esten dispuestos a acelarar sus procesos con nuestro software y no otras herramientas como la IA.   
   - Que la instalación IoT sea rentable y escalable.  
   - Que los partners brinden soporte técnico confiable.

---

#### 1.2.2.3. Lean UX Hypothesis Statements.

---

Usando la información recolectada en los Business Outcomes, Usuarios, Beneficios y Features. Podemos formular nuestras hipótesis, cada una centrada en un Feature a desarrollar.

Hipótesis 1:

Creemos que se logrará una reducción del 30% en el tiempo dedicado a tareas administrativas
si los administradores del hotel
alcanzan mayor control y organización sobre los procesos operativos
con el panel de control centralizado.

Hipótesis 2:

Creemos que se logrará un aumento del 20% en la cantidad de huéspedes que realizan reservas repetidas en un año
si los huéspedes del hotel
alcanzan una experiencia de reserva personalizada y sin complicaciones
con la funcionalidad de personalización de habitación en línea.

Hipótesis 3:

Creemos que se logrará una reducción del 20% en los costos operativos en los primeros 6 meses
si los dueños del hotel
alcanzan una mayor visibilidad sobre el rendimiento financiero y operativo
con el acceso móvil a reportes financieros y operativos.

Hipótesis 4:

Creemos que se logrará un 60% de uso diario del sistema durante los primeros 3 meses
si los administradores del hotel
alcanzan una comunicación y gestión más rápida
con la función de mensajería integrada en la aplicación.

Hipótesis 5:

Creemos que se logrará un aumento de 0.5 puntos en la calificación promedio de satisfacción del huésped en reseñas en línea
si los huéspedes del hotel
alcanzan una estadía más cómoda y adaptada a sus preferencias
con las opciones de personalización de la habitación, como la temperatura.

---

#### 1.2.2.4. Lean UX Canvas

---

![canva](https://github.com/user-attachments/assets/028d6d2b-6b9e-4f62-8912-53c598248914)

## 1.3. Segmentos objetivo

<u>Stakeholders externos:</u>

**Propietario de hotel**

Descripción: Persona que posee uno o más establecimientos hoteleros. Su rol principal es estratégico: toma decisiones de inversión, supervisa la rentabilidad del negocio y delega las operaciones diarias al administrador. Busca soluciones que optimicen recursos, incrementen ingresos y mejoren la experiencia del cliente.

Ubicación geográfica: Predominantemente en zonas urbanas y destinos turísticos estratégicos del Perú, como Lima, Cusco, Arequipa, Piura y otras regiones con alta demanda de hospedaje.

Características demográficas: Rango de edad entre 40 y 65 años. En su mayoría de género masculino. Tienen estudios superiores, principalmente en Administración, Economía o Hotelería. Su nivel socioeconómico es medio-alto a alto. Priorizan herramientas que les permitan tener control financiero, reportes de desempeño y retorno de inversión.

**Administrador de hotel**

Descripción: Profesional contratado o asociado encargado de la gestión operativa del hotel. Supervisa al personal, controla inventarios, gestiona reservas, coordina el mantenimiento y asegura la satisfacción del cliente. Necesita herramientas eficientes para el manejo diario.

Ubicación geográfica: Se encuentra en el mismo establecimiento hotelero o en su ciudad de operación. Común en ciudades con fuerte actividad hotelera Lima, Cusco, Arequipa o Piura.

Características demográficas: Edad promedio entre 25 y 50 años. Cuentan con estudios técnicos o universitarios en Gestión Hotelera, Administración, Turismo o afines. Su ingreso económico es medio, y valoran soluciones tecnológicas que les ahorren tiempo, automaticen procesos y reduzcan errores operativos.

**Huésped de hotel**

Descripción: Usuario que realiza reservas de habitaciones a través de la plataforma, motivado por viajes de ocio, aventura o negocios.

Ubicación geográfica: Principalmente residentes en diversas regiones del Perú, aunque con potencial de expansión hacia otros países de Latinoamérica.

Características demográficas: Rango de edad entre 20 y 50 años. Se trata de viajeros con intereses turísticos o profesionales, con estudios universitarios completos o en curso, familiarizados con el uso de plataformas digitales para la planificación de viajes.

<u>Stakeholders internos:</u>

- **Equipo de Desarrollo de SweetManager:** Encargado del diseño, desarrollo y mejora continua de la plataforma SweetManager, asegurando su alineación con las necesidades reales de los usuarios.

- **Equipo de Marketing:** Responsable de definir e implementar estrategias de comunicación y posicionamiento para alcanzar eficazmente a los segmentos objetivo, incluyendo propietarios y gerentes de hoteles.

- **Equipo de Soporte Técnico:** Brinda asistencia constante a los usuarios, resolviendo incidencias técnicas de forma ágil para garantizar una experiencia de uso satisfactoria.


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th colspan="7" style="text-align: center;">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
            <td colspan="5">Porque de esta manera, se conoce a los potenciales competidores en el mercado, evaluamos y analizamos lo que ofrecen para aprovechar algunos puntos débiles encontrados y de esta manera diferenciarnos de ellos.</td>
        </tr>
    </thead>
    <tbody>
        <tr style="text-align: center;">
            <td colspan="2">Empresas</td>
            <td><strong>SweetManager</strong><br></td>
            <td><strong>Sistema hotelero Xafiro</strong><br><img src="./assets/img/competitive-analysis/xafiro-brand.png"></td>
            <td><strong>Samin PMS</strong><br><img src="./assets/img/competitive-analysis/saminpms-brand.png"></td>
            <td><strong>Binz360</strong><br><img src="./assets/img/competitive-analysis/binz360-brand.jpg"></td>
        </tr>
        <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil</td>
            <td>Overview</td>
            <td>Solución tecnológica peruana enfocada en la gestión eficiente de hoteles, diseñada para facilitar el trabajo administrativo y operativo, así como, modernizar los procesos administrativos, mejorando el confort, la seguridad y la eficiencia energética de los espacios utilizando dispositivos IoT como alternativa.</td>
            <td>Software peruano que administra la gestión de los hoteles a nivel administrativo y operativo, es multiplataforma pudiendo manejar el sistema desde cualquier dispositivo, permite el ahorro de tiempo en tareas repetitivas y manuales, cuenta con facturación electrónica con la SUNAT.</td>
            <td>Sistema peruano que ofrece una solución completa para la gestión hotelera, incluyendo funcionalidades como reservas, facturación electrónica integrada con SUNAT, gestión de housekeeping, optimizando operaciones y mejorando la satisfacción del huésped.</td>
            <td>Proporciona un software hecho en Perú para la gestión de hoteles el cual incluye administración de reservas, huéspedes, caja, almacén, entre otros. Cuenta con facturación electrónica integrada con SUNAT, automatizaciones de los flujos de trabajo indicando reportes mediante dashboards.</td>
        </tr>
        <tr>
            <td>¿Qué valor ofrece a los clientes?</td>
            <td>SweetManager está encargado de integrar un sistema hotelero para su fácil gestión colocando como punto innovador los dispositivos IoT con comunicación en tiempo real para el manejo de trámites administrativos y una configuración sencilla y adaptable hacia el cliente.</td>
            <td>Xafiro está encargado de digitalizar mediante un software, la planificación, facturación y administración de los hoteles con una fácil integración de reservas para los huéspedes, pudiendo utilizar el sistema en cualquier dispositivo o plataforma. Cuenta con planes de suscripción mensual.</td>
            <td>Samin PMS maneja un sistema completo para la gestión de cualquier hotel en el Perú, mediante la facturación electrónica, administración de reservas, check-in, check-out, housekeeping, caja, almacén y otros, impulsando sus resultados mediante reportes brindados en dashboards.</td>
            <td>Binz360 mantiene una solución ante la administración de hoteles mediante procesos automatizados que brinda con su herramienta, un software que promete no continuar con las gestiones repetitivas y manuales en cuadros Excel o cuadernos. Abarca y cumple con diferentes secciones importantes de un hotel como caja, almacén, facturación, entre otros.</td>
        </tr>
        <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil de Marketing</td>
            <td>Mercado objetivo</td>
            <td><strong>Demográfico</strong><br>Hoteles medianos y grandes con más de 20 habitaciones con capacidad de inversión tecnológica además de contar personal administrativo entre 30-55 años con interés en digitalización.<br><strong>Geográfico</strong><br>Principalmente en Perú con posible expansión en Latinoamérica, comenzando con ciudades totalmente turísticos como Lima, Cusco, Arequipa y Trujillo.<br><strong>Psicológico</strong><br>Profesionales que buscan optimizar recursos y reducir costos con tecnología IoT, con enfoque en sostenibilidad y eficiencia energética.<br><strong>Comportamiento</strong><br>Empresas que ya usan tecnología básica pero requieren de una solución más innovadora y avanzada.</td>
            <td><strong>Demográfico</strong><br>Hoteles pequeños y medianos de hasta 50 habitaciones con empresarios y emprendedores jóvenes (25 a 45 años) con hoteles familiares o boutique.<br><strong>Geográfico</strong><br>Mercado peruano especialmente en regiones turísticas en ciudades como Cusco, Arequipa, Iquitos, Trujillo. Además cuenta con expansión potencial en pequeñas ciudades y zonas rurales con turismo emergente.<br><strong>Psicológico</strong><br>Hoteles con mentalidad de crecimiento pero que aun dependen de procesos manuales.<br><strong>Comportamiento</strong><br>Dueños de hoteles que prefieren suscripción mensual en vez de una inversión inicial alta.</td>
            <td><strong>Demográfico</strong><br>Hoteles de todos los tamaños, desde pequeños hasta grandes cadenas hoteleras. Empresarios y administradores hoteleros entre 30-55 años con experiencia en el sector y equipos administrativos con más de 10 empleados.<br><strong>Geográfico</strong><br>Cobertura nacional en Perú, con enfoque en Lima, Cusco, Arequipa y Piura. Potencial expansión a otros países de Latinoamérica con alta demanda de digitalización hotelera.<br><strong>Psicológico</strong><br>Empresas que buscan automatización total y centralización de procesos con una mentalidad analítica enfocada en reportes y dashboards para la toma de decisiones.<br><strong>Comportamiento</strong><br>Empresas que requieren facturación electrónica integrada con SUNAT y buscan reducir errores administrativos y mejorar la eficiencia operativa.</td>
            <td><strong>Demográfico</strong><br>Hoteles medianos con procesos aún manuales que requieren digitalización progresiva. Propietarios y gerentes de hotel entre 28-50 años con interés en modernización.<br><strong>Geográfico</strong><br>Foco en Perú, especialmente en regiones con menor adopción tecnológica y en zonas turísticas en crecimiento.<br><strong>Psicológico</strong><br>Hoteles tradicionales que buscan actualizarse pero sin cambiar por completo sus procesos, con propietarios acostumbrados a métodos manuales como Excel o cuadernos.<br><strong>Comportamiento</strong><br>Hoteleros que desean una solución sencilla para automatizar tareas administrativas repetitivas sin una transformación drástica.</td>
        </tr>
        <tr>
            <td>Estrategias de marketing</td>
            <td>Se introduce una propuesta innovadora con la integración de IoT, permitiendo a los huéspedes personalizar su experiencia mediante el control de iluminación, temperatura y entretenimiento desde una app móvil, como también la implementación de funciones ya conocidas en el mercado (facturación electrónica, automatizaciones, administración y monitoreo, etc). Además, se incorpora un equipo estrátegico de publicidad para compartir en redes sociales y permitir reseñas, teniendo énfasis en ciudades altamente turísticos. Para reducir preguntas y dudas, se incorpora una landing page con "Preguntas y respuestas" capaz de proporcionar información verídica sobre disponibilidad, promociones y posible asistencia personalizada.</td>
            <td>Su principal estrategia es el motor de reservas directo, que ayuda a los hoteles a aumentar sus ingresos hasta un 38% al recibir reservas sin intermediarios ni comisiones. También destacan por su facturación electrónica integrada con la SUNAT, facilitando la gestión contable. Se enfocan en el ahorro de tiempo, asegurando que su sistema reduce hasta 970 minutos mensuales en tareas operativas, optimizando el trabajo del personal.</td>
            <td>Se diferencian con integraciones adicionales como Motor de Reservas, Restaurante Smart y Housekeeping Smart, ampliando las funcionalidades del software. Además, ofrecen marketing digital para hoteles, incluyendo gestión de redes sociales y publicidad en Facebook Ads. Para generar confianza, permiten demostraciones gratuitas del sistema antes de la compra.</td>
            <td>Ofrecen una prueba gratuita de 14 días para que los clientes experimenten el sistema antes de comprometerse. Cuentan con planes de precios escalables desde S/7.50 por habitación, lo que permite flexibilidad según el tamaño del hotel. Se enfocan en la automatización, eliminando procesos manuales como cuadernos y hojas de Excel, mejorando la eficiencia operativa.</td>
        </tr>
        <tr>
            <td rowspan="3" style="writing-mode: vertical-lr; text-align: center;">Perfil de Producto</td>
            <td>Productos & Servicios</td>
            <td>
                SweetManager ofrece una solución integral para la gestión hotelera con un enfoque innovador basado en tecnología IoT. Permite a los huéspedes controlar el termostato de su habitación y acceder a opciones de entretenimiento desde una aplicación móvil personalizada, mejorando su experiencia y comodidad. Además, optimiza el consumo energético mediante sensores inteligentes y facilita la administración con herramientas de reservas, check-in/check-out, facturación electrónica y reportes analíticos en tiempo real.
            </td>
            <td>
                Xafiro es un software hotelero diseñado para la digitalización de la gestión de reservas, facturación electrónica y administración de hoteles. Cuenta con un motor de reservas directo para aumentar ingresos sin comisiones, gestión de habitaciones en tiempo real, reportes de ocupación y rendimiento, así como integración con la SUNAT para facturación electrónica.
            </td>
            <td>
                Samin PMS ofrece un sistema de gestión hotelera completo que abarca reservas, check-in/check-out, tarifas, housekeeping y facturación electrónica con SUNAT. Además, cuenta con módulos adicionales como Restaurante Smart y Housekeeping Smart, permitiendo automatizar y optimizar diferentes áreas del hotel. Proporciona reportes y métricas para mejorar la toma de decisiones estratégicas.
            </td>
            <td>
                Binz360 es una solución hotelera enfocada en la automatización de procesos administrativos y operativos. Incluye un dashboard centralizado con visualización de habitaciones, reportes financieros y de ventas, administración de tarifas y disponibilidad, módulos de caja y almacén, así como facturación electrónica integrada con la SUNAT. Su objetivo es eliminar tareas repetitivas y mejorar la eficiencia operativa del hotel.
            </td>
        </tr>
        <tr>
            <td>Precios & Costos</td>
            <td>
                SweetManager ofrece planes de suscripción mensual adaptados al tamaño del hotel. Su modelo flexible permite escalar servicios según las necesidades del cliente, con costos adicionales por integración de dispositivos IoT como termostatos y sistemas de entretenimiento.
            </td>
            <td>
                Xafiro maneja planes mensuales según el número de habitaciones y funcionalidades requeridas. Ofrece paquetes básicos y avanzados, con integración opcional de facturación electrónica a un costo adicional.
            </td>
            <td>
                Samin PMS cuenta con planes modulares según las necesidades del hotel. Su facturación electrónica y módulos adicionales pueden incluir costos extra dependiendo de la cantidad de habitaciones y usuarios.
            </td>
            <td>
                Binz360 ofrece una suscripción mensual basada en el número de habitaciones y servicios contratados. Dispone de precios diferenciados para hoteles pequeños y grandes, con opciones de personalización y soporte técnico avanzado.
            </td>
        </tr>
        <tr>
            <td>Canales de distribución (Web y/o Móvil)</td>
            <td>
                SweetManager está disponible como aplicación web y móvil, con una interfaz intuitiva optimizada para smartphones y tablets. Su integración con dispositivos IoT permite gestionar funciones del hotel en tiempo real desde cualquier dispositivo conectado.
            </td>
            <td>
                Xafiro opera principalmente como una plataforma web accesible desde cualquier navegador, con compatibilidad limitada para dispositivos móviles. Cuenta con una versión responsiva, pero sin aplicación móvil dedicada.
            </td>
            <td>
                Samin PMS ofrece una plataforma web con acceso adaptable a móviles. Algunos módulos cuentan con aplicaciones específicas para Android y iOS, enfocadas en la gestión operativa del hotel.
            </td>
            <td>
                Binz360 dispone de una plataforma web optimizada para distintos dispositivos. Su versión móvil permite acceder a funciones básicas de administración, pero la experiencia completa está diseñada para escritorio.
            </td>
        </tr>
        <tr>
            <td rowspan="4" style="writing-mode: vertical-lr; text-align: center;">Análisis SWOT</td>
            <td>Fortalezas</td>
            <td>
                Integración con IoT para control en tiempo real de temperatura, entretenimiento y automatización. <br>
                Aplicación móvil intuitiva con control total del hotel. <br>
                Facturación electrónica integrada con SUNAT. <br>
                Enfoque en sostenibilidad y eficiencia energética.
            </td>
            <td>
                Plataforma estable con amplia experiencia en el mercado. <br>
                Compatible con múltiples dispositivos. <br>
                Integración con sistemas contables y de reservas.
            </td>
            <td>
                Software con funcionalidades completas para gestión hotelera. <br>
                Aplicaciones móviles para tareas específicas. <br>
                Automatización de procesos administrativos.
            </td>
            <td>
                Enfoque en la digitalización de hoteles medianos y grandes. <br>
                Software intuitivo con opciones de personalización. <br>
                Adaptabilidad para distintos tipos de hoteles.
            </td>
        </tr>
        <tr>
            <td>Debilidades</td>
            <td>
                Nueva en el mercado, falta de reconocimiento frente a competidores. <br>
                Alto costo inicial debido a la implementación de IoT. <br>
                Dependencia de infraestructura tecnológica avanzada.
            </td>
            <td>
                Falta de una aplicación móvil completa. <br>
                Sistema menos flexible para pequeñas empresas. <br>
                Dependencia de integraciones externas para procesos avanzados.
            </td>
            <td>
                Curva de aprendizaje moderada para nuevos usuarios. <br>
                Algunas funcionalidades requieren costos adicionales. <br>
                No cuenta con una estrategia clara de expansión internacional.
            </td>
            <td>
                Dependencia de procesos automatizados sin diferenciación en innovación. <br>
                No ofrece herramientas avanzadas de personalización. <br>
                Plataforma con menos soporte para IoT.
            </td>
        </tr>
        <tr>
            <td>Oportunidades</td>
            <td>
                Expansión en mercados latinoamericanos con turismo en crecimiento. <br>
                Implementación de más dispositivos IoT para mayor automatización. <br>
                Asociación con cadenas hoteleras para integración exclusiva.
            </td>
            <td>
                Mejoras en su plataforma móvil para captar más usuarios. <br>
                Creación de nuevos módulos especializados en hotelería de lujo. <br>
                Expansión a mercados con menos competencia digital.
            </td>
            <td>
                Desarrollo de más integraciones con plataformas de pago y reservas. <br>
                Crecimiento del turismo y digitalización en la hotelería. <br>
                Enfoque en automatización avanzada para destacarse.
            </td>
            <td>
                Oportunidad de fortalecer la experiencia móvil y en la nube. <br>
                Posible adopción de nuevas tecnologías para optimizar procesos. <br>
                Crecimiento en mercados de hoteles boutique y pequeñas cadenas.
            </td>
        </tr>
        <tr>
            <td>Amenazas</td>
            <td>
                Competencia con marcas ya posicionadas en el mercado. <br>
                Posibles barreras de adopción tecnológica en hoteles tradicionales. <br>
                Dependencia de la estabilidad de las redes IoT.
            </td>
            <td>
                Avance de competidores con mejor integración móvil. <br>
                Cambios en regulaciones fiscales que afecten su facturación electrónica. <br>
                Crecimiento de soluciones más económicas en el mercado.
            </td>
            <td>
                Aparición de nuevas startups con innovación tecnológica superior. <br>
                Adaptación lenta a tendencias emergentes en hotelería. <br>
                Posible saturación del mercado con soluciones similares.
            </td>
            <td>
                Entrada de nuevas soluciones con mejor escalabilidad. <br>
                Cambios en preferencias de los hoteles hacia plataformas más flexibles. <br>
                Disminución de la inversión tecnológica en sectores hoteleros pequeños.
            </td>
        </tr>
    </tbody>
</table>




### 2.1.2. Estrategias y tácticas frente a competidores

1. Estrategias para afrontar las fortalezas de la competencia  
<ul>
    <li>Diferenciación tecnológica con IoT:  
        SweetManager integrará termostatos inteligentes, control de entretenimiento desde una app y sensores IoT para la automatización hotelera, ofreciendo una experiencia más innovadora y eficiente.
    </li>
    <li>Enfoque en la experiencia del usuario:  
        Mientras que los competidores se centran en la gestión administrativa, SweetManager también priorizará una interfaz moderna, intuitiva y adaptable, garantizando una mejor experiencia para los usuarios.
    </li>
</ul>

2. Estrategias ante las debilidades de la competencia  
<ul>
    <li>Planes escalables y flexibles:  
        Los competidores ofrecen precios fijos poco accesibles para hoteles pequeños. SweetManager implementará suscripciones modulares, permitiendo que cada cliente pague únicamente por las funcionalidades que necesite según el tamaño de su negocio.
    </li>
    <li>Mayor compatibilidad con diferentes dispositivos:  
        Mientras los competidores tienen interfaces limitadas, SweetManager optimizará su aplicación web y móvil para asegurar una experiencia fluida en cualquier dispositivo.
    </li>
</ul>

3. Estrategias para las oportunidades de la competencia  
<ul>
    <li>Asociaciones estratégicas con proveedores de IoT:  
        SweetManager establecerá alianzas con fabricantes de dispositivos IoT, como termostatos inteligentes, controles de entretenimiento y cerraduras electrónicas, para reducir costos de hardware, asegurar compatibilidad y mejorar la integración.
    </li>
    <li>Optimización del consumo energético:  
        La integración de dispositivos IoT con el sistema de energía del hotel permitirá un mejor control del consumo eléctrico, reduciendo significativamente los costos operativos.
    </li>
</ul>

4. Estrategias frente a las amenazas  
<ul>
    <li>Seguridad y privacidad:  
        Implementación de cifrado avanzado y estándares de protección de datos para garantizar confianza en la digitalización y evitar vulnerabilidades de seguridad.
    </li>
    <li>Asociaciones estratégicas con marketing:  
        Estrategia de marketing digital, publicidad y colaboraciones con influencers del sector hotelero para posicionar la marca y captar clientes antes de la expansión de los rivales.
    </li>
</ul>


## 2.2. Entrevistas

Las entrevistas son una herramienta fundamental para comprender las necesidades, deseos y desafíos de los usuarios, así como para validar las hipótesis y suposiciones del negocio. A través de las entrevistas, se pueden obtener valiosos conocimientos sobre las expectativas de los clientes, sus experiencias actuales y sus preferencias en cuanto a productos y servicios. En el caso de Sweet Manager, las entrevistas con propietarios, administradores y huéspedes serán fundamentales para diseñar una solución que se adapte a las necesidades del mercado y ofrezca un valor significativo a los usuarios.

### 2.2.1. Diseño de entrevistas

En esta sección se documentarán las preguntas que se utilizaron en nuestras entrevistas, conteniendo las preguntas generales que se comparten entre los segmentos objetivos, y las preguntas que fueron creadas específicamente para cada una.

**Preguntas complementarias generales**

- ¿Qué navegador usas con más frecuencia?

- ¿Qué dispositivo tecnológico usas con más frecuencia?

- ¿Cómo describes tu personalidad?

- ¿Presentas alguna frustración en el trabajo?

- ¿Cuáles son los canales de interacción que usas?

- ¿Qué tipo de ambiente de trabajo te resulta más motivador y productivo?

- ¿Cómo se llama el distrito o lugar de tu residencia?

- ¿Qué objetivos tienes tanto laboralmente como personalmente?

**Preguntas Segmento 1: Gerentes**

- ¿Cuáles son los principales desafíos que enfrentan en la gestión diaria de su hotel?

- ¿Qué caracteristicas o funcionalidades consideraría más utiles para mejorar la eficiencia de su hotel?

- ¿Cómo gestiona actualmente las reservas de habitaciones y el seguimiento de ingresos y gastos en su hotel?

- ¿Qué herramientas o software utilizan actualmente para la gestión hotelera y qué aspectos les gustaría mejorar de esas herramientas?

- ¿Qué aspectos valoran más al evaluar nuevas soluciones de software para su hotel?

- ¿Cómo crees que podríamos mejorar la comunicación y la colaboración del equipo?

- ¿Qué desafíos enfrentan al gestionar proveedores y controlar los inventarios en su hotel?

- ¿Cómo gestionan actualmente la satisfacción y las preferencias de los clientes en su hotel?

- ¿Cómo ve conveniente un sistema hotelero dedicado a la gestión de recursos, comunicación con proveedores, seguimiento de ganancias, etc?

**Preguntas Segmento 2: Administradores**

- ¿Qué herramientas o sistemas utilizan actualmente para realizar su trabajo y qué aspectos les resultan más difíciles o menos eficientes?

- ¿Qué características adicionales le gustaría ver en un sistema de gestión hotelera para facilitar su trabajo diario?

- ¿Cómo se sienten acerca de la adopción de nuevas tecnologías en el lugar de trabajo y cómo creen que podría mejorar su experiencia laboral?

- ¿Qué desafíos enfrenta al gestionar las solicitudes de los huéspedes y asegurarse de que se cumplan sus expectativas durante su estancia?

- ¿Cómo creen que podríamos simplificar los procesos de registro de huéspedes y check-in/check-out en su hotel?

- ¿Qué herramientas o recursos adicionales les ayudarán a ofrecer un mejor servicio a los huéspedes y mejorar su experiencia general en el hotel?

**Preguntas Segmento 3: Huéspedes**

- ¿Cómo sueles buscar y reservar un hotel cuando planeas un viaje?

- ¿Qué filtros o criterios son más importantes para ti al elegir un hotel? (precio, ubicación, servicios, etc.)

- ¿Alguna vez te has sentido frustrado al reservar una habitación en línea? ¿Qué sucedió?

- ¿Qué tanto valoras que una aplicación recuerde tus preferencias para futuras reservas?

- ¿Qué tipo de información o servicios te gustaría tener guardados en un perfil de usuario?

- ¿Te gustaría que la app te hiciera sugerencias de hoteles según tu historial o perfil?

- ¿Te gustaría tener acceso a un historial de todas tus reservas anteriores?

- ¿Te gustaría poder comunicarte con el personal del hotel directamente desde la app antes o durante tu estadía?

- ¿Qué tan importante es para ti tener la opción de cancelar una reserva de manera rápida y sencilla?

- ¿Has tenido la necesidad de reservar directamente al llegar a un hotel sin haberlo hecho en línea?

### 2.2.2. Registro de entrevistas

A continuación, se registraron todas las entrevistas realizadas para nuestra solución, categorizadas según su segmento objetivo, y con un resumen que destaca las características y críticas realizadas sobre nuestro proyecto.

Inicio: 0:00 <br><br>
Fin: 36:51

**Entrevista 01 (Gerentes)**

URL del Vídeo: 

Nombres: 

Apellidos:

Edad:

Sexo:

Ocupación:

Lugar donde vive: 

Duración de la entrevista: 

Personalidad: 

IMAGEN VA AQUI

En resumen, Carlo Rebagliati es un gerente de hotel con un largo camino de experiencia. Él es una persona analítica, comunicativa, empática y profesional que le importan las estadísticas y los beneficios y consecuencias de cada decisión. Nos relata que sus canales de comunicación preferidos son Whatssap, Zoom y cara a cara; adicionalmente, su navegador más frecuente es Google Chrome y usa Smartphone Android. Los principales desafíos que tiene su hotel es el llamado a los turistas desde provincia, ya que la mayoría de la clientela que tiene son turistas. Afortunadamente, está manteniendo a sus trabajadores motivados para que las bajas ventas por temporadas no afecte su rendimiento. Adicionalmente, mencionó que tienen una plataforma web donde los clientes realizan sus reservas, también tienen un área contable y administrativa para el seguimiento de ganancia y recursos. Finalmente, cree necesario una aplicación o software que se concentre en la gestión de un hotel, tanto para la comunicación, administración, gestión y seguimiento de recursos.

**Entrevista 02 (Gerentes)**

**Entrevista 03 (Gerentes)**

**Entrevista 01 (Administradores)**

**Entrevista 02 (Administradores)**

**Entrevista 03 (Administradores)**

**Entrevista 01 (Huéspedes)**

**Entrevista 02 (Huéspedes)**

**Entrevista 03 (Huéspedes)**

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

Para tener una mejor idea de cómo será la experiencia del usuario con nuestro producto, utilizaremos las herramientas de User Persona, User Task Matrix, User Journey Mapping, Empathy Mapping y As-is Scenario Mapping.

### 2.3.1. User Personas
<h2>User Persona Owner de Hotel</h2>
<div style="text-align: center;">
  <img src="./assets/img/user-persona/owner.jpeg" alt="User persona Owner" width="100%" />
</div>
<br><br>
<h2>User Persona Administrador de Hotel</h2>
<div style="text-align: center;">
  <img src="./assets/img/user-persona/admin.jpeg" alt="User persona Admin" width="100%" />
</div>
<br><br>
<h2>User Persona Huésped</h2>
<div style="text-align: center;">
  <img src="./assets/img/user-persona/huesped.jpeg" alt="User persona Huesped" width="100%" />
</div>


### 2.3.2. User Task Matrix

En esta parte se expone la User Task Matrix, una herramienta clave para reconocer cuáles son las tareas más relevantes y frecuentes que llevan a cabo los User Personas dentro de su ambiente laboral. Esta matriz nos permite observar y comparar las actividades de huéspedes, administradores y dueños; resaltando tanto sus diferencias como similitudes en cuanto a frecuencia e importancia. Gracias a este análisis, logramos entender mejor sus necesidades y retos, lo que nos permite enfocar el diseño del producto en las funcionalidades que realmente importan para su día a día.

| Task                         | Huésped (Frecuencia/Importancia) | Administrador (Frecuencia/Importancia) | Dueño (Frecuencia/Importancia) |
| ---------------------------- | -------------------------------- | -------------------------------------- | ------------------------------ |
| Reserva de habitaciones | Alta/Alta | Baja/Baja | Baja/Baja  |
| Gestión de reservas | Baja/Baja | Alta/alta | Media/Media  |
| Solicitud de servicio a las habitaciones | Alta/Alta | Baja/Baja | Baja/Baja  |
| Programación de limpieza de habitaciones | Baja/Baja | Alta/Alta | Baja/Media  |
| Registro de preferencias de temperatura e iluminación | Alta/Alta | Baja/Baja | Baja/Baja  |
| Negociación con proveedores | Baja/Baja | Media/Media | Alta/Alta |
| Gestión de las habitaciones | Baja/Baja | Alta/Alta | Alta/Alta |
| Gestión de las finanzas | Baja/Baja | Media/Media | Alta/Alta  |
| Administración de recursos | Baja/Baja | Alta/Alta | Alta/Alta |
| Comunicación y organización constante | Baja/Baja | Alta/Alta | Alta/Alta |
| Solicitud de abastecimiento | Baja/Baja | Media/Alta | Alta/Alta |
| Control de entradas y salidas | Baja/Baja | Alta/Alta | Media/Alta |

### 2.3.3. User Journey Mapping

Esta sección expone los User Journey Mapping correspondientes a cada perfil de usuario, destacando las etapas principales de interacción con SweetManager, los puntos de contacto implicados y las emociones y experiencias vividas en cada fase. El propósito es detectar áreas de mejora y perfeccionar la experiencia del usuario. A continuación, se detallan los recorridos de usuario para cada uno de los perfiles definidos.

__User Journey Mapp - NOMBRE - Owner (As-Is)__

__Inicio del día:__ El owner comienza el día revisando el dashboard general para tener una visión clara del estado del hotel. Se siente presionado por mantenerse al tanto de todo lo que ocurre y asegurarse de que no haya inconvenientes operativos.
__Gestión de abastecimientos:__ Luego verifica los niveles de inventario y se encarga de solicitar lo necesario para mantener el hotel abastecido. Esta tarea le genera frustración debido a la falta de automatización y seguimiento eficiente en el sistema actual.
__Comunicación general:__ Revisa los mensajes y notificaciones pendientes del equipo de trabajo. Aunque valora estar informado, se siente abrumado por tener que responder a múltiples temas sin una bandeja de entrada organizada.
__Cierre del día:__ Finaliza el día con una revisión rápida del dashboard para asegurarse de que todo esté encaminado para el día siguiente. Experimenta una mezcla de tranquilidad y agotamiento, esperando mejoras en la gestión diaria.

<div style="text-align: center;">
  <img src="https://i.imgur.com/XEmHh7U.png" alt="Imagen del Journey Mapp Owner" width="70%" />
</div>

__User Journey Map - NOMBRE - Admin (As-Is)__

__Inicio del turno:__ La administradora inicia su jornada revisando las reservas activas del día. Se siente presionada por garantizar una buena experiencia para cada huésped y por evitar errores en el check-in.
__Gestión de reservas:__ Administra nuevas reservas, edita datos de huéspedes y responde consultas. Experimenta cierta ansiedad debido a la interfaz poco amigable del sistema actual, lo que le toma más tiempo del necesario.
__Comunicación con el owner:__ Debe informar al owner sobre cambios importantes o incidencias. Aunque es parte de sus responsabilidades, se siente frustrada cuando no obtiene respuestas rápidas, lo que complica su capacidad de reacción.
__Soporte al huésped:__ Atiende directamente a los huéspedes con solicitudes especiales o problemas durante su estancia. Esta parte le resulta gratificante, aunque también puede volverse estresante en horas pico.
__Fin del turno:__ Revisa que las tareas estén completas y deja notas para el siguiente turno. Termina el día con una mezcla de satisfacción por el trabajo bien hecho y cansancio por la carga operativa.

<div style="text-align: center;">
  <img src="https://i.imgur.com/dlJetpy.png" alt="Imagen del Journey Mapp Admin" width="70%" />
</div>


__User Journey Map - NOMBRE - Huésped  (As-Is)__

__Inicio de la experiencia:__ Sebastián encuentra el hotel a través de redes sociales o plataformas externas. Ingresa al sitio web o app para hacer una reserva. Se siente confundido al no encontrar un proceso claro y rápido para completar su reserva.
__Proceso de reserva:__ Llena el formulario de reserva, selecciona fechas y tipo de habitación. Se siente impaciente si el sistema se demora o si no puede pagar de inmediato.
__Pago:__ Intenta realizar el pago en línea, pero el sistema no siempre es intuitivo o confiable. Esto le genera inseguridad y dudas sobre la confirmación de su reserva.
Estancia: Durante su estadía, valora la comodidad del hotel, pero siente que podría haber más comunicación proactiva desde el staff o vía mensajes automáticos para guiarlo mejor.
__Fin de la experiencia:__ Al terminar su estancia, espera recibir un comprobante y tener la opción de dejar una reseña. Si el proceso es fluido, se va satisfecho; si no, puede irse con una percepción negativa del servicio digital.

<div style="text-align: center;">
  <img src="https://i.imgur.com/ApJq6TJ.png" alt="Imagen del Journey Mapp Huesped" width="70%" />
</div>

### 2.3.4. Empathy Mapping

<h2>Empathy Map del Dueño de hotel</h2>
<div style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
    <img src="./assets/img/empathy-mapping/owner.png" alt="Empathy Map Dueño">
</div><br>
<p>En este mapa de empatía, se ha representado al dueño como el principal administrador de la aplicación. El dueño busca comodidad para sus clientes y la aplicación tiene como objetivo disminuir su carga de trabajo al gestionar los trámites de los huéspedes.</p>
<br><br>
<h2>Empathy Map del Administrador</h2>
<div style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
    <img src="./assets/img/empathy-mapping/admin.png" alt="Empathy Map Administrador">
</div><br>
<p>En este mapa de empatía, se ha representado al administrador como usuario que recibiría ayuda por parte de la aplicación. El administrador busca una experiencia de gestión cómoda y sin complicaciones para el cliente principal, y la aplicación tiene como objetivo facilitar esos procesos.</p>
<br><br>
<h2>Empathy Map del Huésped</h2>
<div style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
    <img src="./assets/img/empathy-mapping/client.png" alt="Empathy Map Huesped">
</div><br>
<p>En este mapa de empatía, se ha representado al huésped como el usuario principal de la aplicación. El usuario busca una experiencia de viaje cómoda y sin complicaciones, y la aplicación tiene como objetivo facilitar su proceso de gestión de trámites al visitar un hotel del país.</p>

### 2.3.5. As-is Scenario Mapping

En esta sección se presentan los Scenario Mapping de los segmentos objetivos: Huésped, Administrador y Dueño, que describen las experiencias actuales de los usuarios potenciales en sus actividades diarias.

#### As-is Scenario Mapping Huésped:

![As-is Scenario Mapping Guest](assets/img/as-is-scenario-mapping/guest-as-is.png)

#### As-is Scenario Mapping Administrador:

![As-is Scenario Mapping Manager](assets/img/as-is-scenario-mapping/manager-as-is.png)

#### As-is Scenario Mapping Dueño:

![As-is Scenario Mapping Owner](assets/img/as-is-scenario-mapping/owner-as-is.png)

El enlace de LucidChart en el que fueron desarrollados es el siguiente: https://lucid.app/lucidchart/429f68af-693f-4eb9-8468-fbe7483400c3/edit?viewport_loc=-124%2C40%2C2239%2C1205%2C0_0&invitationId=inv_b81ad239-80ca-44d9-b7d6-b91638411afb

## 2.4. Ubiquitous Language

Esta sección contiene un glosario de términos y conceptos definidos sin ambigüedad utilizados en el dominio. Su propósito es garantizar una comunicación clara y consistente entre todos los miembros del equipo y los stakeholders, tal como lo establece Eric Evans en su libro Domain-Driven Design: Tackling Complexity in the Heart of Software.

| Término (Inglés)         | Término (Español)            | Definición |
|--------------------------|------------------------------|------------|
| **Check-In**             | (Registro de entrada)        | Proceso mediante el cual un huésped se registra al llegar al hotel, proporciona sus datos y recibe acceso a su habitación. |
| **Check-Out**            | (Salida del huésped)         | Proceso mediante el cual el huésped finaliza su estadía, paga su cuenta y devuelve la llave o tarjeta. |
| **Reservation**          | (Reserva)                    | Acción mediante la cual un huésped aparta una habitación para fechas específicas. |
| **Reservation Status**   | (Estado de la reserva)       | Condición actual de una reserva, como confirmada, pendiente, cancelada o completada. |
| **Reservation Type**     | (Tipo de reserva)            | Clasificación de la reserva según su fuente o condiciones, por ejemplo: directa, en línea, grupal o por agencia. |
| **Availability**         | (Disponibilidad)             | Cantidad de habitaciones libres para reservar en un rango de fechas determinado. |
| **No-show**              | (No presentación)            | Caso en el que un huésped con reserva confirmada no se presenta en el hotel. |
| **House Rules**          | (Reglamento del hotel)       | Normas y políticas internas que deben seguir los huéspedes durante su estadía. |
| **Housekeeping**         | (Limpieza)                   | Departamento encargado de la limpieza, arreglo y mantenimiento diario de las habitaciones. |
| **Inventory Management** | (Gestión de inventario)      | Control del suministro de productos y materiales necesarios para el funcionamiento del hotel. |


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se presentan los Scenario Mapping de los segmentos objetivos: Huéspedes, Administradores y Dueños, que describen cómo serán las interacciones, tareas y actividades de los usuarios una vez implementado y utilizado el sistema. De este modo, se proporciona una visión general de las características de la aplicación.

#### To-be Scenario Mapping Huésped:

![To-be Scenario Mapping Guest](assets/img/to-be-scenario-mapping/guest-to-be.png)

#### To-be Scenario Mapping Administrador:

![To-be Scenario Mapping Manager](assets/img/to-be-scenario-mapping/manager-to-be.png)

#### To-be Scenario Mapping Dueño:

![To-be Scenario Mapping Owner](assets/img/to-be-scenario-mapping/owner-to-be.png)

El enlace de LucidChart en el que fueron desarrollados es el siguiente: https://lucid.app/lucidchart/8cc2ff7d-f132-4d27-b515-1662e7c51001/edit?viewport_loc=179%2C-140%2C2360%2C1270%2C0_0&invitationId=inv_7ae99d2c-7dba-4432-948a-2e6151bb969e

## 3.2. User Stories

Redactamos las historias de usuario para el sistema de gestión hotelera basándonos en las necesidades y desafíos identificados en las entrevistas y el análisis de los segmentos de gerentes, administradores y huéspedes. Las historias de usuario describen las funcionalidades y características que los usuarios finales esperan del sistema, y se utilizan para guiar el diseño y desarrollo del producto.

<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> EP1 </td>
      <td> Información del producto </td>
      <td> Como visitante del sitio web, quiero obtener información relacionada al producto que se ofrece. </td>
      <td><b>Given</b> el visitante está en la landing page. <br/><b>When</b> observa la información relevante sobre la empresa. <br><b>Then</b> se interesa en saber más sobre el producto <br><b>Y</b> se redirecciona a la aplicación web/móvil.</td>
      <td></td>
    </tr>
    <tr>
      <td>HU01</td>
      <td>Obtener información de la empresa</td>
      <td>Como visitante del sitio web, quiero obtener información adicional sobre la empresa a cargo del producto.</td>
      <td><b>Given</b> el visitante se encuentra en la sección de nosotros.<br/><b>When</b> observa la información relevante sobre la empresa. <br><b>Then</b> se interesa en saber más sobre el producto.<br><b>Y</b> se redirecciona a la aplicación web/móvil.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU02</td>
      <td>Informarse sobre los beneficios del producto</td>
      <td>Como visitante del sitio web, quiero informarme sobre los beneficios del producto ofrecido.</td>
      <td><b>Given</b> el visitante se encuentra en la sección de beneficios. <br><b>When</b> observa los beneficios que se ofrecen al usar una solución.<br><b>Then</b> se interesa en saber más del producto.<br><b>Y</b> se redirecciona a la aplicación web/móvil.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU03</td>
      <td>Conocer los testimonios de los clientes pasados</td>
      <td>Como visitante, quiero accceder a los testimonios de clientes anteriores para evaluar la experiencia y la calidad de atención al cliente.</td>
      <td><b>Given</b> el visitante se encuentra en la sección de testimonios.<br><b>When</b> observa los diferentes testimonios. <br><b>Then</b> evalúa la experiencia y desempeño del personal basado en los comentarios de clientes previos. <br><b>Y</b> se redirecciona a la aplicación web/móvil.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU04</td>
      <td>Informarse sobre los diferentes planes de subscripción</td>
      <td>Como visitante, quiero conocer los diferentes planes de subscripción disponibles para determinar cuál se ajusta a mis necesidades.</td>
      <td><b>Given</b> el visitante se encuentra en la sección de planes de subscripción disponibles. <br><b>When</b> visualiza los diferentes planes<br><b>Then</b> puede determinar su plan de subscripción ideal.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Crear organización</td>
      <td>Como usuario quiero crear una organización para pertenecer a ella y utilizar los servicios de Sweet Manager.</td>
      <td><b>Given</b> el usuario se encuentra en el Login. <b>When</b> presiona en el botón "SignUp" e ingresa sus datos. <br><b>Then</b> empezará con un flujo de páginas en donde inicializará las reglas de su organización y su plan de subscripción.</td>
      <td></td>
    </tr>
    <tr>
      <td>HU01</td>
      <td>Crear cuenta</td>
      <td>Como gerente quiero registrar una cuenta para poder gestionar las finanzas, abastecimientos e información relevante de mi hotel.</td>
      <td>
        <b>GERENTE</b>
        <br>
        <b>Given</b> el usuario ingrese sus datos de hotel y gerente. 
        <br>
        <b>When</b> se paga el plan y se inicializa correctamente la organización.
        <br>
        <b>Then</b> se muestra un mensaje de bienvenida.
        <br><b>Y</b> se redirecciona al dashboard.
        <br>
        <b>ADMINISTRADOR</b>
        <br>
        <b>Given</b> el gerente lo invitó a su organización.
        <br>
        <b>When</b> acepta la invitación y se redirecciona a la aplicación.
        <br>
        <b>Then</b> se muestra un mensaje de bienvenida.
        <br><b>Y</b> se redirecciona al perfil de su cuenta.
        <br>
        <b>HUÉSPED</b>
        <br>
        <b>Given</b> el huésped está por reservar una habitación.
        <br>
        <b>When</b> el sistema le pide registrar una cuenta personal.
        <br>
        <b>Then</b> registra su cuenta personal.
        <br><b>Y</b> registra su reserva correctamente.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Gestionar las finanzas, abastecimientos e información de la organización.</td>
      <td>Como gerente del hotel quiero actualizar y revisar las finanzas, recursos y abastecimientos del hotel para mantener un seguimiento de estos.</td>
      <td><b>Given</b> el gerente está conectado.<br><b>When</b> revisa las finanzas y recursos.<br><b>Then</b> crea peticiones de abastecimiento y/o comunica con sus administradores.</td>
      <td></td>
    </tr>
    <tr>
      <td>HU01</td>
      <td>Revisar ingresos y egresos de la organización</td>
      <td>Como gerente del hotel quiero revisar las finanzas en términos de ingresos y egresos de mi hotel para mantener un constante seguimiento de estos.</td>
      <td><b>Given</b> el gerente está conectado a su cuenta.<br><b>When</b> se encuentra en el dashboard.<br><b>Then</b> revisa los ingresos y egresos<br><b>Y</b> escoge el plazo semanal o mensual de finanzas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>HU02</td>
      <td>Revisar stock de recursos del hotel</td>
      <td>Como gerente del hotel quiero revisar el stock actual de los recursos para tomar una decisión de abastecimiento.</td>
      <td><b>Given</b> el gerente está en la página de recursos.<br><b>When</b> nota que uno de sus recursos está por agotar el stock.<br><b>Then</b> contacta a su proveedor y crea una solicitud de abastecimiento.</td>
      <td>EP03</td>
    </tr>
    <!-- Row 11 -->
    <tr>
      <td>HU03</td>
      <td>Comunicarse con sus administradores.</td>
      <td>Como gerente del hotel quiero enviar mensajes a cualquiera de mis administradores para mantener comunicación interna.</td>
      <td><b>Given</b> el gerente está en la página de mensajería.<br><b>When</b> quiere enviar mensaje a sus administradores.<br><b>Then</b> redacta el asunto y cuerpo del mensaje.<br><b>Y</b> lo envía a todos los administradores.</td>
      <td>EP03</td>
    </tr>
    <!-- Row 12 -->
    <tr>
      <td>HU04</td>
      <td>Mejorar la subscripción de la organización.</td>
      <td>Como gerente del hotel quiero mejorar/cambiar la subscripción de la organización para ajustarla a nuestras necesidades actuales.</td>
      <td><b>Given</b> el gerente está en la página de subscripciones.<br><b>When</b> quiere mejorar o degradar la subscripción actual. <b>Then</b> entra a la página para cambiar la subscripción actual y aceptar los términos y condiciones.</td>
      <td>EP03</td>
    </tr>
    <!-- Row 13 -->
    <tr>
      <td>HU05</td>
      <td>Invitar administradores a su organización.</td>
      <td>Como gerente del hotel quiero invitar administradores a mi organización para que tengan acceso al servicio.</td>
      <td><b>Given</b> el gerente está en la página de administradores<br><b>When</b> quiere invitar a un nuevo administrador a la organización.<br><b>Then</b> Invita mediante su correo electrónico a la organización.</td>
      <td>EP03</td>
    </tr>
    <!-- Row 14 -->
    <tr>
      <td>HU06</td>
      <td>Agregar proveedores a su lista de contactos.</td>
      <td>Como gerente del hotel quiero agregar proveedor a mi lista de contactos para tener su información guardada en caso la necesite.</td>
      <td><b>Given</b> el gerente está en la página de proveedores<br><b>When</b> quiere registrar un nuevo proveedor a la lista de contacto.<br><b>Then</b> Registra su información de contacto.</td>
      <td>EP03</td>
    </tr>
    <!-- Row 15 -->
    <tr>
      <td>EP04</td>
      <td>Gestionar las reservas y comunicación en la organización.</td>
      <td>Como administrador del hotel quiero administrar las reservas de los huéspedes y comunicación adecuada con el dueño para potenciar el desempeño del hotel.</td>
      <td><b>Given</b> el administrador está en la página de reservas<br><b>When</b> está atendiendo a un huésped.<br><b>Then</b> Actualiza el estado de la reserva.</td>
      <td></td>
    </tr>
    <!-- Row 16 -->
    <tr>
      <td>HU01</td>
      <td>Gestionar reservas de huéspedes</td>
      <td>Como administrador del hotel, quiero gestionar las reservas de los huéspedes para verificar disponibilidad, realizar check-in y check-out, y asegurar una correcta administración.</td>
      <td>
        <b>Escenario 1:</b> Ver listado de reservas<br>
        <em>Given</em> que el administrador accede a la página de reservas<br>
        <em>When</em> se cargan las reservas activas<br>
        <em>Then</em> el sistema muestra una lista con nombre del huésped, fechas y estado.<br><br>
        <b>Escenario 2:</b> Check-in<br>
        <em>Given</em> que el huésped ha llegado al hotel<br>
        <em>When</em> el administrador actualiza la reserva<br>
        <em>Then</em> el sistema marca la reserva como "En curso".<br><br>
        <b>Escenario 3:</b> Check-out<br>
        <em>Given</em> que el huésped ha finalizado su estadía<br>
        <em>When</em> el administrador registra la salida<br>
        <em>Then</em> el sistema marca la reserva como "Completada".
      </td>
      <td>EP04</td>
    </tr>
    <!-- Row 17 -->
    <tr>
      <td>HU02</td>
      <td>Enviar mensajes al dueño</td>
      <td>Como administrador del hotel, quiero comunicarme con el dueño mediante mensajes internos para reportar incidencias, solicitar aprobación o compartir información importante.</td>
      <td>
        <strong>Escenario:</strong> Envío de mensaje<br>
        <em>Given</em> que el administrador está en la sección de mensajería<br>
        <em>When</em> desea enviar un mensaje al dueño<br>
        <em>Then</em> redacta el asunto y contenido<br>
        <em>Y</em> el mensaje se guarda y notifica al dueño en su bandeja.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU03</td>
      <td>Ver huéspedes alojados actualmente</td>
      <td>Como administrador del hotel, quiero ver una lista de los huéspedes que están actualmente alojados para tener un control en tiempo real de la ocupación.</td>
      <td>
        <b>Escenario:</b> Ver huéspedes alojados<br>
        <em>Given</em> que el administrador está en la sección de reservas activas<br>
        <em>When</em> accede a la pestaña de huéspedes actuales<br>
        <em>Then</em> el sistema muestra una lista con nombre del huésped, habitación asignada y fechas de estadía.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU04</td>
      <td>Consultar disponibilidad de habitaciones</td>
      <td>Como administrador del hotel, quiero consultar la disponibilidad de habitaciones para asignar correctamente a los nuevos huéspedes.</td>
      <td>
        <b>Escenario:</b> Consultar disponibilidad<br>
        <em>Given</em> que el administrador desea verificar habitaciones disponibles<br>
        <em>When</em> filtra por tipo y fecha<br>
        <em>Then</em> el sistema muestra una lista de habitaciones libres para esas fechas.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU05</td>
      <td>Generar reporte de reservas del día</td>
      <td>Como administrador del hotel, quiero generar un reporte diario de reservas para tener un resumen de entradas y salidas.</td>
      <td>
        <b>Escenario:</b> Descargar reporte diario<br>
        <em>Given</em> el administrador desea generar reporte diario<br>
        <em>When</em> hace clic en "Generar reporte"<br>
        <em>Then</em> el sistema genera un archivo con las reservas del día, estado, nombre del huésped y habitación asignada.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU06</td>
      <td>Registrar reserva presencial</td>
      <td>Como administrador del hotel, quiero crear una reserva manualmente cuando un huésped llega sin haber hecho una reserva previa, para registrarlo en el sistema.</td>
      <td>
        <b>Escenario:</b> Registrar nueva reserva desde recepción<br>
        <em>Given</em> que el huésped llega al hotel sin reserva<br>
        <em>When</em> el administrador accede al formulario de nueva reserva<br>
        <em>Then</em> completa los datos del huésped, habitación y fechas<br>
        <em>Y</em> el sistema crea la reserva como "En curso".
      </td>
      <td>EP04</td>
    </tr>
    <!-- Row 18 -->
    <tr>
      <td>EP05</td>
      <td>Crear perfil global para SweetManager y realizar reservas fácilmente.</td>
      <td>Como huésped de Sweet Manager</td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 19 -->
    <tr>
      <td>HU01</td>
      <td>Crear perfil global en SweetManager</td>
      <td>Como huésped quiero crear un perfil global para guardar mis preferencias y usarlas en futuras reservas.</td>
      <td>
        <strong>Escenario 1:</strong> Registro de huésped.<br>
        <em>Given</em> que el huésped no tiene una cuenta<br>
        <em>When</em> completa el formulario de registro con su información personal<br>
        <em>Then</em> el sistema debe crear un perfil asociado y almacenar sus datos de forma segura.<br><br>
        <strong>Escenario 2:</strong> Configuración de preferencias.<br>
        <em>Given</em> que el huésped tiene una cuenta activa<br>
        <em>When</em> accede a la sección de preferencias y establece opciones como temperatura o tipo de habitación<br>
        <em>Then</em> el sistema debe guardar esas preferencias para usarlas automáticamente en futuras reservas.
      </td>
      <td></td>
    </tr>
    <!-- Row 20 -->
    <tr>
      <td>HU02</td>
      <td>Buscar y filtrar hoteles de Sweet Manager</td>
      <td>Como huésped quiero filtrar y buscar hoteles según mis preferencias para encontrar un hotel adecuado.</td>
      <td>
        <b>Escenario 1:</b> Buscar hoteles por nombre o ciudad.<br>
        <em>Given</em> que el huésped está en la página de búsqueda de hoteles<br>
        <em>When</em> escribe un nombre de hotel o ciudad en el campo de búsqueda<br>
        <em>Then</em> el sistema debe mostrar una lista de hoteles que coincidan con los criterios.<br><br>
        <b>Escenario 2:</b> Aplicar filtros de preferencia.<br>
        <em>Given</em> que el huésped está visualizando la lista de hoteles<br>
        <em>When</em> selecciona filtros como tipo de habitación<br>
        <em>Then</em> el sistema debe actualizar la lista mostrando solo los hoteles que cumplan con esas condiciones.
      </td>
      <td>EP05</td>
    </tr>
    <!-- Row 21 -->
    <tr>
      <td>HU03</td>
      <td>Reservar una habitación</td>
      <td>Como huésped quiero reservar habitaciones para asegurarme tener un alojamiento durante mi estancia.</td>
      <td>
        <b>Escenario 1:</b> Selección de fechas.<br>
        <em>Given</em> que el huésped está en la página de reservas del hotel<br>
        <em>When</em> selecciona una fecha de entrada y una de salida válidas<br>
        <em>Then</em> el sistema debe mostrar las habitaciones disponibles para ese rango de fechas.<br><br>
        <b>Escenario 2:</b> Cálculo de precio.<br>
        <em>Given</em> que el huésped ha seleccionado una habitación y un rango de fechas<br>
        <em>When</em> el sistema calcula el precio<br>
        <em>Then</em> debe mostrar el precio total basado en el número de noches y el precio por noche.<br><br>
        <b>Escenario 3:</b> Confirmación de reserva.<br>
        <em>Given</em> que el huésped ha revisado los detalles de la reserva<br>
        <em>When</em> confirma la reserva y realiza el pago<br>
        <em>Then</em> el sistema debe guardar la reserva y mostrar una confirmación al huésped.
      </td>
      <td>EP05</td>
    </tr>
    <!-- Row 22 -->
    <tr>
      <td>HU04</td>
      <td>Visualizar reservas activas</td>
      <td>Como huésped quiero visualizar mis reservas activas para saber cúando y dónde me hospedaré</td>
      <td>
        <b>Escenario 1:</b> Visualización de reservas.<br>
        <em>Given</em> que el huésped ha iniciado sesión.
        <em>When</em> accede a la vista de reservas activas.
        <em>Then</em> el sistema muestra sus reservas activas con fechas, hotel y tipo de habitación (detalle de reserva).
      </td>
      <td>EP05</td>
    </tr>
    <!-- Row 23 -->
    <tr>
      <td>HU05</td>
      <td>Cancelar reserva</td>
      <td>Como huésped quiero cancelar una de mis reservas para evitar costos innecesarios si mis planes cambian.</td>
      <td>
        <b>Escenario 1:</b> Cancelación dentro del plazo permitido<br>
        <em>Given</em> que el huésped tiene una reserva activa y aún está dentro del plazo de cancelación gratuita.<br>
        <em>When</em> accede a su lista de reservas activas y selecciona la opción de cancelar la reserva.<br>
        <em>Then</em> el sistema debe cancelar la reserva y mostrar un mensaje de confirmación.<br><br>
        <b>Escenario 2:</b> Registro de cancelación<br>
        <em>Given</em> que una reserva ha sido cancelada<br>
        <em>When</em> el huésped consulta su historial<br>
        <em>Then</em> debe ver la reserva como cancelada con la fecha y motivo (si se solicita).
      </td>
      <td>EP05</td>
    </tr>
    <!-- Row 24 -->
    <tr>
      <td>HU06</td>
      <td>Ver historial de reservas</td>
      <td>Como huésped quiero ver mi historial de reservas para revisar mis viajes pasados y tener un registro de mis estadías.</td>
      <td>
        <b>Escenario 1:</b> Visualizar historial completo<br>
        <em>Given</em> que el huésped ha iniciado sesión en la aplicación<br>
        <em>When</em> accede a la sección "Historial de reservas"<br>
        <em>Then</em> el sistema debe mostrar una lista con todas las reservas anteriores, incluyendo fecha, hotel y estado (completada o cancelada).<br><br>
        <b>Escenario 2:</b> Visualizar detalles de una reserva específica<br>
        <em>Given</em> que el huésped está viendo su historial<br>
        <em>When</em> selecciona una reserva de la lista<br>
        <em>Then</em> el sistema debe mostrar los detalles: hotel, habitación, fechas, monto pagado y todo el detalle.
      </td>
      <td>EP05</td>
    </tr>
    <!-- Row 25 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 26 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 27 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 28 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 29 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Row 30 -->
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 3.3. Impact Mapping

Impact Mapping es una metodología visual que facilita la identificación clara de los objetivos que realmente queremos alcanzar para conectar efectivamente con nuestros usuarios. Utilizamos esta herramienta para mantener el enfoque y asegurar que trabajamos en función de nuestras metas principales. Así, al finalizar el mapa mental, logramos definir las acciones y funcionalidades necesarias para desarrollar el proyecto de forma eficiente.

__Business goal:__

Alcanzar 50 organizaciones creadas en Sweet Manager en un plazo de 3 meses.

<div style="text-align: center;">
  <img src="https://i.imgur.com/s6SZV6g.png" alt="Imagen del impact map del Owner" width="90%" />
</div>

__Business goal:__
Reducir el tiempo promedio de reserva de habitaciones en un 40% durante los próximos 3 meses
<div style="text-align: center;">
  <img src="https://i.imgur.com/sVpHaE0.png" alt="Imagen del impact map del Owner" width="90%" />
</div>

__Business goal:__
Optimizar el 60% de las reservas realizadas por huéspedes en un plazo de 4 meses.
<div style="text-align: center;">
  <img src="https://i.imgur.com/iiLV6BD.png" alt="Imagen del impact map del Owner" width="90%" />
</div>

## 3.4. Product Backlog

| Orden | User Story ID | Título                                                    | Descripción                                                                                                  | Story Points (1/2/3/5/8) |
|-------|---------------|------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|--------------------------|
| 1     | HU01          | Gestionar las reservas en la organización                  | Como administrador del hotel quiero gestionar las reservas de los huéspedes para asegurar la correcta gestión de las mismas. | 5                        |
| 2     | HU03          | Reservar una habitación                                    | Como huésped quiero reservar habitaciones para asegurarme tener un alojamiento durante mi estancia.         | 5                        |
| 3     | HU01          | Revisar ingresos y egresos de la organización              | Como gerente quiero registrar una cuenta para poder gestionar las finanzas, abastecimientos e información relevante de mi hotel. | 3                        |
| 4     | HU02          | Revisar stock de recursos del hotel                        | Como gerente del hotel quiero revisar el stock actual de los recursos para tomar una decisión de abastecimiento. | 3                        |
| 5     | HU06          | Agregar proveedores a su lista de contactos                | Como gerente del hotel quiero agregar proveedor a mi lista de contactos para tener su información guardada en caso la necesite. | 3                        |
| 6     | HU02          | Gestionar la comunicación en la organización               | Como administrador del hotel quiero comunicarme con el dueño mediante mensajes internos de la aplicación para algún caso lo requiera. | 3                        |
| 7     | HU02          | Informarse sobre los beneficios del producto               | Como visitante del sitio web, quiero informarme sobre los beneficios del producto ofrecido.                  | 2                        |
| 8     | HU04          | Informarse sobre los diferentes planes de subscripción     | Como visitante, quiero conocer los diferentes planes de subscripción disponibles para determinar cuál se ajusta a mis necesidades. | 2                        |
| 9     | HU03          | Comunicarse con sus administradores                        | Como gerente del hotel quiero enviar mensajes a cualquiera de mis administradores para mantener comunicación interna. | 2                        |
| 10    | HU04          | Mejorar la subscripción de la organización                 | Como gerente del hotel quiero mejorar/cambiar la subscripción de la organización para ajustarla a nuestras necesidades actuales. | 2                        |
| 11    | HU05          | Invitar administradores a su organización                  | Como dueño, quiero añadir administradores a mi organización para delegar tareas.                             | 2                        |
| 12    | HU02          | Buscar y filtrar hoteles de Sweet Manager                  | Como huésped quiero filtrar y buscar hoteles según mis preferencias para encontrar un hotel adecuado.       | 2                        |
| 13    | HU01          | Obtener información de la empresa                          | Como visitante del sitio web, quiero obtener información adicional sobre la empresa a cargo del producto.   | 1                        |
| 14    | HU03          | Conocer los testimonios de los clientes pasados            | Como visitante, quiero acceder a los testimonios de clientes anteriores para evaluar la experiencia y la calidad de atención al cliente. | 1                        |
| 15    | HU01          | Crear perfil global en SweetManager                        | Como huésped quiero crear un perfil global para guardar mis preferencias y usarlas en futuras reservas.     | 1                        |
| 16    | HU01          | Crear cuenta                                               | Como gerente quiero registrar una cuenta para poder gestionar las finanzas, abastecimientos e información relevante de mi hotel. | 1                        |




# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming
recomiendo echarle un ojo a estos: 
https://learning.oreilly.com/library/view/learning-domain-driven-design/9781098100124/ch12.html
https://learning.oreilly.com/library/view/patterns-principles-and/9781118714706/part03.xhtml
https://domainstorytelling.org/#dst-requirements
https://openpracticelibrary.com/practice/event-storming/ 
#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: *<Bounded Context Name>*

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Layer

#### 4.2.X.3. Application Layer

#### 4.2.X.4. Infrastructure Layer

#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.X.6.2. Bounded Context Database Design Diagram

# Conclusiones

## Recomendaciones

# Video About-the-Team

# Bibliografía
- Gothelf, J., & Seiden, J. (2021). Lean UX, 3rd Edition. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/
- Progressa Lean. (2014). 5W+2H Técnica de análisis de problemas - Progressa Lean. Progressa Lean. https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/
- UX Planet. (2017). Information Architecture. Basics for Designers. - UX Planet. Medium; UX Planet. https://uxplanet.org/information-architecture-basics-for-designers-b5d43df62e20
- Gothelf, J. (2024). Leanux Sampler. https://es.scribd.com/document/655516553/Leanux-Sampler
#Anexos


