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
### Registering at Joint Science Operations Center (JSOC)
Note that for running the PFSS functionality of the Solar-MACH tool, a registered user account is needed for obtaining HMI maps through JSOC! For this, please register your email at http://jsoc.stanford.edu/ajax/register_email.html
 
## Hands on sessions (on site)
### Tuesday
- **WP6: Analysis & Visualization tools**
    - All the necessary information can be found at http://propagationtool.cdpp.eu

### Wednesday
- **WP2: Multi-spacecraft SEP event analysis**
    1. [Download this file](httpsgithub.com/serpentine-h2020/serpentine/archive/refs/heads/main.zip) and extract to a folder of your choice (or clone the repository https://github.com/serpentine-h2020/serpentine if you know how to use `git`).
    2. Open your terminal/command line/Anaconda prompt.
    3. In the terminal, navigate to the downloaded (extracted) folder `notebooks`.
    4. Make sure the corresponding conda environment is activated by running `conda activate serpentine` in the terminal.
    5. Run `jupyter notebook`
    6. Your standard web-browser should now open the Jupyter interface, where you can double click on the the corresponding folders and `.ipynb` files to launch them.
