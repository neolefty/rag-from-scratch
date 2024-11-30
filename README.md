# RAG from Scratch

Based on this [RAG from scratch playlist](https://www.youtube.com/watch?v=wd7TZ4w1mSw&list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x) from [Lance Martin at LangChain](https://github.com/rlancemartin).

## Getting Started

Run the Jupyter Lab via Docker Compose:

```bash
$ docker compose up
```

Then open http://localhost:8888.

## Helpful

To install `voyageai` locally, and you are defaulting to python 3.13 which is "incompatible", you might need to run:

```bash
brew install pipx
pipx install --python 3.12 --include-deps voyageai==0.3.1
```
