# Digital Ocean ChatBot Example

## Authentication

You will need to set your `OPENAI_API_KEY` environment variable with a valid OpenAI API key.

You must create an API key in Digital Ocean and pass it to the script through this environment variable.

GPTSCRIPT_API_DIGITALOCEAN_COM_BEARER_AUTH

The ChatBot will only have access to perform actions the Digital Ocean API Key has access to. For example, you could create a new API key with read-only access to your account and use that to keep track of things that are running without making changes.

## Running the ChatBot

```bash
gptscript github.com/gptscript-ai/do-chat
```
