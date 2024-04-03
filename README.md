# Scool spike sorting Aussois 2024

Material for spike sorting session in *neurotech spring school* in Aussois2024.



Here in this repository, you will find some notebooks for demo and handsons.

## 

**Morning session**

* 10:30 - 11:30 What you always wanted to know about Spike sorting (but were afraid to ask)

**Diner session**
 
* 20:00 - 20:30 Overview on the wonderful world of SpikeInterface
* 20:30 -  21:15 Deep interactive demo : with simulated and then real data
* 21.15 - 22:00 Notebook and handson
  * preprocessing
  * motion correction
  * postprocessing


## Installation

**Procedure for Windows/Apple:**

If you already have anaconda/vscode installed jump to 4.

  * Step 1 : If your username/login has spaces and/or weird symbols, **YOU MUST** create
    a new user with a simpler name (no spaces, no symbols). Login with such a user name.
  * Step 2: download anaconda from here https://www.anaconda.com/download
    For Windows users (even though it is sometimes not recommended) we advise to check “Anaconda to your path”.
    It will help with vscode compatibility.
  * Step 3 : If you do not have a code editor we advise installing vscode.
    https://code.visualstudio.com/download.
    After installation, you can add the plugins “python” and “jupyter”
  * Step 4 : Go to this page https://github.com/samuelgarcia/school_spike_sorting_Aussois_2024
  * Step 5 : click on **"code"** (green button) and download the zip. Etxract the zip.
  * Step 6 : Open the anaconda prompt (a terminal).
  * Step 7 : go at the correct place where the zip is etracted.
    This command is a tip not the good one :`cd C:/users/myusername/where_the_zip_is`
  * Step 8 : create the python environement `conda env create -f spikeinterface_environment.yml`.
    This can take a while and download many paquets. This need bandwith.
    **Do not expect to do this during the tutorial**


**Procedure for linux ubuntu/debian style:**

anaconda on linux is sometimes messing a lot for new users.
Standard installation using system and pip are faster and easier to manage.
  
  * `sudo apt install python3.11 python3.11-venv python3.11-dev`
  * `mkdir ~/.virtualenvs`
  * `python3.11 -m venv ~/.virtualenvs/si_env`
  * `source ~/.virtualenvs/si_env/bin/activate`
  * `pip install --upgrade pip`
  * `pip install spikeinterface[full]`
  * `pip install PySide6`
  * `pip install jupyterlab`
  * `pip install https://github.com/NeuralEnsemble/python-neo/archive/master.zip`
  * `pip install https://github.com/SpikeInterface/spikeinterface/archive/main.zip`
  * `pip install https://github.com/SpikeInterface/spikeinterface-gui/archive/main.zip`
  * `pip install https://github.com/magland/sortingview/archive/main.zip`
  * `pip install https://github.com/NeuralEnsemble/ephyviewer/archive/master.zip`
  


## Dataset

Please download datasets here https://drive.google.com/drive/folders/1GtBCuSSlwypjXQ8aw5P6F4uOFP7fjIpE?usp=sharing





