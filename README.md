# sample-web-app
This web app is built using python to get the sum of the collection of numbers providing as a json input to the web service. Json output return back to the client as the response. 

## Key Functions

#### Web app is designed to return HTTP status code 200 for index call as a simple health check. 

#### proc is the arithmatic function used for providing summation of the input numbers. 

## Libraries used for this app

Below python libraries are used for this development.

```cherrypy - Web Framework```
```pandas```

## Important files

1. buildspec.yml - This file is used to automate the workflow of building and pushing the docker image for AWS Code Build.
2. Dockerfile - This file is used for dockerize the webapp.

## Prerequisites

1. Python3
2. Cherrypy
3. pandas

```pip install pandas```
```pip install CherryPy```

## How to run the webservice

```python ws.py```

Web service is exposed with port 8080 as below,
```http://0.0.0.0:8080```


