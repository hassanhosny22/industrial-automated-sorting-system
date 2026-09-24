# Industrial Automated Sorting System

##  Project Overview

A simulated industrial production line developed using **Siemens PLC Simulation, SIMATIC Manager, Ladder Logic, and Factory I/O**.

The system automatically detects and sorts three different product types based on their shapes and colors.

A sensor generates a different value for each product type. The value is stored in the PLC memory and compared with predefined values to identify the product. Based on the detected type, the corresponding sorting arm is activated to direct the product to its designated line.

##  Tools & Technologies

* Siemens PLC Simulation
* SIMATIC Manager
* Ladder Logic (LAD)
* Factory I/O
* Sensors & Product Detection
* PLC Memory Operations
* Value Comparison
* Automated Sorting Arms
* Counters

##  Control Features

* Start / Stop
* Emergency Stop
* Counter Reset
* Three Individual Product Counters
* Automatic / Manual Mode Selector
* Product Detection & Classification
* Automated Sorting

### Manual Mode

Manual mode allows the main conveyor to operate independently without activating the sorting arms.

##  System Sequence

1. The conveyor transports the product through the detection area.
2. The sensor detects the product and generates a corresponding value.
3. The detected value is stored in the PLC memory.
4. The stored value is compared with predefined values.
5. The PLC identifies the product type.
6. The corresponding sorting arm is activated.
7. The product is directed to its designated line.
8. The corresponding product counter is incremented.

##  PLC Programming Concepts

This project provided practical experience with:

* Sensor-based detection
* Memory operations
* Value comparison
* Sequential control
* Counters
* Mode selection
* Emergency stop logic
* Industrial automation concepts

##  Project Demonstration

The project demonstration is available on LinkedIn:

[Watch the Project on LinkedIn](https://www.linkedin.com/posts/hassan-hosny-shawky-8bab47304_industrialautomation-plc-factoryio-activity-7508597534244913152-PTaT)

##  Simulation Environment

The complete production line was simulated using **Factory I/O**, while the control logic was developed using **Siemens PLC Simulation and SIMATIC Manager**.

##  Author

**Hassan Hosny Shawky**

Mechatronics Engineering Student
Sphinx University — Egypt

[LinkedIn](https://www.linkedin.com/in/hassan-hosny-shawky-8bab47304)

[GitHub](https://github.com/hassanhosny22)
