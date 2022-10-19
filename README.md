# Accumulation Score

Analysis of abundance or depletion of a given interaction compared to random. One partner of a given interaction is kept constant.

### Example:   
Study of two celltypes (e.g. astrocytes and neurons). Number of neurons is counted in the neighborhood with a radius of maxDistNeighbor of each astrocyte. The labels are then shuffled n_combinations times and the number of neuron in astrocyte neighborhood is counted for each shuffle. The count of the unshuffled data is expressed as a z-score of the shuffled count distribtuion. The labels of cells classified as astrocyte are not shuffled.

### Example data set:  
Multi-channel image data of one core was analyzed in QuPath, as demonstrated in https://www.youtube.com/watch?v=WTAgXpuuqNY.
Detection Measurements were exported as a .txt-file. The exported results file list the cells in one core, characterized by their position in X- and Y (in micrometer) and a cell class.

The code can be re-used according to license: BSD-3-Clause.  
October 2022, Anna Klemm, BioImage Informatics Facility, SciLifeLab/NBIS, biif@scilifelab.se
