# GST-Sentiment-Analysis

GST (Goods and Services Tax) is a comprehensive tax system that was implemented in India in 2017. It replaced a number of indirect taxes at the national level and aims to simplify the tax system and make it more transparent and efficient.

Sentiment analysis refers to the use of natural language processing techniques to identify and extract subjective information from text data. Sentiment analysis can be a useful tool for understanding public opinion and sentiment towards GST, and can provide valuable insights for policymakers and other stakeholders. This is done by collecting and analyzing twitter tweets related to GST.

Most of the opinions were neutral, which means that people were sharing information about the gst instead of sharing any positive or negative opinions.

## Running the API
To run the API server, navigate to the project directory and execute the following command:

```
uvicorn src.main:app --reload
```

* This command starts the Uvicorn server with the FastAPI application from `src/main.py`. The `--reload` flag makes the server restart after code changes, which is useful during development.

## How to Interact with the API
You can interact with the API by sending a POST request to the `/analyze_sentiment` endpoint, including Twitter data in the request body. This endpoint analyzes the sentiment of the provided Twitter data.
