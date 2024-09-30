# Asset Security o Seguridad de Activos

Bienvenidos a la guia de seguridad de activos realizada gracias al [curso](https://www.coursera.org/learn/assets-threats-and-vulnerabilities/) de Google de Ciberseguridad 

## Introducción a la seguridad de activos

Para enfrentarnos a la seguridad de los activos hemos de tener 3 conceptos clave muy claros: **Riesgo, Amenaza, Vulnerabilidad.** Anteriormente ya hemos definido estos [conceptos](https://github.com/Ramonperu/ManageSecRisk-GoogleCybersec) por encima pero vamos a ampliar la definicion acompañándolo de la seguridad de los activos.

### **Riesgo de seguridad**

Cualquier cosa que pueda afectar negativamente a la confidencialidad, integridad o disponibilidad de un activo.

- **Perspectiva organizacional:** Diferentes organizaciones valoran diferentes activos y, por lo tanto, perciben el riesgo de manera diferente.

- **Cálculo de riesgos:** Probabilidad x Impacto = Riesgo

  Propósito:

  - Prevenir eventos costosos y disruptivos.
  - Identificar áreas de mejora en sistemas y procesos.
  - Determinar niveles aceptables de riesgo.
  - Priorizar los activos críticos que necesitan protección.

### **Factores de riesgo**

#### Amenazas:

Circunstancias o eventos que pueden dañar los activos.

- **Tipos:** Intencionales (por ejemplo, piratería informática maliciosa) y no intencionales (por ejemplo, error del empleado).

#### Vulnerabilidades:

Debilidades que las amenazas pueden explotar.

- **Tipos:** Técnicas (fallas de software) y humanas (negligencia).

**Relación entre los factores de riesgo**

La probabilidad de que un activo resulte dañado aumenta cuando una amenaza puede explotar una vulnerabilidad.



## **Activos digitales y fisicos**

La gestión de activos implica el seguimiento de los activos y los riesgos asociados para protegerlos eficazmente.

La clasificación de activos categoriza los activos por sensibilidad e importancia, lo que ayuda a la gestión de riesgos y la priorización de recursos.

### **Clasificaciones comunes de activos y su importancia**

- **Restringido:** Representa el nivel más alto de sensibilidad. El acceso a estos activos está estrictamente controlado y limitado a un grupo muy reducido de personas con autorización específica. *La divulgación no autorizada podría tener consecuencias graves para la organización.*
  - **Ejemplos:** Información altamente confidencial como secretos comerciales, datos de tarjetas de crédito de clientes, planes estratégicos a largo plazo, código fuente de software crítico.
- **Confidencial:** Los activos confidenciales también requieren un alto nivel de protección, aunque no tan estricto como los restringidos. El acceso está limitado a personas autorizadas dentro de la organización y, en algunos casos, a socios comerciales de confianza. *La divulgación no autorizada podría causar daños significativos a la organización.*
  - **Ejemplos:** Información financiera sensible, datos de clientes (nombre, dirección, correo electrónico), contratos, información de empleados (salarios, evaluaciones de desempeño).
- **Interno:** Estos activos son de uso interno dentro de la organización y están disponibles para los empleados que los necesitan para realizar su trabajo. No obstante, no están destinados al público en general. *La divulgación no autorizada podría tener un impacto negativo en la organización, pero no tan grave como en los casos anteriores.*
  - **Ejemplos:** Documentos internos, políticas y procedimientos, información de contacto de empleados, memorandos internos.
- **Público:** Esta categoría incluye información que no se considera sensible y que puede ser compartida públicamente sin riesgo para la organización.
  - **Ejemplos:** Comunicados de prensa, información disponible en el sitio web de la empresa, folletos de marketing, información general sobre productos o servicios.

### **Clasificación según su estado** 

**Estados de los datos:**

- ***Datos en uso:** Datos a los que uno o más usuarios acceden activamente.*
- ***Datos en tránsito:** Datos que se mueven de un punto a otro.*
- ***Datos en reposo:** Datos almacenados que no están siendo utilizados activamente.*

**Seguridad de la información (InfoSec):** Se centra en proteger los datos en todos sus estados del acceso no autorizado. *Las prácticas débiles de InfoSec pueden tener graves consecuencias, como el robo de identidad, las pérdidas financieras y los daños a la reputación.*



## Riesgo y seguridad de activos

Los planes de seguridad robustos son cruciales para mitigar los riesgos que podrían comprometer la confidencialidad, integridad o disponibilidad de activos valiosos.

### Elementos de un plan de seguridad

- *Las políticas establecen las reglas y la orientación para la reducción de riesgos y la protección de la información, formando la base de un plan de seguridad.*
- *Los estándares proporcionan puntos de referencia y referencias específicas para implementar controles de seguridad, garantizando la coherencia y la eficacia.*
- *Los procedimientos describen instrucciones paso a paso para llevar a cabo tareas de seguridad, promoviendo la responsabilidad y la eficiencia en toda la organización.*

### Guías de seguridad en acción

#### NIST CFS

Anteriormente ya vimos por encima este [marco](https://github.com/Ramonperu/SecFrameworks-GoogleCybersec) de ciberseguridad, vamos a ampliar la informacion

<img align="center" src="/img/2ºimagenn.PNG"  />

#### Componentes NIST CFS

##### El Núcleo

El Núcleo del CSF identifica cinco funciones principales para un plan de seguridad:

1. ***Identificar:** Desarrollar una comprensión de los sistemas, activos, datos y contexto de la organización desde una perspectiva de gestión de riesgos de ciberseguridad.*
2. ***Proteger:** Desarrollar e implementar las salvaguardas apropiadas para garantizar la entrega de servicios críticos.*
3. ***Detectar:** Desarrollar e implementar las actividades apropiadas para identificar la ocurrencia de un evento de ciberseguridad.*
4. ***Responder:** Desarrollar e implementar las actividades apropiadas para tomar medidas con respecto a un evento detectado de ciberseguridad.*
5. ***Recuperar:** Desarrollar e implementar las actividades apropiadas para mantener los planes de resiliencia y restaurar cualquier capacidad o servicio que se haya visto afectado debido a un evento de ciberseguridad.*

##### Los Niveles

Los Niveles proporcionan a los equipos de seguridad una forma de medir el rendimiento en cada una de las cinco funciones del Núcleo. Estos niveles van desde el Nivel 1 (Parcial) hasta el Nivel 4 (Adaptativo):

- ***Nivel 1 (Parcial):** Las actividades de seguridad informática son reactivas e implementadas de forma ad-hoc. La organización puede no tener conocimiento de todas sus actividades de riesgo.*
- ***Nivel 2 (Informado por riesgos):** La organización identifica los riesgos a sus operaciones (incluidos los activos, individuos, otros organismos y la nación) derivados de las amenazas a los sistemas y la información.*
- ***Nivel 3 (Repetible):** La organización gestiona los riesgos de ciberseguridad mediante la planificación y ejecución sistemática de actividades de seguridad informática para mejorar su capacidad de resistencia a los incidentes de ciberseguridad.*
- ***Nivel 4 (Adaptativo):** La organización adapta sus prácticas de gestión de riesgos de ciberseguridad en función de las lecciones aprendidas y de la colaboración con otros para adaptarse al panorama cambiante de amenazas.*

##### Los Perfiles

Los Perfiles(Plantillas) proporcionan información sobre el estado actual de un plan de seguridad. Permiten comparar el estado actual con un estado objetivo o con el estado en un momento anterior.





## Activos de organizaciones y su proteccion

### **Tipos de controles de seguridad**

Los controles de seguridad se pueden clasificar en tres tipos:

- Los controles técnicos utilizan tecnología, como el cifrado y los sistemas de autenticación, para proteger los activos.

- Los controles operativos se enfocan en el mantenimiento diario de la seguridad, como la capacitación de concientización y la respuesta a incidentes, generalmente realizados por personas.

- Los controles de gestión se centran en cómo los otros dos tipos reducen el riesgo, incluyendo políticas, estándares y procedimientos, como las políticas de seguridad que definen los controles para lograr los objetivos de una organización.



### **Privacidad de la información y control de acceso**

La privacidad de la información garantiza la protección de los datos contra el acceso y la distribución no autorizados, lo que permite a las personas y organizaciones controlar su información.

***El principio de privilegio mínimo*** implica otorgar a los usuarios solo el ***nivel de acceso mínimo necesario*** para realizar sus tareas, minimizando los riesgos asociados con las filtraciones de datos, las modificaciones no autorizadas y las vulnerabilidades del sistema

- La implementación de PoLP implica identificar a los usuarios (individuos, dispositivos o software) y determinar los niveles de acceso apropiados en función de sus roles y responsabilidades.
- Las auditorías periódicas de las cuentas de usuario, los privilegios y los cambios de cuenta son esenciales para garantizar la seguridad continua y mitigar riesgos como la acumulación de privilegios (los usuarios acumulan acceso innecesario con el tiempo).



### **Propiedad y custodia de datos**

Los propietarios de los datos tienen la autoridad para determinar quién puede acceder, modificar, utilizar o eliminar su información.

Todos los que custodian los datos, incluidos individuos, organizaciones y sistemas, son responsables del manejo, la transferencia y el almacenamiento seguros de estos.

#### Ciclo de vida de los datos

Las organizaciones manejan grandes cantidades de datos que deben mantenerse privados, ya sea que estén almacenados, en uso o en tránsito.

El ciclo de vida de los datos tiene cinco etapas:

<img align="center" src="/img/1ºimagenn.PNG"  />

- ***Recopilación:** Obtener datos de diferentes fuentes.*
- ***Almacenamiento:** Guardar datos de forma segura.*
- ***Uso:** Acceder y utilizar datos para fines comerciales.*
- ***Archivo:** Conservar datos para referencia futura o cumplimiento.*
- ***Destrucción:** Eliminar datos de forma segura cuando ya no son necesarios.*

#### **Gobernanza de Datos**

Conjunto de procesos para gestionar la información, incluyendo políticas para mantener la privacidad, precisión, disponibilidad y seguridad de los datos.

- Roles:
  - ***Propietario de los datos:** Decide quién puede acceder, editar, usar o destruir la información.*
  - ***Custodio de los datos:** Responsable del manejo, transporte y almacenamiento seguro de la información.*
  - ***Administrador de datos:** Mantiene e implementa las políticas de gobernanza de datos.*

#### **Protección de Datos en Cada Etapa**

Las políticas de gobernanza de datos definen los procedimientos para mantener la seguridad de los datos  en cada etapa del ciclo y establecen límites de acceso.

**Recopilación:**

- ***Minimización de datos:** Recolectar solo los datos necesarios para el propósito previsto.*
- ***Consentimiento:** Obtener el consentimiento explícito antes de recopilar datos personales.*
- ***Seguridad en la entrada de datos:** Validar y desinfectar los datos ingresados por el usuario para prevenir ataques de inyección.*

**Almacenamiento:**

- ***Cifrado:** Proteger los datos en reposo, ya sea en bases de datos, servidores o dispositivos de almacenamiento.*
- ***Control de acceso:** Restringir el acceso a los datos según el principio de privilegio mínimo.*
- ***Copias de seguridad y recuperación:** Implementar un sistema de copias de seguridad y recuperación ante desastres para garantizar la disponibilidad de los datos.*

**Uso:**

- ***Autenticación y autorización:** Verificar la identidad de los usuarios y otorgarles permisos específicos para acceder y utilizar los datos.*
- ***Registro y auditoría:** Monitorear y registrar el acceso y las modificaciones de los datos para detectar actividades sospechosas.*
- ***Prevención de pérdida de datos (DLP):** Implementar medidas para evitar la fuga o el uso no autorizado de datos sensibles.*

**Archivo:**

- ***Almacenamiento seguro:** Almacenar los datos archivados en un entorno seguro y controlado.*
- ***Retención y eliminación:** Definir políticas claras sobre cuánto tiempo se deben conservar los datos y cómo eliminarlos de forma segura cuando ya no sean necesarios.*

**Destrucción:**

- ***Borrado seguro:** Eliminar los datos de forma permanente utilizando métodos que impidan su recuperación.*
- ***Destrucción física:** Destruir físicamente los dispositivos de almacenamiento que contienen datos sensibles cuando ya no se utilicen*

#### **Información Legalmente Protegida**

- Los propietarios de los datos tienen derecho a decidir si comparten o no sus datos.
- Tipos de información que requieren protección:
  - **PII (Información de Identificación Personal):** Información que puede utilizarse para identificar a una persona.
  - **PHI (Información Protegida de Salud):** Información relacionada con la salud física o mental de una persona.
  - **SPII (Información de Identificación Personal Sensible):** Tipo específico de PII que requiere un manejo más estricto, como números de cuenta bancaria o credenciales de inicio de sesión.



### Regulamiento y normativa

#### **Regulaciones que Afectan al Manejo de Datos:**

- **Reglamento General de Protección de Datos (GDPR):** Creado por la Unión Europea, otorga a los individuos control total sobre sus datos personales. Afecta a cualquier empresa que maneje datos de ciudadanos o residentes de la UE, independientemente de dónde opere.
- **Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago (PCI DSS):** Conjunto de estándares de seguridad creados por las principales organizaciones financieras para proteger las transacciones con tarjetas de crédito y débito contra el robo de datos y el fraude.
- **Ley de Portabilidad y Responsabilidad del Seguro Médico (HIPAA):** Ley estadounidense que exige la protección de la información médica confidencial de los pacientes. Prohíbe la divulgación de la información médica de una persona sin su conocimiento y consentimiento.

#### **Evaluaciones y Auditorías de Seguridad: **

Para que las empresas cumplan con las regulaciones de seguridad y privacidad, necesitan un enfoque doble y continuo:

**Auditorías de Seguridad: **Verifica que los controles, políticas y procedimientos de seguridad de una organización cumplan con las expectativas y regulaciones establecidas.

- **Ejemplo:** Si una regulación exige MFA para cuentas de administrador, la auditoría verificaría si todas las cuentas cumplen.

**Evaluaciones de Seguridad:** Prueban la resistencia de las implementaciones de seguridad actuales frente a amenazas reales.

- **Ejemplo:** Tras una auditoría, se descubre que muchos usuarios usan contraseñas débiles. La evaluación lleva a implementar MFA para todos los usuarios, mejorando la seguridad general.



## METODOS DE ENCRIPTACIÓN

La encriptación es un proceso clave en la seguridad de la información, que transforma datos legibles en un formato codificado para protegerlos de accesos no autorizados. A lo largo de la historia, se han desarrollado varios métodos de encriptación y se han ido desarrollando y mejorando ante sus flaquezas

### Infraestructura de clave publica o PKI

Cifra la información y establece confianza entre las partes.

**Métodos de cifrado:**

- ***Cifrado asimétrico:** Emplea un par de claves pública-privada. La clave pública cifra los datos y solo la clave privada correspondiente puede descifrarlos. Este método es muy seguro pero más lento.*
- ***Cifrado simétrico:** Utiliza una única clave secreta tanto para el cifrado como para el descifrado. Es más rápido pero menos seguro.*

Utiliza tanto el cifrado asimétrico como el simétrico en función de si la prioridad es la velocidad o la seguridad. Ambos métodos de cifrado son vulnerables al uso indebido de las claves si caen en las manos equivocadas. La PKI aborda esto a través de los certificados digitales.

- **Establecimiento de confianza con certificados digitales:**
  - **Certificados digitales:** Archivos que verifican la identidad de los titulares de claves públicas, emitidos por Autoridades de Certificación (CA) de confianza.
  - **Obtención de un certificado:** Las entidades proporcionan información a una CA, que verifica su identidad y emite un certificado que contiene los datos cifrados y la firma digital de la CA.
  - **Generación de confianza:** Los certificados digitales actúan como tarjetas de identificación en línea, lo que permite la confianza entre ordenadores y redes durante el intercambio de información.

**Algoritmos de cifrado**

- AES (Estándar de cifrado avanzado) es un algoritmo simétrico ampliamente utilizado conocido por su seguridad, que emplea longitudes de clave de 128, 192 o 256 bits.
- RSA (Rivest-Shamir-Adleman) es un algoritmo asimétrico prominente utilizado para asegurar datos confidenciales, generando longitudes de clave de 1024, 2048 o 4096 bits.

### Funciones HASH

Las funciones hash toman una entrada (como un archivo o un programa) y la convierten en un código único llamado valor hash o "hash". Este valor hash es como una huella digital única para ese archivo o programa.

**¿Para qué sirven?**

**Verificar que la información no ha sido modificada:** Si cambias aunque sea una letra en el texto original, la función hash generará un código completamente diferente. Esto es útil para asegurarse de que los archivos no hayan sido alterados.

**Proteger contraseñas:** En lugar de guardar la contraseña directamente, se guarda su código hash. Así, aunque alguien acceda a la base de datos, no podrá ver las contraseñas reales.

**Evolución y desafíos:**

- **MD5:** Una de las primeras funciones hash, pero se descubrió que era vulnerable a "colisiones", es decir, que dos informaciones diferentes podían tener el mismo código hash.
- **SHA:** Se crearon funciones hash más robustas, como la familia SHA, que generan códigos más largos y complejos, dificultando las colisiones.
- **"Salting":** Para hacer aún más seguras las contraseñas, se añade una cadena de caracteres aleatorios ("sal") antes de aplicar la función hash. Esto hace que sea mucho más difícil descifrarlas.
