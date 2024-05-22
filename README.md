### Proyecto-Estacionamiento

## Vigilancia Tecnológica

- **Fecha:** 23 de mayo del 2024
- **Autores:** Esteban Palomar Murcia y Juandavid Artunduaga Gómez

## 1. Descripción del Proyecto

En principio, el proyecto "Estacionamiento" consiste en un sistema automatizado que utiliza diferentes sensores para detectar la disponibilidad de espacios de estacionamiento. Cada sensor está conectado a un microcontrolador, como un Arduino, que lee los datos de distancia proporcionados por los sensores. Si un espacio está disponible, el sensor activa una luz verde, y si está ocupado, se enciende una luz roja. Estos datos se envían a un servidor, donde se almacenan y gestionan en una base de datos. Este proyecto permite a los usuarios visualizar los espacios libres de una manera más rápida.

## 2. Objetivo

Este proyecto se hace con el fin de mejorar la experiencia del usuario al momento de buscar un estacionamiento en los centros comerciales, facilitando la gestión eficiente de los espacios y ahorrándoles tiempo en estas situaciones. Aplicaremos todos nuestros conocimientos tanto de software como de hardware para hacer un sistema amigable con el usuario y el administrador.

Utilizaremos diferentes recursos para el desarrollo del proyecto.

### Hardware 

- Sensores
- Microcontroladores
- Luces indicadoras
- Componentes adicionales

### Software

- Lenguajes de programación (Python, JavaScript, PHP)
- Bases de datos
- Bibliotecas y frameworks

## 3. Requisitos Funcionales

- El sistema debe obtener la información de los sensores para detectar la presencia de los vehículos.
- Según la información obtenida de los sensores, el sistema debe dar la señal por medio de las luces rojas/verdes si está o no disponible el espacio.
- El servidor debe almacenar los datos de disponibilidad por medio de una base de datos.

## 4. Requisitos No Funcionales

- El sistema debe estar bien optimizado.
- La comunicación entre todos los componentes como sensores, luces, controlador y el servidor debe ser muy estable.
- La interfaz del programa debe ser fácil de utilizar e interactiva.
- El proyecto debe tener una manera fácil de actualizar y mantener.

## 5. Análisis del Entorno y Mercado Actual

Aunque ya existe competencia en este tipo de proyectos, hay oportunidades para diferenciarse mediante la innovación y la excelencia en la experiencia del usuario. Cumplir con las regulaciones y considerar factores ambientales y sociales son cruciales para el éxito del proyecto. Hay muchas partes del mundo que aún no tienen estos sistemas. Donde más está presente este tipo de proyecto es en el primer mundo, debido a que cuentan con tecnologías más desarrolladas.

En la zona donde se piensa realizar el proyecto no se encuentran este tipo de sistemas, por eso queremos empezar a implementarlos.

El mercado de las soluciones inteligentes crece cada vez más, y qué mejor que ofrecer soluciones a los problemas comunes que enfrentan los usuarios de estacionamientos, como el tiempo perdido buscando un lugar para aparcar y la gestión ineficiente de los espacios. El proyecto trae beneficios para todos, tanto para los usuarios como para las empresas que lo deseen adquirir. El respaldo del mercado es positivo para este caso, además de que en la zona no hay mucha competencia, lo que conlleva a que puede ser muy aclamado por las empresas.

El proyecto se podría adaptar a las diferentes necesidades de las empresas para que se pueda expandir, si se saben utilizar las herramientas que nos ofrece el entorno, como:

### Tecnologías 
En internet se puede encontrar una amplia variedad de tecnologías que se pueden utilizar de acuerdo a las necesidades de este proyecto y lo mejor de todo, es que se pueden adquirir de una manera sencilla. Algunas de ellas son:

### Hardware

- **Sensores de Detección:**
  - Sensores de Ultrasonido (HC-SR04): Populares por su precisión y costo efectivo para medir distancias y detectar objetos.
  - Sensores Infrarrojos (IR): Utilizados para detectar la presencia de vehículos mediante la reflexión de luz infrarroja.
  - Sensores Inductivos: Detectan la presencia de metal, ideales para detectar vehículos en espacios de estacionamiento.
  - Sensores de Cámara: Utilizan visión por computadora para identificar espacios disponibles y ocupados, aunque son más complejos y costosos.
  
- **Microcontroladores y Computadoras de Placa Única:**
  - Arduino: Adecuado para proyectos pequeños, es fácil de programar y conectar con sensores y LED.
  - Raspberry Pi: Más potente que Arduino, adecuado para proyectos que requieren procesamiento más avanzado y conectividad de red.
  - ESP8266/ESP32: Microcontroladores con capacidades de WiFi integradas, ideales para IoT y aplicaciones de red.

### Software

- **Plataformas de Desarrollo de Software:**
  - JavaScript
  - Node.js: Para desarrollar el backend del sistema, aprovechando su capacidad de manejar múltiples conexiones concurrentes.
  - Python: Utilizado para procesamiento avanzado de datos y control de hardware en Raspberry Pi.
- **Bases de Datos:**
  - MySQL / PostgreSQL: Bases de datos relacionales, adecuadas para aplicaciones que requieren consultas SQL complejas y transacciones.
- **Herramientas de Desarrollo y Colaboración:**
  - GitHub / GitLab / Bitbucket: Plataformas para alojar repositorios de código y facilitar la colaboración en equipo.
  - Visual Studio Code

## Viabilidad del Proyecto

- **Viabilidad Económica:** La economía del proyecto es buena porque los costos de adquisición de los sensores, microcontroladores y otros componentes electrónicos necesarios son relativamente bajos. Los costos operativos incluyen mantenimiento de hardware, control de bases de datos y servidores en la nube, y actualizaciones de software, todos los cuales son escalables.
- **Viabilidad Operativa:** La viabilidad operativa del proyecto es alta ya que se puede implementar por etapas, desde la indicación por medio de luces LED que el puesto está libre hasta informar que el parqueadero está en su límite de cupos. El mantenimiento de sensores y sistemas suele ser sencillo, ya que los microcontroladores y sensores son robustos y requieren poco mantenimiento. Además, el mismo personal de la empresa puede recibir formación rápidamente para gestionar el sistema y resolver problemas básicos, garantizando un funcionamiento continuo y eficiente del sistema de seguimiento.
- **Viabilidad Comercial** La comercialización del proyecto es muy prometedora ya que existe una demanda creciente de soluciones de estacionamiento inteligentes en áreas urbanas densas, centros comerciales, oficinas y aeropuertos. Este tipo de sistema mejora la eficiencia y la experiencia del usuario, lo que es un fuerte motivador para su adopción.
