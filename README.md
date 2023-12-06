# decision-tree
## First experiment:
### Training and Testing with Fixed Train-Test Split Ratio:
<ul>

<li>Divide the dataset into a training set and a testing set (30% of the samples).</li>
<li>Repeat this experiment five times with different random splits of the data into training 
and test sets.</li>
<li>Report the sizes and accuracies of the decision trees in each experiment, Compare the 
results of different models and select the one that achieves the highest overall 
performance</li>
</ul>

## Second experiment:
### Training and Testing with a Range of Train-Test Split Ratios:
Consider training set sizes in the range of 30% to 70% (increments of 10%). Start with a 
training set size of 30% and increase it by 10% until you reach 70%.
#### For each training set size:
<ul>
<li> Run the experiment with five different random seeds</li>
<li> Calculate the mean, maximum, and minimum accuracy at each training set size.</li>
<li> Measure the mean, maximum, and minimum tree size.</li>
<li> Store the statistics in a report.</li>
<li> Create two plots: one showing accuracy against training set size and another showing 
the number of nodes in the final tree against training set size.</li>
</ul>
