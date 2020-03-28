# TopoCut

Some code for creating svg files from DEM data in order to make relief models.


## Installation instructions:

1. Clone the repository.

`$ git clone https://github.com/kcaylor/topocut.git`

2. Install requirements.

`$ pip install -r requirements.txt`

3. Start JupyterLab

`$ jupyter lab`

4. Run the notebook `ExtractDEM.ipynb`


## TODOs:

1. Make a CLI for the code so notebook isn't needed.

2. Figure out how to edit SVG files so that we can remove the fill color and set the path thickness to the cut line thickness for laser cutters. This could happen before or after export, depending on the approach. May be possible with Matplotlib, but it wasn't obvious so I gave up.

### Additional Notes:

1. Inkscape is a free utility for working with SVG files on a Mac:

`$ brew cask install inkscape` 

