Triple Ten Bootcamp - Data Science - Streamlit App

Web app to learn about, play around with, and test a streamlit application hosted on render

Initialize with a virtual environment:

with venv: `python -m venv venv` (use `pyenv global 3.*` to use a specific python version)

with conda: `conda create --prefix ./venv` (use `conda create --prefix ./venv python=3.*` to use a specific python version)

with venv: `source venv/bin/activate`

with conda: `conda activate ./venv`

to deactivete:

with venv: `deactivate`

with conda: `conda deactivate`

After creating venv and running it:

`pip install -r requirements.txt`

`streamlit run app.py`
