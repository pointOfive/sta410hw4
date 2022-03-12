# UofT STA410/2102 Statistical Computation

Return to STA410 Programming Portfolio Parent Repository [here](https://github.com/pointOfive/STA410_HW/blob/master/README.md#uoft-sta4102102-statistical-computation).

## Submitting Programming Portfolio Assignment 4
Submit `sta410hw4.ipynb` on [MarkUs](https://markus-ds.teach.cs.toronto.edu/) before the end of the calendar day (EoD) on the due date.

## Programming Portfolio Assignment 4

[Programming Portfolio Assignment 4](sta410hw4.ipynb) addresses sampling from statistical distributions using PyMC3, TensorFlow, and classes and custom code.

1. (Bayesian) probabilistic programming is introduced through the official PyMC3 tutorial
2. Adaptive (squeezeed) rejection sampling is introduced through a custom python class
3. Hidden Markov models are fit via sequential importance sampling with bootstrap resampling 
4. Normalizing flow (bijection) generative modeling of arbitrary distributions is demonstrated

### Accessing Programming Portfolio Assignment 4
UofT students may access this the collection of programming problems with the [UofT JupyterHub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw4&branch=main) or [UofT JupyterLab](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw4&branch=main&urlpath=/lab/tree/sta410hw4) via

> [JupyterHub] https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw4&branch=main
>
> [JupyterLab] https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw4&branch=main&urlpath=/lab/tree/sta410hw4

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).
If for some reason JupyterHub/Lab is not loading the repository, you can delete and reload repositories (after downloading and saving your work).  

> From JupyterHub/Lab, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.

Alternatively, the programming problems may also be accessed without UofT authentication using [Google Colab](https://colab.research.google.com) via

> https://colab.research.google.com/github/pointOfive/sta410hw4/blob/main/sta410hw4.ipynb

***If you're working in some other environment, 
the versioning there must support [notebook format 4.5](https://github.com/jupyterlab/jupyterlab/issues/9729), e.g., 
[JupyterLab >= 3.0.13](https://github.com/jupyterlab/jupyterlab/releases/tag/v3.0.13) (for "JupyterLab UI")
or [Jupyter Notebook >= 6.2](https://jupyter-notebook.readthedocs.io/en/stable/changelog.html#changelog) (for "Jupyter classic UI"); 
otherwise, your notebook cell-ids will not be supported and you will not get any credit for your submitted work.***

> You may check if cell ids are present or changing at each save with `! grep '"id":' <path/to/notebook>.ipynb`
