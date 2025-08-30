# word2vec-demo
Word2vec using Amazon food reviews dataset


## Quick Start

### Locally
You need first install a python environment using [uv](https://docs.astral.sh/uv/). If you want to know more about UV, check [this video](https://www.youtube.com/watch?v=k0F9YaAbNwo).
```
brew install uv
```

then initiate env to create environment (.venv)
```
uv venv
```

Activate it, VSCode/Cursor will recognize .venv automatically
```
source .venv/bin/activate
```

It is advised to run below to resolve package dependency and exact version resolution
```
uv lock
```

Install the language model for english
```
uv run python -m spacy download en_core_web_md
```

Activate [`pre-commit`](https://pre-commit.com/)hooks to format your code and enforce a consistant coding style
```
uv run pre-commit install
```
