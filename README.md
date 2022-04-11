# Analyzing Starbucks A/B Testing results
This project tries to complete the Starbucks Take-Home Assignment provided by Udacity, in collaboration with Starbucks, in the context of their [Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

The results are shared on a [Medium post](https://medium.com/@pcmaldonado/starbucks-take-home-assignment-a8b647fb21e0).

## Context
In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. 

## Goal
The task is to use the training data to understand what patterns in V1-V7 (abstract customers' features) indicate that a promotion should be provided to a user. Specifically, the goal is to maximize the following metrics:
* **Incremental Response Rate (IRR):** how many more customers purchased the product with the promotion, as compared to if they didn't receive the promotion
* **Net Incremental Revenue (NIR):** how much is made (or lost) by sending out the promotion.

## Questions
1. Analyze the results of the experiment of the treatment on product purchase and Net Incremental Revenue
2. Build a model that selects the best customers to target that maximizes the IRR and the NIR
