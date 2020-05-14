# Docker Environment for Google Cirq

Everything needed to hit the ground running with Google Cirq.

## Motivation

Google already provides a (rather bloated) Docker image for their Cirq framework but it does not include Jupyter Notebooks, a tool that I love using to keep track of any new discoveries or neat code snippets.

## Architecture

Builds heavily off of Quantum Computing at Davis' [Hephaestus](https://github.com/Quantum-Computing-at-Davis/Hephaestus) environment series, based off of Alpine Linux with Conda built-in.

## Usage

Copy and paste the `Dockerfile` and `docker-compose.yml` to a directory of your choice and just run:

```
docker-compose up
```

then copy-paste the Jupyter Notebook URL into the browser of your choice.