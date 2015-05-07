Python examples for working with stratigraphic data from Stratigy
=================================================================

This repository contains example code in the form of IPython Notebooks
(now also known as [Jupyter Notebooks](http://jupyter.org/)).

The examples load data from [Stratigy](http://stratigy.danielkerkow.de), a
key-value based representation of stratigraphical data in a PostgreSQL
database, with a web frontend written in Python, and a JSON-based API.

For working with stratigraphic data with Stratigy, follow these simple
steps:

 - go to [stratigy.danielkerkow.de](http://stratigy.danielkerkow.de) and create
 a site representing the location of your stratigraphical record
 - enter your stratigraphical records for this site
 - clone this repository or download the notebook
 - install Python and the required packages
 - start the notebook and substitute the Site-ID with your own
 - start playing!

 ## Install Python and the required packages

 For __Windows__ users, I recommend using the Anaconda Python distribution.

 On __Linux__, Python should be already preinstalled. However, I
 recommend creating a
 [virtual environment](https://virtualenv.pypa.io/en/latest/)
 and installing the packages in there, to avoid conflicts with
 system packages.

__Requirements__

The example code needs the following Python extensions, which you can
install for example with `pip install <package>`:

- matplotlib
- pandas


## Cloning and starting the notebook

When you have Python and the dependencies installed, clone this repo and
start the notebook server locally:

```bash
# clone it
git clone https://github.com/dkerkow/stratigy_demo_ipython.git

# change into the repo folder
cd stratigy_demo_ipython

# start the notebook
ipython notebook
```
You should then see a browser tab opened showing the available notebooks
in the folder. Open one of it and start exploring.
