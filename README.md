# Usage
First, load the submodule:
```
git submodule init
```

To view the plots you need to install several packages. Below are the commands to create a new conda environment and install the necesary packages:
```
conda create -n plots 
conda activate plots
conda install python pandas
conda install -c plotly plotly
conda install -c conda-forge ipywidgets
```
Additionally, you need a way to run jupyter notebooks. For example, using jupyter lab:

```
conda install jupyterlab
```

