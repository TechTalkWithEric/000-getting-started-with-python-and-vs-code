# A Step-by-Step Guide to Creating a Python Virtual Environment


To create a clean and isolated environment for your Python projects you can use virtual environments. Virtual environments allow you to manage project dependencies and isolate them from other Python installations on your system. 

If you are using Python 3, it is generally recommended to use the built-in `venv` module. However, if you need more advanced features or want to create virtual environments for Python 2, you can opt for `virtualenv`.

To set up a virtual (venv) environment, follow these steps:


1. Setup your virtual environment:

    Open the command prompt (or terminal) and run the following command:

    ```sh
    python3 -m venv .venv
    ```

    The first command `python3` simply instructs the command line to launch/execute `python3`, the `-m` indicates the module we want to execute which is `venv`.  The last parameter is the location of the virtual environment.  It will create a director with the name of whatever you provide.

    I keep it simple and name it `.venv`.  You can name this whatever you want.  I opt of the `.` to make it a `hidden` directory (standard for mac/linux).  This way git won't attempt to pick it up and I don't have to add it to the `gitignore` file.



    This command installs the virtualenv package, which is used to create and manage virtual environments.


2. Activating the virtual environment:

    To start using the virtual environment, you need to activate it. Depending on your operating system, the activation command will vary:

    replace `<virtual_environment_director>` with whatever you choose as your dirctory. If you followed the examples above it will be `.venv`

    - On Windows:
    ```
    <virtual_environment_director>\Scripts\activate
    ```

    - On macOS and Linux:
    ```
    source <virtual_environment_director>/bin/activate
    ```

    After executing the appropriate activation command, you should see the name of your virtual environment (e.g., .`venv`) in the command prompt, indicating that you are working inside the virtual environment.

3. Installing Packages:

    
    [see install packages with pip](./03-install-pip.md)

    

4. Running Python Scripts:

    To execute Python scripts within your virtual environment, simply run the "python" command followed by the script's filename:

    ```sh
    python script.py
    ```

    Replace "script.py" with the name of your Python script.

    We'll cover running and debugging your python scripts in another lesson.

## Congratulations! 
You have successfully installed Python and created a Python environment using `venv`. With a properly set up environment, you can now develop Python projects with ease, manage dependencies efficiently, and experiment with various libraries and frameworks. 

## **IMPORTANT** 
Remember to activate your virtual environment each time you start a new project to maintain a clean and isolated development environment. 

