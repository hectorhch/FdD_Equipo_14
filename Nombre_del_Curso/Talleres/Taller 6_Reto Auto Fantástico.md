## **INFORME DE PRÁCTICA: RETO N° 3 \- AUTO FANTÁSTICO**

### **1\. Título:**

* Implementación de un sistema de secuencia lumínica secuencial (Efecto Auto Fantástico) mediante Arduino Uno.

### **2\. Objetivo**

* Diseñar, simular y programar un sistema digital basado en una placa Arduino Uno para controlar una barra de múltiples diodos LED, logrando un efecto de barrido lumínico bidireccional (de ida y vuelta) mediante el uso de arreglos (*arrays*) y bucles de repetición (for).

### **3\. Materiales y Componentes Utilizados**

* 1 Placa Arduino Uno R3.  
* 1 Placa de protoboard (Protoboard).  
* 6 Diodos LED (color rojo o combinados).  
* 6 Resistencias de $220\Omega$ (para la protección individual de cada LED).  
* Cables de conexión (jumpers).

### **4\. Descripción del Montaje y Conexiones (Hardware)**

El circuito se implementó interconectando múltiples elementos de salida digital sobre la protoboard y la placa de desarrollo:

* **Etapa de Salida (LEDs):** Se dispusieron 6 diodos LED de forma consecutiva en la protoboard. Las patas positivas (ánodos) de cada LED se conectaron de manera directa y ordenada a los pines digitales del 6 al 11 de la placa Arduino Uno.  
* **Etapa de Protección y Tierra:** Las patas negativas (cátodos) de cada uno de los LEDs se conectaron en serie a una resistencia de $220\Omega$, cuyos extremos convergieron hacia una línea común conectada al pin de tierra (GND) del Arduino, cerrando así el circuito eléctrico.

### **5\. Código de Programación (Software)**

Para optimizar el código y evitar la repetición de instrucciones, se programó utilizando arreglos unidimensionales (*arrays*) y estructuras iterativas de control (for) en el entorno de desarrollo Arduino IDE:



**6\.** **Imágenes del Reto \#3 realizado en TinkerCad:**

(Imágenes tomadas del TinkerCad, la imagen de la izquierda indica el regreso del patron de los LEDS, la imagen de la derecha se evidencia como va avanzando este patron, lo cual es ida y vuelta)





Link del TinkerCad: [https://www.tinkercad.com/things/4zXxMV4LtE6-smashing-kieran-leelo?sharecode=G0tatd4Xpnjll\_vRO8KNutbDAqo9cE1dbp9zq7Hjx4g](https://www.tinkercad.com/things/4zXxMV4LtE6-smashing-kieran-leelo?sharecode=G0tatd4Xpnjll_vRO8KNutbDAqo9cE1dbp9zq7Hjx4g) 

