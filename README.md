SimpleTwitterOAuth
==================

PHP to load Tweets using TwitterOAuth


Implementing Twitter OAuth for PHP Twitter Feeds
A quickfire guide to setting up and displaying your feed with OAuth

With the recent changes in the Twitter API, in an attempt to make the platform more standardised and secure, many website have been left with dead and broken custom Twitter feeds. The new process for implementing custom Twitter feeds on your website requires a little more work than before starting with Twitter’s API v1.1 Authentication Model.

Duration: 45 minutes
Knowledge of: HTML, PHP
Step 1 - Create a Twitter Application

Signup for a Twitter Application by visiting https://dev.twitter.com/apps/ . Here sign-in with your Twitter account. This doesn’t necessarily have to be the same as the account your application is for. Follow through the steps to create a new application. Once your application is created you can then create an access token.

Step 2 - Download OAuth API Library

You will now have four sets of numbers which can be entered into your PHP configuration:

Consumer Key
Consumer Secret
Access Token
Access Token Secret

With these in hand, you’ll need a PHP library for working with Twitter's OAuth API. Thankfully you don’t need to make one from scratch; just head over to https://github.com/abraham/twitteroauth and clone/download this to your project/solution.

Step 3 - Write and Test it

Copy  the script 'tweets.php' or create a new PHP file inside the folder ’twitteroauth’. The script provides all the functionality you'll need for a simple feed including a Twitter-style timestamp:

In this file add the feed’s Twitter handle, Consumer Key, Consumer Secret, Access Token and Access Token Secret. Check everything’s been entered correct and you’re now ready to run and test tweet.php.

Note:  The connection url may not work with https on all configurations so use http instead if you receive a Null error.

That’s it! 
