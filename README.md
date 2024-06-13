To prepare for my upcoming software engineering classes, I meticulously set up my coding environment. Here is a detailed account of the steps I followed:

# Operating System Installation
The first step was to ensure my operating system was up-to-date. I opted for Windows 11, given its robust support for development tools and modern features.

1. I visited the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
2. I downloaded the Installation Assistant and ran it.
3. Following the on-screen instructions, I upgraded to Windows 11.
4. After installation, I set up my user account and configured the initial settings to personalize my desktop environment.

# Text Editor Installation
Next, I installed Visual Studio Code, a powerful and versatile text editor suitable for various programming languages.

1. I went to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. I downloaded the Windows installer and ran it.
3. During installation, I accepted the license agreement and chose the installation directory.
4. Once installed, I launched Visual Studio Code and customized the settings to my liking, adjusting themes, font sizes, and layout.

# Version Control System Setup
Version control is crucial for managing code changes and collaboration. I set up Git and created a GitHub account.

1. I downloaded Git from the [Git website](https://git-scm.com/downloads) and installed it.
2. After installation, I opened Git Bash and configured my Git identity:
   ```bash
   git config --global user.name "ChaoKinyua"
   git config --global user.email "ckinyua33@gmail.com"
   ```
3. I then created a GitHub account and a new repository on GitHub.
4. In my local project directory, I initialized a Git repository:
   ```bash
   git init
   git remote add origin https://github.com/yourusername/your-repository.git
   ```
5. I made my first commit and pushed it to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push -u origin master
   ```

# Programming Languages and Runtimes
For my classes, Python was essential, so I installed it along with its package manager, pip.

1. I downloaded Python from [python.org](http://www.python.org) and ran the installer.
2. I ensured that the "Add Python to PATH" option was checked during installation.
3. To verify the installation, I opened Command Prompt and typed:
   ```bash

   python --version
   ```

   This confirmed that Python was installed correctly.

# Package Manager Installation
Pip, the package manager for Python, was included with the Python installation. I verified its installation as follows:

1. I opened Command Prompt and checked the pip version:
   ```bash
   pip --version
   ```
2. This confirmed that pip was installed and ready to manage Python packages.

# Database Configuration
For database management, I chose MySQL. Here's how I set it up:

1. I downloaded the MySQL installer from the [MySQL website](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. I ran the installer and selected the "Developer Default" setup type.
3. Following the setup wizard, I configured the MySQL Server and Workbench.
4. I set a root password during the setup process and completed the installation.
5. Finally, I opened MySQL Workbench and connected to the MySQL server using the root account to ensure everything was functioning correctly.

# Development Environments and Virtualization
To enhance my development workflow, I considered Docker for containerization, ensuring consistent environments across different machines.

1. I downloaded Docker Desktop from the [Docker website](https://www.docker.com/products/docker-desktop/) and installed it.
2. After installation, I verified it by running:
   ```bash
   docker --version
   ```
3. Optionally, I pulled a sample Docker image to confirm that Docker was working correctly:
   ```bash
   docker run hello-world
   ```

# Extensions and Plugins
To further optimize my development environment, I explored and installed several Visual Studio Code extensions.

1. I opened Visual Studio Code and navigated to the Extensions view by clicking the Extensions icon in the Activity Bar.
2. I searched for and installed the following recommended extensions:
   - Python: For Python language support and tools.
   - GitLens: To enhance Git capabilities within VS Code.
   - Prettier - Code formatter: For automatic code formatting.
   - MySQL: For managing MySQL databases directly from VS Code.

# Reflection:
# Challenges:
Git Configuration: Initial configuration of Git and linking it with GitHub was challenging due to authentication issues.
MySQL Installation: Setting up MySQL and configuring it properly took several attempts to ensure the service was running correctly.
MYSQL also at first during the configuration couldn't excute the "starting server" command due to existing antiviruses in my PC.

# Solutions:
Git Authentication: Used SSH keys for secure and smooth authentication with GitHub.
MySQL Troubleshooting: Followed official MySQL documentation and community forums to resolve configuration issues.
I overrided the antivirus to install MYSQL.