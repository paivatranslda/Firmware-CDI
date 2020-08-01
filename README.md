# HONDA NSR125 / CRM125 - PROGRAMABLE CDI + RC Control
DIY Reprogramable CDI / RC Control Replacement
DIY Honda NSR125RR / CRM125R Programable CDI based on Thierry own design, Transmic AC CDI V7  https://transmic.net/16628_v7/ACCDI16F628v79r20c0.pdf from https://transmic.net .
Thierry made a generic PIC16 based programable diy cdi, and I pretend to make a version for HONDA NSR125RR model.

1- A word of thanks to Thierry for let me use is own design.
2- My acknowledge is limited, so help needed if someone is interested. 
3- With NSR125/CRM125, Transmic AC CDI work OK but OEM RC VALVE control will not work with it, for a street 2-strokes 125cc, losting RC Valve capability isn´t acceptable for power band control. - This is not true with 2-strokes racing engines.
  
  
  Work Points:
    Find one standard aluminium box. Yes aluminium, I like recyclable materials.
    Leave option for use OEM connectors or new modern waterproof connectors
    Would be nice to design a new and improved 3 Phase DC Retifier. / Later 
    
  PCB Design
    Standard size to fit inside a aluminium box.
    4 holes for fixing on box and electric ground 
  
  Circuit Design
    Use MAX9926 insted of inversed signal transistors for VR sensor reading.
    Use high eficient DC-DC conversor for Power Supply.
    Use TB6612FNG H-Bridge controller or other MOSFET based controller. / Leave L298N Alone
    Use daugther PIC12F638 for control RC valve seperated from PIC16F628A.
    2D Programable RC Valve map control.
    
    
   RC VALVE Morphlogy
    RC Valve is one analog servo alike system conteined in a plastic box.
    It got one motor with some redutor gears atached, one 15Kohm Variable Resistor conect to the end shaft ( just like servo's) and outside at the end  of the shaft one rond cable suport.
    It works by open and close RC Valve throw a dual cable system.
    Now, the RC controller is a very rudentary, analog only circuit inside a CDI alike box.
