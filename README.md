# Project Overview

Given a web-based application that reads RSS feeds use a Jasmine Testing Suite to verify code is working as written.

# Test Suites:  

RSS Feeds:

Test 1: Make sure that the allFeeds variable has been defined and that it is not empty.
>Is Defined?  Yes, Test feeds defined
>Is Not 0: Yes


Test 2: test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
>Is Defined? Yes, URL is defined and is NOT empty
>Is Named? Yes, NAME is defined and is NOT empty


Menu:

Test 1: Menu element is hidden by default.
>Is True? Yes, should be hidden

Test 2: ensures the menu changes visibility when the menu icon is clicked.
>Is on click false? Yes, should display on Click and should hide on Click
>Is on click true? Yes, should display on Click and should hide on Click


Initial Entries:

Test 1: Ensure when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
>Is Is Not 0: Yes, When loadFeed() completes there is at least 1 entry element in the feed container


New Feed Selection:

Test 1: Ensure when a new feed is loaded by the loadFeed function that the content actually changes.
>Is Not initial entry? Yes, Check if loadFeed() takes in new content

# Credit/Sources:
1. jQuery http://api.jquery.com/hasclass
2. https://jasmine.github.io/tutorials/your_first_suite
