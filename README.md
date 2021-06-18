https://mybinder.org/v2/gh/akitsuchiyagaito/ohbm-handson-test3/2dc46a3898be030b68d11effb662445d143a9aa4

# Content to reproduce paper titled "Hello World"

## Content

Data and scripts are contained in the respective folders

## Installation

Python is required. It is recommended to install and run the code in a virtual environment.

1. Install miniconda
2. Creat a new environment: 'conda create -n mypythonenv python=3.6'
3. Activee environment: 'conda activate mypythonenv'
4. Follow next steps

Install required packages with 'pip':

```
pip install -r requirements.txt
```

In addition, also install he 'BrainStat' package:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install
```

## Running the analysis

Navigate to the 'code' directory, and then run 'analysis_01.py'
