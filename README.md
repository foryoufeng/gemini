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
cp .env.example .env
uv sync
```

## run

```sh
uv run main.py
```