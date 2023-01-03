# tweeterimages
download images of a twitter user
base on this post https://twitter.com/DanTraderOM/status/1610201095070187520
It would be usefull to check posts of traders that use tweeter to share their trades. So they can be analyzed. 

This code uses the tweepy library to authenticate with the Twitter API and retrieve the images from the user's timeline. It then saves the images to a local directory called "images." Next, it creates a list of Image objects for each image that meets certain criteria (in this case, the function meets_criteria is used to filter out images that don't match a certain set of criteria). Finally, it saves the list of frames as a GIF using the save method of the Image class, just like in the previous example.
