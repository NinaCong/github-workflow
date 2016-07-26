# Template
Below is both a template for the README files in each Github repository, as well as a fully-filled out example. Please keep in mind that the code snippet to be pasted into the Wordpress post needs you to paste in the project's repo-name TWICE.

## [INSERT year-slug]
[INSERT Description of what this project is.]

[INSERT Link to the published version of this project on Github.]

Paste this into your Wordpress post:

```
<div id="github-container"></div>
<script> var pymParent = new pym.Parent("github-container", "//medillcherubs.github.io/[INSERT year-slug]/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/[INSERT year-slug]/edit/gh-pages/index.html -->
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```


# Full Example
A completely functional and filled-out example of a Cherub Github repo README.

## 2016-homepage-slideshow
Slideshow at the bottom of the homepage

https://medillcherubs.github.io/2016-homepage-slideshow/

Paste this into your Wordpress post:

```
<div id="homepage-slideshow"></div>
<script type="text/javascript" src="//www.cherubs2015.org/wp-content/themes/cherubs-2015/js/vendor/pym.min.js"></script> <script> var pymParent = new pym.Parent("homepage-slideshow", "//medillcherubs.github.io/2016-homepage-slideshow/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-homepage-slideshow/edit/gh-pages/index.html -->
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
