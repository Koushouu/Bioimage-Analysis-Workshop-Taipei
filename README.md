# Bioimage Analysis Workshop Taipei

Course material for bioimage analysis workshop at Academia Sinica, Taipei. The course materials are heavily based on:

- **EMBL Bio-IT bioimage analysis workshop**, especially the part by Toby Hodges and Jonas Hartmann: [https://git.embl.de/grp-bio-it-workshops/image-analysis-with-python](https://git.embl.de/grp-bio-it-workshops/image-analysis-with-python)
- **Introduction to Bioimage Analysis** by Pete Bankhead: [https://bioimagebook.github.io/](https://bioimagebook.github.io/)
- **Bioimage Analysis Lecture 2020** by Robert Haase: [https://www.youtube.com/watch?v=e-2DbkUwKk4&list=PL5ESQNfM5lc7SAMstEu082ivW4BDMvd0U](https://www.youtube.com/watch?v=e-2DbkUwKk4&list=PL5ESQNfM5lc7SAMstEu082ivW4BDMvd0U)

## Pre-requirement of the workshop

Please prepare the following before the workshop:

- Please install Anaconda ([https://www.anaconda.com/](https://www.anaconda.com/)) on your laptop (Yes, you need a laptop) and follow the “Creating a Python Environment for the workshop” work flow as below for the setup.
- If you are not confortable with python, please follow the “Basics in Python” Jupyter notebook to learn the basics of python programming
- If you want something more to get yourself more comfortable with python programming for image proessing, follow “Basics in Python2” Jupyter notebook.

## Creating a Python Environment for the workshop

1. With Anaconda prompt, create a virtual environment with the name “bioimage-analysis”
    
    ```powershell
    conda create --name bioimage-analysis python=3.8
    ```
    
2. Then activate the environment
    
    ```powershell
    conda activate bioimage-analysis
    ```
    
3. Install all the necessary packages
    
    ```powershell
    conda install numpy
    conda install matplotlib
    conda install scipy
    conda install scikit-image
    conda install ipywidgets
    
    jupyter nbextension enable --py --sys-prefix widgetsnbextension
    ```
    
4. In anaconda navigator, change the environment to the newly created environment
    
    ![Untitled](Bioimage%20Analysis%20Workshop%20Taipei%20713e3db33cf646a6b17ca62c7449b647/Untitled.png)
    
5. Install Jupyter notebook in this environment
6. Launch the jupyter notebook