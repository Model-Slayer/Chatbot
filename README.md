# Chatbot

This is a sample chatbot to help a customer buy a product. Built using Rasa 2.8.12

## Create python 3.7 virtual environment

Run: 
```bash
sudo apt-get install python3.7-venv
python3.7 -m venv rasa
source rasa/bin/activate
``` 

## Install dependencies

Run:
```bash
pip install -r requirements.txt
```

## Run the bot

Use `rasa train` to train a model.

Then talk to your bot by running:
```
rasa shell --debug
```

## Overview of the files

`data/stories.yml` - contains stories

`data/nlu.yml` - contains NLU training data


`data/rules.yml` - contains the rules upon which the bot responds to queries

`actions/actions.py` - contains custom action/api code

`domain.yml` - the domain file, including bot response templates

`config.yml` - training configurations for the NLU pipeline and policy ensemble


