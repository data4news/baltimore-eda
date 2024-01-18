# quarto-quickstart

Python + R notebook using [Quarto](https://quarto.org/docs/get-started/)!

Example notebook: http://dhrumilmehta.com/quarto-quickstart



## Installation

1. Install Quarto https://quarto.org/docs/get-started/ (check out both steps of the installation guide)
2. Open and run the `quarto-quickstart.qmd` notebook to make sure your setup is working correctly
3. Install Python packages `pip install -r requirements.txt`
4. Install R packages `RScript setup.R`

## Exploratory Data Analysis

1. Follow the steps in `eda_notebook.qmd`

**note** 

You may need to re-install python. This setup doesn't work if Python wasn't installed with the `--enable-shared` option. I had to first uninstall python and then re-install it with the `--enable-shared` option. Since I use pyenv, I installed it as follows:

```
env PYTHON_CONFIGURE_OPTS="--enable-shared" pyenv install 3.11.2
```
