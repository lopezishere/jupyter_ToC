Jupyter Notebook Table of Content
=================================

Original code taken from [kmahelona](https://github.com/kmahelona/ipython_notebook_goodies)

Make a table of contents for your notebook. Uses headings (e.g. H1, H2, etc.) to build TOC, 
and provides anchors (added where needed).

**Usage:** 

1. Add a *markdown* cell at the top of your notebook with the following:
```
<h1 id="tocheading">Table of Contents</h1>
<div id="toc"></div>
```

2. Add a *code* cell anywhere in the notebook with the following

	2.1. For a ToC with roman numbers numeration (original from kmahelona)
```
%%javascript
$.getScript('https://kmahelona.github.io/ipython_notebook_goodies/ipython_notebook_toc.js')
```

	2.2. For a ToC without any index number automatic generation
```
%%javascript
$.getScript('https://kmahelona.github.io/ipython_notebook_goodies/ipython_notebook_toc.js')
```


# Changelog
> Added a new version that creates the ToC without the roman index number. Useful in case you add the number manually to differenciate two anchors.
ipython_notebook_toc_noIndex.js