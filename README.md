# cyberjapan-explorer

A [Tangram](http://github.com/tangrams/tangram) map based on a dataset from the Geospatial Information Authority of Japan: https://github.com/gsi-cyberjapan/vector-tile-experiment/blob/gh-pages/README_en.md.

Live demo: http://meetar.github.io/cyberjapan-explorer

Roll over a feature to show its properties.

Click a feature to select its properties, and filter.

Or, enter text by hand to filter.

### To run locally:

Start a web server in the repo's directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to: [http://localhost:8000](http://localhost:8000)

