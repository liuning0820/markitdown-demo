# README

## Usage

```sh

uv venv --python=3.11 .venv
# For Windows
source .venv/Scripts/activate
# For Mac & Linux
source .venv/bin/activate
# NOTE: Be sure to use 'uv pip install' rather than just 'pip install' to install packages in this virtual environment
uv pip install 'markitdown[all]'
uv pip install 'markitdown[pdf, docx, pptx]'

markitdown path-to-file.pdf -o document.md

```

## Reference

[MarkItDown GitHub Repository](https://github.com/microsoft/markitdown)