# Streamlit-Dockerize
A simple script to dockerize a streamlit dashboard so that it can be easily deployed with docker. 

## Pre-Requisites
 - docker
 - docker-compose
 - python

## Installation
The script can be installed to your path by running
```bash
./install
```

## Usage
```bash
chmod +x streamlit-dockerize
streamlit-dockerize -p <PORT [8501]> -e <ENTRANCE [main.py]> /path/to/app/directory
```

