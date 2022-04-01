# bid-optimizer
This project optimizes the bid rate on Amazon marketplace ads.
It pulls historical data about bid performance from Amazon's reports.
It then uses Bayes rule to update the parameters of a model representing
the bid-click and click-sale curves. From the models it calculates
the optimal bid rate.
The program is intended to be used daily. The optimal bid rate 
suggestion will only move so far from the previous suggestion.
