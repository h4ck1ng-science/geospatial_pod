# geospatial_pod

## Environment creation

Install Anaconda and Jupyter lab/notebook: https://www.anaconda.com/products/distribution

In linux/mac open the terminal, in Windows open the Anaconda Command Prompt.

```
conda create --name geospatial python=3.9
conda activate geospatial
```

Dependencies
```
pip install hda
pip install sentinelsat
pip install numpy scipy pandas 
pip install chardet
pip install ipywidgets
conda install geopandas
conda install scikit-learn-intelex
conda install -c conda-forge rasterio
conda install -c conda-forge folium
conda install -c anaconda scikit-image
conda install -c conda-forge zarr
```

Adding the conda environment to jupyter lab
```
pip install ipykernel
python -m ipykernel install --user --name geospatial
```
