[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg?style=for-the-badge)](https://www.repostatus.org/#active) [![License: Apache License 2.0](https://img.shields.io/badge/License-Apache%202.0-olivegreen.svg)](https://github.com/biasvariancelabs/aitlas/blob/master/LICENSE) [![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/)

![logo](media/AiTALS_horizontal_gradient_subtitle.png)


The AiTLAS toolbox (Artificial Intelligence Toolbox for Earth Observation) includes state-of-the-art machine learning methods for exploratory and predictive analysis of satellite imagery as well as repository of AI-ready Earth Observation (EO) datasets. It can be easily applied for a variety of Earth Observation tasks, such as land use and cover classification, crop type prediction, localization of specific objects (semantic segmentation), etc. The main goal of AiTLAS is to facilitate better usability and adoption of novel AI methods (and models) by EO experts, while offering easy access and standardized format of EO datasets to AI experts which allows benchmarking of various existing and novel AI methods tailored for EO data.

# Getting started

AiTLAS Introduction https://youtu.be/-3Son1NhdDg

AiTLAS Software Architecture: https://youtu.be/cLfEZFQQiXc

AiTLAS in a nutshell: https://www.youtube.com/watch?v=lhDjiZg7RwU

AiTLAS examples:
- Land use classification with multi-class classification with AiTLAS: https://youtu.be/JcJXrMch0Rc
- Land use classification with multi-label classification: https://youtu.be/yzHkEMbDW7s
- Maya archeological sites segmentation: https://youtu.be/LBFY4pCfzOU
- Visualization of learning performance: https://youtu.be/wjMfstcWBSs

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
- Install the following packages from the installation folder:
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

---
# Citation
For attribution in academic contexts, please cite this [work](https://arxiv.org/abs/2201.08789) as
```
@article{dimitrovski2022aitlas,
      title={AiTLAS: Artificial Intelligence Toolbox for Earth Observation}, 
      author={Ivica Dimitrovski and Ivan Kitanovski and Panče Panov and Nikola Simidjievski and Dragi Kocev},
      year={2022},
      journal={arXiv preprint arXiv:2201.08789},
}





