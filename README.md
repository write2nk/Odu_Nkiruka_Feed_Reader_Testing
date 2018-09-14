# Odu_Nkiruka_Feed_Reader_Testing
## Feed Reader Testing ##
The project title is feed reader testing App, It is a web-based application that reads RSS feeds. `Jasmine 2.1.2` was used for testing. In programming, `testing` is important in oreder to check all the functionalities of your program/code. This project helped me to boost my skills in writing test code.

## How to run the App ##
The App can be locally by following this steps:
- Ensure that you have the [node.js](https://nodejs.org/en/) installed in the system
- Clone/download the code and unzip on your machine
- run the index.thml file to view what the app is doing.

## The Test Suites ##
The test suite for the feed reader testing is basically, four:
1. The RSS test suite:
* It is the first test suite that tests to ensure that `allFeeds` variables has been defined and that it is not empty. 
* To test if it works properly, change `allFeeds` in `apps.js` to be empty array and refesh the page to see what happens.
* also checks if URL is defined and if the Name property is not empty

2. The Menu Test suite:
* The second test suite that ensures that all menu element is hidden by default.
* The menu toggle events in chrome dev tools, which shows and hide the menu icon by toggling the class `menu-hidden` on `<body>` tag.

3. Initial Entries Suite:
* It is the third test suite that ensures that when the `loadFeed` function is called that it completes its work, 
* The loadFeed is also asynchronous so that the feedreadertest runs `beforeEach()`and `done()` it runs and loads correctly

4. News Feed Selection:
* It is the last test suite that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

## Dependencies ##
- Google APIs
- Jasmine 2.1.2

To test view the App, simply click the [link](https://write2nk.github.io/Odu_Nkiruka_Feed_Reader_Testing/) 

https://write2nk.github.io/Odu_Nkiruka_Feed_Reader_Testing/
