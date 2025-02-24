# Graph-Property-Dataset

Graph property dataset, there are four folders containing a total of 352 sub-datasets.

## GraphRandom-Train
* The dataset in this folder includes all positive samples where the graph node number equals the base size for each property. 
* Negative samples are obtained by randomly selecting the same number of graphs as the positive samples.
* There is one dataset for each property, with a total of 16 datasets.

## GraphRandom-Test
* The dataset in this folder contains 10 datasets for each property, where the graph node number ranges from base size + 1 to base size + 10.
* Each dataset consists of 5,000 randomly selected positive samples and 5,000 negative samples, totaling 10,000 graphs per dataset.
* With 10 datasets per property and 16 properties in total, there are 16 × 10 = 160 datasets.

## GraphPerturb-Train
* Compared to the GraphRandom dataset, the GraphPerturb dataset includes graphs with highly similar structures due to a different method of selecting negative samples.
* The datasets in this folder contain all positive samples where the graph node number equals the base size for each property. 
* Instead of selecting negative samples randomly, they are generated using a specific algorithm to create graphs that are structurally highly similar to the positive samples.
* There is one dataset for each property, with a total of 16 datasets.

## GraphPerturb-Test
* The datasets in this folder also contain highly structurally similar graphs, with 10 datasets per property, where the graph node number ranges from base size + 1 to base size + 10.
* Each dataset consists of 5,000 randomly selected positive samples and 5,000 negative samples generated using a specific algorithm, totaling 10,000 graphs per dataset.
* With 10 datasets per property and 16 properties in total, there are 16 × 10 = 160 datasets.