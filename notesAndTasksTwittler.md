#Twittler Project:

Create a Twitter like client using the provided data_generator.js file.  Requirements from README.md listed below:

##Requirements:
####Bare Minimum Requirements:
- [x] Show the user new tweets somehow. (You can show them automatically as they're created, or create a button that displays new tweets.)
- [x] Display the timestamps of when the tweets were created.
- [x] Design your interface so that you want to look at and use the product you're making.
- [x] Allow the user to click on a username to see that user's timeline.

####Advanced
- [x] Show when the tweets were created in a human-friendly way (eg "10 minutes ago"). You'll want to find and use a library for this.
- [ ] Allow the user to tweet. (This is going to require you to understand a little more about data_generator.js, but you shouldn't need to modify anything.)

###Next Action:
- [x] fix user filter bug
- [X] fix li removal of stats on profile card
- [x] fix long tweet wrap issue - look up word wrap for a p within a div
- [x] change time format
- [x] add page header and format
- [x] center everything
- [x] add user avatars for each tweet
- [x] format text update for loading tweets
- [x] fix text update for loading tweets
- [x] add stats to user section
- [x] clean up formating around the tweet to give some more white space 
- [x] fix tweet load order so newest is at the top
- [x] fix duplicated tweets and tweet load order
- [x] Create a button that displays new tweets
 might be able to use .trigger() on some kind of dealy.
- [x] Display timestamps
- [x] integrate bootstrap template
- [x] Create filter for each user name
- [x] Make each name a link
- [x] Click the link and then remove all users 
- [x] create a method for going back to all tweets
- [x] add side bar
- [x] set boarder around tweets
- [x] format tweets Name, handle, time, and then on the line below the tweet content
- [x] Create heading
- [x] float over window with scrolling

###Back log:
- [ ] update time each time new tweets are loaded.
- [ ] add pending tweets count to Load Link
- [ ] fix resize animation for title bar
- [ ] move all CSS out of bootstrap
- [ ] build tweet function
- [ ] 


###Notes on adding Tweet Function
- [ ] Create a text box on the left nav
- [ ] add the user to the user list 
- [ ] create a handler for that text box
- [ ] Tweet text box handler pushes the tweet to the streams array and calls the print tweets function
- [ ] Update tweet count in user stats to a live number. 
- [ ] create a simple user count array that counts the number of tweets from all users and then pull the current user from that array and display in the user card stats.
