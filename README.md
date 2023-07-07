# arduino-indoor-weatherstation

<h2>Micah Simmerman</h2>

<h2>CSPB-3112, Professional Development Project</h2>

Title: Arduino Indoor Weather Station 

The aim of this project will be to create a system to monitor my 4X4 grow tent garden, which currently contains four potted plants and two hydroponic systems, whenever my wife and I are away on vacation. 

The goal will be to integrate several arduino sensors (i.e., those for temperature, pH, and total dissolved solids, etc.) on a common serial bus and a single-board computer driver. After the sensors are installed, integrated, and beta-testedand, I will investigate methods to collect, aggregate, and stream this data using a REST API architecture and bluetooth and/or wifi enabling transceiver modukes. In just such a way, this project will investigate concepts relevant to the internet of things (IOT), with a focus on real-time data collection, routing, persistence, aggregation, and browser presentation. Various server and server-less architecture patterns will be explored, and the REST API endpoint will be presented on this website.

Vision Statement: My goals for this project are: 1.) Learn the basics of Arduino sensors, network hardware, compiler, and the IDE. 2.) Develop hands-on experience with IOT networks and the development of application-driven devices. 3.) Increase my awareness of object oriented programming patterns in strongly-typed languages such as C++ and Java 4.) Extend my knowledge of data transformations, tuple formatting, and web-development using HTML/CSS/JavaScript architectural patterns.

Motivation: My motivation for completing this project is to begin a personal long-term research project to develop my hobbies and interests, while deepening my understanding of a fascinating topic of research. My hope is that by orienting a portfolio around my personal interests, I will be likely to continue adding to the project and developing this portfolio in the future.

Project Goals: 1.) Assemble an Arduino device to monitor pH, TDS, temperature, humidity, etc. of a 4x4 indoor garden growtent. 2.) Install IOT network modules and access output of the device via local area network (LAN) and/or WAN connections. 3.) Develop a simple REST API webpage application (REACT seems a likely candidate) to present the livestream data in a briwser and render measurements in (e.g.) an XHTML table. 4.) Enjoy the benefits of having a WAN-connected serial relay monitor the health of my plants for me. 

Risks to Project Completion: This project requires Arduino hardware, as well as a moderate background in analytical sensors and network relay devices. I have very limited experience with electrical wiring (although I did take Physics), and I am completely unfamiliar with the Arduino native development language as of the start of this project.

Mitigation Strategies: In addition to the sensors, wires, and board components that I will need to create the weather monitor, I have also purchased an Arduino &#34;Project Board&#34; that comes with a highly-recommended tutorial. There are many YouTube videos and blog articles about creating a pH meter using Arduino parts, and I have also found a tutorial about installing the Arduino Bluetooth and ESP-8266 WiFi transceivers. 

Project Assessments: The end goal will be to display real-time measurements from the extended transceiver onto a REST API endpoint that I can connect with other microservices at a later date.

Project Link: https://micah614.github.io/arduino-indoor-weatherstation/
