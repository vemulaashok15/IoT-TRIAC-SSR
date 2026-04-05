**IoT-Based Solid State Relay (SSR) Using TRIAC**

 **Description**

This project demonstrates the design and implementation of an IoT-based Solid State Relay (SSR) using a TRIAC to control AC loads remotely. It ensures safe, efficient, and contactless switching of high-voltage appliances.
**Features**
* Remote ON/OFF control of AC loads
* Fast and silent switching (no mechanical relay)
* Electrical isolation using optocoupler
* Energy efficient and reliable
* Suitable for smart home automation

**Components Used**

* Microcontroller ( ESP8266)
* TRIAC (BT136)
* Resistors
* AC Load (Bulb / Fan)
* Power Supply

 **Working Principle**

The microcontroller sends a signal to the optocoupler, which isolates the low-voltage control circuit from the high-voltage AC side. The optocoupler then triggers the TRIAC, allowing current to flow and power the connected load. The IoT module enables remote control via a mobile app or web interface.

**How to Run**

1. Assemble the circuit as per the diagram
2. Upload the code to the microcontroller using Arduino IDE
3. Configure Wi-Fi credentials (if applicable)
4. Power the circuit
5. Control the load remotely
   
**⚠️ Safety Note**

⚡ This project involves AC mains voltage. Handle with care and ensure proper insulation to avoid electric shock.

**Applications******

* Smart home automation
* Remote appliance control
* Industrial automation
* Energy management systems
