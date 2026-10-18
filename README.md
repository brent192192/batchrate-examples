# Batchrate examples

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brent192192/batchrate-examples/blob/main/notebooks/classify-1000-rows.ipynb)

Runnable examples for [Batchrate](https://batchrate.ai), which runs OpenAI-compatible batch jobs on open models. Everything uses the official `openai` Python package with `base_url="https://api.batchrate.ai/v1"`.

## Notebooks

| Notebook | What it does |
| --- | --- |
| [classify-1000-rows.ipynb](notebooks/classify-1000-rows.ipynb) | Labels 1,000 support tickets in one batch job with `qwen3.6-35b-a3b` and a JSON Schema response format, then checks accuracy and cost. |

You need a Batchrate API key. In Colab, add it as a secret named `BATCHRATE_API_KEY`; elsewhere, set the `BATCHRATE_API_KEY` environment variable or paste it when prompted.

## Learn more

- [batchrate.ai](https://batchrate.ai)
- [Docs](https://batchrate.ai/docs)
- [Guides](https://batchrate.ai/guides)

## License

[MIT](LICENSE)
