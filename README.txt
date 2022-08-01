The ipynb file has the code required to run the spectral triadic decomposition algorithm. The input format is REQUIRED to be an edgelist, ideally in a .txt or .edges file. Data should be reformatted accordingly, or the code responsible for reading should be modified to accommodate changes. 

The code outputs clusters of vertices saved in the clusters.pickle file. It also calculates some relevant statistics. Storage required to compute this code: enough space to store lists of triangles, lists of edges, and lists of vertices. The code has been run on Python 3.7.6, and requires the following packages:

numpy
scipy
math
operator
matplotlib
datetime
tqdm
functools

The first cell of the ipython file should import all necessary packages for you. Subsequently the file is subdivided into sections for preprocessing, functions for cleaning, extraction and statistic calculation, and the main which calls these processes to carry out the extraction.

Additional downstream tasks would benefit from other common packages such as itertools, random, pandas and networkx.
