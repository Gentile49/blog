---
layout: post
title:  "Data Gem CLI"
date:   2017-08-10 19:36:55 +0000
---


So I watched the walkthrough video and ran bundle gem with the title.  

Looked at my new gem and didn't know what to do.  Got the president of my school to walk me through setting up the environment.

Once that was in place I created three classes a book class, a cli class, and a scraper class.  

Then I ran some tests that calling Book.new would run the code in my book initialize method.  

And when I was satisfied I began to program.  

I set up an easy to use cli interface with a list method and a menu method.  

The list method is self explanatory I used the scraper class within book where I call a new scraper class and can access those methods. 

Then I use a new book class within cli so that I can again call those methods.  

So for list I just call the bookList method. 

In menu I put out a message and ask for input in the form of a selection 1 - 25, list, or exit. 

I parse that input so that I can use the integer if it is an integer when I call on the bookDetail method next. 

That is done within a case statement, including cases for list, exit, 1 - 25, and else.

Then I have written all the code I needed.  And I say goodbye.  


