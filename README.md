# AI-Enhanced Sensor Data Quality Dashboard

This project is an AI-Enhanced Sensor Data Quality Dashboard designed to monitor and analyze sensor data in real-time. The dashboard visually represents sensor data quality, displays live readings, and offers quick actions such as filtering noise, detecting anomalies, and exporting reports.

## Features
- *Overall Data Quality Score:* Displays the percentage of sensors with normal readings.
- *Data Quality Analysis:* Doughnut chart representing the proportion of high-quality, noisy, and anomalous sensor readings.
- *Live Sensor Data:* Real-time sensor readings displayed in a tabular format.
- *Quick Actions:* Buttons to filter noise, detect anomalies, and export sensor data reports.

## Technologies Used
- *Frontend:* HTML, Bootstrap 5
- *Charts:* Chart.js
- *Scripting:* JavaScript

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/your-username/ai-sensor-dashboard.git
   
2. Navigate to the project directory:
   bash
   cd ai-sensor-dashboard
   
3. Open index.html in your browser.

## How It Works
- The dashboard simulates data from 10 sensors, generating random readings every 5 seconds.
- Sensor readings are categorized as:
  - *Normal:* Reading ≥ 60
  - *Noisy:* 30 ≤ Reading < 60
  - *Anomalous:* Reading < 30
- The overall data quality score is calculated as the percentage of sensors with normal readings.
- The doughnut chart updates dynamically with each data refresh.

## Quick Actions
- *Filter Noise:* Simulates the application of noise filtering techniques.
- *Detect Anomalies:* Initiates anomaly detection.
- *Export Report:* Exports sensor data as a CSV file (sensor_report.csv).

## File Structure

├── index.html
└── README.md


## Usage
1. Launch the dashboard by opening index.html.
2. Monitor the real-time sensor data, overall quality score, and analysis chart.
3. Use the quick action buttons as needed.

## Contributing
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
Developed with ❤ using HTML, Bootstrap, and JavaScript.