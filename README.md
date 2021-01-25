# Introduction
[Textograph](https://github.com/textograph/textograph) is a web-base application for creating tree-view diagrams from PDF file or any text (by human, not automatic).
the created graph can be uploaded to your own server or saved as an html file. 
![textograph anki](img/image.png?raw=true)

# Features
* Creating tree graph from text
* Supports both plain text and PDF as input source
* Export graphs to anki flash card program
* Save Graphs to remote server
* Add pdf references to nodes **(new)**

# Dependencies
The code for creating graphs came from awesome [D3js](https://github.com/d3/d3) library and [radial tree](https://observablehq.com/@d3/radial-tidy-tree) and [collapsible tree](https://observablehq.com/@d3/collapsible-tree) implementations.
# How to use
1. [Download](https://github.com/textograph/textograph/releases) this repo and unzip it or clone this repository into your desired directory using git:
  ```
  git clone https://github.com/textograph/textograph.git
  ```
2. open index.html with your web browser (tested on Fireforx and Chrome). there is an online test version at [here](http://test.textograph.digitaltoxicity.ir/)
3. enjoy reading the text as well as creating diagram
  - Open a PDF file using PDF button or select Edit button and paste text into dialog and press ok
  - select a text and create two children nodes (forward arrow)
  - change view and zoom helps to better see the created diagrams
  - as you add more nodes to the graph, it looks better
  - selecting auto mode will enhance node creation (it needs learning curve to master using it)
4. select nodes and export to anki to review them more and more
5. save to server or disk if you wish

# How to inrteract with anki
please refer to this [link](https://github.com/textograph/anki-add-on)


# Using Web Server for Saving Graph
there is also a mini webserver developed by laravel framework to serve as an online graph saver. instructions can be found [here](https://github.com/textograph/textograph-server-docker).

# Contribution
is welcomed

# Licence
Copyright Apache version 2.0, Mahdi Saravi 2020
