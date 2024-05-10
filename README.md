# POC

You need to set an OPENAI_API_KEY environment variable with your OpenAI API key.

you also need to set an env var for the digital ocean token, GPTSCRIPT_API_DIGITALOCEAN_COM_BEARER_AUTH

Because you might want to create SSH keys or something pass in a workspace so you can get the keys after you are done chatting.

```bash
gptscript --workspace=./workspace ./chatbot.gpt
```
