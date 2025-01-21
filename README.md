# CLI Setup

Many bioinformatics packages run using a command line environment (CLI) as opposed to a graphical user interface (GUI) which we are used to using in our day to day use of computers. A CLI allows your to interact with with your computers operating system (OS) to run programs, manage and manipulate files, etc. The three main flavors of operating systems are Linux, MacOS, and Windows. Depending on which one you are using you will install packages for that particular OS and CPU architecture (ie. x86_64 (Intel) or ARM64 (Apple Silicon) for MacOS). To install packages on your system, you can either download the appropriate binary file, install from source, or use a package manager such as Conda, depending on the recommended or required installation method. The easiest method is to install using the Conda package manager which also allows your to create a space to install specific versions of packages, dependencies, and Python (https://docs.anaconda.com/working-with-conda/environments/). Using Conda environments is essential allows you to avoid dependency issues for packages already installed on your system and also create a reproducible environment for your analysis. 


To get started with creating Conda environments, I suggest downloading [**Miniconda**](https://docs.anaconda.com/miniconda/), rather than Anaconda, as Miniconda is a minimal distribution of Anaconda only including conda, Python, and required packages. Again, depending on your OS your installation command will be slightly different. Please follow the *Installing Miniconda* instructions for your OS in the Anaconda Documentation: https://docs.anaconda.com/miniconda/install/#quick-command-line-install/ .  

Once installed, you will need to exit and restart your terminal. Conda should initialize upon terminal startup and you should be in your base environment. For example:

![Screenshot 2025-01-21 at 11 00 04 AM](https://github.com/user-attachments/assets/39499f4f-aad9-4184-bdbb-95fa2908560d)





