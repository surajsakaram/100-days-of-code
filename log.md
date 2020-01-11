# 100 Days Of Code - Log

### Day 0: January 5, 2020

**Today's Progress**: Discussed with Harsha the goals for this challenge, a potential collaboration on a data science project, and why do this challenge. I will start this challenge on January 9th, 2020.

**Thoughts:** Complacency is the kiss of death. I feel I've become complacement in my learning process -- splashing around in shallow waters instead of diving deep. Through this challenge, I seek to attack all the things that most frustrate me and make me feel less than capable. No more copy and paste from stackoverflow (or at least significantly cut back). It will be I who answers stackoverflow questions. 

### Day 1: January 9th, 2020

**Today's Progress**: If unchecked, plotting will be the death of me. Thus, I chose to get on with it by going through this ggplot2 Tutorial (http://r-statistics.co/Complete-Ggplot2-Tutorial-Part1-With-R-Code.html) and learn about the ins and outs of one of the most useful R plotting packages out there.

**Thoughts** Once I master ggplot, I will only ever communicate in plots.

### Day 2: January 10th, 2020

**Today's Progress**: I used ggplot to create PCA plots to visualize RNA-Seq data and how my data points cluster. Principal Components Analysis (PCA) is regarded as one of the most widely used dimensionality reduction techniques on the planet. Funny enough, it doesn't actually reduce anything. The intuition behind PCA is to leverage a coordinate transformation (move the frame of referene around) to better separate the data points. The transformed data (Principal Components) are ordered by the component which captures the greatest amount of variability about our data with each subsequent principal component placed orthagonal to the previous component. The number of principal components is equal to the number of original features in the dataset, however, since each principal component explains less and less variation about the data, the transformed dataset is now amenable for dimensionality reduction. 

It's hard to visualize but ultimately you could take for example a 1000 feature dataset and represent it in 2 or 3 principal components aka a 2D or 3D plot. Why you ask? To check for any patterns in the data such as how do the data points cluster? Does my data cluster based on attributes that's otherwise known but not inherently provided in the data? Are there any hidden patterns that are unexpected? 

**Thoughts** Although the code to create pca plots is rather simple (it can get tricky fast the more fancy you want to make your plots), massaging your data into the right input structure makes up the bulk of the work, certainly reinforcing all the claims you may have seen in various media that data munging is in fact one of things data scientist spend most of their time doing.