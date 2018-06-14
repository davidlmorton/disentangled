# Disentangled

This repository is for code that was used to generate plots for [Learning Disentangled Representations](https://medium.com/@davidlmorton/learning-disentangled-representations-part-1-simple-dots-c5553ecc995b).
Exploring the learning of disentangled data representations by deep neural networks.

The notebooks here heavily utilize a package called [pytorch-sconce](https://github.com/davidlmorton/pytorch-sconce), that makes training pytorch modules a lot easier.

## Running the Notebooks

To run the notebooks, just install [tox](https://pypi.org/project/tox/) and then run:

```
tox -e jupyter -- notebook
```

Tox will take care of building the python virtualenv and installing the notebook's dependencies. Enjoy.
