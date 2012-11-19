# Class Examples
This repo houses example files for the JavaScript for Journalists course at [UC Berkeley Graduate School of Journalism](http://journalism.berkeley.edu). These files each correspond to a different lesson during the class.

Remember, the tutorials for the class can be found on the [Knight Digital Media Center Website](http://multimedia.journalism.berkeley.edu/tutorials/javascript-journalists/)
## [Instagram API Example](https://github.com/UCB-J-School/Class-Examples/blob/master/instagram/instagram.html)
To use this Instagram API example, you must signup for an Instagram account using your iOS or Android device first. Then register an application on [Instagram's Developer site](http://instagram.com/developer/).

Find the endpoint URL you  wish to use, which should contain your `access_key` as a parameter. (make sure it works in a browser) Set your endpoint to the `endpoint` variable in the Instagram file. You can edit the `processData` function however you wish, but it's currently set to display a new photo every time it's clicked.

## [Twitter Version 1 API Example](https://github.com/UCB-J-School/Class-Examples/blob/master/twitter/twitter.html)
**NOTE:** Twitter is deprecating their [version 1 API](https://dev.twitter.com/docs/api) soon. Their newer 1.1 api requires authentication for every call, which means you can't do it purely over JavaScript. 

This sample script calls Tweets from a specific location using Twitter's [search API](https://dev.twitter.com/docs/api/1/get/search). Edit the `processData` function as needed. Currently, it is designed to go through and display tweets, profile images and screen names. There is also a handy `linkify_tweet` method that is attached to String objects, which will link @username words, #hashtags and standard links.

## Timeline Example
Forthcoming.