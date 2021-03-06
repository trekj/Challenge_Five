# Financial Planning 
In this Python project, we will create a tool on financial analysis by using a single Jupyter notebook for the purpose of evaluating the credit union memeber's financial health. 
1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.
2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


## Technologies
This project is written in ***Python 3.8*** with the following libraries:

***OS Module*** -provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc.

***Request Module*** is a python module that you can use to send all kinds of HTTP requests. It is an easy-to-use library with a lot of features ranging from passing parameters in URLs to sending custom headers and SSL Verification.

***json*** -stands for JavaScript Object Notation. It is a lightweight data-interchange format that is used to store and exchange data. It is a language-independent format and is very easy to understand since it is self-describing in nature.

***Python-dotenv*** -reads key-value pairs from a .env file and can set them as environment variables.rom dotenv import load_dotenv.

***alpaca_trade_api*** -The Alpaca SDK will check the environment for a number of variables that can be used rather than hard-coding these into your scripts. Alternatively you could pass the credentials directly to the SDK instances.

***MCForecastTools*** A Monte Carlo simulation is a useful tool for predicting future results by calculating a formula multiple times with different random inputs.

***panda*** -a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.

***numpy*** -is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python.

***matpoltlib*** -is a comprehensive library for creating static, animated, and interactive visualizations in Python.

## Installation Guide

Before running the application first install the following dependencies.

import os

import requests

import json

import pandas as pd

from dotenv import load_dotenv

import alpaca_trade_api as tradeapi

from MCForecastTools import MCSimulation



## Usage

After cloning the repository,  open the directory Starter Code and run the program by typing python financial_planning_tools.ipynb 

## Contributors
#### James Tagapan

jtagapan@gmail.com

## License
Licensed under the MIT License. Copyright 2020
