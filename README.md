# Cytoscape.js rendering and layout performance test page

This repo serves as a common testing environment for performance testing of Cytoscape.js with respect to layouts and rendering.

## Cytoscape.js testing

To test against a local build of Cytoscape.js (i.e. an in-progress version), clone the repo and replace the `<script>` reference with a local build.

To test against the latest official release of Cytoscape.js, the page can be viewed live [on Github pages](https://cytoscape.github.io/js-perf).

Stats are logged to the console.

## Cytoscape desktop software

This repo can be used for comparisons between Cytoscape and Cytoscape.js.  The graph data (JSON) can be loaded in an app using Cytoscape.js or in the Cytoscape desktop software.

To load a graph in the Cytoscape desktop app, import one of the JSON files included in the repo.

File > Import > Network > File > fileName.json 