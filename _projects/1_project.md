---
layout: page
title: Book Recommender System
description: a project using ALS matrix factorization and SGD
img: /assets/img/book_recommender.jpg
importance: 1
category: machine learning
---

Alternating least square matrix factorization is a simple algorithm which anybody who has taken a linear algebra course can understand. Although writing the implementation is PyTorch was easy, the biggest obstacles were the huge size of the matrix, sparsity of the matrix, and hyperparameter tuning cost.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/book_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/book_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    EDA and methods
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/book_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hyperparameter Tuning 
</div>

I did batch gradient descent and stored the matrix as tensors for sake of memory. Also, I experimented with lots of gradient descent techniques like SGD, ADAM, AdaGrad, etc. 

[Code](https://github.com/AImeetsAG/Book-Recommender--Matrix-Factorization-with-ASGD)



