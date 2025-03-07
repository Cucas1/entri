This repository contains an assessment app created for the Entri SE position, developed in Python 3.10.11. 
Follow the steps below to clone the repository, set up a Python virtual environment, install the dependencies, and run the app locally. 
Choose the instructions corresponding to your operating system.

**Prerequisites**
Python 3.10.11 (or compatible version)
Git


**Instructions**

**1. Clone the Repository**
Open your terminal (Command Prompt on Windows, Terminal on Linux/MacOS) and run:
git clone https://github.com/Cucas1/entri

Then change to the project directory:
cd entri

**2. Create a Python Virtual Environment**
Run the following command to create a virtual environment named .venv:
python -m venv .venv


**3. Activate the Virtual Environment**
Windows
.venv\Scripts\activate

Linux or MacOS
source .venv/bin/activate


**4. Install the Application Dependencies**
Install the required Python packages using pip:
pip install -r ./entri_flask/requirements.txt

**5. Access the .env file and fill it with your ApplicationID and Secret**
Feel free to use any text editor in your OS like Notepad for Windows or VIM for Linux.

**6. Run the Application**
Start the application by running:
python ./entri_flask/app.py

Open any browser and access http://127.0.0.1:5000

-----------------------------------------------------------------------------------------------------------------------------------------------------

If you just click on "Connect Now!" button, it will the Entri banner and ask for your domain.
The default DNS records are the ones shared in the assessment.

If you already have a domain and different DNS records to add, just fill the form with the domain name and the DNS records in JSON format, then hit "Connect Now!"
