---
layout: page
title: CH Robinson Dynamic Pricing
description: a data science project to optimize pricing and lanes for freights
img: /assets/img/chrob3.png
importance: 3
category: machine learning
---

## Description
93.67% of quote requests do not result in a customer purchasing with the company. Of those who do purchase a transportation service, only 64.02% choose the cheapest option provided. Our goal is to provide rates for a choice set of quotes that balance the probability that something from the choice set is ordered, while also providing a rate that has good profit.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chrob1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    EDA
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chrob2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chrob3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Methods
</div>

## Methodology
The research completed sampled 28,297 quote requests from C.H. Robinson which were grouped into 3 sets for model testing: a training set(January to May 1,2022), a cross-validation set(May 2022) and a testing set(June
2022). After initially cleaning and wrangling the data, we began exploring ways to interpret and model the data. A good model for the data would allow us to predict customer purchase outcomes as we apply different dynamic
pricing strategies. We generated models utilizing the following machine learning tools: k-Nearest Neighbors (kNN), XG Boost and CatBoost and interpreted the respective SHAP values. Due to time constraints and
complexity in the problem, we were unable to apply dynamic pricing strategies or utilize Thompson Sampling to its fullest extent. In the next section, we will summarize our results.

<a href="https://github.com/AImeetsAG/Dynamic-Pricing-Project" target="_blank">Code</a>




