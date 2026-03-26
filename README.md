
# Microcredencial Introducción a Python 

Authors: [Dr. Isaac Lera](https://personal.uib.es/isaac.lera), [Dr. Miquel Miró](https://personal.uib.cat/miquel.miro), [Dr. Francesc Xavier Gaya](personal.uib.es/francesc-xavier.gaya), [Aina Colom]() <br/>
Official web site: [https://cep.uib.cat/master/MAD2/12174/index.html](https://cep.uib.cat/master/MAD2/12174/index.html) <br/>
Edition: 2026, v1<br/>

## How to read the doc

Documentation available at: [https://ttad.readthedocs.io/](https://ttad.readthedocs.io/)

## How to get the code 

```bash
git clone https://github.com/wisaaco/MCINTROPYTHON.git
cd MCINTROPYTHON
uv sync
```

to install libraries:
```bash
uv add seaborn
```

to rebuild the docs:
```bash
 uv run --extra docs sphinx-build -b html docs docs/_build/html
```