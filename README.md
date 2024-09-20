# CCSS - Word Embeddings Workshop 

> Working with AI for Humanities and Social Science Research: Python and R for Word Embeddings and Language Models
> UBC, September 2024

Welcome to our repository for our word embeddings and AI workshop.  To make this workshop more accessible to participants, we have three options available for hands-on participation.  However, if you do not want to code-along with, and you would like to just see the rendered notebooks instead, you can see them here:

* [Link to rendered notebooks](https://comet.arts.ubc.ca/docs/4_Advanced/advanced_word_embeddings/advanced_word_embeddings_python_version.html)

## Options for Using these Notebooks

There are three options in the workshop to code along with us during the session:

1.  Use them as through our [JupyterOpen](https://open.jupyter.ubc.ca/) hub, via your web-browser.  This option requires a [UBC Campus-Wide Login (CWL)](https://www.myaccount.ubc.ca/myAccount/)
2.  Use them via [Google Colab](https://colab.google/), again in your web-browser.  This option requires a Google Account.
3.  Use them locally (on your computer), by installing [RStudio](https://posit.co/downloads/), [R](https://cran.rstudio.com/), and [Python](https://www.python.org/downloads/).

### Option 1: Jupyter Open

This is the simplest option, but it does require a CWL.  To do this click here:

* [Launch Notebook](https://open.jupyter.ubc.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fubcecon%2Fai-workshop&urlpath=lab%2Ftree%2Fai-workshop%2F&branch=ccss-2024)

And then log in with your CWL credentials.  

You will then need to install some packages to run the notebooks part of this project.  To do this, open a new terminal in the Launcher, or click `File > New > Terminal` and then type in:

```
bash path\to\setup-py.sh
```

and hit `enter`.  This will run, and can take a few minutes to complete.

### Option 2: Google Colab

This is also straightforward.  To do this, click this link:

<https://colab.research.google.com/github/ubcecon/ai-workshop/blob/ccss-2024/>

And log-in with your Google Account:

* Select the version `advanced_word_embeddings_python_colab_version.ipynb` which is designed for Google Colab.
* Make sure you run the top-most set-up cell before starting.

_Special thanks to Eric Daigle for setting this up_

### Option 3: Run Locally

The final option is the most complex, but the notebooks can be run locally on your hardware.

* Before you get started, download and install: [RStudio](https://posit.co/downloads/), [R](https://cran.rstudio.com/), and [Python](https://www.python.org/downloads/).
* Next, download and extract the workshop files at this link: <https://github.com/ubcecon/ai-workshop/archive/refs/heads/ccss-2024.zip>
* Finally, open the `.qmd` version of your notebook in RStudio, from the `local` folder and run the install block.
