# Georgetown University Math & Statistics 511

the `jupyter` notebooks in this repository form the lecture notes for the GU
MAST 511 course. like any `jupyter` notebook, they exist in two states:

1. rendered: click on any of the `.ipynb` files in the repo above and you will
   be taken to a `github`-rendered version of the notebook for your own use
2. executable: load any of these `.ipynb` files into an active `jupyter`
   notebook server session


## running these notebooks

in addition to simply reading these notebooks as presented here on github, you
may want to execute the contents in a real `python` session. if that is the
case, there are a number of options -- I will outline two that I think are
convenient


### google colab

you may automatically access this (or any) `github` repository using 
[Google Colab](https://colab.research.google.com). when you open that link, you
will be prompted to pick a notebook -- click on the `github` tab and use
https://github.com/rzl-ds/gu511 as your url.

<div align="center"><img src="http://drive.google.com/uc?export=view&id=1izBXgctCgrZGsme9nqmOmCmKp6kMG_6O"></img></div>

google will then create virtual machines with complete environments for running
that notebook -- you don't have to do anything. all you need is a google account
and your your georgetown.edu accounts will do.

*note*: this will launch the notebooks but you won't be able to do the super
`l33t` `RISE` slide show view I do in class. 


### running locally

if you would like to run these notebooks locally, you simply need to download 
the files and make sure your local `python` environment meets the 
pre-requisites. the primary requirement is that you be running `python` version
3.4+, and that you have the `jupyter` package installed. in addition to that you
will likely need to install different packages in order to execute different 
notebooks, and I suggest you use an environment manager for that (specifically,
`conda` or `pip` and `virutalenv`). for more details on exactly how to do that, 
refer to the `python` environment lecture in this repository.