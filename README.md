# Pison Challenge

## Steps followed:
1.	First, I plotted the data from the server on a graph. For that, I stored sufficient amount of data into a text file(around 200K lines) and made a graph using matplotlib(Red indicates Activation) with x axis as timestamp and y axis as data
2.	  I concluded that there was no evident relation between timestamp and label. However, there  was strong relation between the data and the label value. Hence, from the above graph, I determined the maximum and minimum data value  for REST label(even though there are few outliers) and used that single information to classify the data.
3.	Finally, I created a simple client using Java to classify the server data.

## Conclusion:
I was able to achive an accuracy of aroung 84% which is quite good for the above simple heuristic approach

![alt text](https://github.com/rrmore/PisonChallenge/blob/master/Graph.jpg)
