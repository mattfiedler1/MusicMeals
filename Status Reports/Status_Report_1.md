Status Report 1

We were able to accomplish quite a bit this week. We got our home page up 
and running, and we were able to connect it to the player page through the 
"show me some music button". We are having some trouble with that page, as 
we are still fiddling with the Spotify API and we are not sure if we should 
keep trying to use that API or maybe switch to a different one that might be 
easier for us to use in our implementation. Once we get this figured out we 
are going to start working with our data and statistics. We will do this in 
the following way: 

	- If a user clicks on either the "Like" or the "Dislike" button, the 
	program will retrieve the data stored for that song and recalculate the 
	like to dislike ratio for that song and store that again. 

	- The song data will be stored with the information about the song, as 
	we do not want there to be a chance of it getting mixed up with another 
	song of the same name, and its like to dislike ratio. 

	- When creating playlists, we will retrieve the ratio data for each song 
	and run a sorting function on the list, placing them in order of most 
	liked songs to most disliked. 

	- We can also display this data on a review page so that the user can 
	see which songs are the most popular and how the general public feels 
	about them.

Our goal for this week is to get the music player up and running and maybe 
we'll have time to implement the like and dislike features. 

# Comments by Ming
* Way cool.  Dislike feature will be fun!
* "as we are still fiddling with the Spotify API and we are not sure if we should keep trying to use that API " => Everyone has issues learning the Spotify API
