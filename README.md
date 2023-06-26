# Visualizing Overlapping Biclusterings and Boolean Matrix Factorizations (plots)

This archive contains additional plots for the paper (to be published)

## Additional plots
The plots are organized in the following fashion. They are first grouped in folders by dataset. Then, every dataset file is named using the following pattern:
```
<dataset_name>-<clustering_algorithm>-<visualization_algorithm>-k<number_of_clusters>-snTrue.pdf
```

- `dataset_name`: The name of the dataset
- `clustering_algorithm`: The name of the clustering algorithm
- `visualization_algorithm`: The name of the visualization algorithm
- `number_of_clusters`: The number of clusters used in the clustering algorithm
- `snTrue`: We use the post-processing technique

Every visualization file contains 3 plots, which are (from left to right):

- The original dataset,
- The ordered dataset with the new color scheme from the paper,
- The ordered dataset whithout the color scheme.

## Additional results
In addition, there is a compressed folder `results.zip`, containing objective function values from the discussed objective functions in the paper.
Every file is a csv file, and regroups all the scores for the different visualization algorithms, as well as running time.
The result files are named following the pattern:
```
<dataset_name>-<clustering_algorithm>-<number_of_clusters>-snTrue.csv
```
