# Install

## Miniconda Installation

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

## Post-Installation
```
conda config --set auto_activate_base false
# It creates ~/.condarc with following content:
  auto_activate_base: false
```


# Jupyter notebook
```
conda install ipykernel
python -m ipykernel install --user --name lal --display-name "python-lal"
# It modifies ~/Library/Jupyter/kernels/
```


# Check environments 
[Python, pip, site-packages](https://medium.com/@will.wang/%E6%92%A5%E9%96%8B-python-pip-site-packages-%E7%9A%84%E8%97%8D%E8%89%B2%E8%9C%98%E8%9B%9B%E7%B6%B2-90e398bb3785)
```
$ pip -V
$ python -m site

```


# Jupyter

