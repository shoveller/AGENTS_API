# Notebook API key setup

The notebook loads `OPENAI_API_KEY` from the process environment. For local
development, copy `.env.example` to `.env` and add your key:

```sh
cp .env.example .env
```

`.env` is ignored by Git. Do not put API keys in notebook cells, notebook
outputs, or commit them. If a key has already been shared or committed, revoke
it and create a replacement.