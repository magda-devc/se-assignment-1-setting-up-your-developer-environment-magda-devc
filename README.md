[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278513&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

    - I tried downloading windows 11 using the provided link which directed me to install Windows Health Checkup setup to find out if my device is compatible but I found out it was not.
    ![alt text](<PC Health Check 16-Jun-24 4_29_09 PM.png>)
    So I was not able to download windows 11.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   - Visual studio was smoothly downloaded and installed in my PC without any issues. After downloading I tried opening a folder and created a simple html file to see if all the configurations were setup properly, and they were.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   - I downloaded git from the git download website. Then followed the setup process keenly, the setup had several steps such as choosing a default editor, changing of  a path environment, SSH which I wasn't familiar with so I had to go and serach for a set up process and foung a website which helped me navigate until the end of the setup. https://phoenixnap.com/kb/how-to-install-git-windows this is the website I used.
   - I had previously created a github account so I only had to initialize a github repository then went to git to commit a folder into my github. I kennly followed the steps written by github when initializing a repository. I received an error message "Please tell me who you are" then used the following commands to correct my error ( git config --global user.name , git config --global user.email),  and finally I pushed the folder to github.

4. Install Necessary Programming Languages and Runtimes:
  Install Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  
  - The setuo in python was successful. I downloaded it from the website and instaled it in my PC. Then added a path in the environmental variables. I opened powershell to check if it was install succeccully, and it was.
  ![alt text](<Administrator_ Windows PowerShell 19-Jun-24 5_50_11 PM.png>)
  - A python extension in vscode is necessary for you to run python code in your machine. So I went to the exensions in the visual studio code and downoaded the python extension that was verified. It was installed successfully.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   - Installing pip. I first checked if pip was previously installed in my computer by using the pip --version command in my windows powershell which returned an eroor message that 'pip was not recognized as an internal or external command' which confirmed that pip was not installed in my computer. I followed the steps of the class recording and some notes I had taken during the class session. Using the command python get-pip.py I successfully installed pip and confirmed if it was actually installed by using the --version command. Then headed to the environment variables to add a path for the pip and later tried to upgrade but it said it was the latest version.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   - Installing mysql was the hardest for me. The setup process was so long and had to pay attention to so many details. I downloaded my sql together with the istructors during the class.
   - I downloaded my sql installer from the website and installed it. I tealised I had installed it wrongly so I headed to the control panel to uninstall it and install it back again. But on re-installing I got an error message.
   ![alt text](<MySQL Installer 16-Jun-24 5_13_13 PM.png>)
   - I googled the error and watched youtube videos until finally I solved the issue and it successfully opened in my machine.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   -  I had previously seen the instructors visual studio code and it was more colourful and pleasing. I explored the extensions such as  sql database, sqlite viewer, python debugger, intellicode, flutter, dart, vscode-icons and learn-linting by Microsoft.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

   -  Code Editor: I chose Visual Studio Code.
   - Version Control System. Used successfully installed git to manage and track changes to my code.
   - Local server. I previously had wamp installed in my computer and did not need to install any other local server.
   - Front-End Framework. I installed the bootstrap to use in styling my websites, and tried to use it in a html file. Also had django which is a python framework used to create websites using python.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).

Link https://github.com/magda-devc/gitIgnoreTest.git

- A reflection on the challenges faced during setup and strategies employed to overcome them.

Challenges Faced:
- Configuring Git: Understanding Git commands and initial setup took some time.
- Python Installation: Ensuring Python was added to the PATH correctly required careful attention.
- MySQL Installation: Configuring the MySQL server and setting up the root password was challenging without prior database experience.

Solutions:
- Git: Followed detailed tutorials and referred to Git documentation.
- Python: Added Python to the PATH environment variable.
- MySQL: Used MySQL official documentation and community forums for troubleshooting.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.


#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
