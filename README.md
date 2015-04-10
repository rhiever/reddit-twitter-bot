#reddit Twitter Bot

A Python bot that takes posts from reddit and automatically posts them on Twitter.

##Disclaimer

I hold no liability for what you do with this script or what happens to you by using this script. Abusing this script *can* get you banned from Twitter, so make sure to read up on proper usage of the Twitter API.

##Dependencies

You will need to install Python's [tweepy](https://github.com/tweepy/tweepy) and [PRAW](https://praw.readthedocs.org/en/v2.1.21/) libraries first:

    easy_install tweepy
    easy_install praw
    
You will also need to create an app account on Twitter: [[instructions]](https://dev.twitter.com/apps)

1. Sign in with your Twitter account
2. Create a new app account
3. Modify the settings for that app account to allow read & write
4. Generate a new OAuth token with those permissions
5. Manually edit this script and put those tokens in the script

Lastly, you will need to create a developer account with Google: [[instructions]](https://developers.google.com/maps/documentation/javascript/tutorial#api_key)

##Usage

Once you edit the bot script to provide the necessary API keys, you can run the bot on the command line:

    python reddit_twitter_bot.py
 
Look into the script itself for configuration options of the bot.

##Have questions? Need help with the bot?

If you're having issues with or have questions about the bot, please [file an issue](https://github.com/rhiever/reddit-twitter-bot/issues) in this repository so one of the project managers can get back to you. Please check the existing (and closed) issues to make sure your issue hasn't already been addressed.
