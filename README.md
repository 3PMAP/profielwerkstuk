# profielwerkstuk
This repo contains the markdown source files for our paper. It's written in markdown, though heavenly injected with LaTeX. 
This is because we use [pandoc](http://pandoc.org) for converting: markdown -> LaTeX -> pdf.

This repo:
- 00_*.md kind of files are the source files. They will all be squashed together and converted when running:
- **create**. It's a 'bash script' (well...) which just runs pandoc with all given commands. So you can make use of:
- **`bib/`**. Here is the bibtex file. Also a csl file for apa style.
- `img/` contains all images.
- [prothesehand.pdf](https://github.com/3PMAP/profielwerkstuk/blob/master/prothesehand.pdf) is the output file. The result. El resultado. Exitus.
