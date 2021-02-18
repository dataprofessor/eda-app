# eda-app

# Watch the tutorial video

[How to build an EDA app using Pandas Profiling | Streamlit #19](https://youtu.be/p4uohebPuCg)

<a href="https://youtu.be/p4uohebPuCg"><img src="http://img.youtube.com/vi/p4uohebPuCg/0.jpg" alt="How to build an EDA app using Pandas Profiling | Streamlit #19" title="How to build an EDA app using Pandas Profiling | Streamlit #19" width="400" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/eda-app/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *eda*
```
conda create -n eda python=3.7.9
```
Secondly, we will login to the *eda* environment
```
conda activate eda
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/eda-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/eda-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
