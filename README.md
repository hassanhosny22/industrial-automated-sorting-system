#  Industrial Automated Sorting System

##  Project Overview

An industrial automated sorting system developed and validated in a **simulated environment** using **Siemens PLC Simulation, SIMATIC Manager, Ladder Logic, and Factory I/O**.

The system automatically detects and sorts three different product types based on their shape and color.

The detected sensor value is stored in PLC memory and compared with predefined values to identify the product type. The corresponding sorting mechanism is then activated to route the product to its designated line.

##  Simulation Environment

* Siemens PLC Simulation
* SIMATIC Manager
* Factory I/O
* Ladder Logic (LAD)

**Note:** This project was developed and tested using simulation software. No physical PLC was used.

##  Main Features

* Automatic product detection
* Product classification
* Sensor value storage
* Value comparison
* Automatic sorting
* Start / Stop control
* Emergency Stop
* Counter Reset
* Individual product counters
* Automatic / Manual mode

##  System Operation

1. A product enters the conveyor.
2. Sensors detect the product.
3. The sensor reading is stored in PLC memory.
4. The stored value is compared with predefined values.
5. The PLC identifies the product type.
6. The corresponding sorting mechanism is activated.
7. The product is routed to its designated line.
8. The appropriate counter is incremented.

##  Operating Modes

### Automatic Mode

The system automatically detects, identifies, and sorts the products.

### Manual Mode

The main conveyor can operate independently without activating the sorting mechanisms.

##  PLC Programming Concepts

This project demonstrates practical use of:

* Digital sensors
* Memory operations
* Comparison instructions
* Sequential control
* Counters
* Interlocking logic
* Operating modes
* Emergency stop logic
* Industrial automation principles

##  Project Demonstration

The project demonstration is available on LinkedIn:

[Watch the Project Demonstration](https://www.linkedin.com/posts/hassan-hosny-shawky-8bab47304_industrialautomation-plc-factoryio-activity-7508597534244913152-PTaT)

##  Project Documentation

Screenshots and additional project documentation can be added here.

##  Author

**Hassan Hosny Shawky**

Mechatronics Engineering Student
Sphinx University — Egypt

[LinkedIn](https://www.linkedin.com/in/hassan-hosny-shawky-8bab47304)

[GitHub](https://github.com/hassanhosny22)
