[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256985&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

#Deliverables:

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

1. Select Your Operating System (OS):
   MICROSOFT 10
   Microsoft was already installed on my laptop. I didn't encounter any challenges with it.

2. Install a Text Editor or Integrated Development Environment (IDE):
   VISUAL STUDIO CODE
   I. Download VS Code:
   Visit the Visual Studio Code website. https://code.visualstudio.com/
   Click on the "Download for Windows" button to download the installer.
   II. Run the Installer:
   Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.
   III. Install VS Code:
   The Setup Wizard will open. Click "Next" to proceed.
   Read and accept the license agreement, then click "Next".
   Choose the destination folder for the installation or leave it as the default, then click "Next".
   Select additional tasks: You can choose to create a desktop icon and add VS Code to your PATH (recommended). Check the boxes for the options you want and click "Next".
   Click "Install" to begin the installation.
   Once the installation is complete, click "Finish" to launch VS Code.
   IV. Launch VS Code:
   launch VS Code from the Start menu, desktop icon, or by searching for "Visual Studio Code" in the Windows search bar.

3. Set Up Version Control System:
   GIT AND GITHUB
   1. Install Git on Windows
      a)Download Git:
      Visit the Git website.
      Click on the "Download for Windows" button to download the installer.

b)Run the Installer:
Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.\*\*

c)Follow the Setup Wizard:
Click "Next" to proceed.
Choose the destination folder for the installation or leave it as the default, then click "Next".
Select components: It’s recommended to leave the default settings. Click "Next".
Select the editor you want Git to use. By default, it is Vim, but you can choose another text editor like Notepad++ or Visual Studio Code. Click "Next".
Adjust the PATH environment: Choose "Git from the command line and also from 3rd-party software". Click "Next".
Choose HTTPS transport backend: Choose "Use the OpenSSL library". Click "Next".
Configure line ending conversions: Choose "Checkout Windows-style, commit Unix-style line endings". Click "Next".
Select the terminal emulator: Choose "Use MinTTY (the default terminal of MSYS2)". Click "Next".
Choose the default behavior of Git pull: Choose "Default (fast-forward or merge)". Click "Next".
Enable Git Credential Manager: Check "Enable Git Credential Manager Core". Click "Next".
Configure extra options: It’s recommended to leave the default settings. Click "Install".

d)Once the installation is complete, click "Finish" to exit the Setup Wizard.

2.  Open Git Bash:
    After installation, open "Git Bash" from the Start menu or by searching for it in the Windows search bar.
    a)Set Up Your Identity:
    Configure your username and email:
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    b)Verify the Configuration:
    To verify your settings, run:
    git config --list

3.  Create a GitHub Account
    Sign Up for GitHub:
    Visit the GitHub website.
    Click on "Sign up" and follow the instructions to create a new account.
    Verify your email address to complete the registration process.
4.  Initialize a Git Repository and Make Your First Commit
    Create a New Project Folder:
    Open File Explorer and create a new folder for your project. For example, create a folder named MyProject on your Desktop.
    Initialize Git Repository:
    Open Git Bash and navigate to your project folder:
    cd ~/Desktop/MyProject
    Initialize a new Git repository:
    git init
    Create a README File:
    Create a README file in your project folder:
    echo "# MyProject" > README.md

5.  Install Git on Windows
    Download Git:
    Visit the Git website.
    Click on the "Download for Windows" button to download the installer.
    Run the Installer:
    Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.

Follow the Setup Wizard:
Click "Next" to proceed.
Choose the destination folder for the installation or leave it as the default, then click "Next".
Select components: It’s recommended to leave the default settings. Click "Next".
Select the editor you want Git to use. By default, it is Vim, but you can choose another text editor like Notepad++ or Visual Studio Code. Click "Next".
Adjust the PATH environment: Choose "Git from the command line and also from 3rd-party software". Click "Next".
Choose HTTPS transport backend: Choose "Use the OpenSSL library". Click "Next".
Configure line ending conversions: Choose "Checkout Windows-style, commit Unix-style line endings". Click "Next".
Select the terminal emulator: Choose "Use MinTTY (the default terminal of MSYS2)". Click "Next".
Choose the default behavior of Git pull: Choose "Default (fast-forward or merge)". Click "Next".
Enable Git Credential Manager: Check "Enable Git Credential Manager Core". Click "Next".
Configure extra options: It’s recommended to leave the default settings. Click "Install".
Once the installation is complete, click "Finish" to exit the Setup Wizard.

2.  Configure Git
    Open Git Bash:
    After installation, open "Git Bash" from the Start menu or by searching for it in the Windows search bar.
    Set Up Your Identity:
    Configure your username and email:
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    Verify the Configuration:
    To verify your settings, run:
    git config --list
3.  Create a GitHub Account
    Sign Up for GitHub:
    Visit the GitHub website.
    Click on "Sign up" and follow the instructions to create a new account.
    Verify your email address to complete the registration process.
4.  Initialize a Git Repository and Make Your First Commit
    Create a New Project Folder:
    Open File Explorer and create a new folder for your project. For example, create a folder named MyProject on your Desktop.
    Initialize Git Repository:
    Open Git Bash and navigate to your project folder:
    cd ~/Desktop/MyProject
    Initialize a new Git repository:
    git init
    Create a README File:
    Create a README file in your project folder:
    echo "# MyProject" > README.md
    Add and Commit Your Changes:
    Add the README file to the staging area:
    Copy code
    git add README.md
    Commit your changes with a message:
    git commit -m "Initial commit"
5.  Push Your Repository to GitHub
    Create a New Repository on GitHub:
    Log in to your GitHub account.
    Click on the "+" icon in the top right corner and select "New repository".
    Fill in the repository name (e.g., MyProject), add a description, and choose whether it
    should be public or private.
    Link Your Local Repository to GitHub:
    In the newly created repository on GitHub, you will see a URL (HTTPS or SSH) to push your existing repository from the command line.
    In Git Bash, add this URL as a remote repository:
    git remote add origin https://github.com/yourusername/MyProject.git
    Push your local repository to GitHub:
    git push -u origin master

6.  Install Necessary Programming Languages and Runtimes:
    Instal Python
    Install Package Managers:
    If applicable, install package managers like pip (Python).

    1.  Download Python Installer
        Visit the Python Website:
        Go to the Python official website.
        Download Python:
        Click on the "Downloads" tab.
        Select "Download for Windows" and click on the latest version of Python available (e.g., Python 3.10.0).
    2.  Install Python
        Run the Installer:
        Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.
        Choose Installation Options:
        Check the box that says "Add Python to PATH".
        Click on "Customize installation".
        Customize Installation:
        Ensure that the following options are checked:
        Documentation
        pip (Python package installer)
        IDLE (Python Integrated Development and Learning Environment)
        Python test suite
        py launcher
        Click "Next".
        Advanced Options:
        Check the box for "Install for all users".
        Leave the default installation directory (e.g., C:\Program Files\Python310).
        Click "Install".
        Complete the Installation:
        Wait for the installation to complete.
        Click "Close" once the installation is finished.
    3.  Verify Python Installation
        Open Command Prompt:
        Press Win + R, type cmd, and press Enter.
        Check Python Version:
        In the Command Prompt, type
        python --version
        You should see the version of Python you installed (e.g., Python 3.10.0).
        Check pip Version:
        In the Command Prompt, type
        pip --version
        You should see the version of pip that was installed with Python.
    4.  Install IDE for Python Development
        Download and Install an IDE:
        Visual Studio Code (VS Code):
        Visit the VS Code website.
        Download the installer and follow the installation instructions.
        PyCharm:
        Visit the PyCharm website.
        Download the Community edition and follow the installation instructions.
        Configure IDE for Python Development:
        For VS Code:
        Open VS Code.
        Install the Python extension from the Extensions view (Ctrl + Shift + X).
        Open the Command Palette (Ctrl + Shift + P) and select Python: Select Interpreter.
        Choose the Python interpreter you installed.
        For PyCharm:
        Open PyCharm.
        Create a new project and set the Python interpreter to the one you installed.
        PyCharm will automatically detect the Python interpreter and configure it.
    5.  Writing and Running Python Code
        Create a Python File:
        Open your IDE.
        Create a new file with the .py extension (e.g., hello.py).
        Write Python Code:
        Open the hello.py file and write the following code:
        print("Hello, World!")
        Run the Python Code:
        In your IDE, run the hello.py file.
        Alternatively, in the Command Prompt, navigate to the directory containing hello.py and type:
        python hello.py
        You should see the output:
        Hello, World!

7.  Configure a Database (MySQL):
    Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

    1.  Download MySQL Installer
        Visit the MySQL Website:
        Go to the MySQL Community Downloads page.
        Download MySQL Installer:
        Click on "MySQL Installer for Windows".
        Choose either the web installer (smaller initial download) or the full installer (includes all MySQL products).
        Click on the "Download" button.
        You may be prompted to login or sign up for an Oracle web account. If you prefer not to, you can click on "No thanks, just start my download" to proceed.
    2.  Install MySQL
        Run the Installer:
        Locate the downloaded .msi file (typically in your Downloads folder) and double-click it to start the installation process.
        Setup Type:
        Choose the setup type. For most users, the "Developer Default" setup is recommended as it includes MySQL Server, MySQL Shell, MySQL Workbench, and more. Click "Next".
        Check Requirements:
        The installer will check for any requirements. If any requirements are missing, follow the prompts to install them. Click "Next".
        Installation:
        Click "Execute" to download and install the selected products. This may take several minutes.
        Product Configuration:
        Once the installation is complete, click "Next" to proceed to configuration.
        Click "Next" to start the configuration process.
    3.  Configure MySQL Server
        High Availability:
        Choose "Standalone MySQL Server / Classic MySQL Replication" and click "Next".
        Type and Networking:
        Select "Development Computer" or "Server Computer" based on your needs.
        Ensure the default port (3306) is selected.
        Optionally, check "Open Windows Firewall port for network access" if you plan to access MySQL from other devices. Click "Next".
        Authentication Method:
        Choose "Use Strong Password Encryption (RECOMMENDED)" and click "Next".
        Accounts and Roles:
        Set a root password and make sure to remember it.
        Optionally, you can add additional MySQL user accounts by clicking "Add User". Click "Next".
        Windows Service:
        Configure MySQL Server as a Windows service.
        Ensure "Start the MySQL Server at System Startup" is checked.
        Optionally, set the Windows Service Name. Click "Next".
        Apply Configuration:
        Click "Execute" to apply the configuration settings. Wait for the process to complete.
        Once completed, click "Finish".
    4.  Install MySQL Workbench (Optional)
        MySQL Workbench Installation:
        If you selected the "Developer Default" setup type, MySQL Workbench will already be installed.
        If not, you can download and install it separately from the MySQL Workbench page.
    5.  Verify MySQL Installation
        Start MySQL Workbench:
        Open MySQL Workbench from the Start menu or by searching for it in the Windows search bar.
        Connect to MySQL Server:
        In MySQL Workbench, click on the "Local instance MySQL" (or a connection name you defined) under "MySQL Connections".
        Enter the root password you set during the configuration and click "OK".
        Create a Database:
        In MySQL Workbench, go to the "Navigator" panel.
        Right-click on "Schemas" and select "Create Schema".
        Enter a name for your database and click "Apply".
    6.  Using MySQL from the Command Line
        Open Command Prompt:
        Press Win + R, type cmd, and press Enter.
        Navigate to MySQL Bin Directory:
        Change the directory to the MySQL bin folder:
        cd C:\Program Files\MySQL\MySQL Server 8.0\bin
        Log into MySQL:
        Use the mysql command to log into the MySQL server:
        mysql -u root -p
        Enter the root password when prompted.
        Create a Database:
        In the MySQL shell, create a new database:
        CREATE DATABASE mydatabase;
        Verify the creation by listing all databases:
        SHOW DATABASES;

8.  Set Up Development Environments and Virtualization (Optional):
    Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
    1.  Install Docker
        Download Docker Desktop:
        Visit the Docker Website:
        Go to the Docker Desktop for Windows page.
        Download Docker Desktop:
        Click on the "Download for Windows" button.
        Install Docker Desktop:
        Run the Installer:
        Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.
        Follow the Setup Wizard:
        Follow the prompts to complete the installation. The default settings are generally sufficient.
        You may be prompted to enable WSL 2 (Windows Subsystem for Linux) integration, which is recommended.
        Restart Your Computer:
        After installation, restart your computer if prompted.
        Verify Docker Installation:
        Open Docker Desktop:
        After restarting, open Docker Desktop from the Start menu or by searching for it in the Windows search bar.
        Check Docker Version:
        Open Command Prompt and type:
        docker --version
        You should see the version of Docker installed (e.g., Docker version 20.10.7).
    2.  Using Docker
        Pull a Docker Image:
        Open Command Prompt:
        Open Command Prompt.
        Pull a Sample Docker Image:
        To pull a sample image, such as hello-world, run:
        docker pull hello-world
        Run a Docker Container:
        To run the pulled Docker image, type:
        docker run hello-world
        You should see a message indicating that Docker is working correctly.
        Create a Dockerfile:
        Create a Project Folder:
        Create a new folder for your project. For example, create a folder named MyDockerProject on your Desktop.
        Navigate to Your Project Folder:
        In Command Prompt, navigate to your project folder:
        cd path\to\MyDockerProject
        Create a Dockerfile:
        Create a file named Dockerfile (no extension) and open it in a text editor. Add the following content:
        dockerfile

# Use an official Python runtime as a parent image

FROM python:3.10-slim

# Set the working directory in the container

WORKDIR /app

# Copy the current directory contents into the container at /app

ADD . /app

# Install any needed packages specified in requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container

EXPOSE 80

# Define environment variable

ENV NAME World

# Run app.py when the container launches

CMD ["python", "app.py"]

Build and Run Your Docker Image:
Create a requirements.txt File:
In your project folder, create a file named requirements.txt and add any Python dependencies you need, e.g.:
Flask
Create an app.py File:
In your project folder, create a file named app.py and add a simple Python application, e.g.:
python
from flask import Flask
app = Flask(**name**)
@app.route('/')
def hello():
return "Hello, World!"
if **name** == "**main**":
app.run(host='0.0.0.0')

Build the Docker Image:
In Command Prompt, navigate to your project folder and run:
docker build -t mydockerapp .
Run the Docker Container:
Run the Docker container with:
docker run -p 4000:80 mydockerapp
Open your web browser and go to http://localhost:4000. You should see "Hello, World!". 3. Set Up Virtual Machines (Using VirtualBox)
Download VirtualBox:
Visit the VirtualBox Website:
Go to the VirtualBox download page.
Download VirtualBox:
Click on "Windows hosts" to download the installer for Windows.
Install VirtualBox:
Run the Installer:
Locate the downloaded .exe file and double-click it to start the installation process.
Follow the Setup Wizard:
Follow the prompts to complete the installation. The default settings are generally sufficient.
Restart Your Computer:
After installation, restart your computer if prompted.
Download an ISO Image:
Download an ISO Image:
For example, you can download the Ubuntu ISO image from the Ubuntu website.
Create a New Virtual Machine:
Open VirtualBox:
Open VirtualBox from the Start menu or by searching for it in the Windows search bar.
Create a New Virtual Machine:
Click on "New" to create a new virtual machine.
Follow the prompts to set up the virtual machine:
Name and operating system: Enter a name (e.g., Ubuntu), type (Linux), and version (Ubuntu 64-bit).
Memory size: Allocate memory (e.g., 2048 MB).
Hard disk: Create a virtual hard disk now and follow the prompts to complete the setup.
Install the Operating System:
Select your newly created virtual machine and click "Start".
Choose the downloaded ISO image when prompted.
Follow the installation process for the operating system (e.g., Ubuntu).

7. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   1. Install Extensions/Plugins
      For Visual Studio Code (VS Code)
      Install Extensions:
      Click on the extension you want to install.
      Click on the "Install" button.
      Configure Extensions:
      Some extensions may require additional configuration. Follow the instructions provided by the extension.
