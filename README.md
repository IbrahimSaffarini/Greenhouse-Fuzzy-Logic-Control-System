# Greenhouse Fuzzy Logic Control System

<p align="justify">
This project is a fuzzy logic system designed to control the electric roof and water spills of a greenhouse using temperature, humidity, and light intensity sensors. The project involves developing fuzzy membership functions, generating rules, simulating the system in LabVIEW, and visualizing data on ThingSpeak.
</p>

## Key Features & Technologies

### 1- Design and Development of Fuzzy Logic System:

- **Sensors and Inputs:**

    - Temperature Sensor: Measures the temperature inside the greenhouse.

    - Humidity Sensor: Measures the humidity levels inside the greenhouse.

    - Light Intensity Sensor: Measures the intensity of light within the greenhouse.

- **Membership Functions:**

    - Inputs: Each sensor input is characterized by four trapezoidal membership functions.

    - Outputs: The system's responses (such as roof adjustment and water spill control) are defined by four triangular membership functions.

### 2- Rule Generation:

- **Fuzzy Rules:**

    - Utilized ChatGPT to generate the membership functions & the 64 rules of fuzzy logic system.

    - Utilized the Fuzzy System Designer to test and adjust the generated rules.

### 3- LabVIEW Simulation:

- **Development Environment:**

    - Utilized LabVIEW to develop and simulate the fuzzy logic system.

- **Block Diagrams:**

    - Created detailed block diagrams representing the logic and flow of data within the system.

- **Front Panels:**

    - Developed front panels for interactive simulation and visualization of inputs, outputs, and system states.

### 4- Visualization with ThingSpeak:

- **Integration:**

    - Integrated ThingSpeak for real-time data visualization and monitoring.

- **Data Visualization:**

    - Visualized sensor inputs and system outputs using charts (lines and bars) and widgets (numeric displays and gauges).

- **Monitoring:**

    - Monitored system performance and behavior through ThingSpeak’s cloud-based platform, allowing remote access and analysis.

### 5- Data Handling:

- **Data Download:**

    - Downloaded data fields from ThingSpeak for further analysis and processing.

- **Data Processing:**

    - Fetched and processed specific elements from the downloaded data to assess system performance and make necessary adjustments.

## System Design & Implementation

### Overview

<p align="justify">
Before delving into the system design and implementation, which includes the block diagram, front panel view, test cases, and ThingSpeak dashboard snapshots, it is best to review the detailed information about the input variables, input membership functions, output membership functions, and the rules that can be found in the <a href="https://drive.google.com/file/d/1071sgmB6e1x3NcdXNK8WpkdTlJ_ZIO7M/view?usp=drive_link">Fuzzy Set Report</a>.
</p>

### System Block Diagram Download Segment

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1BKH1eMXfBEDDypwxvo3qWYyvCg7AfMo1" alt="Block Diagram Download Segment" />
</div>

### System Block Diagram Upload Segment

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1oengSsdQbW77sHkitkhc1MnemU_qBkAv" alt="Block Diagram Upload Segment"" />
</div>

### System Front Pannel View

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1_ar4XQzp0hQBynwglJiZbkZReOvsaBsi" alt="Front Pannel View" />
</div>

### Fuzzy System Designer Multiple Rules with Different Weights

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1zp_pD1uqOgrr1uGhpsXdH5eo2hIm-qVW" alt="Fuzzy System Designer Multiple Rules with Different Weights" />
</div>

### Front Panel View of the Dominant Rule (38)

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1d5dnr4ePldJmpJuwOcybWv_LIdC6Yxkb" alt="Front Panel View of the Dominant Rule (38)" />
</div>

### ThingSpeak Visualizations & Widgets

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1wOvaWiGU75OiN6iTvtzi0WZOwj7IkvJy" alt="ThingSpeak First Four Fields Charts" />
</div>

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1y-DJJW6xtQDKoNZaHTJXhray-SQs-WU9" alt="ThingSpeak Chart, Gauges, and Numeric Display" />
</div>

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1v8kE6GPTDRwBk-1qT_5KJi-YNNcvBesp" alt="ThingSpeak Water Spills Gauge" />
</div>

### Light Intensity Numeric Display & Lamp is Off < 2000

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1XjLLT0sJOxXt3htV82ioQFhZkFl5YgC0" alt="Light Intensity Numeric Display & Lamp is Off" />
</div>

### Light Intensity Numeric Display & Lamp is On > 2000

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1uYTHSCa16hEsfsy7LK-Y5jWudeprOK6S" alt="Light Intensity Numeric Display & Lamp is On" />
</div>

## Installation & Setting Up the Project

### Prerequisites

#### 1- Ensure you have LabVIEW installed on your computer.

#### 2- Create a ThingSpeak account.

#### 3- Create a new project (channel) in your ThingSpeak account.

#### 4- Configure the channel with the following five fields:

  - Temperature

  - Humidity

  - Light Intensity

  - Electric Roof

  - Water Spills

#### 5- Obtain the Write API Key and the Channel ID for your ThingSpeak channel.

#### 6- Set up the visualizations and widgets for the fields in the public view.

### Running The Project

#### 2- Download the Repository.

#### 3- Open the Project in LabVIEW.

#### 4- Navigate to the Block Diagram window.

  - Press **CTRL + E** on your keyboard

  - OR Press on **Window** menu button

  - Select **Show Block Diagram**

#### 5- Configure ThingSpeak Integration.

  - Enter your **ThingSpeak Write API Key** & **Channel ID** in the appropriate fields.

#### 6- Configure Fuzzy Set Integration.

  - Enter the file path to the fuzzy set that you have downloaded from this repository.

#### 7- Run and Monitor the System.

<p align="justify"><i>
    Note: You can access the Fuzzy System Designer by clicking on the <strong>Tools</strong> menu, selecting <strong>Control and Simulation</strong>, and then opening the fuzzy set file by selecting the <strong>File</strong> menu and choosing the <strong>Open</strong> option. You can adjust the fuzzy set as needed from there.
</i></p>


## Contact for Support

For any queries or support related to this project, feel free to contact me at ibrahimsaffarini2001@gmail.com.
