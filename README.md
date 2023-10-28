# resume
LaTeX template for my personal resume

Based off of [jakegut/resume](https://github.com/jakegut/resume/)

# Building
Use the [texlive](https://hub.docker.com/r/texlive/texlive) image to build the pdf with `pdflatex`

```
docker run -it -v $PWD:/workdir -u 1000   texlive/texlive pdflatex resume.tex
```
