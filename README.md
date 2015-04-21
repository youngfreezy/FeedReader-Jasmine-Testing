# FeedReader-Jasmine-Testing


About


Tests were added in jasmine/spec/feedreader.js to test the website.

The following tests were implemented:

RSS feeds are defined in allFeeds and are not empty.
Each feed in allFeeds has a defined and valid URL.
Each feed has a defined and non-blank name.
The navigation menu is hidden by default.
The nav. menu toggles visibility after clicking the menu icon.

The first feed has at least one entry.
The feed changes content after selecting a new feed.

How to Run


Download or clone the repository and open SpecRunner.html file in your browser locally. You will see a section below the page showing the test results.  To add or edit the feed sources, open js/app.js and change the allFeeds object.