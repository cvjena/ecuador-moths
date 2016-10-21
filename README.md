# Ecuador Moth Dataset

This folder contains the Ecuador moth dataset prepared for the evaluation
of fine-grained recognition approaches. If you use this dataset, please 
cite the corresponding paper:

Erik Rodner, Marcel Simon, Gunnar Brehm, Stephanie Pietsch,
J. Wolfgang Waegele, and Joachim Denzler. 
Fine-grained Recognition Datasets for Biodiversity Analysis. 
CVPR Workshop on Fine-grained Visual Classification (CVPR-WS). 2015.

and the original paper of

Gunnar Brehm, Patrick Strutzenberger, and Konrad Fiedler.
Phylogenetic diversity of geometrid moths decreases with elevation 
in the tropical andes. Ecography, 36(11):1247–1253, 2013.

For more details visit the website of the project:
http://www.inf-cv.uni-jena.de/fgvcbiodiv


## Directory Information

- ``images/``
    The images as provided by Brehm et al

- ``imagelist.txt``
    The filenames relative to the dataset directory.
    Each line contains a separate image.

- ``labels.txt``
    The class IDs for each image in imagelist.txt. Each line
    in labels.txt corresponds to the image in the same line
    in imagelist.txt

- ``tr_ID.txt``
    The train-test-split for each image in imagelist.txt. Each line
    in tr_ID.txt corresponds to the image in the same line in 
    imagelist.txt. A value of 1 means, this image is used for training,
    a value of 0 means this image is used for testing.
