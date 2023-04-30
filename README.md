# Recommendation-System

A Movie Recommendation System implementation for the course CS 328: Data Science

## Neural Collaborative Filtering

Based on the paper:
```
He, Xiangnan, et al. "Neural collaborative filtering." Proceedings of the 26th international conference on world wide web. 2017.
```

Dataset used: MovieLens-1M

### Model Architecture:

<figure align = "center">
    <img src="img/NCF.png" width = "500">
    <figcaption align = "center">
        <b>Architecture of The Neural Matrix Factorization (NeuMF) Model</b>
    </figcaption>
</figure>

<!-- <img src="img/NCF.png" width = "500"> -->


### Learning Curves

Epoch Loss
<figure align = "center">
    <img src="img/loss.png" width = "500">
</figure>

Hitrate@10
<figure align = "center">
    <img src="img/hr.png" width = "500">
</figure>

NDCG@10
<figure align = "center">
    <img src="img/ndcg.png" width = "500">
</figure>
