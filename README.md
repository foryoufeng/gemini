# gemini

access google gemini api

## install uv

```sh
sudo apt update
sudo apt install pipx -y
pipx install uv
pipx ensurepath
```

## install project

```sh
uv pip install -q -U google-genai
```

## run

```sh
uv run main.py
```