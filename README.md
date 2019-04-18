# Feed Reader Testing Project

This is a project using the Jasmine browser to run tests on a feed reader automatically.


## How to run the tests

Open your favorite browser and load index.html. The test results will appear at the bottom of the page. Without these tests passing you cannot successfully run the application.

## Which tests are run

### RSS Feeds

The RSS Feeds tests run to confirm that:
1. The RSS Feeds are defined
2. The URLs of the feeds are defined
3. The names of the feeds are defined

The Menu tests run to confirm that:
1. The Menu is hidden by default
2. The Menu toggles when the user clicks on the menu icon

The Initial Entries test runs to confirm that:
1. There are at least one entry in the feed

The New Feed Selection test runs to confirm that:
1. When a new feed is loaded, the content of the feed reader actually changes

