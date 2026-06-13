# Instructions

## Install conda

- Open the terminal and check for conda: conda --version
- If you don't have conda, then go to https://docs.anaconda.com/miniconda/ and install miniconda
- On Windows, open the Anaconda Prompt after miniconda is installed

## Create project environment

- Create a project folder called whatever name you want to give it (e.g. SHRO2026)
- Copy the file environment.yml to the project folder
- Open the Anaconda Prompt and change to directory to the project folder
- Enter: `conda env create --file=environment.yml`
- Enter: `conda activate shro2026_environment`
- You should see "(shro2026_environment)" appearing before the prompt
- Tp open spyder from the Anaconda Prompt, enter: `spyder`
