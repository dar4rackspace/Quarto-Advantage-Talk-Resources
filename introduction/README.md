# Introduction

- Test how to migrate your .pyndb file to qmd
	- In terminal use: `quarto convert yournotebook.ipynb` to convert it to qmd file and get the benefits of plain text!
- Render multiple formats from a single qmd or ipynb
	- To Render PDFs: ensure tinytex is installed with `quarto install tinytex`

## Python Reqs

### Mac/Linux

```
python3 -m pip install jupyter jupyterlab
python3 -m pip install matplotlib plotly
python3 -m jupyter lab hello.ipynb
```

### Windowns

```
py -m pip install jupyter 
py -m pip install matplotlib plotly
py -m pip install pyyaml
py -m jupyter lab hello.ipynb
```

## See details 

- [Hello Quarto](https://quarto.org/docs/get-started/hello/jupyter.html)
- [All Quarto Output Formats](https://quarto.org/docs/output-formats/all-formats.html)
- [Quarto for the Python User](https://www.jumpingrivers.com/blog/quarto-for-python-users/)