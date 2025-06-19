# Detecting floating objects using deep learning and Sentinel-2 imagery

<p align="center">
    <a href="https://github.com/eds-book/b34facfa-cea8-48f5-89f6-f11ce00812a9/actions/workflows/monthly-build.yaml/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/eds-book/b34facfa-cea8-48f5-89f6-f11ce00812a9/actions/workflows/monthly-build.yaml/badge.svg">
    </a>
    <a href="http://mybinder.org/v2/gh/eds-book/b34facfa-cea8-48f5-89f6-f11ce00812a9/main?labpath=notebook.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://doi.org/10.5281/zenodo.8308843">
        <img alt="doi" src="https://zenodo.org/badge/493600192.svg">
    </a>
    <a href="https://github.com/alan-turing-institute/environmental-ds-book/pull/22">
        <img alt="notebook review" src="https://img.shields.io/badge/view-review-purple">
    </a>
</p>

<p align="center">
<img src="images/thumbnail.png" alt="thumbnail" width="500"/>
</p>

## How to run

### Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

### Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/eds-book-gallery/b34facfa-cea8-48f5-89f6-f11ce00812a9.git
    ```

4. Move into the cloned repository
    ```bash
    cd b34facfa-cea8-48f5-89f6-f11ce00812a9
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate b34facfa-cea8-48f5-89f6-f11ce00812a9
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`
