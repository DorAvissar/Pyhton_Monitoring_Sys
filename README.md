<!-- ABOUT THE PROJECT -->
## About The Project

The System Monitoring tool is a Python-based application that allows users to monitor their system's CPU, computer data, running processes and memory usage in real-time.

### Key features of this project:
* Real-time Monitoring: The script uses the 'psutil' library to fetch real  information. 
* Warning System: The script checks if the CPU usage or Memory usages gets over 80% and issues a warning message.
* Web Interface via Flask: The python script uses the Flask web framework to create a simple web application.


### Built With
The project is built with Python, HTML, JavaScript, and CSS. The following libraries were used:
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [psutil](https://pypi.org/project/psutil/)
* [Chart.js](https://www.chartjs.org/)
* [Flask-Session](https://flask-session.readthedocs.io/en/latest/)

[![Python][Python]][Python-url] [![HTML5][HTML5]][HTML5-url] [![Flask][Flask]][Flask-url] [![JavaScript][JavaScript]][JavaScript-url]


<!-- Getting Started Section -->
## Getting Started
To get started with the system monitoring, follow the steps below:
<!-- Requirements Section -->
### Requirements

- Python 
- Flask
- psutil
- Flask-Session
<!-- Installation Section -->
### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/DorAvissar/Pyhton_Monitoring_Sys.git
   cd Python-System-Monitor
    ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
    ```

### Usage

1. Run the application:
   ```bash
   python app.py
    ```

2. Open your web browser and navigate to http://localhost:5000/ to access the monitoring dashboard. (username: admin ; password: admin)
3. Monitor your system's CPU and memory usage in real-time.

<!-- Docker Section -->
### Docker image
[![Docker][Docker]][Docker-url]
1. Run this command to build a Docker image
```bash
docker build -t <your_image_name> .
```

2. To start the Flask server run this command
```bash
docker run -p 5000:5000 <image-name>
``` 

This will start the Flask server in a docker conatiner on your localhost. \
Navigate to [http://localhost:5000/](http://localhost:5000/) on your browser to access the application. \
(username: admin ; password: admin)

### Screenshots

https://github.com/DorAvissar/Pyhton_Monitoring_Sys/blob/main/static/images/LOGIN.png



https://github.com/DorAvissar/Pyhton_Monitoring_Sys/blob/main/static/images/dashborad.png

