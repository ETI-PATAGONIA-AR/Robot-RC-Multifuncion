# Robot-RC-Multifuncion
¡Presentamos el nuevo Robot RC Multifunción de ETI Patagonia! (Control Bluetooth, Cámara, Modo SoccerRC y Modo Laberinto)

Un proyecto pensado para ir mucho más allá de un simple robot a control remoto.
Este robot reúne en una misma plataforma diferentes tecnologías de robótica, electrónica y programación, permitiendo utilizarlo en modo RC, con control de velocidad, con cámara y también como robot autónomo para resolver laberintos.

## 🎥 En este video te mostramos el funcionamiento del Robot RC Multifunción, sus diferentes modos de trabajo y las posibilidades que ofrece esta plataforma.
[![Demo en YouTube](https://img.shields.io/badge/▶_Ver_demo-YouTube-red)](https://www.youtube.com/watch?v=iiziI1K9s3U)

## 🎮 MODO RC
Controlá el robot mediante Bluetooth desde una aplicación Android o desde nuestra aplicación para Windows.

Podés controlar:

▶️ Avance
◀️ Retroceso
↩️ Giro a izquierda
↪️ Giro a derecha
⏹️ Detención
⚙️ Regulación de velocidad mediante PWM

## 📷 VISIÓN CON ESP32-CAM
Como expansión del proyecto incorporamos una ESP32-CAM, que permite obtener una transmisión de video y visualizar lo que está viendo el robot.
La cámara se integra como un add-on independiente y puede visualizarse desde nuestra aplicación para Windows.

📱 La aplicación Android se utiliza solo para el control del robot y no tiene acceso a la cámara.

💻 La aplicación Windows permite controlar el robot y visualizar la cámara cuando está instalada la expansión ESP32-CAM.

## 🧭 MODO LABERINTO
Pero acá es donde el proyecto cambia completamente.
Mediante una pulsación prolongada durante el arranque podemos seleccionar el Modo Laberinto.
En este modo el robot trabaja de manera autónoma utilizando:

🔹 Sensor ultrasónico HC-SR04
🔹 Servo SG90 para explorar el entorno
🔹 Encoder para odometría
🔹 L298N para el control de los motores
🔹 Algoritmo de navegación
🔹 Detección de callejones sin salida
🔹 Giros de 90° y 180°
🔹 Retroceso mediante odometría
🔹 Autocalibración de los giros

El sistema incluso realiza una autocalibración antes de comenzar la competencia, calculando los tiempos necesarios para realizar los giros.

## 🔧 UNA SOLA PLATAFORMA, VARIAS FUNCIONES

La idea detrás de este proyecto es justamente esa:

crear una plataforma robótica que pueda crecer.
Hoy puede utilizarse como robot RC.
Mañana podemos agregarle una cámara.

También podemos utilizarlo para navegación autónoma, experimentar con sensores, modificar los algoritmos o desarrollar nuevas aplicaciones de control.

Y todo esto utilizando una plataforma basada en Arduino Nano, Bluetooth, L298N, sensores, servo y encoder.

### DISPONIBLE: STL para impresion 3D, diagrama de circuitos, Sketch y mucho mas...

📌 Proyecto desarrollado por ETI Patagonia
📌 visita nuestra web: https://eti-patagonia-ar.github.io/ETI-Patagonia-ARG/index.html 
📌Contacto: prof.martintorres@educ.ar

Si te interesa la electrónica, Arduino, robótica y programación, suscribite al canal y acompañanos en los próximos desarrollos.

#ETIPatagonia #RobotRC #RobotMultifuncion #Arduino #Robotica #ESP32CAM #Bluetooth #ArduinoNano #L298N #RobotLaberinto #RobotAutonomo
