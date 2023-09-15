# crypto_clustering
Data describing changes in pricing of different forms of currency over different time periods - ranging from 24 hours to 2 years - were used to examine whether differnet categories of crypto currency could be created. 

Descriptive graphs of change over time periods of each form of currency revealed more variability in amount of change over a 1 year time period than over shorter time periods. Data were first standardized by conversion to z-scores before analysis.

An elbow graph revealed four as an optimal number of clusters to create. KMeans clustering demosntrated that most types of crypto currency formed two groups. One of the two groups had a larger increase in price change over a 7-day period than a 24 hour period. A second group was fairly stable in price over both a 7-day period and a 24-hour period. The third group demonstrated little difference from this pattern. The fourth group had a relative decline in price over a 24 hour period and stable price (relatively speaking) over a 7-day period.

Principal components analysis was used to further investigate clustering among currency. Three components were first used to capture patterns of currency change over various time periods. An elbow graph investigating these components revealed that currencies could again be divided into four groups.

Graphical depiction of these groups, based on values on two of the components, the four groups can be differentiated based on their relative scores on the first and second components of the principal components analysis. Specifically, two of the groups both cluster around 0 on PCA1. One of these two groups scores positively on PCA2, while the other scores negatively. The other two groups are well-differentiated. One of the groups scores positively on both PCA1 and PCA2, while the other is positive on PCA1 but negative on PCA2. 

To further elucidate the meaning of these results, the relative values of the three PCA components were examined. Bitcoin, bitcoin-cash, and ethereum, for instance, all demonstrated negative values on PCA1 and positive values on PCA2 and PCA3. In contrast, tether and ripple demonstrated negative values on each PCA component. Bitcoin, bitcoin-cash, and ethereum all exhbited relative short-term gains, while tether and ripple exhibited either relatively no short-term change or decline in short term values, compared to the other currency. One possibility, which must be investigated further, is that crypto currencies can be differentiated based on the degree to which they exhibit short-term relative to long-term changes in value. 
