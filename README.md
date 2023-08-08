# WTA_Benchmark
Benchmark data for the weapon target assignment problem.

Please look at the Symmetrical-Benchmark Branch for the data.

These instances were generated based on rules found in as of yet unpublished paper.
The paper citation will be provided when available.

The file format is as follows:
X: number of weapons
Y: number of targets
<A,..,An>: a list of target values. The first value is the value of target 0 and so on.
[Probability Matrix][]: A 2D matrix of destruction probabilities. The rows represent Weapons and the columns represent targets. So [0][1] is the first weapon attacking the second target. Each probability is in the range [0,1.0] 
