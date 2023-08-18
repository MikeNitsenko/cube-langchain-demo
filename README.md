# Cube Semantic Loader Demo

This repo is the implementation of locally hosted bot for question answering over Cube's Semantic Layer.

## Pre-requisites

- Valid Cube Cloud deployment. Your data model should have a least one view
- This example uses OpenAI API, so you'll need an OpenAI API key
- Python version `>=` 3.8

## How to run

- Install dependencies: `pip install -r requirements.txt`
- Run `python ingest.py`. It will use `CubeSemanticLoader` Langchain library to load metadata and save it in vectorstore
- Create `.env` file using `.env.example` and fill it with according values
- Run `streamlit run main.py`