# Installation

The best way to install `aitlas`, is if you create a virtual environment and install the  requirements with `pip`. Here are the steps:
- Create a virtual environment
```bash
conda create -n aitlas python=3.8
```
- Use the virtual environment
```bash
conda activate aitlas
```
- Install the following packages:
```bash
pip install GDAL-3.4.1-cp38-cp38-win_amd64.whl 
pip install Fiona-1.8.20-cp38-cp38-win_amd64.whl
pip install rasterio-1.2.10-cp38-cp38-win_amd64.whl
pip install aitlas-0.0.1-py3-none-any.whl 
```
- Enable the use of the `aitlas` virtual environment in Jupyter notebooks
```bash
python -m ipykernel install --name aitlas 
```
