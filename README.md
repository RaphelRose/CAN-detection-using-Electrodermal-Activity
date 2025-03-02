# CAN-detection-using-Electrodermal-Activity
Cardiovascular autonomic neuropathy (CAN) is a serious complication of diabetes and other chronic conditions, characterized by autonomic nervous system dysfunction that can lead to life-threatening cardiovascular events. Despite its severity, CAN is often underdiagnosed due to the lack of accessible, non-invasive diagnostic tools. 
This project aims to develop a Electrodermal Activity (EDA) sensor to monitor skin conductance and autonomic responses, providing an early detection system for CAN. The system will integrate real-time data processing and analysis thus offering a cost-effective and non-invasive solution to improve early diagnosis and management of CAN in at-risk populations.

## Abstract
This project introduces a novel EDA (Electrodermal Activity) sensor designed to measure skin conductance levels, which can be used as an indicator of physiological responses. 
By capturing real-time changes in skin conductance, this sensor provides valuable data on the autonomic nervous system's activity, which is closely linked to cardiovascular health. 
The collected data is visualized through signal graphs, enabling the identification of patterns and anomalies that may indicate cardiovascular disorders.
This innovative approach offers a non-invasive method to monitor heart health, potentially aiding in early diagnosis and preventive care. 
The project will detail the sensor’s functionality, data interpretation, and its applications in cardiovascular health monitoring.

## Existing Methodology
SUDOSCAN is a non-invasive device that measures skin conductance to assess sweat gland function and autonomic nerve activity. It uses electrodes to detect ions in sweat, providing quick results. SUDOSCAN is commonly used to diagnose and monitor conditions like diabetic neuropathy and other autonomic disorders by evaluating small nerve fiber function.

## Methodology
The EDA sensor system is developed using readily available electronic components and open-source platforms to create a cost-effective and efficient device for measuring skin conductance levels. 
The methodology involved several key steps: 
### Arduino UNO: The Arduino UNO microcontroller serves as the central processing unit of the sensor system.  
Resistors and Capacitors: To stabilize the sensor's readings and filter noise, ensuring accurate measurement of skin conductance.
Operational amplifier: An op-amp amplifies the weak signals from the EDA sensor, making them strong enough for the Arduino to process and analyze. It also conditions the signal, ensuring accuracy and stability.
Sensor Design: The sensor comprises two electrodes that are placed on the skin to measure conductance. The change in skin conductance, which correlates with sweat gland activity, is captured by these electrodes and transmitted as a variable electrical signal.
Data Processing: Amplification of the signal is done using an operational amplifier (Op-Amp) to ensure accurate readings. The processed data is then analyzed by the Arduino.
Real-Time Visualization: The skin conductance data is plotted on a graph, enabling visualization of fluctuations and patterns indicative of cardiovascular and neural health.
Analysis for Cardiovascular Disease Detection: Interpretation of the graphical data helps to identify potential anomalies or patterns that could suggest cardiovascular and neural conditions, providing a basis for early diagnosis.

## Novelty
The EDA sensor we developed represents a breakthrough in non-invasive cardiovascular health monitoring. Unlike traditional diagnostic tools that require extensive and often costly equipment, our sensor provides a simple yet effective way to measure skin conductance levels as an indirect marker of cardiovascular health.

## Conclusion
This project successfully helps us to detect CAN and other disorders by demonstrating the development of an EDA sensor using an Arduino to measure skin conductance levels. By visualizing this data in real-time, we can detect patterns that may indicate cardiovascular diseases, providing a non-invasive and accessible tool for monitoring heart health. The sensor’s portability and ease of use make it suitable for both clinical and personal applications, potentially aiding in early diagnosis and preventive care.
