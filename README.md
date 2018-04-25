
# Feed Reader Testing.


## Project Overview

A web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where I come in.




### What did I learn?

I learned how to use Jasmine to write a number of tests against a pre-existing application. These test the underlying business logic of the application as well as the event handling and DOM manipulation.



### Tests list:

1- tests to make sure that the allFeeds variable has been defined and that it is not empty.

2- loops through each feed and determines if the URL is defined and not empty.

3- loops through each feed and determines that each feed has a name and not empty.

4- ensures the menu element is hidden by default.

5- ensures the menu changes visibility when the menu icon is clicked, does the menu display when clicked and does it hide when clicked again..

6- tests that there is at least one entry in feed.

7- tests that new content is loaded by loadFeed().
