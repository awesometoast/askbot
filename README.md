# Extremely simple text generation web UI

A python/flask UI for using OpenAI with basic training data. Made for experimentation purposes. Default dataset is a fake article about a uniquely named fictional steampunk toaster.

## Installation

Clone this repo.
Make sure you have python installed. You may also want to install `python-is-python3` on Linux.

Install dependencies with:
```
pip install -r requirements.txt
```
Create an OpenAI API key and replace all instances of string `YOUR_KEY` with your actual key.

Put .txt files in `chatbot_docs`

Then run `python embeddings.py`

To start the UI, run `python webapp.py` and go to [http://localhost:8001](http://localhost:8001`).