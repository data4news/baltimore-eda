# baltimore-eda

Hello and welcome to Frontiers of Computational Journalism with Dhrumil Mehta and Nick Thieme! We're excited to work with you this year.

This is the first assignment of the class, and the goal is to both get a sense of how you think about telling stories off of data and to get you introduced a bit to Baltimore, which will be the focus of our first assignment (Nick is a data journalist in Baltimore).

To get started, please clone this repository and follow the steps in `eda_notebook.qmd`. If you don't already have Quarto installed, please follow the steps below. See you soon! 

# Setup

Using Python and R in the same notebook with quarto! 

Example notebook: http://dhrumilmehta.com/quarto-quickstart

## Installation

1. Install Quarto https://quarto.org/docs/get-started/ (check out both steps of the installation guide)
2. Open and run the `quarto-quickstart.qmd` notebook to make sure your setup is working correctly
3. Install Python packages `pip install -r requirements.txt`
4. Install R packages `RScript setup.R`

**note:** 

You may need to re-install python. This setup doesn't work if Python wasn't installed with the `--enable-shared` option. I had to first uninstall python and then re-install it with the `--enable-shared` option. Since I use pyenv, I installed it as follows:

```
env PYTHON_CONFIGURE_OPTS="--enable-shared" pyenv install 3.11.2
```
