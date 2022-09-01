# SERPENTINE User Workshop 2022 Materials

## Python Requirements Installation 
This guide helps you to install the required software to run the Python/Jupyter Notebook examples of the workshop.
1. Make sure you have a recent version of [Anaconda](https://www.anaconda.com/products/distribution) installed. 
2. Open your terminal/command line/Anaconda prompt and run the following:
    ``` bash
    $ conda create --name serpentine python=3.9
    $ conda activate serpentine
    ```
3. Check that you have `git` installed. To test this, try to run the `git` command in your open terminal from step 2. If the command is not found, run the following to install it:
    ``` bash
    $ conda install git
    ```
    (Especially on Windows git needs to be installed once, but also for MacOS users this might be the case. UNIX (e.g. Ubuntu) sysemts should have a git version pre-installed.) 
3. [Download this file](https://raw.githubusercontent.com/serpentine-h2020/user-workshop-2022/master/requirements.txt) that contains a list of the required Python packages to a folder of your choice.
4. In your terminal/command line/Anaconda prompt, navigate to the folder with the downloaded file `requirements.txt`, and run the following (first command is just to verify that you are in the correct conda environment):
    ``` bash
    $ conda activate serpentine
    $ pip install -r requirements.txt
    ```
