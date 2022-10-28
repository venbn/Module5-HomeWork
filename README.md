
## Dev

I use Jupyter notebook to write the Python code, this code is built in Jupyter notebook on a Mac PC. 
The process must be pretty much same when executing from GitBash on WindowsPC except that you will need Visual Studio Code to install required extensions/moduled.
To ensure, a suitable environment is existing to execute this code, you will need to have python3 and pip3 installed already. 
Python versions older than 3 might not function effeciently. The Python version used to write this code is 3.10.6, any verison of Python3 should work.

## Dependencies

Apart from python3 and pip3, you will need to have jupyter, anaconda and matplotlib installed at the operating system level.
All the dependent librariries required to successfully use pandas and numpy modules must be installed as well as the code is heavily dependent on pandas, alpaca_trade_api, python-dotenv and matplotlib modules.

Following modules must be already installed before running the code and conda environment must be activated as well. To execute the code, Jupyter notebook must be used. 

Below commands are Mac compatible.

pip3 install matplotlib
pip3 install conda
pip3 install anaconda3
python3 -m pip3 install python-dotenv
pip3 install python-dotenv
pip3 install alpaca_trade_api
conda install hvplot

Before running the code, conda environment must be created and activated.

conda create -n cenv python=3.10.6
conda activate cenv

## Pre-requisites

Ensure all the below csv files are existing on the OS from where you are executing the code. You will need to run "Jupyter notebook" from the same directory (Module5-HomeWork) where all the files exist. Below is the list of files which need to exist for the successful execution of the code.

MCForecastTools.py
python_requests.ipynb
__pycache__
mc_30years_sim_plot.png
mc_30year_dist_plot.png
mc_5years_sim_plot.png
mc_5year_dist_plot.png
mc_10years_sim_plot.png
mc_10year_dist_plot.png
financial-planner.ipynb
README.md

Git must be installed. If using Windows GitBash must be installed.

To execute the code from Windows - you will need Visual Studio Code installed as well to look at the code.

The file 'financial-planner.ipynb' is the file to be opened from the 'Jupyter notebook' interface ONLY.

## Execution process

Clone the directory which contains all the .csv files and the .ipynb file to your system using the following commands

git clone https://github.com/venbn/Module5-HomeWork.git

Once the clone completes.. 

Go to the directory "Module5-HomeWork"

cd Module5-HomeWork

Execute 'Jupyter notebook' command

In the Jupyter notebook interface, open the file 'financial-planner.ipynb'

You should be able to see the code
