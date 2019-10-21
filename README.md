# main-training.github.io
Website for training at the Montreal AI and Neuroscience conference

Most of the content is stored in .md (and a little bit .rst) files under `source`.

The website itself is located under `build/html` and the file `index.html` simply redirects to that folder for deployment with github pages.

To update the files, install the dependencies listed in `requirements.txt` (including sphinx), and type `make html` at the root of the directory. You may have to flush the content of `build` before updating the website.
