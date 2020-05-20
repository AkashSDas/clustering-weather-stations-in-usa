


# Clustering Weather Stations


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [License](#license)

  
  

## About

> A `machine learning` model is used to make `clusters` of `weather stations` of USA using the `DBSCAN` clustering algorithm.

> **`Here DBSCAN clustering algorithm is used`**

> Here it is an `Unsupervised Learning` problem and moreover it is an `Clustering` problem.

## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` and `Pandas` are used to work with the data.

> `Matplotlib` and `mpl_toolkits` is used to visualise the results.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Weather Stations



![Weather Stations](https://github.com/AkashSDas/Clustering-Weather-Stations/blob/master/project-results-images/img1.png)

#### Clustering based on Location of Weather Station

![Clustering based on Location of Weather Station](https://github.com/AkashSDas/Clustering-Weather-Stations/blob/master/project-results-images/img2.png)

#### Clustering based on Location of Weather Station and Temperature

![Clustering based on Location of Weather Station and Temperature](https://github.com/AkashSDas/Clustering-Weather-Stations/blob/master/project-results-images/img3.png)

## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Clustering-Weather-Stations'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/Clustering-Weather-Stations
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'Clustering-Weather-Stations'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```
- dataset, jupyter notebook and model are in `'Clustering-Weather-Stations'/venv/src` folder.
```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
