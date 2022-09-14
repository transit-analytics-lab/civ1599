# CIV1599 - Analytics for Transit and Mobility Systems

Welcome to the GitHub for the code-based content developed and to be used for the Fall 2022 offering of CIV 1599 - Analytics for Transit and Mobility Systems.

If you find yourself on this page and are not sure what this is - you're probably in the wrong spot... though you are welcome to take a look around. This repository contains labs and worked examples for a first-of-its-kind graduate course which surveys and examines data analytics specifically for transit and other sustainable mobility systems.

## Getting Started
To use the workbooks in this course you will need to set up a modern (ideally 3.9+) version of Python on your computer. You will also need to install  relatively wide set of libraries which are useful for the various data analysis sections we walk through.

### Using Conda (Miniconda)
In some of these modules we will be working with spatial and machine learning libraries which can be particularly tricky to get working on Windows computers using the standard Python and `pip` approach to installing. If you are comfortable spending the time getting these to work (I highly suggest looking into `pipwin` in this case), or are using linux and would like to preserve the Python installation you currently have on your computer you can install the libraries yourself as required.

If you are looking for the easy way, we are going to be using the `conda` package manager (Python developers love their snake and Monty Python references), the simplist of which is [Miniconda](https://docs.conda.io/en/latest/miniconda.html). You can use this link to download and install miniconda on your system. I recommend removing other installations of Python on your system if and where possible (once you get the hang of using Conda you can easily install what you need for other projects as well).


You can set up a new Conda environment by opening an Acaconda prompt/console (on Windows I suggest "run as administrator" for less installation headaches on your own machine) by making sure conda is update and creating a new environment (e.g. one called `civ-1599`) with:

    conda update -n base conda
    conda create -n civ-1599 python=3.10

and choosing `y` when prompted to proceed. Activate the environment with

    conda activate civ-1599

once the library is activated (should have a `(civ-1599)` indicator at the start of the prompt) you can install the basic libraries needed with

    conda install -c conda-forge pandas altair jupyterlab

again choosing `y` when prompted. Additional libraries can be installed as needed throughout the course.

