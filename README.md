# PhonePe Pulse Data Visualization 2018-2022
This project is a data visualization tool for PhonePe's pulse data from 2018 to 2022. It allows users to explore and analyze various metrics related to PhonePe's business performance.

### HOME
![Home Ph](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/e479ae16-807b-4376-a4ac-587967e2260a)
### TOP CHARTS
TRANSACTION
![Top Transcation](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/ae8d6a32-259f-4158-b08e-65ad893d315a)
USERS
![Top Users](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/c1c02cbf-25d2-4dd0-b921-d5bd4fd51cde)
### VISUALIZATION
TRANSACTION
![Vis](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/5d323e31-1298-4823-9240-6690c325d20e)
Top Payment Type
![vis top payment](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/b1676a33-a98e-4e29-ad90-5b82fa146b0f)
State to explore
![vis state](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/16e299cb-bac6-4aba-923a-68a9d3b177d6)
USERS
![vis users](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/47ac47b4-1828-4ea4-8da0-30dda5fbc577)
Users State
![vis users state](https://github.com/DeepikaChinnasamy/Phonepe_Pulse/assets/127653700/b4f864ce-3064-454e-a8b6-8439d65cb8c9)

## Installation and Cloning
Clone the repository to your local machine using git clone https://github.com/PhonePe/pulse.git Install the required Python packages.
#### Libraries/Modules needed for the project!
    import pandas as pd
    import mysql.connector as sql
    import streamlit as st
    import plotly.express as px
    import os
    import json
    from streamlit_option_menu import option_menu
    from PIL import Image
    from git.repo.base import Repo
#### Data extraction:
Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON. Use the below syntax to clone the phonepe github repository into your local drive.
    from git.repo.base import Repo
    Repo.clone_from("GitHub Clone URL","Path to get the cloded files")
##### Refer my PhonePe_cloning and extraction.ipynb file
## Dashboard creation:

To create colourful and insightful dashboard I've used Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in Pie, Bar, Geo map functions are used to display the data on a charts and map and Streamlit is used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.

## Data retrieval:

Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.

## EXPLORE
Run python Phonepe_Pulse.py to start the application(streamlit run Phonepe_Pulse.py). Access the application in your web browser by navigating to http://localhost:8501 Select the desired date range and metrics to visualize. Explore the data using the interactive charts provided by Plotly Express.

