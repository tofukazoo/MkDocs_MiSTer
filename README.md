# MkDocs_MiSTer
A work-in-progress replacement for the MiSTer FPGA Github Wiki.

In order to contribute to this documentation repository first please read the instructions on MkDocs' website --> https://www.mkdocs.org/user-guide/writing-your-docs/

Try your best to follow along with the general structure of folders (categories) and the quality of the articles. Remember, quality over quantity. :)

It's very easy to contribute, just fork this repo, make your changes (such as making a new markdown file or editing one) and follow normal markdown syntax, commit changes to your fork, submit your pull request, and we will review it to see if it's suitable to merge.

**IMPORTANT!** Always use relative URLS when possible! Anything in this repo should be linked using relative URLS! e.g. `/assets/logo_small.png` and NOT this `https://raw.githubusercontent.com/birdybro/MkDocs_MiSTer/main/docs/assets/logo_small.png`.

To temporarily view your changes as a test locally --> https://www.mkdocs.org/user-guide/deploying-your-docs/#local-files

## Prerequisites and deploying a local environment

* Python 3
* Pip

Make sure you update [python 3](https://www.python.org/downloads/) and [update pip](https://pip.pypa.io/en/stable/installation/).

`cd` into the root folder of this repo

```
pip install mkdocs
pip install mkdocs-material
pip install mkdocs-minify-plugin
pip install mkdocs-redirects
```

Deploy to local server from that root folder:

```
mkdocs serve
```

And it should give you a weburl in the terminal to go to, http://127.0.0.1:8000
