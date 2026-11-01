# colab-demo

A small repository for Google Colab demos.

## Creative ideas notebook

Open creative_ideas.ipynb in Google Colab. Run the SDK installation cell once, then run the idea generator cell. It asks for an OpenAI API key once in a hidden getpass prompt; use an API key, not your ChatGPT password. The key is held only in the active Colab runtime and is not written into the notebook or its output.

After entering the key, type an everyday object at the prompt. The notebook sends it to the OpenAI Responses API using gpt-6-luna and displays exactly three numbered, unusual but practical ideas. It then asks for another object without restarting the cell. Type quit to stop the loop.

The notebook displays clear messages for empty responses and common API errors. It does not print the raw error details, so the key is not exposed in error output. Each object you submit makes a separate API request.

For reference, see the GPT-6 Luna model documentation (https://developers.openai.com/api/docs/models/gpt-6-luna) and the OpenAI Python SDK documentation (https://developers.openai.com/api/reference/python).
