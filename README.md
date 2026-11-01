# colab-demo

A small repository for Google Colab demos.

## Creative ideas notebook

Open creative_ideas.ipynb in Google Colab and run the cells from top to bottom. The notebook asks for an everyday object and uses the OpenAI Responses API with gpt-6-luna to suggest one unusual, practical use.

The first code cell installs the OpenAI Python SDK. The next cell asks for an OpenAI API key with a hidden getpass prompt. Use an API key from the OpenAI API platform, not your ChatGPT password. The notebook does not include or save your key; enter it only at runtime, and do not paste it into a code cell or notebook output.

The model call uses the Responses API. See the GPT-6 Luna model documentation (https://developers.openai.com/api/docs/models/gpt-6-luna) and OpenAI Python SDK documentation (https://developers.openai.com/api/reference/python).
