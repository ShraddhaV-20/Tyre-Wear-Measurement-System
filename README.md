# Tyre-Wear-Measurement-System

### Problem Statement :
The existing tyre wear measurement involves manual vision based techniques for detection which consumes a lot of time, manual labour, and might be subjected to errors. The company needs a way to automate the process of tyre wear measurement so that time is utilized judiciously and rightful detection and analysis of wear measurement is achieved. 

### Statement of Need : 
To build a system that replaces the manual vision based technique for detection and analysis of tyre wear. Readimgs of the tyre wear using laser sensor to be tabulated and JSON file shared to the client API for further process to continue.

### Objectives of the work : 
The project objective is built upon designing a system to measure the tyre wear for VRL Logistics Ltd. The client at the logistics company requires to automate the process of tyre wear measurement. Currently, they employ visual inspection on the tyres and then take it out from the vehicle to check for tyre wear. Objectives are meant to be Smart, Measurable, Achievable, Relevant, and Time-bound. There are endless methodologies present for project management but the SMART approach has gained a lot of credibility. Having a clear and concise objective allows us to set the path straight. 
Goals and objectives follow the **SMART** rule.

1. **S**pecific : To develop a system that replaces manual vision based technique for tyre wear measurement
2. **M**easurable : Use of laser sensor to read tyre tread readings, tabulate the values, generate graph, and share the JSON file to client API
3. **A**chievable : Automate the process of tyre wear measurement
4. **R**elevant : To deliver client requirements as per needs specified
5. **T**ime-bound : To deliver client requirements as per needs specified in stipulated time slot

![twms_1](https://user-images.githubusercontent.com/95766195/195146244-a2b7c5f1-f164-4807-88c2-2a130edcec28.PNG)

### Graphical User Interface :
The frontend of the GUI is created using the PyQt5 designer. GUI is designed to complete the 
further processing to measure tyre wear. Readings are collected from the Arduino Code into a 
CSV File using a library ArdoSpread Sheet. The CSV file is used to tabulate and display 
readings, plot and save a copy of the graph, convert the CSV file into a JSON File, and finally, 
push this JSON file to the client API.
Details like, Date, Tyre specification, and Tyre ID and entered by the user.
Buttons description: 
1. Generate Values: This button reads data from the files, analyses the laser readings from tyre
depth, and finally generates a tabular column, followed by a graph plot.
2. Conversion: This button converts the CSV file into JSON file
3. Push to server: This button collects the recent JSON file and pushes it to the client API server




