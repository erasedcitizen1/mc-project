# Monte Carlo Simulation of the 2021-2022 English Premier League (and beyond)
## Purpose
Simulates the results of the English Premier League for a number of seasons forward (specified by the user).
## Installation (Pre-requisites)
This project uses the Anaconda distribution of Python so the user must first install Anaconda prior to running any scripts.
Visit https://docs.anaconda.com/anaconda/install/index.html for instructions to install the latest version of Anaconda. Anaconda is supported on 
Windows, macOS and Linux with separate installation instructions available for each of these operating systems. The user should download the latest version of Python 3
corresponding to their operating system.

The script for this project was written using the Jupyter Notebook editor on Anaconda. This is a specific IDE (Integrated Development Editor) that comes with the Anaconda distribution. Note that files written in
Jupyter Notebook have a unique format compared with other .py files (Jupyter files have the extension .ipynb) so they cannot be opened with any other Python editor (e.g PyCharm). Therefore, the user **must** use Jupyter Notebook to run the scripts. Once Anaconda
has been installed the user can load the Jupyter Notebook editor by following instructions at https://jupyter.readthedocs.io/en/latest/running.html

Once Jupyter Notebook is up and running, the user is ready to run the program.

## Running the program
For those not familiar with Jupyter Notebook, please visit https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html.

The entire program is executed in the file labelled 'main.ipynb' so the user should open this file with Jupyter Notebook. One of the nice advantages of Jupyter is that its format allows for easy reproducibility of results
with pieces of code executed in separate cells. Jupyter also supports Markdown, a lightweight language to format text. We use both of these features so that the user can step through the code sequentially
and reproduce any results with relative ease.

There is an additional python script needed for the Monte Carlo simulation step. Given the computational burden for this particular task, we apply parallel computing to speed up
the simulations by splitting the task across multiple cores. However, due to a quirk with using Jupyter Notebook, we must import.

Instructions on how the user can configure the settings for the simulation are detailed in 'main.ipynb' (i.e the main script file) while all relevant documentation is also included
in this file.




