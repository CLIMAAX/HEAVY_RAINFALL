# EXTREME PRECIPITATION

Repository for collaboration on workflows for the Extreme precipitation hazard


# How to run

## Running on Binder

The notebook is designed to be launched from Binder.

Click [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CLIMAAX/HEAVY_RAINFALL/main) to access the repository through MyBinder.

## Running locally
You may also download the repository from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone git@github.com:CLIMAAX/HEAVY_RAINFALL.git
    ```

4. Move into the cloned repository
    ```bash
    cd HEAVY_RAINFALL
    ```

5. Create and activate your environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate climaax_extreme_precipitation
    ```

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`
7. Edit the notebook
8. Commit and push to the repo. **This step will be changed soon, introducing Pull Requests**.

# Credits
The **How to run** section was adapted from the [Environmental Data Science Book](https://edsbook.org/welcome.html) project.
