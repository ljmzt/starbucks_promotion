# Udacity Portfolio Exercise: Starbucks

### Background and Purpose

This repository contains files for Udacity Data Scientist Nanodegree Portfolio Exercise: Starbucks.

The purpose of this exercise is to analyze the synthetic dataset provided by Starbucks, which is a A/B test on whether sending out a $0.15 promotion can actually bring profit or not.

The full description is quoted here:

> The dataset you will be provided in this portfolio exercise was originally used as a take-home assignment provided by Starbucks for their job candidates. The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. Each data point includes one column indicating whether or not an individual was sent a promotion for the product, and one column indicating whether or not that individual eventually purchased that product. Each individual also has seven additional features associated with them, which are provided abstractly as V1-V7.

The uniqueness of this dataset is that it uses metrics that aren't that "normal", which are

> Incremental Response Rate (IRR)
> IRR depicts how many more customers purchased the product with the promotion, as compared to if they didn't receive the promotion. Mathematically, it's the ratio of the number of purchasers in the promotion group to the total number of customers in the purchaser's group (treatment) minus the ratio of the number of purchasers in the non-promotional group to the total number of customers in the non-promotional group (control).

and

> Net Incremental Revenue (NIR)
> NIR depicts how much is made (or lost) by sending out the promotion. Mathematically, this is 10 times the total number of purchasers that received the promotion minus 0.15 times the number of promotions sent out, minus 10 times the number of purchasers who were not given the promotion.
