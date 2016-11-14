# Project Overview

This project's code was provided to me, and my job was to write tests for the website in Jasmine (http://jasmine.github.io/) to make sure everything was functioning properly.

# How I completed the project

Reviewed the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)

1. Took the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Downloaded the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Reviewed the functionality of the application within my browser.
4. Explored the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
5. Explored the Jasmine spec file in **./jasmine/spec/feedreader.js** and reviewed the [Jasmine documentation](http://jasmine.github.io).
6. Edited the `allFeeds` variable in **./js/app.js** to make the provided test fail and saw how Jasmine visualizes this failure in your application.
7. Returned the `allFeeds` variable to a passing state.
8. Wrote a test that looped through each feed in the `allFeeds` object and ensured it had a URL defined and that the URL was not empty.
9. Wrote a test that loops through each feed in the `allFeeds` object and ensured it had a name defined and that the name is not empty.
10. Wrote a new test suite named `"The menu"`.
11. Wrote a test that ensured the menu element is hidden by default.
12. Wrote a test that ensured the menu changed visibility when the menu icon was clicked. This test required two expectations: does the menu display when clicked and does it hide when clicked again.
13. Wrote a test suite named `"Initial Entries"`.
14. Wrote a test that ensured when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
15. Wrote a test suite named `"New Feed Selection"`.
16. Wrote a test that ensured when a new feed is loaded by the `loadFeed` function that the content actually changes.
17. Made sure that no test is dependent on the results of another.
18. Used callbacks to ensure that feeds were loaded before they were tested.
19. Implemented error handling for undefined variables and out-of-bound array access.
20. Made sure all of my tests passed.
21. Wrote a README file detailing all steps required to successfully run the application.

# How to Run the App
1. Access feed-reader-testing repository, located here: https://github.com/cschonhaut/Feed-Reader-Testing-Final-Project
2. Open index.html with a browser.
3. There should be 8 specs, 0 failures at the bottom of the html page.
