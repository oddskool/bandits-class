# How to show the slides
## stuff
conda install -c damianavila82 rise
jupyter-nbextension install rise --py --sys-prefix
jupyter nbextension enable rise --py --sys-prefix
## presentation
jupyter nbconvert Class.ipynb --to slides --post serve
