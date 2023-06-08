# CMA Developer Code Test, v2

## Goals

The purpose of the test is to demonstrate candidate aptitude in the following areas:

* Ability to solve problems creatively and rigorously.
* Ability to understand APIs and use them to solve problems.
* Proficiency in CMA’s tech stack; Python and Mongo specifically
* Strong grasp of how structured data works and how to manipulate it.
* Comprehension of specialized data, in this case CMA’s artwork data.
* Strong documentation and communication skills.

## Coding and Problem Solving

Write a script or utility that performs the operations and functions outlined below.

The solution is by no means intended to be a finished product, but the code should be clear, concise, and well commented. 

Solutions must be in Python 3.10+.

* Use [CMA’s Open Access API](https://openaccess-api.clevelandart.org/) to extract a “highlight” artwork based on criteria you decide (e.g. biggest, smallest, oldest, longest artist first name, etc.) from a [CMA exhibition](https://www.clevelandart.org/exhibitions) of your choosing (current or past) that has at least 8 CMA-owned works (CMA exhibitions often have many works on loan. The API response will only show CMA-owned works. You may have to look at a few exhibitions to find one with more than 8 works!).  
* Use the API to find 5 artworks (in or out of the exhibition you chose) that are related by one or more criteria in the artwork data to create a “mini exhibition”. 
* Set up a data source in [MongoDB Atlas](https://www.mongodb.com/). If you don’t have an account, you can sign up for a free one here: [https://www.mongodb.com/cloud/atlas/register](https://www.mongodb.com/cloud/atlas/register). 
* Use the Atlas API to insert the following data into a Mongo collection:
  * athena id
  * accession number
  * tombstone
  * image
  * any fields used for highlight or similarity criteria
  * an identifier for your mini exhibition 

## Documentation

Briefly answer the following questions about the exercise above:

* How did you approach this problem and why you end up with the solution you did?
* How long did it take you to complete?
* How would you change your solution in order to scale it up to a web application where users can select an exhibition, highlight and similarity criteria, and receive results?
* How would you set this up as a process that runs daily, with different results, and posts them to social media platforms via API?

## And Finally...

When complete, post your code and responses to GitHub and send us a link to the repo.




