# Python project template
In order to begin a python project do following steps:

1. Clone the repository:
    ```bash
    git clone git@github.com:FForzano/python_project.git
    ```
    or 
    ```bash
    git clone https://github.com/FForzano/python_project.git
    ```

2. Change project name and origin repository
3. Go into the project directory
    ```bash
   cd python_project
   ````
4. Create the virtual environment, activate it and install required packages
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```
5. If you are using zsh and you have
   [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) installed, the virtual
   environment is activated and deactivated automatically when you go into the
   directory.
6. Start coding