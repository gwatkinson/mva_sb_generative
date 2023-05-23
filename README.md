# Likelihood training of Schrödinger bridge using Forward-backward SDEs theory

[![Build](https://github.com/gwatkinson/mva_snlp_canine/actions/workflows/main.yml/badge.svg)](https://github.com/gwatkinson/mva_snlp_canine/actions/workflows/main.yml)
[![Code quality](https://github.com/gwatkinson/mva_snlp_canine/actions/workflows/quality.yml/badge.svg)](https://github.com/gwatkinson/mva_snlp_canine/actions/workflows/quality.yml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This is the repository associated with the project for the MVA course __Generative Modelling__.

This is a group project realised by :

* Benjamin Maurel
* Jérémie Stym-Popper
* Gabriel Watkinson

Don't hesitate to contact any of us if you have any questions.

This experiments presented here and in the report comes from modification of https://github.com/ghliu/DeepGSB/tree/main. 

## Installation

1. Clone the repository.
```bash
git clone https://github.com/gwatkinson/mva_sb_generative
```

2. Install the project and dependencies, creating a virtual environment with `poetry` (you need to [install poetry](https://python-poetry.org/docs/#installation) it beforehand). If you prefer to use an existing environment, you just have to activate it and run the same command:
```bash
poetry install
```

3. Activate the created environment if needed.
```bash
source $(poetry env info --path)/bin/activate  # for linux
# & ((poetry env info --path) + "\Scripts\activate.ps1")  # for windows powershell
# poetry shell  # or this spawns a new shell
```

4. Install pre-commit, if you are planning to add code.
```bash
pre-commit install
```

5. Use Pytorch with GPU support (optional). Use this if Pytorch doesn't see your GPU. This reinstalls Pytorch in the virtual environment, and needs to be rerun after each modification of the environment.
```bash
poe torch_cuda
```

## Reproduce the experiments

blabla
