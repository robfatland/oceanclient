# oceanclient


This repository is a simple example of a Python API client connected to data publication and access learning materials.


To run a demonstration first clone this repository to a local machine with Jupyter installed. (The example code
also depends on installed `pandas`, `matplotlib`, `requests` and maybe a couple of other things. A future TTDL item
would be to include `requirements.txt` to properly build an environment.) Here is the `git clone` command:


```
git clone https://github.com/robfatland/oceanclient
```


This will create a folder `oceanclient` containing a Jupyter notebook `sensors.ipynb` and a 
Python code library file `oceanclient.py`. Start up the `jupyter lab` and run the first cell
in the `sensors.ipynb` notebook. The code in this cell is pretty simple, something like


```
import oceanclient as oc
dfT, dfS = oc.Chart('2022-01-05', 9)
```


This should produce a data chart and return two pandas Dataframes in about ten seconds. 
