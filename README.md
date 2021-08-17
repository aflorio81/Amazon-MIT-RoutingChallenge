# Amazon-MIT-RoutingChallenge
Implementation of the ''pool and select'' framework for solving the Amazon/MIT routing challenge.

Authors: Alexandre Florio, Paulo da Costa, Sami Serkan Özarık.

## Description
This project contains all code developed by our group 'TurkishChurrasco' for solving the [Amazon/MIT Routing Challenge](https://routingchallenge.mit.edu).

Optimization of last-mile delivery routes is a complex operational task, as many factors must be taken into account. For example, the total distance traveled, customer availability and time windows, parking spaces, congestion patterns, etc., all play an important role when defining efficient delivery routes. The ''pool and select'' framework is a machine learning-based framework for optimizing last-mile delivery routes.

## Dependencies
The implementation requires:
* The `rapidjson` ([https://rapidjson.org](https://rapidjson.org)) XML parser;
* A `date.h` implementation (e.g., [this one](https://github.com/HowardHinnant/date/blob/master/include/date/date.h));
* The [mlpack](https://www.mlpack.org) library for training the score prediction models by Laso regression.
