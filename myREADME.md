## My FEND Feedreader Project Overview

This project is a web-based application that reads RSS feeds.  The code includes the
testing tool, [Jasmine](http://jasmine.github.io/), but the test suite required some
modification in order to effectively test each specification.  This was completed
and the Jasmine specs have all passed for this RSS feedreader app.


### Usage

This is a simple website that is accessed by either cloning the repository or
downloading the zip file.  Once you have the files on your system, you can initiate
the RSS feed and included specification tests by clicking on the _index.html_ file.  

The RSS feed entries are listed first, but scroll to the bottom of the page to see
the status of each **Jasmine** spec.  Underneath the Jasmine logo is a row of
green dots signifying a successful test for each of the 7 specs.  If one of the tests
failed, the green dot would be replaced by a red x with detail related to the error.

If further test specs are requested for this RSS feedreader app, simply modify the
**jasmine/spec/feedreader.js** file.


### Tools

**_Jasmine_** is used as a testing tool for this RSS feedreader application.


### Contributions

A big _Thank You_ to Udacity Mentors for the Javascript help and hints.
