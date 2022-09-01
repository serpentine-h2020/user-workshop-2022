# Installation 
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
3. [Download this file](https://github.com/serpentine-h2020/serpentine/archive/refs/heads/main.zip) and extract to a folder of your choice (or clone the repository https://github.com/serpentine-h2020/serpentine if you know how to use `git`).
4. Open your terminal/command line/Anaconda prompt, navigate to the downloaded (extracted) folder `notebooks/sep_analysis_tools` that contains the file `requirements.txt`, and run the following (first command is just to verify that you are in the correct conda environment):
    ``` bash
    $ conda activate serpentine
    $ pip install -r requirements.txt
    ```


# Run 
1. Open your terminal/command line/Anaconda prompt.
2. In the terminal, navigate to the downloaded (extracted) folder `notebooks/sep_analysis_tools` that contains some `.ipynb` files.
3. Make sure the corresponding conda environment is activated by running `conda activate serpentine` in the terminal.
4. Run `jupyter notebook`
5. Your standard web-browser should now open the Jupyter interface, where you can double click on the corresponding `.ipynb` files to launch them.

