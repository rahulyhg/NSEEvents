# NSEEvents

NSE Events is a python application that takes the RSS feed from NSE website (http://www.nseindia.com) and parses it and creates a calendar of events on Google Calendar.

## What can I do with it?
You can setup a job to update your google calendar with events from NSE.  I wrote this to solve my problem where I didnt have visibility to when corporate events were going to be applicable to stocks I own.  

## How do I use it?
Get hold of a low power PC and set it up as a batch job to run once a day.  As of now (April 2012) NSE updates dont seem to happen more frequently than once a day.  It will keep your calendar updated with latest company news.

## Pre-requisites

You need the Google API Python client.  You can install it by issuing the following command.

easy_install --upgrade google-api-python-client

