# Welcome!

Welcome to our repository for our word embeddings and AI workshop.  To make this more accessible to participants, we have three options available for hands-on participation.  If you would like to just see the rendered notebooks, you can see them here:

<https://comet.arts.ubc.ca/docs/econ_adv/02_word_embeddings/02_word_embeddings.html>

## How to Use these Notebooks

We have set-up this workshop with three options for use:

1.  Use them as part of our [JupyterOpen](https://open.jupyter.ubc.ca/) hub, via your web-browser.  This option requires a [UBC Campus-Wide Login (CWL)](https://www.myaccount.ubc.ca/myAccount/)
2.  Use the via [Google Colab](https://colab.google/), again in your web-browser.  This option requires a Google Account.
3.  Use them locally, by installing [RStudio](https://posit.co/downloads/), [R](https://cran.rstudio.com/), and [Python](https://www.python.org/downloads/). 

## Option 1: Jupyter Open

This is the simplest option, but it does require a CWL.  To do this click here:

<https://open.jupyter.ubc.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fubcecon%2Fai-workshop&urlpath=lab%2Ftree%2Fai-workshop%2F&branch=main>

And log in with your CWL credentials.  You will need to install some packages as part of this project.  To do this, you open a terminal in the Launcher and type in:

```
bash setup-r.sh
```

If you're using R or:

```
bash setup-py.sh
```

If you're using Python and hit `enter`.  This will run, and can take a few minutes to complete.

## Option 2: Google Collab

This is also straightforward.  To do this, click this link:

<https://colab.research.google.com/github/ubcecon/ai-workshop/blob/main/>

And log-in with your Google Account:

* Select the version `Word2vec_Workshop_R_Version_collab` which is designed for Google Collab
* At the top, click *"Copy to Drive"* to move it to your own drive.
* You may also need to install packages; make the the `install.packages` commands are uncomments and run them. It's slow.  Give it a minute.

_Special thanks to Eric Daigle for setting this up_

## Option 3: Run Locally

The final option is the most complex, but can be run locally on your hardware.

* Before you get started, download and install: [RStudio](https://posit.co/downloads/), [R](https://cran.rstudio.com/), and [Python](https://www.python.org/downloads/).
* Next, download and extract the workshop files at this link: <https://github.com/ubcecon/ai-workshop/archive/refs/tags/0.5.zip>
* Finally, open the `.qmd` version of your notebook, and run the install block.
