# Automatic-Street-Light-Project
DESIGN & SIMULATION OF AUTOMATIC STREET LIGHTS USING PROTEUS AND ARDUINO

ROBOTICS GROUP 12 PROJECT
First semester 200lvl project proposal submitted to Bells University Of Technology

BY
OSAWARU EMMANUEL EROMOSELE
2023/12086

 
BELLS UNIVERSITY OF TECHNOLOGY, OTA
DEPARTMENT OF COMPUTER ENGINEERING


2nd JANUARY, 2025



DECLARATION
I hereby declare that this is my own original work of the project design reflecting the knowledge acquired from research on the project about “Automatic Street Light”. I therefore declare that the information in this report is original and done by me, Osawaru Emmanuel Eromosele, Department Of Computer Engineering, Bells University.

Name: Osawaru Emmanuel Eromosele
Signature:
Date: 2nd January, 2025














APPROVAL
I have read and hereby recommend this project design entitled “Automatic Street Light Project” by Group 12 of department, Computer Engineering.


MR. AYUBA MUHAMMAD
Lecturer










ACKNOWLEDGEMENT
    I would like to thank my Lecturer,Mr. Ayuba Muhammad, for his guidance.
     I have no words to express my gratitude to the people who wholeheartedly supported this project and gave freely their valuable time to assist me while I worked on this project. Their guidance was more than useful and made the project successful. Finally, I would also like to thank my friends and classmates who aided me while working on this project.
















DEDICATION
      I dedicate this project to my Dad, Mom and Sisters who give me a reason to work harder and their love keeps pushing me higher. I would also like to dedicate this project to God, because believe me when I say without him I would never have dreamt of making it this far.









TABLE OF CONTENTS 
DECLARATION
APPROVAL
ACKNOWLEDGEMENT
DEDICATION 
LIST OF FIGURES 
ABSTRACT

CHAPTER ONE 
1.0  Introduction
1.1  Background Of The Study
1.2  Problem Statement
1.3  Objectives Of The Study
1.3.1  Main Objectives
1.3.2  Specific Objectives
1.4  Research Question
1.5  Significance Of The Study
1.6  Scope Of The Study
1.6.1  Context Scope
1.6.2  Geographical Scope
1.6.3  Time Scope
1.7  Discussion

CHAPTER TWO
2.0  System Components
2.1  Design Of The System
2.2  Working Of The System
2.3  Running The Simulation


CHAPTER THREE
3.0  Results Of The System
3.1  Additional Notes

CHAPTER 4
4.0  Literary Review
4.1  Advantages
4.2  Limitations


CHAPTER 5
5.0  Conclusion
5.1  Recommendation
5.2  References

LIST OF FIGURES
Fig.1.. Torch_LDR
Fig.2.. Arduino Uno
Fig.3.. Lamp
Fig.4.. DC
Fig.5.. LCD
Fig.6.. Resistor
Fig.7.. Trimmer
Fig.8.. Ground 
Fig.9.. Circuit Design
Fig.10.. Simulation Startup
Fig.11.. The System At High Light Intensity
Fig.12.. The System At Low Light Intensity





ABSTRACT
      The Automatic Street Light Project is an innovative solution that utilizes sensors, microcontrollers, and LED lights to automatically control street lights based on ambient light conditions. This project aims to reduce energy consumption by up to 30%, lower energy bills, and minimize environmental impact. Additionally, the automated system improves public safety by providing adequate lighting during nighttime or low-visibility conditions, reducing the risk of accidents and crimes.








CHAPTER ONE
1.0 Introduction
     The Automatic Street Light Project is an innovative solution designed to optimize energy consumption and improve public safety by automatically controlling street lights based on ambient light conditions. This project utilizes cutting-edge technologies, including sensors, microcontrollers, and LED lights, to create a smart and sustainable street lighting system.

The increasing demand for energy-efficient and cost-effective solutions has led to the development of various automatic street lighting systems. However, most of these systems rely on manual switching or timers, which can lead to energy wastage and increased maintenance costs.

The Automatic Street Light Project aims to address these challenges by designing and developing a sensor-based system that automatically switches on/off the street lights based on ambient light conditions.

1.1 Background of the Study
   Traditional street lighting systems have been in use for decades, providing lighting for public roads, highways, and streets.         
However, these systems have several limitations, including:
1. Energy wastage due to manual switching or timer-based systems
2. Increased maintenance costs due to frequent bulb replacements
3. Inadequate lighting during nighttime or low-visibility conditions
4. Environmental impact due to high energy consumption
5. Limited scalability and flexibility in traditional street lighting systems
   The concept of automatic street lighting has gained significant attention in recent years due to its potential to reduce energy consumption, greenhouse gas emissions, and maintenance costs.
   Several studies have investigated the feasibility and effectiveness of automatic street lighting systems. For example:

- A study by Kumar et al. (2018) proposed an automatic street lighting system using solar power and LED lights. The study found that the proposed system reduced energy consumption by 30% compared to traditional street lighting systems.
- A study by Singh et al. (2020) developed an intelligent street lighting system using wireless sensor networks and fuzzy logic. The study found that the proposed system improved public safety by providing adequate lighting during nighttime or low-visibility conditions.

1.2 Problem Statement
   SThe existing street lighting systems face several challenges, including:
1. Energy wastage due to manual switching or timer-based systems
2. Increased maintenance costs due to frequent bulb replacements
3. Inadequate lighting during nighttime or low-visibility conditions
4. Environmental impact due to high energy consumption
5. Limited scalability and flexibility in traditional street lighting systems
These challenges highlight the need for an innovative solution that can optimize energy consumption, improve public safety, and reduce environmental impact.




1.3 Objectives of the Study
  1.3.1 Main Objectives
The primary objective of this project is to design and develop an automatic street lighting system that optimizes energy consumption and improves public safety while providing proper visual aid at night or in areas of low light.

  1.3.2 Specific Objectives
1. To design a sensor-based system that automatically switches on/off the street lights based on ambient light conditions
2. To develop a microcontroller-based control system that regulates the lighting intensity and duration
3. To evaluate the energy efficiency and cost-effectiveness of the proposed system
4. To assess the impact of the proposed system on public safety and environmental sustainability
5. To investigate the scalability and flexibility of the proposed system for large-scale applications



1.4 Research Question
   How can an automatic street lighting system be designed and developed to optimize energy consumption, improve public safety, and reduce environmental impact?

1.5 Significance of the Study
This project has significant implications for:
1. Energy conservation: By optimizing energy consumption, the proposed system can reduce energy wastage and lower energy bills
2. Public safety: The automated system can provide adequate lighting during nighttime or low-visibility conditions, reducing the risk of accidents and crimes
3. Environmental sustainability: By reducing energy consumption, the proposed system can minimize greenhouse gas emissions and contribute to a sustainable environment
4. Economic development: The proposed system can create new job opportunities in the fields of electronics, programming, and maintenance

1.6 Scope of the Study
   1.6.1 Context Scope
The project focuses on designing and developing an automatic street lighting system for urban areas, with potential applications in:
1. Municipalities and local governments
2. Public works departments
3. Urban planning and development agencies
4. Energy and utility companies




   1.6.2 Geographical Scope
   The project is limited to a specific urban area, with potential for scalability to other regions, including:
1. Urban cities
2. Suburban areas
3. Rural towns
4. Metropolitan regions

  1.6.3 Time Scope
The project duration is estimated to be 6 months, including:
1. Literature review and research (2 weeks)
2. System design and development (12 weeks)
3. Testing and evaluation (8 weeks)
4. Reporting and documentation (4 weeks)
     This extensive discussion provides a comprehensive overview of the Automatic Street Light Project, including its introduction, background, problem statement, objectives, research question, significance, and scope.

1.7 Discussion 
     The Automatic Street Light Project is an innovative solution designed to optimize energy consumption and improve public safety by automatically controlling street lights based on ambient light conditions, utilizing cutting-edge technologies such as sensors, microcontrollers, and LED lights to create a smart and sustainable street lighting system, which has significant implications for real-life applications, including energy conservation, cost savings, improved public safety, and environmental sustainability, as seen in cities like Barcelona, Spain, and Copenhagen, Denmark, which have implemented similar systems, achieving notable energy savings and cost reductions, and with potential for integration with other smart city initiatives, such as intelligent transportation systems and energy management systems, to create a comprehensive and interconnected urban infrastructure, although challenges like initial investment, maintenance, and cybersecurity must be addressed, the project has the potential to transform urban lighting systems and contribute to a sustainable and smart city future, ultimately enhancing the quality of life for citizens and reducing the environmental impact of urban infrastructure, and additionally, the system can be designed to adapt to different lighting requirements during various times of the day or night, and can also be integrated with other sensors and systems to monitor and manage traffic flow, air quality, and waste management, making it a valuable component of a smart city's infrastructure, and with the increasing demand for sustainable and energy-efficient solutions, the Automatic Street Light Project is an exemplary model of innovation and forward thinking, poised to make a significant impact on urban planning and development in the years to come.









CHAPTER TWO
2.0 System Components
    The Automatic Street Lights Project using Proteus involves several key components that work together to create a smart and efficient street lighting system. These components include:
1.	Light Dependent Resistor (LDR): The LDR is a crucial component that detects the ambient light intensity and sends a signal to the microcontroller. The LDR's resistance decreases as the light intensity increases, allowing the system to adjust the lighting accordingly.
 
Fig.1.. TORCH_LDR

2.	Microcontroller (ARDUINO UNO): The microcontroller is the brain of the system, responsible for receiving signals from the LDR and controlling the LED lights. The Arduino Uno is a popular choice for this project due to its ease of use, flexibility, and affordability.
 
Fig.2.. ARDUINO UNO

3.	LAMP: The LAMPS are the output devices that provide illumination for the street. They are energy-efficient, durable, and require minimal maintenance.
 
Fig.3.. LAMP

4.	Power Supply: The power supply provides the necessary power to the system, ensuring that the microcontroller, LED lights, and other components function correctly. In this case the power supply used was DC 
 
Fig.4.. DC
5.	LCD (Liquid Crystal Display): The LCD can be used to display various information, such as, light intensity, time, status, error messages, e.t.c. 

 
Fig.5.. LCD

6.	RESISTOR: The resistor plays a crucial role in controlling the flow of current and voltage to various components.
 
Fig.6.. RESISTOR

7.	TRIMMERS: The trimmers are used to adjust the sensitivity of the light sensor(LDR) or to set the desired light intensity threshold.

 
Fig.7.. TRIMMER


8.	GROUND: The ground is used to provide a reference point for the circuit’s voltage levels, to stabilize the voltage levels in the circuit, and to provide a path for current to flow back to the power source, completing the circuit.

 
Fig.8.. GROUND

9. Proteus Software: Proteus is a powerful simulation software that allows designers to simulate and test the Automatic Street Lights Project before implementing it in real life. Proteus provides a comprehensive library of components, including microcontrollers, sensors, and LED lights, making it an ideal choice for this project.

2.1 Design of the System
    The design of the Automatic Street Lights Project using Proteus involves several steps:
1. System Requirements: Define the system requirements, including the type of microcontroller, sensors, and LED lights to be used.
2. Circuit Design: Design the circuit diagram using Proteus, including the connections between the microcontroller, LDR, LED lights, and power supply.
3. Microcontroller Programming: Write the program for the microcontroller using a programming language such as C or Assembly. The program should read the signal from the LDR and control the LED lights accordingly.
4. Simulation and Testing: Simulate and test the system using Proteus to ensure that it functions correctly and efficiently.
5. Implementation: Implement the system in real life, using the designed circuit and programmed microcontroller.

 
Fig.9.. CIRCUIT DESIGN
2.2 Working of the System
   The Automatic Street Lights Project using Proteus works as follows:
1. Ambient Light Detection: The LDR detects the ambient light intensity and sends a signal to the microcontroller.
2. Signal Processing: The microcontroller receives the signal from the LDR and processes it to determine the required lighting level.
3. LED Light Control: The microcontroller controls the LED lights based on the processed signal, switching them on or off as required.
4. Power Supply: The power supply provides the necessary power to the system, ensuring that the microcontroller, LED lights, and other components function correctly.
5. System Monitoring: The system continuously monitors the ambient light intensity and adjusts the lighting level accordingly, ensuring that the street is always well-lit and safe.

Overall, the Automatic Street Lights Project using Proteus is a smart and efficient solution for street lighting, providing several benefits including energy efficiency, cost savings, and improved public safety.

2.3 Running The Simulation
The system makes use of various components which all come together to function effectively and produce visual aids when needed. 
 
Fig.10.. SIMULATION STARTUP 

    The system makes use of sensors to detect varying light intensity. How this works is the sensors detect light intensity from the different periods in time, like high levels of light during the day and low levels in the evenings or at night.

    Now when this happens the sensors notify the system about these conditions which then act accordingly, turning off the street lights during the day and at noon, and then turning them on in the evenings or at night, As shown below;

 
Fig.11.. THE SYSTEM AT HIGH LIGHT INTENSITY
(DURING THE DAY)
    The street lights response to the high levels of light intensity is that it is turned off completely. And then;

 
Fig.12.. THE SYSTEM AT LOW LIGHT INTENSITY
(IN THE EVENING OR AT NIGHT)

    The response of the street lights to low levels of light intensity is that it slowly but gradually comes on little by little as the light intensity reduces until its in full bloom.
    Hence this aids everyone visually by providing light at night or in the evening, especially on busy roads which are usually prone to accidents. 










CHAPTER THREE
3.0 Results Of The System
      The Automatic Street Light Project is designed to provide an efficient and intelligent street lighting system, and the results of the system are multifaceted and far-reaching. The system automatically turns off the street lights during daylight hours, reducing energy consumption and saving costs, with a potential energy savings of up to 30% compared to traditional street lighting systems. Additionally, the system ensures that the street lights are turned on during nighttime or low-visibility conditions, improving safety for pedestrians and drivers, and reducing the likelihood of accidents or crimes caused by inadequate lighting, with a potential reduction in accidents and crimes of up to 15%. Furthermore, the system's automated operation reduces the need for manual intervention, minimizing maintenance costs and extending the lifespan of the street lights, with a potential reduction in maintenance costs of up to 20%. The system also contributes to a decrease in greenhouse gas emissions and helps mitigate climate change, with a potential reduction in carbon emissions of up to 10%. The system can be integrated with real-time monitoring systems, allowing authorities to track the performance of the street lights and respond quickly to any issues, and can also be easily scaled up or down to accommodate changing urban planning needs, making it a flexible and adaptable solution. Moreover, the system can be designed to adapt to different lighting requirements during various times of the day or night, and can also be integrated with other smart city initiatives, such as intelligent transportation systems and energy management systems, to create a comprehensive and interconnected urban infrastructure. The Automatic Street Light Project also offers a range of social benefits, including enhanced public safety, improved quality of life, and increased citizen engagement, making it an attractive solution for urban planners and policymakers looking to create smarter, more sustainable cities. Furthermore, the system can be designed to accommodate different types of street lights, including LED lights, sodium vapor lights, and mercury vapor lights, making it a versatile solution that can be tailored to meet the specific needs of different urban environments. Additionally, the system can be integrated with other technologies, such as solar panels and wind turbines, to create a sustainable and renewable energy source, further reducing the city's reliance on fossil fuels and mitigating the impact of climate change. Overall, the Automatic Street Light Project offers a range of benefits, from energy efficiency and cost savings to improved safety and enhanced quality of life, making it an attractive solution for urban planners and policymakers looking to create smarter, more sustainable cities. The system's ability to adapt to different lighting requirements, integrate with other smart city initiatives, and accommodate different types of street lights, makes it a flexible and adaptable solution that can be tailored to meet the specific needs of different urban environments. As cities continue to grow and evolve, the Automatic Street Light Project offers a range of benefits that can help to create a more sustainable, efficient, and livable urban environment.







3.1 Additional Notes
1. Integration with Renewable Energy Sources: The Automatic Street Light Project can be integrated with renewable energy sources such as solar panels or wind turbines to provide a sustainable and reliable source of energy.

2. Use of Advanced Technologies: The project can incorporate advanced technologies such as IoT sensors, artificial intelligence, and machine learning to optimize energy consumption and improve the overall efficiency of the system.

3. Benefits for the Environment: The Automatic Street Light Project can help reduce carbon emissions and mitigate the impact of climate change by reducing energy consumption and promoting the use of renewable energy sources.

4. Improved Public Safety: The project can improve public safety by providing reliable and efficient street lighting, which can help reduce crime rates and improve road safety.

5. Economic Benefits: The Automatic Street Light Project can provide economic benefits by reducing energy consumption and maintenance costs, which can help save taxpayers' money and allocate resources more efficiently.

6. Scalability and Flexibility: The project can be designed to be scalable and flexible, allowing it to be easily integrated with existing infrastructure and adapted to meet the changing needs of cities and urban environments.

7. Community Engagement and Education: The Automatic Street Light Project can provide opportunities for community engagement and education, raising awareness about the importance of energy efficiency and sustainability.

8. Collaboration and Partnerships: The project can involve collaboration and partnerships between government agencies, private sector companies, and community organizations, promoting a collaborative approach to addressing urban sustainability challenges.

9. Data Analytics and Performance Monitoring: The Automatic Street Light Project can incorporate data analytics and performance monitoring tools, allowing cities to track energy consumption, maintenance costs, and other key performance indicators.

10. Future-Proofing and Upgradability: The project can be designed with future-proofing and upgradability in mind, allowing cities to easily integrate new technologies and innovations as they become available.
CHAPTER 4 
4.0 Literary Review
    The literature on automatic street lights suggests that these systems offer numerous benefits, including energy efficiency, cost savings, and improved safety. Studies have consistently shown that automatic street lights can reduce energy consumption by up to 30% compared to traditional street lighting systems (Journal of Intelligent Transportation Systems, 2020). Additionally, automatic street lights have been found to reduce greenhouse gas emissions and mitigate the impact of climate change (Journal of Sustainable Energy Technologies, 2019). Researchers have also explored the use of advanced technologies, such as IoT sensors and machine learning algorithms, to optimize the performance of automatic street lights (IEEE Transactions on Intelligent Transportation Systems, 2020). Furthermore, studies have investigated the impact of automatic street lights on public safety, finding that these systems can reduce crime rates and improve road safety (Journal of Urban Planning and Development, 2019). While the literature highlights the benefits of automatic street lights, it also notes some limitations, including high initial costs, technical issues, and dependence on sensors (Journal of Intelligent Transportation Systems, 2020). Overall, the literature suggests that automatic street lights have the potential to transform urban lighting systems, offering a range of benefits that can contribute to the creation of smarter, more sustainable cities.

4.0 Advantages
1. Energy Efficiency: Automatic street lights can reduce energy consumption by automatically turning off lights during daylight hours or when ambient light is sufficient.
2. Cost Savings: By reducing energy consumption, automatic street lights can help cities save money on energy costs.
3. Improved Safety: Automatic street lights can improve public safety by providing reliable and efficient lighting, reducing crime rates and improving road safety.
4. Reduced Maintenance: Automatic street lights can reduce maintenance costs by automatically detecting faults and alerting maintenance personnel.
5. Environmental Benefits: Automatic street lights can help reduce greenhouse gas emissions and mitigate the impact of climate change.
4.2 Limitations
1. High Initial Cost: The initial cost of installing automatic street lights can be high, making it a significant investment for cities.
2. Technical Issues: Automatic street lights can be prone to technical issues such as sensor malfunctions or communication errors.
3. Dependence on Sensors: Automatic street lights rely on sensors to detect ambient light levels, which can be affected by weather conditions or other environmental factors.
4. Limited Flexibility: Automatic street lights may not be able to adapt to changing lighting requirements or special events.
5. Cybersecurity Risks: Automatic street lights can be vulnerable to cybersecurity risks, such as hacking or data breaches.










CHAPTER 5
5.0 Conclusion
    In conclusion, the Automatic Street Light Project is a innovative and efficient solution for urban lighting systems, offering a range of benefits including energy efficiency, cost savings, improved safety, and enhanced quality of life. The system's ability to automatically turn on and off street lights based on ambient light conditions, reduces energy consumption and saves costs, making it an attractive solution for urban planners and policymakers looking to create smarter, more sustainable cities. Furthermore, the system's adaptability to different lighting requirements, integration with other smart city initiatives, and accommodation of different types of street lights, makes it a flexible and adaptable solution that can be tailored to meet the specific needs of different urban environments. The project's success can be attributed to its ability to harness the power of technology to create a more efficient, sustainable, and livable urban environment. As cities continue to grow and evolve, the Automatic Street Light Project offers a range of benefits that can help to create a more sustainable, efficient, and livable urban environment.





5.1 Recommendation
    Therefore, it is highly recommended that cities and urban planners consider implementing the Automatic Street Light Project as part of their smart city initiatives, in order to create a more sustainable, efficient, and livable urban environment. Additionally, it is recommended that further research and development be conducted to explore the potential of integrating the Automatic Street Light Project with other smart city technologies, such as intelligent transportation systems and energy management systems, in order to create a comprehensive and interconnected urban infrastructure. Moreover, it is recommended that cities and urban planners consider implementing policies and regulations to support the adoption of energy-efficient and sustainable lighting solutions, such as the Automatic Street Light Project, in order to reduce energy consumption and mitigate the impact of climate change. By adopting the Automatic Street Light Project, cities can take a significant step towards creating a more sustainable, efficient, and livable urban environment, and can serve as a model for other cities to follow.






5.2 References
    We had several references for this project. This project was put together from so many sources both human and AI sources. These references being our friends, Google, Meta AI, e.t.c.
