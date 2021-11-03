#

High resolution land surface data with a global coverage is a key requirement as input to global simulation models of, for instance, water resources, air pollution, and land use change.
Processing, reproducing and sharing inputs and derived products is a reoccurring challenge due to the amount of intermediate and final data, often implied by a hyper-resolution modelling requirement.

This Python based processing workflow provides a straightforward creation of input data for raster-based global simulation models.

##

A few steps are required to run the scripts:

 1. You will need a working Python environment.
    We recommend to install Miniconda, or use Anaconda if you have installed that already.
    Follow the Miniconda instructions given at [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html).
    The user guide and short reference on Conda can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html).

 2. Open a terminal (Linux/macOS) or Miniconda command prompt (Windows) and browse to a location where you want to store the repository contents.

 3. Clone this repository, or download and uncompress the zip file. Afterwards change to the `land_surface_data_generator` folder.

 4. Create the required Python environment:

    Linux/macOS:

    `conda env create -f environment/environment.yaml`

    Windows:

    `conda env create -f environment\course_environment.yaml`


The environment file will create a environment named *lsdg* using a recent Python version.
In case you prefer a different name or Python version you need to edit the environment file.

