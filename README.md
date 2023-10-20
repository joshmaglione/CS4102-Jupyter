# CS4102-Jupyter
A repository for the CS4102 Jupyter Notebooks 

- [CS4102-Jupyter](#cs4102-jupyter)
  - [Frequently Asked Questions](#frequently-asked-questions)
    - [What is this about?](#what-is-this-about)
    - [Do I need to be a Python expert?](#do-i-need-to-be-a-python-expert)
    - [How can I get my Jupyter Notebooks to look like they do in class?](#how-can-i-get-my-jupyter-notebooks-to-look-like-they-do-in-class)
    - [How can I install Python on my computer?](#how-can-i-install-python-on-my-computer)
    - [How can I use all the modules like pandas etc.?](#how-can-i-use-all-the-modules-like-pandas-etc)


This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

Thanks to [Götz Pfeiffer](https://www.universityofgalway.ie/our-research/people/mathematical-statistical-sciences/goetzpfeiffer/) for making his [Jupyter Notebooks](https://github.com/gpfeiffer/cs4102) available.

## Frequently Asked Questions

### What is this about? 

Half of our lectures in CS4102 will be putting into practice the data analysis methods we discuss. By using Jupyter Notebooks, we can look at text (including mathematics) as well as run Python code in the same document. 

### Do I need to be a Python expert? 

No. Ideally one is familiar with the general syntax and structure of Python code. If not, try playing around with `python_tutorial.ipynb`. This is a mini python tutorial written by [Götz Pfeiffer](https://www.universityofgalway.ie/our-research/people/mathematical-statistical-sciences/goetzpfeiffer/). 

### How can I get my Jupyter Notebooks to look like they do in class?

I use [VS Code](https://code.visualstudio.com/) together with many extensions within VS Code for Jupyter Notebooks and Python.

For Python, the extensions I use are 
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
  
For Jupyter Notebooks, the extensions I use are 
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Jupyter Notebook Renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers)

I also use [Rainbox CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) for viewing CSV files.

### How can I install Python on my computer? 

Go to [python.org](https://www.python.org/), and follow the instructions there for your operating system. 

### How can I use all the modules like pandas etc.?

Many python packages can be managed using [`pip`](https://en.wikipedia.org/wiki/Pip_(package_manager)). `Pip` will come installed with the latest version of Python. One can update `pip` by opening a terminal (command prompt or powershell) and running:
```bash
pip install --upgrade pip
```

In order to use all the modules (Python packages) we use in class, run the following code in your terminal (command prompt or powershell)
```bash
pip install numpy matplotlib pandas statsmodels scikit-learn
```

Some users might use `pip3` instead of `pip`.