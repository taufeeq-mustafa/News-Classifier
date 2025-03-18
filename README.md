# News Classifier

AI News Classifier is an LLM-powered news classification system that categorizes news articles into Politics, Sports, Business, or Tech using LangChain, Groq’s Mixtral-8x7b, and Kaggle’s News Category Dataset.

## Features

✅ Fetches and processes news data from Kaggle<br>
✅ Uses Groq's LLM (Mixtral-8x7b) for classification<br>
✅ Maps similar categories into broader groups<br>
✅ Handles JSONL format datasets using Pandas<br>
✅ FastAPI integration for API-based classification

## Tech Stack

<li>Python
<li>LangChain (Groq API)
<li>FastAPI & Uvicorn
<li>Pandas
<li>KaggleHub

## Run Locally

Clone the project

```bash
git clone https://github.com/taufeeq-mustafa/News-Classifier
.git
```

Install dependencies

```bash
pip install langchain groq elasticsearch pandas fastapi uvicorn kagglehub
```


Start the server
```bash
uvicorn main:app --reload
```


## License

[MIT](https://choosealicense.com/licenses/mit/)
