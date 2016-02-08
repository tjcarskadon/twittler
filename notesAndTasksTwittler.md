##Notes and tasks:

###Next Action:
- [ ] change time format
- [x] add user avatars for each tweet
- [x] format text update for loading tweets
- [x] fix text update for loading tweets
- [x] add stats to user section
- [x] clean up formating around the tweet to give some more white space 
- [x] fix tweet load order so newest is at the top
- [x] fix duplicated tweets and tweet load order

###Back log:
- [ ] fix time updating
- [ ] add some kind of right window section
- [ ] fix time updating issue
- [ ] figure out how to display tweets when new onese are added to the array
- [ ] add page header and format
- [ ] adjust dynamics to be like twitter page



#Global Tasks:
- [x] Create a button that displays new tweets
 might be able to use .trigger() on some kind of dealy.
- [x] Display timestamps
- [x] integrate bootstrap template
- [x] Create filter for each user name

###Name filter tasks:
- [x] Make each name a link
- [x] Click the link and then remove all users 
- [x] create a method for going back to all tweets

###Design tasks:
- [x] add side bar
- [x] set boarder around tweets
- [x] format tweets Name, handle, time, and then on the line below the tweet content
- [x] Create heading
- [x] float over window with scrolling


#Nice to haves:
- [ ] mode that lets you choose between auto display and clicking the button to display new tweets
- [ ] extra sections with lorem ipsum as place holder 

#user - image map
- shawdrost = steve dallas
- sharksforCheap = opus
- mracus = milo
- douglascalhoun = owj 

#Notes:
- tweets are in the streams object stored as arrays with all the data.
- Need to handle what happens if you click the button lots of times qucikly and no tweets are ready
- Might be a good idea to use classes as a flag for hiding and revelaing users when filtering.
- odd issue with the way tweets are reloading after user filtering.  Currently it seems the original tweets are showing up on top of the newer tweets when they should be ending up in the oppostie order.  Not sure what to sort here because there isn't a single array that holds all the tweets.  Maybe I need to load them and then sort by time or something????
-