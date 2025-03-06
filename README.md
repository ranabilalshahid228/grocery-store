# Grocery-store Management
Overview
This repository contains a three-tier application developed using Python and several associated libraries. It features a dynamic user interface built with Flask, HTML, CSS, and JavaScript, and a robust backend powered by MySQL. Although the current dataset is a demo, the architecture is designed to scale seamlessly with larger datasets.

**Architecture**
The project follows a classic three-tier architecture:

**Presentation Layer:**

**Technologies:** Flask, HTML, CSS, JavaScript
Role: Handles HTTP requests, renders dynamic content, and provides an intuitive, responsive user interface.
**Application Layer:**

**Technologies:** Python and various libraries
Role: Contains the core business logic and processing. Developed using PyCharm to ensure high code quality and maintainability.
**Data Layer:**

**Technology:** MySQL
Role: Manages data storage and retrieval. The design ensures that the demo dataset can be replaced with a larger dataset without altering the overall system architecture.
Technologies Used
Python: The primary programming language for application logic.
Flask: A micro web framework used to develop the user interface and manage web requests.
HTML, CSS, JavaScript: Standard web technologies employed to create a responsive and engaging front-end.
MySQL: A reliable database management system for handling persistent data.
PyCharm: The integrated development environment (IDE) used to develop and maintain the codebase.
Features
**Modular Three-Tier Architecture:**
Separates the presentation, application, and data layers to improve maintainability and scalability.

**Responsive User Interface:**
currently its simple and responsive user interface but can be easily modified according to user requirement to deliver a seamless user experience.

**Scalable Data Management:**
Although currently demonstrated with a sample dataset, the system is fully capable of handling large-scale datasets.

**Robust Business Logic:**
Built with Python and industry-standard libraries, ensuring efficient processing and easy future enhancements.

Getting Started
Prerequisites
Python 3.12
MySQL Server
MySQL Workbench 8.0 CE
**Required Python Libraries:** Listed in the requirements.txt file.
Installation
**Clone the Repository:**
_git clone https://github.com/yourusername/your-repo.git_
_cd your-repo_
Install Dependencies:

_pip install -r requirements.txt_
Set Up the MySQL Database:
Configure your MySQL database and update the connection settings in the configuration file.
Run the Flask Application:
_python app.py_
Access the Application:
Open your browser and navigate to _http://localhost:5000._
**Contributing**
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgments**
Flask
MySQL
PyCharm
