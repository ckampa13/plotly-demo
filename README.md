# plotly-demo
Plotly demo for IDEAS Weekly Meeting (Tuesday 01-14-2020). Includes toy data of magnetic fields in a helical solenoid.

## Installing / Running
The easiest way to run this demo is to create an Anaconda environment.

First, clone this repository and cd into repo:
```console
(base) foo@bar:~$ git clone https://github.com/ckampa13/plotly-demo.git
(base) foo@bar:~$ cd plotly-demo
(base) foo@bar:~/plotly-demo$
```

Next, create Anaconda environment from the environment file. Note that this file will set the name of the environment to "plotly-demo"

```console
(base) foo@bar:~/plotly-demo$ conda env create -f environment.yml
(base) foo@bar:~/plotly-demo$ conda activate plotly-demo
(plotly-demo) foo@bar:~/plotly-demo$ jupyter-notebook 
```

This will launch a Jupyter notebook instance in your web browser. You can now open and run the demo file: **"plotly_demo_IDEAS.ipynb"**.
