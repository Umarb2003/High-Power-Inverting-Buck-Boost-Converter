# High-Power-Inverting-Buck-Boost-Converter

# Project Discription
This project involves the design and simulation of a high-power inverting buck-boost converter circuit utilizing the TL494 IC. The TL494 is central to the circuit, enabling precise regulation and control of output voltage and current, making it ideal for various switch-mode power supply applications. The project demonstrates efficient PWM-based control for stepping up or stepping down voltage to meet load requirements.

The design prioritizes practical implementation by using readily available discrete components while addressing crucial factors such as thermal management, optimal routing, and reliability in high-power scenarios. A comprehensive 2-layer PCB layout and schematic were created in Altium Designer, leveraging advanced features such as the Design Rule Check (DRC) to verify compliance with manufacturing standards. A detailed Bill of Materials (BOM) was also prepared to streamline component procurement.

The circuit was prototyped on a breadboard for testing and debugging, providing insights into real-world hardware challenges and solutions. Key components include the IRFZ44N MOSFET, a fast recovery diode, and high-capacitance electrolytic capacitors to manage ripple and transient responses effectively. The design achieves inverting functionality, with the ability to convert positive input voltages to regulated negative output voltages, showcasing its versatility in power electronics applications.

This project not only highlights the theoretical and practical aspects of power electronics but also emphasizes the importance of systematic design, thermal considerations, and manufacturability in developing reliable and efficient circuits for real-world use.

High power Inverting Buck-Boost Converter Circuit based on the TL494 IC.

The created project was based on the Circuit Digest project titled "High Power Inverting Buck-Boost Converter Circuit Design with TL494 IC". 
The original project link is listed below:
https://circuitdigest.com/electronic-circuits/high-power-inverting-buck-boost-converter-circuit-design-with-tl494

I recreated the original author's schematic on Altium Designer, and utilized it to design a custom PCB. The schematic and footprint files are shown below.


Circuit schematic of Buck boost Converter design
![Buck boost converter altium schematic](https://github.com/user-attachments/assets/b1f901f2-4f42-40f3-948e-df6851a201f0)

Altium pcb board layout - 2d view
![Buck boost converter altium pcb board layout - 2d view](https://github.com/user-attachments/assets/f39290ff-e9fe-4706-a318-57e27b40ccb9)

Altium pcb board layout - 3d view (front view)
![Buck boost converter altium pcb board layout - 3d view (front view)](https://github.com/user-attachments/assets/cc414d75-af52-4c3d-bf53-8b880e59f691)
Altium pcb board layout - 3d view (top view)
![Buck boost converter altium pcb board layout - 3d view (top view)](https://github.com/user-attachments/assets/ff4868e7-4738-44e0-b37a-60c7acff522e)

Altium pcb board design - Bill of Materials
![Buck boost converter altium pcb board layout - BOM](https://github.com/user-attachments/assets/4652a0d8-98ae-4805-8097-50dba6bd23a0)

Altium pcb board design - Design Rule verification Report
![Buck boost converter altium pcb board layout - design rule verification report](https://github.com/user-attachments/assets/9803f840-840d-425e-a1a0-6f8d7bd6291a)







