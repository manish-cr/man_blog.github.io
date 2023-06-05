---
title: Breast Cancer
categories: [project, portfolio]
tags: [python]
---

![breast cancer](https://www.yourhealth.net.au/wp-content/uploads/2017/09/pink-ribbon-for-breast-cancer-awareness.jpg)
*pink ribbon*

For this project, I decided to take a different approach. Instead of creating a classification model, I implemented a K Means Clustering (KMC).

This is so as to visualize the causes of breast cancer in women.

![3D plot](/3D%20plot.PNG)
*3D Breast cancer distibution using Plotly*

From the above diagram, it is obvious that the mean breast texture and perimeter are good indicators of malignant tumors.

**Other improvements**:
- use of PCA to get meaningful features before performing KMC
- use of cross-validation (Grid Search CV) to improve clustering

**Improvements to be made**:
- cross validating with classification methods to see how well clustering did
- cross-comparison with other clustering methods (e.g. Hirearchical Clustering, DBSCAN etc.)  
[github notebook](https://github.com/manish-cr/data-science-projects/tree/master/Breast%20Cancer)