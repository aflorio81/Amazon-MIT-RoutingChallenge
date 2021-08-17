# Amazon-MIT-RoutingChallenge
Implementation of the **pool and select** framework for solving the Amazon/MIT routing challenge.

Authors: Alexandre Florio, Paulo da Costa, Sami Serkan Özarık.

## Description
This project contains all code developed by our group *TurkishChurrasco* for solving the [Amazon/MIT Routing Challenge](https://routingchallenge.mit.edu).

### Context
Optimization of last-mile delivery routes is a complex operational task in transportation logistics. Many factors must be taken into account when designing efficient routes: the total distance traveled, customer preferences and time windows, availability of parking spaces, spatiotemporal congestion patterns, and so on. The **pool and select** framework is a machine learning-based framework for optimizing last-mile delivery routes. It works by first generating a large pool of feasible delivery sequences (*pool* phase), then predicting and selecting the best sequence from the pool (*select* phase). In both phases, 

### Reference
For more details on the pool and select framework and this implementation, please refer to

**Florio, A.M., da Costa, P., & Özarık, S.S. (2021). A Machine Learning Framework for Last-Mile Delivery Optimization**.

## Dependencies
The implementation requires:
* The `rapidjson` ([https://rapidjson.org](https://rapidjson.org)) XML parser;
* A `date.h` implementation (e.g., [this one](https://github.com/HowardHinnant/date/blob/master/include/date/date.h));
* The [mlpack](https://www.mlpack.org) library for training the score prediction models by Laso regression.
