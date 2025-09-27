How to use magproc in Windows

This is designed for chanel names in either column of [normalize](./AirMagTools/normalize.csv). 
If your datafile has chanel names not found in normalize, either:
    1) The columns are added the 'variation' column in normalize, and the appropriate name is matched in the 'normal' column.
        * this is the preferred method. Please fork the repository and make a pull request.
    2) The data file header needs fixed to accommodate the expected names
  
# Installation instructions:
- Install python (≥3.10)
    - if in a Windows environment, search 'python' in the [Microsoft app store](apps.microsoft.com)
    - if in a Mac environment, we suggest using [Homebrew][https://brew.sh/] [python@3.10](https://formulae.brew.sh/formula/python@3.10) 
    - if in a Linux environment, use the package manage for your flavor of linux

- Open a new python prompt (Windows) or terminal (Mac, Linux).

- Navigate to where you want your virtual environment (VE) to be installed:
    - `cd <path_to_VE_directory>`

- Create a new virtual environment:
    - `python -m virtualenv <your_ve_name_here>`

- Activate the virtual environment
    - Windows: `<path_to_your_ve_here>\Scripts\activate`
    - Max, Linux: `<path_to_your_ve_here>\bin\activate`

- Navigate to where you want AirMagTools to live:
    - `cd <path_to_repository_directory>`

- Clone github repo to local machine:
    - `git clone https://github.com/SagebrushGeoTools/AirMagTools.git`

- Navigate AirMagTools:
    - `cd ./AirMagTools`

- Install AirMagTools:
  - `pip install .`

If using a Jupyter notebook:
- Install jupyter
    - `pip install jupyter`

- Create Jupyter kernel from virtual environment:
    - `python -m ipykernel install --name <your_ve_name_here> --user`

- Copy Example notebook to your working project directory:

- From your working project directory start Jupyter:
    - `jupyter lab`

- Change the input file paths in the notebook. Use shift enter to run cells.
