# Synthetic handwritten Groningen Meaning Bank (GMB) dataset

Dataset of synthetically generated handwritten pages intended for research on
full page text and entity recognition. The data was generated using the tool in
https://github.com/manucarbonell/handwritten-document-synthesizer and data taken
from https://gmb.let.rug.nl/.

This dataset was developed for the following
[paper](https://arxiv.org/abs/1912.10016). If you use this dataset in your
research, please cite the origin of the data [The Groningen Meaning
Bank](https://www.let.rug.nl/bos/bibtex/Bos2017GMB-bib.html) and
[cite](CITATION.cff) the paper:

    Manuel Carbonell, Alicia Fornés, Mauricio Villegas, and Josep Lladós. "A
    neural model for text localization, transcription and named entity
    recognition in full pages." Pattern Recognition Letters 136 (2020): 219-227.

Use [nw-page-editor](https://github.com/mauvilsa/nw-page-editor) to visualize
the xmls. To get a nicer visualization of the annotated entities load the css
included in this repository as follows: `nw-page-editor --css
code/nw-page-editor-entities.css data`.
