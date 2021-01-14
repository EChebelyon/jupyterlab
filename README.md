This repo illustrates some features of JupyterLab, these features make it my preferred notebook environment.

## Jupyter lab installation and awesome extensions
Create a conda environment if you use conda

`conda create --name <NAME OF YOUR ENV>`

you can choose to set channel priorities.

Activate the environment

`conda activate <NAME OF YOUR ENV>`

Install Jupyterlab

`conda install -c conda-forge jupyterlab`

or 

`pip install jupyterlab`

conda has a conflict resolution mechanism and is therefore preferrable, although it might take a long time.

Spin up the server on your localhost:

`jupyter lab`

Once the server is running on the browser you can change the themes, fonts, display orientations etc. 

### Useful Extensions:

- [IPywidgets](https://github.com/jupyter-widgets/ipywidgets)
- [geojson](https://github.com/jupyterlab/jupyter-renderers/tree/master/packages/geojson-extension)
- [drawIO](https://github.com/QuantStack/jupyterlab-drawio)
- [IPyleaflet](https://github.com/ellisonbg/ipyleaflet)
- [Git](https://github.com/jupyterlab/jupyterlab-git)
- [Github](https://github.com/jupyterlab/jupyterlab-github)
- [TOC](https://github.com/ian-r-rose/jupyterlab-toc) : ships with JupyterLab 3.0
- [Spellchecker](https://github.com/ijmbarr/jupyterlab_spellchecker)
- [Debugger](https://github.com/jupyterlab/debugger)
- [JupyterLab Spreadsheet](https://github.com/quigleyj97/jupyterlab-spreadsheet)
- [ipympl](https://github.com/matplotlib/ipympl)

### Rockster Extensions
- [Voilà](https://github.com/voila-dashboards/voila) : Ships with JupyterLab 3 and turns notebooks to webapps
- [Jupyter Dash](https://github.com/plotly/jupyter-dash): React.js, Flask and Plotly
- [JupyterHub](https://github.com/jupyterhub/jupyterhub): Multi-user server for Notebooks
