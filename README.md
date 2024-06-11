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
4. Install Git on Windows
   a)Download Git:
   Visit the Git website.
   Click on the "Download for Windows" button to download the installer.

b)Run the Installer:
Locate the downloaded .exe file (typically in your Downloads folder) and double-click it to start the installation process.

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

2. Open Git Bash:
   After installation, open "Git Bash" from the Start menu or by searching for it in the Windows search bar.
   a)Set Up Your Identity:
   Configure your username and email:
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   b)Verify the Configuration:
   To verify your settings, run:
   git config --list

3. Create a GitHub Account
   Sign Up for GitHub:
   Visit the GitHub website.
   Click on "Sign up" and follow the instructions to create a new account.
   Verify your email address to complete the registration process.
4. Initialize a Git Repository and Make Your First Commit
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

Certainly! Below is a detailed step-by-step guide for installing Git, configuring it on your local machine, creating a GitHub account, initializing a Git repository for your project, and making your first commit on Windows.

Step-by-Step Guide: Setting Up Git and GitHub on Windows

1. Install Git on Windows
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

2. Configure Git
   Open Git Bash:
   After installation, open "Git Bash" from the Start menu or by searching for it in the Windows search bar.
   Set Up Your Identity:
   Configure your username and email:
   sh
   Copy code
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   Verify the Configuration:
   To verify your settings, run:
   sh
   Copy code
   git config --list
3. Create a GitHub Account
   Sign Up for GitHub:
   Visit the GitHub website.
   Click on "Sign up" and follow the instructions to create a new account.
   Verify your email address to complete the registration process.
4. Initialize a Git Repository and Make Your First Commit
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
