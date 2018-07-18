# Variant calling pipeline with Fusera and bcbio
---

This directory contains iPython notebook that uses [Fusera](https://github.com/mitre/fusera) to access data in cloud storage and [bcbio](https://bcbio-nextgen.readthedocs.io/en/latest/) pipeline to do variant calling with GATK.

---

## Getting started

You will need to install Jupyter notebooks and the bash kernel for Jupyter notebooks. Please open up a terminal and run the following to install:

```bash
#   Install Jupyter notebooks
python3 -m pip install --upgrade pip
python3 -m pip install jupyter

#   Enable the bash kernel in Jupyter notebooks
python3 -m pip install bash_kernel
python3 -m bash_kernel.install
```

**Running Jupyter notebook:**

```bash
#   You may have to change this path depending on where you clone
#   this GitHub repository
#   Here, I am assuming you cloned this repo into ~/
cd ~/Jupyterized_Pipelines/fusera_vc
jupyter notebook
```
