# Proyecto: 
Ejercicio de inter-operabilidad entre dos sistemas de registros médicos electrónicos en territorio peruano.

## Actores participantes:
* **DIRESA Cajamarca:** Gobierno regional descentralizado con activo digital de tipo SAAS denominado **oneVisionCax**, para los fines operativos: "SIHCE Cajamarca" (Pendiente certificación por central MINSA).
* **zlTech:** Entidad cooperante autónoma de origen estadounidense, desarrolladora de software, con activo digital de tipo SAAS denominado **QHALI** e indexado en hl7 internacional apartado Perú.
* **DIPOS:** Dirección Ejecutiva de Intercambio Prestacional, Organización y Servicios de la Dirección General de Aseguramiento e Intercambio Prestacional del Ministerio de Salud Peruano (**DGAIN**), en base a sus competencias, lidera la implementación de las Redes Integradas de Salud a nivel nacional.

## Abstracto:
- En el marco de la implementación de Redes Integradas de Salud (RIS) en Perú, y en relación a las actividades para la operación de los registros médicos electrónicos, la DIPOS/DGAIN brinda asistencias técnicas a los Gobiernos Regionales que busquen el éxito de sus hitos, ya que estos impactan de manera transversal la gestión de la información en salud dentro del territorio de las RIS.
- DIRESA Cajamarca viene desplegando activos de software administrativos y en salud dentro de su jurisdicción, creaciones desarrolladas in-House y a través de integraciones continuas a lo largo de los últimos 5 años.
- zlTech viene desplegando Qhali, un activo digital que funge como interfaz para modelos de AI. Abordando las brechas en la oportunidad de atención (oferta-demanda en salud), generándose así un nuevo canal seguro para los ciudadanos que buscan orientación de manera rápida y efectiva.
- La presente actividad de cooperación busca acercar estos modelos de innovación en salud con la intención de ejecutar un ejercicio de **inter-operabilidad** entre ambos softwares independientes.
- oneVisionCax recibe información de Qhali, la cual estructura los datos a través del modelo [[LLM]] (entre otros) que entra en contacto con un ciudadano del ámbito geográfico RIS del proyecto. oneVisionCax consume los registros y opera los CRUD que corresponden. Estos cambios de estado son consumidos por Qhali en su DB o storage para ser utilizado como canal de notificación al ciudadano que inició el evento en su plataforma.
- El software utilizado como estrategia del ejercicio de interoperabilidad es el OpenSource Mirth Connect, el cual funge como traductor de los canales de comunicación de entrada y salida.

## winToWin ps triangular cooperation
* **DIRESA**
  - Primera región en lograr la interoperabilidad entre sistemas de registros médicos independientes, logrando así avanzar en los hitos relacionados a atención de pacientes en red (RIS), así como la posibilidad de despliegues a nivel de intercambio prestacional entre entidades extra institucionales, públicas, mixtas y/o privadas.
* **zlTech**
  - Primera entidad que genera en su portafolio una actividad relacionada a la interoperabilidad entre sistemas de registros médicos (certificación de hl7Peru), como parte de su actividad de cooperación. Así mismo a través de esta actividad conocerá la adherencia de las poblaciones regionales a las nuevas tecnologías vinculadas con IA en el support al triage.
* **DIPOS**
  - Hace efectiva la asistencia técnica para con las implementaciones de las redes integradas de salud (RIS), llegando a lineamientos que sirven de base para la actualización o generación de nueva documentación normativa.

## Financiamiento
* Dicha actividad piloto no involucra gastos ni inversiones por parte de las direcciones del MINSA ni de los organos del Gobierno Regional. Sus activos se enmarcan en el recurso humano que atiende el proyecto.
* zlTech como entidad cooperante realiza las inversiones necesarias para la implementación del piloto, toda vez que forma parte de sus actividades de difusión corporativa en territorio Peruano y como acercamiento de estas nuevas tecnologías.

**update:** 2024-06-26 Tuesday
