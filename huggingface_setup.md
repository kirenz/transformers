# Huggingface Setup

If you want to use the Hugging Face API to access pre-trained models and tokenizers, you'll need to follow these general steps.

## Create account and API key

- Create a Hugging Face account if you don't already have one. You can create an account for free on the [Hugging Face website](https://huggingface.co/).

- Log in to your Hugging Face account and navigate to your profile page. Click on the "Settings" button in the top right corner of the page.

- Scroll down to the "API keys" section of the settings page and click on the "Create new API key" button. Give your new API key a name and click on the "Create" button.

- Copy your new API key to your clipboard. This key is a long string of random characters and is used to authenticate your requests to the Hugging Face API.

Install the Hugging Face Transformers library in your Python environment using pip or another package manager. You can install the library by running the following command:

## Store your API key

- We define our API key as a variable in a separate Python file so we can import it into the main script. 

- Create a separate Python file called `config.py`and define your API key as a variable:

```python
API_KEY = 'your_api_key_here'
```



