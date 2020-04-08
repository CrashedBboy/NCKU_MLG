# Content

### Introduction

* Motivation
    - Why betweeness centrality is important
    - Current challenge of evaluating BC of a node
* Algorithm Brief Intro

### Problem Define

1. Input
2. Output

### Algorithms

- Model Architecture
    - Neighborhood Aggregation
    - Layer Combination
- Data Synthesizing
- Optimization Objective
    - Pairwise Loss
    - Softmax Loss
- Evaluation Metric
    - Kendall tau distance
    - Top-N% Accuracy
- Validation
- Early Stop

### Experiments

* Environment
* Number of epoch per graph
* `Top-N% accuracy` of synthetic graph of different scales, compared with other algorithms
* `Kendall tau distance` of synthetic graph of different scales, compared with other algorithms
* `Running Time` comparison on synthetic networks
* `Top-1% accuracy` generalization results on different scales
* `Kendall tau distance` generalization results on different scales
* `Top-N% accuracy` & `running time` on real-word data, compared with other algorithms
* `Kendall tau distance` on real-word data, compared with other algorithms

### Conclusion

* disadvantages
* future work