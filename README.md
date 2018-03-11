# Journals
...because keeping track of journal formatting can be difficult.

## LaTeX templates
- [Nature](https://ctan.org/tex-archive/macros/latex/contrib/nature/)

```latex
\documentclass{nature}
\bibliographystyle{naturemag}
```

- [ACM](http://www.latextemplates.com/template/acm-publications)
```latex
\documentclass{acmsmall}
\bibliographystyle{ACM-Reference-Format-Journals}
```

## Repository of LaTeX Templates
[Here](http://www.latextemplates.com/cat/academic-journals)

## Adding LaTeX Templates

**Step 1** 
In order to add new templates to `LaTex`, add `.tex` and `.cls` files to `/usr/local/texlive/2017/texmf-dist/tex/latex/` directory and `.bst` files to `/usr/local/texlive/2017/texmf-dist/bibtex/bst/`. **Note**: you may have to run `sudo` in order to move these files into these directories.

**Step 2**
Once the files are in the appropriate locations run: 

```bash
sudo texhash
```

This should add these to the `ls-R` file.

#### Helpful Links
[Adding `sty` file](https://tex.stackexchange.com/questions/10252/how-do-i-add-a-sty-file-to-my-mactex-texshop-installation)

[Using `pandoc` to convert `.tex` to different file types](https://jabranham.com/blog/2016/11/using-pandoc-export-to-word/)

## Using LaTeX in Jupyter Lab

Jupyter Lab provides the capability to automatically render `.pdf` documents when editting `.tex` files. [Here](https://github.com/jupyterlab/jupyterlab-latex) is a link to the `jupyterlab_latex` extension.

`jupyterlab-drawio` also [provides convenient functionality for creating diagrams in jupyter lab](https://blog.jupyter.org/a-diagram-editor-for-jupyterlab-a254121ff919).
