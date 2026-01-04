# MLX Chat

A simple UI / Web / Frontend for MLX mlx-lm using Streamlit.

![](screenshot.png)

## Install

Install dependencies using [uv](https://docs.astral.sh/uv/):

```shell
$ uv sync
```

## Update

After fetching a newer version, update dependencies:

```shell
$ uv sync
```

## Run

```shell
$ uv run streamlit run app.py
```

You can also use a custom model.txt file (see [mlx-community](https://huggingface.co/mlx-community) for more models):

```shell
$ uv run streamlit run app.py -- --models mymodels.txt
```
