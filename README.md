Takeaway Challenge [![Build Status](https://travis-ci.org/makersacademy/takeaway-challenge.svg?branch=master)](https://travis-ci.org/makersacademy/takeaway-challenge)
==================

User Stories
-----

```
As a customer
So that I can check if I want to order something
I would like to see a list of dishes with prices

As a customer
So that I can order the meal I want
I would like to be able to select some number of several available dishes

As a customer
So that I can verify that my order is correct
I would like to check that the total I have been given matches the sum of the various dishes in my order

As a customer
So that I am reassured that my order will be delivered on time
I would like to receive a text such as "Thank you! Your order was placed and will be delivered before 18:52" after I have ordered
```

Description
-----
 The takeaway challenge is based upon being able to order dishes from a set menu and then getting a text confirmation from Twillio once the order is placed. The user should not be allowed to order dishes that are not on the menu and the amount to be paid should be verified against what the application calculates the total cost to be. 

Testing: rspec

Installation:

   - Clone git repo
   - Run bundle install from the command line
   - Run rspec to see tests
   - To interact with application use irb or pry


[![Coverage Status](https://coveralls.io/repos/makersacademy/takeaway-challenge/badge.png)](https://coveralls.io/r/makersacademy/takeaway-challenge)
