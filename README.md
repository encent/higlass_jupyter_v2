# higlass_jupyter_v2

This is a repository with code snippets for HiGlass visualization with Jupyter notebook.

### Running HiGlass with Jupyter

Clone this repo:

```bash
git clone https://github.com/encent/higlass_jupyter_v2
cd higlass_jupyter_v2
```

If you don't have conda/Anaconda on your PC, [install it first](https://docs.anaconda.com/miniconda/#quick-command-line-install).

Create HiGlass conda environment:

```bash
conda env create -f environment.yml
```

Activate environment, install higlass-jupyter extension, and run Jupyter Notebook:

```bash
conda activate higlass
git clone https://github.com/manzt/hg
cd hg
pip install -e.
cd ..
jupyter notebook higlass_viz.ipynb
```

After that, follow the instructions inside the Jupyter Notebook.

### P.S.

After you are done with your HiGlass analysis, shut down the Jupyter server: simply go to the terminal where you first launched Jupyter Notebook and type `Ctrl+C`, then `yes`. After that, deactivate conda environment: `conda deactivate`.

If something does not work or you have a question, feel free to contact me.
