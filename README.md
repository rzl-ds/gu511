# Georgetown University Math & Statistics 511

the `jupyter` notebooks in this repository form the lecture notes for the GU511
course. like any `jupyter` notebook, they exist in two states:

1. rendered: click on any of the `.ipynb` files in the repo above and you will
   be taken to a `github`-rendered version of the notebook for your own use
2. executable: load any of these `.ipynb` files into an active `jupyter`
   notebook server session


## advanced usage: running these notebooks

### Microsoft Azure Notebooks

All of these notebooks are also hosted on
[Microsoft Azure Notebooks](https://notebooks.azure.com/rzachlamberty/libraries/gu511) (a
preview service offered by Microsoft which allows you to run all of the
notebooks contents on a remotely provisioned Azure server).

This setup is recommended for most users -- you won't need to create a new
environment to run these commands, nor install any software locally. Thanks,
Microsoft!


## running locally

if you would like to run these locally, you need to make sure your environment
meets the requirements listed in `environment.yml`. if you are using the `conda`
package manager, you can make sure this is the case by creating an environment
based on that `environment.yml` file.

To create a new environment from scratch, within the directory of this
repository run

```bash
conda env create -f environment.yml [--name YOUR_NAME]
```

this will create an environment (named `gu511` by default, or `YOUR_NAME` if you
pass your own via the `--name` command line flag) and install the needed
dependencies into that environment.

with some regularity you should also update that created environment to pick up
any new dependencies or version updates. if the environment already exists, you
can simply run

```bash
conda env update -f environment.yml [--name YOUR_NAME]
```
