[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15298355&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   THESE ARE REQUIRED PROCESS TO INSTALL THE WINDOW 11

1. Downloading the Installation Media:

Go to the Windows 11 download page: This is the official source for obtaining the Windows 11 installation media. You can find it by searching for "Download Windows 11" on the Microsoft website.

Click on the "Download now" button: This button will typically be located under the heading "Create Windows 11 Installation Media." By clicking it, you'll download the Media Creation Tool, a small program that helps you create a bootable USB drive or DVD, or directly upgrade your current PC.

2. Running the Media Creation Tool:

Run the downloaded tool: Double-click the downloaded file (usually named "MediaCreationToolW11.exe") to launch the Media Creation Tool.

Follow the on-screen instructions: The tool will guide you through a straightforward process. It will typically ask you to:

Accept the license terms: Agree to Microsoft's licensing terms to proceed.
Choose what you want to do: Select the option "Upgrade this PC now" if you want to directly upgrade your current computer to Windows 11. Choose "Create installation media (USB flash drive, DVD, or ISO file)" if you want to create a bootable USB drive or DVD to install Windows 11 on another computer.

3. Upgrading Your PC (Direct Upgrade):

If you selected "Upgrade this PC now" in step 2, the tool will automatically check your system compatibility and download the necessary Windows 11 installation files. This process might take some time depending on your internet speed.

Follow the on-screen instructions: The tool will guide you through the upgrade process, which typically involves several steps like:

Selecting language, edition (like Home or Pro), and other installation options.
Choosing whether to keep your personal files and applications during the upgrade.
Confirming your selections and starting the upgrade process.

4. Upgrading Your PC (Using Bootable Media):

If you selected "Create installation media" in step 2, the tool will ask you to:

Choose which media to use: Select a USB flash drive with at least 8GB of free space or a blank DVD disc.
Choose edition (optional): If you plan to install different Windows 11 editions on multiple computers, you can choose the specific edition(s) here. Otherwise, select "Windows 11 (multi-edition)" for flexibility.
Choose language (optional): Select the language for the installation media.
The tool will then download the necessary files and create a bootable USB drive or DVD.

Booting from the media: Once the bootable media is created, insert it into the target computer and restart it. The computer should boot from the media and launch the Windows 11 setup process.

Follow the on-screen instructions: The setup process will be similar to the direct upgrade path, guiding you through language selection, edition choice, keeping personal files, and initiating the installation.

5. Completing the Installation and Setup:

The installation process, whether direct upgrade or using bootable media, might take some time depending on your system configuration. The computer will restart automatically several times during the process.

Initial setup: Once the installation is complete, you'll need to go through the initial Windows 11 setup process. This typically involves steps like:

Connecting to a Wi-Fi network.
Signing in with your Microsoft account.
Configuring privacy settings.
Choosing additional settings and customizations.
Additional Notes:

System Requirements: Make sure your computer meets the minimum system requirements for Windows 11 before attempting the upgrade. You can check these requirements on the Microsoft website.

Compatibility Check: Consider using the PC Health Check app from Microsoft to check if your current PC is compatible with Windows 11.

Backup: It's always recommended to back up your important data before performing any major system upgrades.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   STEPS TO INSTALL THE VISUAL STUDIO

1. Choose: Select a text editor or IDE that aligns with your programming needs and workflow.

1. Download: Visit the official website of your chosen editor and download the installer for your operating system.

1. Run Installer: Double-click the downloaded installer and follow the on-screen instructions to complete the installation.

1. Launch the Editor: Once installed, launch your editor or IDE.

1. Install an Extension (Using Visual Studio Code as an Example):
   Essential Extensions:
   -ESLint: This extension helps identify and fix potential errors and stylistic issues in your JavaScript code, promoting cleaner and more maintainable code.
   -Prettier: Prettier automatically formats your code according to a consistent style guide, ensuring a uniform and visually appealing codebase across your project.
   -Live Server: This extension allows you to launch a local development server directly within Visual Studio Code. This enables you to preview your HTML, CSS, and JavaScript code changes in a web browser instantly without needing to manually set up a server.
   GitLens: If you're using Git for version control, GitLens provides a rich visual interface to explore your code's history, view authorship, compare branches and commits, and navigate through changes made over time.

1. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

STEPS TO INSTALL THE VERSION CONTROL SYSTEM

1.  Install Git:

Go to https://www.git-scm.com/downloads and download the installer for your operating system (Windows, Mac, Linux).
Run the installer and follow the on-screen instructions. 2. Create a GitHub Account:

Head over to https://github.com/index.html and create a free account. 3. Initialize a Git Repository (on Your Machine):

Open your terminal or command prompt window.
Navigate to your project directory using the cd command (e.g., cd my-project).
Type git init and press Enter to create a Git repository in your project folder. 4. Make Your First Commit:

Edit a file in your project (e.g., a code file).
Now, type git status and press Enter. This shows which files have been changed.
To include a changed file in your commit, type git add <filename> (replace <filename> with the actual file name). Alternatively, use git add . to add all modified files.
Finally, type git commit -m "Your message" and press Enter. Replace "Your message" with a brief description of your changes. 5. Connect to GitHub (Optional):

OTHER EXPLANATION WE CAN USE THE GIT DOCUMENTATION IN ORDER TO START USING IT ( https://www.git-scm.com/docs)

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

STEPS TO INSTALL THE PROGRAMMING

1. Grab Python:

Head to the official Python website: https://www.python.org/downloads/
Download the installer for your operating system (Windows, Mac, or Linux). Look for the big, clear download button! 2. Run the Installer:

Double-click the downloaded file.
Follow the on-screen instructions. It's usually pretty straightforward – just click "Next" a few times.
Important Tip: During installation, look for an option that says something like "Add Python to PATH" or "Make Python available from command line" (exact wording might vary). Make sure to check this box! This makes running Python commands super easy later. 3. Check It's Working (Optional):

Open your terminal or command prompt window (search for "command prompt" or "terminal" on your computer).
Type python --version (or python3 --version on some systems) and press Enter. If you see the installed Python version displayed, you're good to go!

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   STEPS TO INSTALL THE PIPS AFTER INSTALL THE PYTHON
   -Python Installation: When you install Python from the official website (https://www.python.org/downloads/), the package manager pip is automatically bundled and installed with it.
   -Adding Python to PATH: During the installation process, there might be an option to "Add Python to PATH" or make it available from the command line. Checking this option ensures you can easily access pip from your terminal or command prompt.
   Verifying pip Installation (Optional):

   -Open your terminal or command prompt window.
   Type pip --version and press Enter. If pip is installed correctly, you'll see the installed version displayed (e.g., pip 21.x.x).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   STEPS TO INSTALL THE MYSQL

   1. Download the MySQL Installer (Considered Done):

   We'll assume you're using Windows for this example. The download link for the MySQL installer on Windows has already been provided: https://dev.mysql.com/downloads/windows/installer/5.7.html

   Downloaded? Great! Let's move on to the next step.

   2. Run the MySQL Installer:

Locate the downloaded installer file (usually an .msi file). It might be in your "Downloads" folder or wherever your web browser saves downloaded files.

Double-click the downloaded installer to launch the installation process.

Follow the on-screen instructions: The installation wizard will guide you through the process. You might encounter options like choosing a "Typical" or "Custom" installation. Here's a simplified explanation of each:

Typical Installation: This option installs the most common components you'll need for a basic MySQL setup. It's a good choice for most users.
Custom Installation: This option allows you to choose specific components to install. Unless you have a specific reason to customize, the "Typical" installation should suffice.
Important: During installation, you'll be prompted to set a root password for MySQL. The root user is the most powerful user in MySQL and is used for administrative tasks. Choose a strong and secure password! Write it down somewhere safe, as you'll need it later to access your MySQL database.

3. Configure MySQL (Optional):

Once the installation is complete, you can optionally configure some additional settings for MySQL. This might involve setting up security features or configuring network access (if you plan to access the database from other machines).

For now, let's keep it simple. We can explore these configurations later if needed.

4. Verify the Installation (Optional):

You can verify if MySQL is installed and running correctly by opening a command prompt window.

In the command prompt, type mysqladmin version and press Enter. If MySQL is installed and running, you should see the MySQL version information displayed.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   1. ESLint: This is a must-have extension for JavaScript developers. It acts as a code linter, identifying potential errors and stylistic issues in your code as you write. This helps you maintain clean and consistent code.

   2. Prettier: This extension automatically formats your code according to a predefined style guide. This ensures consistency across your project and saves you time from manually formatting your code.

   3. GitLens: If you're using Git for version control, GitLens is a fantastic extension. It provides a visual representation of your code history, making it easier to understand changes and navigate through different versions of your project.
      Intellisense: This built-in VS Code feature provides code completion suggestions as you type. It can suggest functions, variables, keywords, and even entire code snippets, significantly improving your coding speed and accuracy.

   4. Pylint (if working with Python): Similar to ESLint, Pylint focuses on Python code, helping you identify potential errors and stylistic issues specific to the Python language.

   5. Beautify: If you work with various languages beyond JavaScript and Python, Beautify can automatically format your code according to different style guides.

   6. Tabnine: This extension offers more advanced code completion suggestions, going beyond just basic function and variable names. It can even suggest entire lines of code based on the context of your current code.

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

   1. Operating System: Windows 10 Home 64-bit
   2. Text Editor/IDE: Visual Studio Code 1.73.0
   3. Programming Language and Version: Python 3.10.8
   4. Package Manager: pip
   5. Installed Packages: numpy, pandas
   6. Configurations: Added Python to system PATH environment variable.
   7. Troubleshooting Steps: During Python installation, I encountered an error related to missing Microsoft Visual C++ Redistributable packages.
      I downloaded and installed the appropriate version from the Microsoft website, and the Python installation proceeded successfully.

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
