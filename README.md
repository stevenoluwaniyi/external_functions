This notebook covers how to use the Chat Completions API in combination with external functions to extend the capabilities of GPT models. To get started, clone this repo or directly run the Jupyter notebook.

In this case the chat completions api will be calling the weather api as an external function.

The external function in this case is a python function. The python function retrieves the current weather information for a specified location using the OpenWeather API. This function is then called in the openai function.
