### javascript-notebook
A very simple self-contained javascript notebook

This is a very simple Javascript notebook in one completely self-contained HTML file. It was inspired by the concept of Jupyter notebooks.

You can enter Javascript code and execute it in the browser, completely locally and possibly offline. The performance can be pretty good.

You can put in HTML documentation and also use HTML to provide UI for simple tools.

All you need is the js+help.html file, which contains basic documentation. You can clear out the notebook and save off various javascript experiments in different files. Being able to save code and outputs is a key useful feature.

This was developed using the Chrome browser. Limited tests have been done with Firefox, and also on various OSs (Linux/Windows/Mac). The main compatibility issue is the handling of the downloading of files and how that varies in different contexts.

It is easy to extract a CSS and a JS file that could be stored separately to make for very small notebook files.

### A basic screen shot

![phi](/phi.png)

### The built-in documentation in js+help.html

![js+help](/js+help-screenshot.png)

### Trying it out

Direct link:

[js+help.html via github.io](https://timcwinkler.github.io/js+help.html)

(You can save locally.)

This link will show you the source HTML text:

[js+help.html](https://raw.githubusercontent.com/timcwinkler/javascript-notebook/main/js%2Bhelp.html)

(You can also use this link to download the file.)

The mfibo.html file is an example with a bit more content. Computing Fibo(n) using the familiar closed-form formula, but using modular arithmetic.

[mfib.html](https://raw.githubusercontent.com/timcwinkler/javascript-notebook/main/mfibo.html)

(Once again, you can use this like to download the file.)
