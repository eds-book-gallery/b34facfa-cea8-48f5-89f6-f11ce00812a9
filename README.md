<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Detecting floating objects using deep learning and Sentinel-2 imagery</h1>
</div>

<p align="center">
    <a href="https://github.com/eds-book-gallery/b34facfa-cea8-48f5-89f6-f11ce00812a9/blob/main/LICENSE">
        <img alt="license" src="https://img.shields.io/badge/license-MIT-yellow.svg">
    </a>
    <a href="https://notebooks.gesis.org/binder/v2/gh/eds-book-gallery/b34facfa-cea8-48f5-89f6-f11ce00812a9/main?labpath=notebook.ipynb">
        <img alt="binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/eds-book-gallery/b34facfa-cea8-48f5-89f6-f11ce00812a9/actions/workflows/render.yaml">
        <img alt="render" src="https://github.com/eds-book-gallery/b34facfa-cea8-48f5-89f6-f11ce00812a9/actions/workflows/render.yaml/badge.svg">
    </a>
    <a href="https://github.com/alan-turing-institute/environmental-ds-book/pull/22">
        <img alt="review" src="https://img.shields.io/badge/view-review-orange">
    </a>
    <br/>
</p>

<p align="center">
    <a href="https://w3id.org/ro-id/b34facfa-cea8-48f5-89f6-f11ce00812a9">
        <img alt="rohub" src="https://img.shields.io/badge/RoHub-FAIR_Executable_Research_Object-2ea44f?logo=Open+Access&logoColor=blue">
    </a>
    <a href="https://doi.org/10.24424/g1bk-dv49">
        <img alt="doi" src="https://zenodo.org/badge/DOI/10.24424/g1bk-dv49.svg">
    </a>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/13321552/222989704-98abb3ad-0074-47c1-b826-8ccc8c69af5e.png?raw=True" alt="thumbnail" width="300"/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
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

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.
The workflow actions were adapted from [2i2c’s hub-user-image-template](https://github.com/2i2c-org/hub-user-image-template) released under BSD-3-Clause license.
