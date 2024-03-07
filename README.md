# Meeting Agendas

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)]( https://daanmatch.github.io/meeting-agendas/)

![build](https://github.com/DaanMatch/meeting-agendas/workflows/deploy/badge.svg?branch=master)

## Updating Instructions

For those wishing to add their agendas to this Jupyter Book:

- Please upload content as `.md` files or `.ipynb` files to the meetings/agendas/ directory.
- Add files to the Table of Contents in the mi2s/_toc.yml file.
- Include any dependencies to the requirements.txt file.
- The book will be rebuilt and deployed automatically. Please tag @shpatrickguo in your commit or in an issue in the repository when you push changes.

## Developer Usage

### Building the book

If you'd like to develop and/or build the My Book book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `mi2s/` directory
4. Run `jupyter-book clean mi2s/` to remove any existing builds
5. Run `jupyter-book build mi2s/`

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
