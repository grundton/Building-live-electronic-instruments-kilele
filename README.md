# Building-live-electronic-instruments-kilele
A repository containing the patches for the Building live-electronic instruments workshop at Kilele.

# Requirements
For this project a working version of [Pure Data](https://puredata.info/downloads) is required. I recommend getting the "vanilla" distribution.

The installation instructions require you to have a working version of [conda](https://docs.conda.io/en/latest/) (a virtual environment manager) and [pip](https://packaging.python.org/en/latest/guides/tool-recommendations/) (a python package installer).

To check whether you have these installed, please try 
`conda --version` and `python3 -m pip --version` in your terminal.

# Installation 
Download the zip file or clone the repository

Before installing any dependencies, I recommend using a seperate virtual environment
```
conda create -n cloudhands python=3.9
```
Now activate the new environment
```
conda activate cloudhands
```
To install the required libraries for cloud hands, simply open a terminal at the root directory and execute
```
pip install -r requirements.txt
```

### Using Cam2Osc_grain.py
Open a terminal window at the root directory.

First activate the correct virtual environment, for example ```cloudhands```.
```
conda activate cloudhands
```
Then execute the cam2osc.py script.
```
python python_script/Cam2Osc_grain.py
```
You might need to allow access to your camera.
You can close the application by pressing q inside the active video window or by interrupting the process inside the terminal.

