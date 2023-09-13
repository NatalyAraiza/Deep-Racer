# Deep-Racer

#### Vehículos Autónomos: Definición y Significado:

Los vehículos autónomos son la encarnación del poder de la inteligencia artificial y el aprendizaje automático en el mundo de la movilidad. En esencia, un vehículo autónomo es capaz de moverse y navegar en su entorno sin intervención humana directa. Utiliza una combinación de sensores avanzados, procesamiento de datos en tiempo real y algoritmos de toma de decisiones para lograr esta autonomía. Desde coches autónomos en las carreteras hasta robots de entrega, la autonomía está transformando la forma en que interactuamos con el mundo.

#### Componentes Clave del Amazon DeepRacer:

Ahora, centrémonos en una joya tecnológica que nos ofrece un vistazo al futuro de la autonomía: el Amazon DeepRacer. Veamos los componentes más importantes que hacen que esta plataforma sea tan emocionante:
Plataforma de Hardware:
    Vehículo Físico: El DeepRacer es un vehículo a escala 1/18 que incorpora una cámara y sensores LiDAR para percibir su entorno.
    Ruedas y Motor: Sus ruedas y motor permiten un movimiento suave y control preciso, fundamental para el aprendizaje y la toma de decisiones autónomas.

Plataforma de Software:
    Entorno de Simulación: El DeepRacer ofrece un entorno virtual para experimentar y entrenar modelos de IA antes de implementarlos en el vehículo físico.
    Aprendizaje por Refuerzo: Esta es la esencia del aprendizaje del DeepRacer. El vehículo aprende a través de la interacción con su entorno, obteniendo recompensas por acciones positivas y mejorando a lo largo del tiempo.

Reinforcement Learning (Aprendizaje por Refuerzo):
    Agente de Aprendizaje: El modelo de IA en el DeepRacer es el agente de aprendizaje. Aprende mediante la exploración y el refinamiento de acciones para maximizar las recompensas.
    Política de Acción: El agente desarrolla una política de acción óptima a lo largo del tiempo, basada en las experiencias pasadas y las recompensas obtenidas.

Liga DeepRacer:
    Comunidad y Competencia: Amazon ha establecido una liga para los entusiastas de la IA y la autonomía. Aquí, los participantes pueden competir virtual y presencialmente, compartiendo conocimientos y mejorando sus modelos.

### Módulo 1 - Arquitectura y Programación de Sistemas:

  Elegimos lenguajes de programación como Python para implementar la lógica de control y aprendizaje de los vehículos. Python nos permite aprovechar una amplia variedad de bibliotecas y marcos de trabajo relevantes para la inteligencia artificial y el procesamiento de datos en tiempo real. Utilizamos Redis como base de datos en memoria para almacenar información sobre las carreras, como tiempos de vuelta y rendimiento de los vehículos. Esto permite un acceso rápido a los datos y una gestión eficiente de la información en tiempo real. Nuestra metodología de programación sigue el enfoque ágil, lo que nos permite adaptarnos rápidamente a los cambios y agregar nuevas características durante el desarrollo. Aplicamos conceptos de Ingeniería de Software, como el principio de responsabilidad única, para asegurar un diseño modular y mantenible del sistema. Estructuramos el sistema en módulos para separar la lógica de control, el aprendizaje de la red neuronal y la interacción con el entorno de la pista.

### Módulo 2 - Sistemas Inteligentes:

Para cumplir con el requisito de sistemas inteligentes, implementamos una red neuronal profunda (Deep Neural Network, DNN) para el aprendizaje y control del vehículo en la pista, haciendo uso del algoritmo ppo, y la biblioteca de TensorFlow, ademas utilizamos una arquitectura de red neuronal convolucional (Convolutional Neural Network, CNN) para procesar los datos de los sensores de la cámara en tiempo real y tomar decisiones de control adecuadas. Nuestro modelo matemático se basa en la retroalimentación constante entre la red neuronal y los datos en tiempo real de los sensores, permitiendo al vehículo aprender y mejorar su rendimiento en cada vuelta.

### Módulo 3 - Sistemas Distribuidos: 

Implementamos un sistema descentralizado en el que múltiples vehículos en la pista interactúan entre sí para evitar colisiones y competir; Cada vehículo cuenta con sensores de distancia y visión, permitiéndoles detectar y responder a la presencia de otros vehículos en su entorno. Establecemos comunicación bidireccional entre los vehículos utilizando protocolos de red estándar, permitiendo la transmisión de datos de posición y velocidad en tiempo real. Justificamos el uso del protocolo MQTT (Message Queuing Telemetry Transport) debido a su eficiencia en la transmisión de mensajes en un entorno distribuido en tiempo real.
