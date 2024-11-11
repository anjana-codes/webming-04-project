# Requests, JSON, and NLP

## Title: webmin-04-project

### Name: ANjana Dhakal, Date:11/06/2024

### Obejectives:
This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to (a) make an API request and (b) find the information we need in the returned response. 

Helpful Hint: You can make a simple API request directly in your browser to test it BEFORE making the same request from your notebook or script.

## Copy and clone base repository
1. Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/json-sentimentLinks to an external site.
2. Clone YOUR new repo down to your machine.

## Install required packages
1. Activate venyl virtual environment
   ```
    python -m venv .env
    source .env/bin/activate
```
2. Install the required packages: 
```
    pip install -U pip setuptools wheel
    pip install -U spacy
    python -m spacy download en_core_web_sm
```

## Export to HTML
Export Using Jupyter Menu
more options (...) tap near outline in the home page of Jupyter Notebook and export as HTML.


## Git add and commit
```
git add .
git commit -m " project completed"
git push origin main

```