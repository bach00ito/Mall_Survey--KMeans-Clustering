# Mall_Survey
The algorithm will categorize the items into k groups of similarity. To calculate that similarity, we will use the euclidean distance as measurement.

The algorithm works as follows:

First we initialize k points, called means, randomly.
We categorize each item to its closest mean and we update the mean’s coordinates, which are the averages of the items categorized in that mean so far.
We repeat the process for a given number of iterations and at the end, we have our clusters.

# Output
![Figure 2021-07-18 173742](https://user-images.githubusercontent.com/70472055/126066748-0ff86b49-8254-48a2-8c1a-b5d4a2445f3d.png)
