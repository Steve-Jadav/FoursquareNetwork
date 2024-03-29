# Foursquare Network Data Analysis

Create a virtualenv and activate source

```shell script
virtualenv venv
source venv/bin/activate
```

Install all requirements via python-pip

```shell script
pip install -r requirements.txt
```

Run the 'graph.py' file. This will redirect you to 3 html pages showing different visualisations. At the same time, the betweenness centralities of a section of users will also be printed on the terminal.

```shell script
python graph.py
``` 

The data/data.json file contains the data used for this project. These data were scrapped using Foursquare Places API.

The data.py file is only used to scrape the data dynamically. We have already used this code to fetch the necessary data required for this project. Hence, there is no need to use this file. Running this file will require a stable internet connection.

The 'settings.py' file contains some predefined values. It includes the API keys.
