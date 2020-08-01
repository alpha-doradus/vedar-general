# Vedar

Proyecto Hackathon Uniandes 2020 del equipo Alpha Doradus.
VEDAR: Aumenta tu educación.

## Visión general

Vedar es una plataforma de video llamadas interactiva, amigable, y eficaz, conectada con un sistema de centralización de información y contenido especializada en el sector educativo. Nace al evidenciar las problemáticas comunicativas, en la enseñanza y el aprendizaje virtual entre docentes y estudiantes, por causa de la pandemia. De esta manera, busca cerrar las brechas de las clases actuales al proveer herramientas tecnológicas que usan la realidad aumentada, modelación en 3D y la detección de gestos como principal medio de interacción.

<img src="https://github.com/Alpha-Doradus/vedar-general/blob/master/images/logo.png?raw=true" width="40%">

## Objetivos Principales
- Ofrecer una sensación de cercanía entre los docentes y estudiantes.
- Brindar mayor expresividad remota a través de la comunicación del lenguaje no verbal.
- Generar un ambiente propio para el aprendizaje y que motive a la comunicación.
- Generar retroalimentación en tiempo real a través de indicadores de 'Concentración de la Clase', 'Participación de los estudiantes' entre otros.
-Centralizar la información y el contenido educativo para el docente y estudiante de forma organizada y amigable.

## Funcionalidades

- Proveer un avatar para cada estudiante, sin mostrar el entorno propio de cada uno para respetar la privacidad de los usuarios.
- Permite obtener un tablero virtual utilizando detección de gestos y su representación, en tiempo real, con objetos y modelos 3D de realidad aumentada.
- Generar datos, estadísticas y gráficas sobre la atención de los estudiantes para los docentes, al tener inteligencia artificial previamente entrenada para detectar caras de confusión o comprensión del conocimiento.
-Mostrar adecuadamente las estadísticas para que tanto el docente como el estudiante puedan tener información relevante para un buen desarrollo del curso.
- Permite conocer los estudiantes que no se encuentran frente a la cámara al mostrar un avatar con apariencia de sueño.
- Generar resumen y transcripción de la clase para los estudiantes.
-Transcripción de resultados de clase tanto para los docentes como para los estudiantes.
- Unificar las herramientas necesarias para la virtualidad (Correos, Whatsapp, Videollamadas, Tareas, Material, Notas).
-Calendario desplegable que esté vinculado con los documentos y fechas.
-Firma de asistencia virtual

## Calidad Idea
Actualmente no existe en el mercado una plataforma educativa que permita unificar las diferentes herramientas esenciales para el aprendizaje, y que además proporcione un servidor de video llamadas en tiempo real que a través de la implementación de tecnología AR y 3D permita hacer un análisis de estadísticas enseñando a nuestro software cómo interpretar el lenguaje no verbal, para así fortalecer la comunicación de forma prudente y apropiada. La competencia más cercana es SPATIAL, sin embargo, no contemplan la unificación y centralización de plataformas y contenido.
## Concepto

En el mundo hay alrededor de 1370 millones de estudiantes y 60 millones de docentes que se vieron obligados a adaptarse a una nueva metodología de clases virtuales debido a la pandemia. La poca rapidez de adaptación en algunos lugares es la muestra de la obsoleta estructura académica, además de la falta de centralización de contenido, la poca conectividad entre plataformas, la sobre productividad y falta de organización. Estos son unos de los pocos problemas reales y actuales que Vedar busca mitigar con sus funcionalidades. 

## Diseño

Para el diseño de la marca se tuvo como pilar la educación, de allí su nombre Vedar (Video Llamadas-Educar) y también por de forma gráfica la letra 'V' de logo simula la silueta en perspectiva de un libro abierto como símbolo principal. Además, como solución principal a la problemática educativa se presenta la tecnología por lo que la letra 'V' elevada al cubo hace referencia a la realidad aumentada y modelos 3D. Finalmente, se implementó una paleta de colores enfocada una sugestión de concentración por el contenido visualizado. 

## Implementación técnica

La implementación cumplió gran parte de las expectativas y objetivos planteados al inicio por los desarrolladores, se completaron las funcionalidades principales del prototipo conceptual, dando como producto final un prototipo funcional a unos pasos de verificación para ser un MVP. A pesar de esto, y debido al poco tiempo, faltaron implementar herramientas secundarias que fueron mencionadas en el pitch presentado.

## Impacto y futuro.
Existe una gran cantidad de dificultades evidenciadas en la adaptación del sistema educativo, que permiten abrir muchas puertas a Vedar para implementar y mejorar la comunicación y el aprendizaje:

- Queremos darle la oportunidad a cualquier persona de acceder a una clase virtual de la mejor calidad y que a través de tecnología de IA se pueda simular estar conectado sin tener acceso a internet sino a través de una llamada de voz que des encriptada por nuestra plataforma simula la clase.
-Queremos hacer un catálogo de los lugares icónicos de la institución educativa para que ambos agentes no pierdan el sentido de pertenencia.
- Facilitar el trabajo colaborativo en cuanto a la asignación salas, roles y tareas a realizar.

- Parte del cambio en el aprendizaje es que el estudiante adquiere mucha responsabilidad para su proceso por lo que a veces el autoaprendizaje se dificulta. Por esto, se quiere dar la opción que la plataforma oriente tiempos de estudio o tiempo de realización de las tareas. 
-Metodología de incentivos al realizar labores y que se van marcando conforme el cronograma especificado del curso.
-Guía interactiva del uso de la plataforma, así como sugerencias de preparación y capacitación de la clase. Se debe contemplar la edad y capacidad tanto de docentes como alumnos al momento de utilizar la plataforma.

## Equipo
Vedar fue creado por un equipo de estudiantes que creen en la comunicación como base del aprendizaje, que le apuestan a una conexión fluida y en tiempo real que pueda brindar información relevante y confidente del lenguaje no verbal, que al ser traducidos por VEDAR generen una sensación de cercanía y confianza entre el estudiante y su profesor.


## Tech stack
Para el desarrollo de VedAR se usaron las siguientes tecnologías:

### Front-end
- HTML5
- CSS3
- Bootstrap
- AOS Scroll Animations

### Back-end
- Python
- OpenCV
- Flask
- Bcrypt
- Jinja2
- SQL (sqlite3)
- Email Validation API by Chema (https://github.com/neo22s/emailvalidator/)

## Web App

### https://github.com/Alpha-Doradus/vedar-web-app

## Prototipo de la plataforma

### Landing Page

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Home.jpg" width="80%">

### Login Page

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Login.jpg" width="80%">

### Register de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Register.jpg" width="80%">

### Perfil de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - User.jpg" width="80%">

### Configuración Perfil de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Settings.jpg" width="80%">

### Amigos de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Friends.jpg" width="80%">

### Mensajes de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Message.jpg" width="80%">

### Pantalla de Clase

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Board.jpg" width="80%">

### Avatar de Usuario

<img src="https://raw.githubusercontent.com/Alpha-Doradus/vedar-general/master/images/VedAR - Student.jpg" width="80%">


## Integrantes del equipo

 - Daniel Camacho
 - Juan Pablo Ramirez
 - Juan Pablo Galvis
 - Juan Alegría
 - Luis Felipe Ariza
