
# Feed Reader Testing.


## Project Overview

A web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where I come in.




### What did I learn?

I learned how to use Jasmine to write a number of tests against a pre-existing application. These test the underlying business logic of the application as well as the event handling and DOM manipulation.




#### Take the JavaScript Testing [course](https://www.udacity.com/course/ud549)
#### Download the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader)

**if you want to check the Test file:
Explore the Jasmine spec file in ./jasmine/spec/feedreader.js and for more review the [Jasmine documentation]
(http://jasmine.github.io).**

### How to run application:

To start the app, open index.html in your browser.

The tests were written in the feedreader.js file.

The test results appears at the bottom of the index.html page.

Tests that are green have passed and red have failed.




### Tests list:

1- Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.

2- Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

3-  New test suite named `"The menu"`.

4- Test that ensures the menu element is hidden by default.
by analyzing the HTML and the CSS to determine how was performing the hiding/showing of the menu element.


5- Twst to ensures the menu changes visibility when the menu icon is clicked, does the menu display when clicked and does it hide when clicked again.

6- Test suite named `"Initial Entries"`.

7- Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

8- Test suite named `"New Feed Selection"`.

9- Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

10- There is No test dependent on the results of another. 'You can try it' 

11- Callbacks are used to ensure that feeds are loaded before they are tested.


### Give it a look and have fun Testing.
