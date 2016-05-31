### Summary

The author present a novel algorithm to deal with noisy oracles in active learning. The noise among oracles is non-uniform  noisy among oracles,
which is different from previous work that assume uniform noise. The algorithms contains exploration unlabbled part and exploitation labelled part
The result shows that the algorithm is outperform the traditional uncertainty sampleing in high oracle noise settings

### KeyPoints

* Exploration
Introuducing a regularizaition term to select an example that is more likely to be correctly labelled yet still with high information

* Exploitation
By examing the difference betwene current known posterior prob and estimated prob to find the most likely incorrecly labelled training data
and re-request the oracle to labbled

* Combination
Introudcing parameter alpha to which strategy is used. Alpha is denpent on the noise level of oracles

### Question

* Would it be better to user other regularization term instead of linear one in exploration?
