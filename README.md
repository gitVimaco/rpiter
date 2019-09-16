# rpiter
RPiTer Twitter client

We have to create a Twitter account on https://apps.twitter.com

The consumer key/secret is used to authenticate the app that is using the Twitter API, while the access token/secret authenticates the user. All of these parameters should be treated as passwords, and should not be included in your code in plain text. One suitable way is to store them in a JSON file "twitter_credentials.json" and load these values from your code when needed. DO NOT UPLOAD THIS FILE TO GITHUB!

'''
import json

# Enter your keys/secrets as strings in the following fields
credentials = {}
credentials['CONSUMER_KEY'] = ...
credentials['CONSUMER_SECRET'] = ...
credentials['ACCESS_TOKEN'] = ...
credentials['ACCESS_SECRET'] = ...

# Save the credentials object to file
with open("twitter_credentials.json", "w") as file:
    json.dump(credentials, file)
'''
