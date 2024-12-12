# Streamlit-Dockerize
A simple script to dockerize a streamlit dashboard so that it can be easily deployed with docker. 

## Pre-Requisites
 - docker
 - docker-compose
 - python

## Installation
The script can be installed to your path by running
```bash
git clone https://github.com/tboudreaux/streamlit-dockerize.git
cd streamlit-dockerize
./install
```

## Usage
```bash
streamlit-dockerize -p <PORT [8501]> -e <ENTRANCE [main.py]> /path/to/app/directory
```

