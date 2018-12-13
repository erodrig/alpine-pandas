## alpine-pandas
[Python 3.6](https://hub.docker.com/_/python/) image with [pandas](https://pandas.pydata.org/) based on Alpine platform
Reduced footprint given the image deletes build dependencies

# Features

* Creates a virtual space at /venv
* Install Python Pandas library
* Install Python cryptography library (tag cryptography)
* Install any missing operative system packages

# Supported tags and respective Dockerfile links
`latest` [(pandas/Dockerfile)](https://github.com/erodrig/alpine-pandas/blob/master/Dockerfile)
`cryptography` [(cryptography/Dockerfile)](https://github.com/erodrig/alpine-pandas/blob/cryptography/Dockerfile)

# Upgrades:
* pip
* setuptools

# FIXES 
Correct timezone problem with Python Alpine Images