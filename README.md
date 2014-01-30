LLR-Tests
=========

Selenium automated browser tests for site functionality testing


Base URL is set in html header so this needs to be changed or parameter defined to run test on particular verions of the site.

Tests that have user details i've added a variable as the first action, this can be changed each time you test to generate usique user info each time. Avoids this user exists on repeated tests.


Useful:

waitforelement - this is very useful as test can run fairly quick and sometimes throws an error trying to select something that hasn't loaded on the page yet.

