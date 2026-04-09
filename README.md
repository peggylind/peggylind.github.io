# PersonalWebsite
Dev repo for my personal website

built with [Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) theme and [HUGOBlox](https://hugoblox.com/).

### local test
`pnpm dev`

### build deployment
`hugo -d ../peggylind.github.io/`

### automatic build publications from .bib
Uses a Python 3 modules `pip3 install -U academic`

run `academic import --bibtex ../../Downloads/peggy_refs.bib --overwrite content/publication`