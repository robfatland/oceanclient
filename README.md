# oceanclient


This repository is a simple example of a Python API client connected to data publication and access learning materials.


## Demonstration

Clone this repository to a local machine where you have Jupyter, pandas, matplotlib and requests installed. 


```
git clone https://github.com/robfatland/oceanclient
```


The resulting `oceanclient` folder contains a Jupyter notebook called `sensors.ipynb` and a 
Python file called `oceanclient.py`. Open `sensors.ipynb` in Jupyter lab and run the first cell. 
The code is something like


```
import oceanclient as oc
dfT, dfS = oc.Chart('2022-01-05', 9)
```


You should get a data chart and two returned pandas Dataframes, takes about ten seconds. 
