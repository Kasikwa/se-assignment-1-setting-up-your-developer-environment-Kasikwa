[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278507&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Via Installation Media:

Insert the USB flash drive or DVD with the Windows 11 installation files into your PC.
Restart your PC and boot from the installation media. This might require changing the boot order in your BIOS/UEFI settings.
When prompted, press any key to boot from the USB/DVD.
Select your language, time, and keyboard preferences, then click “Next.”
Click “Install now.”
Enter your product key if prompted, or select “I don’t have a product key” if you are reinstalling.
Accept the license terms and click “Next.”
Choose the type of installation: Upgrade (keep files and settings) or Custom (clean installation).
Follow the on-screen instructions to complete the installation.
et Up Your Account:

Sign in with your Microsoft account or create a new account.
Set up security options like Windows Hello (face recognition, fingerprint, or PIN).
Configure Settings:

Customize your privacy settings.
Adjust system settings to your preference (display, sound, notifications, etc.).
Install Updates:

Go to Settings > Update & Security > Windows Update and check for updates to ensure your system is up-to-date.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

1. Determine Your Requirements:
Programming Languages: Identify the languages you will be working with (e.g., Python, JavaScript, Java, C++).
Features: List the features you need, such as syntax highlighting, code completion, debugging tools, version control integration, and plugins/extensions.
Workflow: Consider your workflow and preferences, including whether you need a lightweight text editor or a full-featured IDE.
2. Research Popular Text Editors and IDEs:
Text Editors:

Visual Studio Code (VS Code): A free, open-source text editor with a wide range of extensions.
Sublime Text: A fast, customizable text editor with a rich plugin ecosystem.
Atom: A hackable text editor developed by GitHub, suitable for various programming languages.
Notepad++: A free, lightweight text editor for Windows with basic features and plugins.
IDEs:

PyCharm: An IDE specifically designed for Python development.
IntelliJ IDEA: A powerful IDE for Java and other JVM languages.
Eclipse: A free, open-source IDE for Java, C++, and other languages.
Visual Studio: A comprehensive IDE for .NET and C++ development, with support for other languages via extensions.
3. Download and Install Your Selected Text Editor or IDE:
Visual Studio Code:

Go to the Visual Studio Code website.
Click on “Download for Windows/macOS/Linux.”
Run the installer and follow the on-screen instructions to complete the installation.
Sublime Text:

Visit the Sublime Text website.
Click on the “Download” button for your operating system.
Run the installer and follow the prompts to install Sublime Text.
Atom:

Navigate to the Atom website.
Click on “Download” for your operating system.
Run the downloaded installer and follow the instructions to install Atom.
Notepad++:

Go to the Notepad++ website.
Click on the “Download” link and select the appropriate installer for your OS.
Run the installer and complete the installation process.
PyCharm:

Visit the JetBrains PyCharm website.
Choose the Community (free) or Professional (paid) edition and download the installer.
Run the installer and follow the instructions to install PyCharm.
IntelliJ IDEA:

Go to the IntelliJ IDEA website.
Select the Community (free) or Ultimate (paid) edition and download the installer.
Run the installer and follow the prompts to install IntelliJ IDEA.
Eclipse:

Visit the Eclipse website.
Download the installer for Eclipse IDE for your preferred language.
Run the installer and follow the instructions to complete the installation.
Visual Studio:

Navigate to the Visual Studio website.
Click on “Download Visual Studio” and choose the edition (Community, Professional, Enterprise).
Run the installer and follow the prompts to install Visual Studio.
4. Configure Your Text Editor or IDE:
Install Extensions/Plugins:

Access the extensions or plugins marketplace from within your text editor or IDE.
Install the necessary extensions for your programming languages and tools (e.g., linters, debuggers, version control).
Set Up Preferences:

Customize the settings and preferences according to your workflow, such as theme, font size, and key bindings.
Configure Version Control:

Set up version control integration (e.g., Git) by installing the relevant plugins and connecting your repository.
Create a Workspace/Project:

Create a new workspace or project and configure the necessary settings, such as project structure, build tools, and dependencies.
5. Verify Installation:
Open a Sample Project:
Open or create a sample project in your text editor or IDE to ensure everything is working correctly.
Run a Test:
Write and run a simple program to verify that the editor or IDE is correctly set up and functioning as expected.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Step 1: Install Git on Your Local Machine
For Windows:

Download the Git installer from the official Git website.
Run the installer and follow the setup instructions. You can use the default settings for most options.
For macOS:

You can install Git using Homebrew. If you don't have Homebrew installed, first install it by running the following command in Terminal:
bash
Copy code
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Once Homebrew is installed, install Git by running:
bash
Copy code
brew install git
For Linux:

Use the package manager for your specific distribution. For example, on Ubuntu, you can install Git by running:
bash
Copy code
sudo apt-get update
sudo apt-get install git
Step 2: Configure Git
After installing Git, you need to configure it with your personal information. Open your terminal (or Git Bash on Windows) and run the following commands, replacing "Your Name" and "your.email@example.com" with your actual name and email address:

bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 3: Create a GitHub Account
Go to GitHub and sign up for a new account if you don't already have one.
Follow the instructions to create your account. You can choose a free plan to get started.
Step 4: Initialize a Git Repository for Your Project
Navigate to your project's directory in your terminal. If you don't have a project yet, create a new directory and navigate to it:

bash
Copy code
mkdir my_project
cd my_project
Initialize a new Git repository in this directory:

bash
Copy code
git init
Step 5: Make Your First Commit
Create a new file in your project directory, for example, a README.md file:

bash
Copy code
echo "# My Project" > README.md
Add the file to the staging area:

bash
Copy code
git add README.md
Commit the file to the repository with a commit message:

bash
Copy code
git commit -m "Initial commit"
Step 6: Push Your Project to GitHub
Go to GitHub and create a new repository. Do not initialize it with a README, .gitignore, or license (you’ve already done that locally).

Follow the instructions provided by GitHub to push an existing repository from the command line. It will look something like this:

bash
Copy code
git remote add origin https://github.com/your_username/your_repository_name.git
git branch -M main
git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Determine Required Programming Languages:

Identify the programming languages needed for your project. For this guide, we'll focus on installing Python.
Visit the Official Python Website:

Go to the official Python website: Python Downloads.
Download Python Installer:

On the Python downloads page, you'll see the latest version of Python available for download.
Click on the link to download the installer for your operating system (Windows, macOS, or Linux).
Run the Python Installer:

Locate the downloaded installer file and double-click to run it.
For Windows:
Check the box that says "Add Python to PATH."
Click "Install Now" or choose "Customize installation" if you need specific configurations.
For macOS:
Open the downloaded .pkg file and follow the on-screen instructions.
For Linux:
Most Linux distributions come with Python pre-installed. You can check the installed version by running python3 --version in the terminal.
If you need a different version, use a package manager to install it. For example, on Ubuntu, you can run:
bash
Copy code
sudo apt update
sudo apt install python3.9
Verify Python Installation:

After installation, verify that Python is correctly installed by opening a terminal or command prompt and typing:
bash
Copy code
python --version
You should see the version number of Python that you installed.
Install Necessary Tools and Packages:

For Python projects, you often need additional packages and tools. Install pip, the Python package installer, if it wasn't installed automatically:
bash
Copy code
python -m ensurepip --upgrade
Use pip to install necessary packages. For example:
bash
Copy code
pip install numpy pandas
Set Up Virtual Environment (Optional but Recommended):

Creating a virtual environment can help manage dependencies and avoid conflicts between projects. To create a virtual environment, run:
bash
Copy code
python -m venv myenv
Activate the virtual environment:
On Windows:
bash
Copy code
myenv\Scripts\activate
On macOS and Linux:
bash
Copy code
source myenv/bin/activate
Install Other Required Runtimes (if any):

If your project requires other programming languages or runtimes, follow similar steps to download and install them. For example, for Java, visit the Oracle Java SE Downloads page.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Windows
Ensure Python is Installed:

Check if Python is already installed by opening Command Prompt and typing:
sh
Copy code
python --version
If Python is not installed, download and install it from the official Python website.
Download get-pip.py:

Download the get-pip.py script from this link.
Run get-pip.py:

Open Command Prompt and navigate to the directory where get-pip.py is saved. Then, run:
sh
Copy code
python get-pip.py
Verifying pip Installation
After installing pip, you can verify the installation by running:

sh
Copy code
pip --version

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Step 1: Download MySQL Installer
Go to the MySQL Downloads page.
Click on the "Download" button for the MySQL Installer.
Choose the appropriate version for your system (32-bit or 64-bit).
You may be prompted to log in or sign up for an Oracle Web account. You can skip this step by clicking "No thanks, just start my download".
Step 2: Run the MySQL Installer
Once the download is complete, locate the installer file (mysql-installer-community-5.7.x.x.msi) in your downloads folder and double-click to run it.
The MySQL Installer window will open. Select the installation type:
Developer Default: Installs the most common features.
Server only: Installs only the MySQL Server.
Client only: Installs only the client applications.
Full: Installs all features.
Custom: Allows you to choose which features to install.
Step 3: Install MySQL
After selecting the installation type, click "Next".
The installer will check for any requirements. If there are missing requirements, you will be prompted to install them.
Click "Execute" to begin the installation. The installer will download and install the selected features.
Step 4: Configure MySQL Server
Once the installation is complete, the MySQL Installer will prompt you to configure the MySQL Server.
Choose the following configurations:
Config Type: Development Machine, Server Machine, or Dedicated Machine.
Connectivity: TCP/IP, Port Number (default is 3306).
Authentication Method: Use the recommended "Use Strong Password Encryption".
Set a root password when prompted. This password will be used to access the MySQL server as the root user.
Optionally, you can create additional user accounts.
Step 5: Start MySQL Server
The installer will complete the configuration and start the MySQL Server.
You will see a confirmation that the MySQL Server has started successfully.
Step 6: Verify the Installation
Open the MySQL Command Line Client from the Start menu.
Enter the root password you set during the configuration.
You should see the MySQL prompt (mysql>), indicating that the MySQL server is running and you can start entering commands.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

1. Install Docker
Docker is a popular containerization tool that allows you to package applications and their dependencies into a container.

For Windows and macOS:

Download Docker Desktop from Docker's official website.
Install Docker Desktop by following the on-screen instructions.
For Linux:

Update your existing list of packages:
bash
Copy code
sudo apt update
Install a few prerequisite packages which let apt use packages over HTTPS:
bash
Copy code
sudo apt install apt-transport-https ca-certificates curl software-properties-common
Add the GPG key for the official Docker repository to your system:
bash
Copy code
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
Add the Docker repository to APT sources:
bash
Copy code
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
Update your existing list of packages:
bash
Copy code
sudo apt update
Install Docker:
bash
Copy code
sudo apt install docker-ce
2. Install Docker Compose (Optional)
Docker Compose is a tool for defining and running multi-container Docker applications.

For all platforms:
Download the Docker Compose binary:
bash
Copy code
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
Apply executable permissions to the binary:
bash
Copy code
sudo chmod +x /usr/local/bin/docker-compose
3. Create a Dockerfile
A Dockerfile is a text document that contains all the commands to assemble an image. Here is a basic example:

Dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container at /usr/src/app
COPY . .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
4. Build and Run the Docker Container
Build the Docker image:
bash
Copy code
docker build -t my-python-app .
Run the Docker container:
bash
Copy code
docker run -p 4000:80 my-python-app
5. Using Virtual Machines
If you prefer using virtual machines (VMs), tools like VirtualBox or Vagrant can help.

VirtualBox
Install VirtualBox:

Download and install VirtualBox from the official website.
Create a New VM:

Open VirtualBox and click "New".
Follow the prompts to create a new virtual machine.
Install an Operating System:

After creating the VM, start it, and follow the prompts to install your preferred operating system.
Vagrant
Install Vagrant:

Download and install Vagrant from the official website.
Initialize a Vagrant Environment:

bash
Copy code
vagrant init ubuntu/bionic64
vagrant up
Access the VM:

bash
Copy code
vagrant ssh

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Visual Studio Code (VSCode)
Prettier - Code formatter

Functionality: Automatic code formatting
Benefits: Maintains consistent code style across your projects
ESLint

Functionality: Linting for JavaScript and TypeScript
Benefits: Helps identify and fix problematic patterns or code that doesn’t adhere to certain style guidelines
Python

Functionality: Rich support for the Python language
Benefits: Includes features like IntelliSense, linting, debugging, and code navigation
GitLens — Git supercharged

Functionality: Enhances Git capabilities
Benefits: Provides insights into code, such as who changed a line of code, when, and why
Docker

Functionality: Adds support for Docker
Benefits: Helps manage Docker containers, images, and compose files
Live Server

Functionality: Launch a local development server with a live reload feature
Benefits: Automatically refreshes the browser on file save
Sublime Text
Package Control

Functionality: Manages packages in Sublime Text
Benefits: Makes it easy to find, install, and manage packages
SublimeLinter

Functionality: Linting framework for Sublime Text
Benefits: Ensures your code is free of syntax and style errors
Emmet

Functionality: Expands abbreviations into HTML/CSS code
Benefits: Speeds up web development
Anaconda

Functionality: Python IDE with Sublime Text
Benefits: Provides code linting, auto-completion, and IDE-like features
GitGutter

Functionality: Shows git diff in the gutter
Benefits: Visual representation of changes in your code
JetBrains IntelliJ IDEA
CheckStyle-IDEA

Functionality: Integrates CheckStyle into IntelliJ IDEA
Benefits: Ensures your Java code adheres to coding standards
SonarLint

Functionality: Continuous code quality inspection
Benefits: Detects and fixes quality issues in your code
Lombok

Functionality: Adds support for Project Lombok
Benefits: Reduces boilerplate code in Java
Rainbow Brackets

Functionality: Adds rainbow brackets
Benefits: Improves readability of nested code blocks
Save Actions

Functionality: Automatically perform actions on save
Benefits: Automates code formatting and organizing imports
Atom
ide-python

Functionality: Python language support
Benefits: Provides features like autocompletion, linting, and code navigation
atom-beautify

Functionality: Code beautifier
Benefits: Supports multiple languages and formats code to be more readable
linter

Functionality: Provides a framework for linting
Benefits: Ensures code adheres to style guidelines and is free of errors
teletype

Functionality: Real-time collaborative editing
Benefits: Enables developers to code together in real-time
file-icons

Functionality: Adds file-specific icons to Atom
Benefits: Makes it easier to visually identify file types

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
