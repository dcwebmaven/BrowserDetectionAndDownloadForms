# BrowserDetectionAndDownloadForms
This repository is for a program I wrote to detect what browser people are using and then present the right download form depending on their browser.

Browser Detection and Download Forms

Acme, Inc. has created a cool software plugin that users can download and use for free. However, there are two problems with this software: 

1.	It only works on Macintosh machines with the Firefox browser or Windows machines with the Internet Explorer browser or the Firefox browser. 

2.	Hackers have been downloading it for shady purposes, so Acme must block all IP addresses starting with "202." from downloading it. 

It's up to you to create a PHP script for Acme that contains the "Download Now!" link or button. That link or button should not show up unless it is feasable and legal for the user to download the plugin, so use environment variables to detect the user's information. 

•	If the user is on the wrong computer/browser combination, tell him so and direct him to a possible solution (ie. a page to download Firefox for Macs). 

•	If the user's IP address starts with "202.", give a different message and do not allow him in. 




