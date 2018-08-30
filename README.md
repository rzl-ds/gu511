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
case, there are a number of options -- I will outline here two that I think are
pretty convenient


### Microsoft Azure Notebooks

you may clone any repository using
[Microsoft Azure Notebooks](https://notebooks.azure.com) (this is a preview
service offered by Microsoft which allows you to run all of the notebooks
contents on a remotely provisioned Azure server). in particular, you may create
a library by cloning from `github`.

the advantage of going with ms azure notebooks is that it won't involve any
changes to your local machine -- no download of the lecture files, no `python`
environment setup. for many, this may be preferable.

in order to do this:

1. create an account
1. add a "library" (ms azure notebook's name for a collection of notebooks)
1. on the "create new library" popup, switch from the "New" tab to the "From
    GitHub" tab
1. fill in the details as seen in the picture below
1. highlight the lecture you wish to run and click the "play" button

<div align="center"><img src="http://drive.google.com/uc?export=view&id=12MVRpuzK2p6X4THSxmRADd3nnxa_QoIM"></img></div>

**warning** the RISE slideshow integration is buggy. try it out, but be ready to
force-quit your browser.


### running locally

if you would like to run these locally, you simply need to download the files
and make sure your local `python` environment meets the pre-requisites. the
primary requirement is that you be running `python` version 3.4+, and that you
have the `jupyter` package installed. in addition to that you will likely need
to install different packages in order to execute different notebooks, and I
suggest you use an environment manager for that (specifically, `conda` or
`pip` and `virutalenv`). for more details on exactly how to do that, refer to
the `python` lecture in this repository.
