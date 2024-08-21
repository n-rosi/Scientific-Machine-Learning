# Scientific Machine Learning

:unicorn: This repository contains a collection of exercises from the homonym book [Data Driven Science and Engineering](https://databookuw.com/) (aut. J. Nathan Kutz, Steven L. Brunton). 

:books: The exercises were executed in occasion of the Scientific Machine Learning special course at DTU Compute. 

:sunglasses: Authors are Nicole Rosi and Jens Peter Schøler. 

:video_camera: The Notebooks contains links to my Youtube channel were videos can be dispalied. 

📔 [Link](https://n-rosi.github.io/Scientific-Machine-Learning/intro.html) to the jupyter-book format.

--------------------------------------------------------------------------------
## Create virtual environment

Create `jupybook` mamba virtual env with most of dependencies included with:
```
conda env create -f environment.yml

```
install `deepxde`:
```
mamba -c conda-forge deepxde
```

these library allow to run all notebooks in this repository. 

--------------------------------------------------------------------------------
## Build jupyter book

Install `jupyter-book`:
```
mamba -c conda-forge jupyter-book
```

build your book:
```
jupyter-book build .
```

see your book preview:
```
cd _build/html

python -m http.server 8000
```

For more information visit: [jupyter book docs](https://jupyterbook.org/en/stable/intro.html).