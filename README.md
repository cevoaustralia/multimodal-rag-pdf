# Multimodal RAG with PDFs

PDFs will contain text, tables and images. This project aims build a RAG system that handles this with the help of multimodal language models.

- text will be handled by a text LLM
- tables will be handled by a text LLM
- images will be handled by a multimodal LLM


# Environment setup and installation
- use `pyenv` to manage python versions
- use `venv` to manage your virtual environments

```bash
pyenv versions
pyenv install 3.12.2
pyenv local 3.12.2
python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
```

