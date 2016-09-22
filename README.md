# LaTeX Template for Thesis

This LaTeX template can be used as a starting point for a bachelor thesis or term project (BA/SA) at HSR.

Here's an [example](main.pdf) of the generated PDF.

## Usage on OSX

1. install a TeX distro

  1. run `brew cask install mactex`

  1. enable it in your shell by adding the following lines to your `~/.zshrc` or the like:
     
     ```sh
# MacTex
PATH="$PATH:/usr/local/texlive/2016/bin/x86_64-darwin"
MANPATH="/usr/local/texlive/2016/texmf-dist/doc/man:$MANPATH"
```
     (Maybe you'll have to adjust the path when using a version >2016.)
     
  1. reload your shell config with `. ~/.zshrc` or just open a new shell

1. clone this repo with `git clone git@github.com:paddor/hsr_thesis_template.git`

1. compile
  1. change directory with `cd hsr_thesis_template`
  1. run `make`
  1. open generated PDF with `open main.pdf`

1. edit and recompile with `make` (sometimes a `make clean` is needed)
