# Snips

<snippet>
  <content>
## Goals
1. Stage 1:
    - Allow backend to accept short encoded videos and decode
    - Save the video file to a directory with the following organization:  
				&nbsp;&nbsp;&nbsp;&nbsp;data/  
						&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;username1/  
								&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;datetimestamp.ext  
						&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;username2/  
								&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;datetimestamp.ext  
								&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;datetimestamp.ext  
 
    - iOS app that can record 2 second videos 
    - iOS app that sends Base64 encoded videos to server
2. Stage 2: 
     - Develop feature that requests specific videos from files (iOS)
     - Display fetched videos in a group in a list (iOS)
     - Handle video request and send corresponding videos (Server)
     - Create scheduled task that deletes videos if exist for 24 hours (Server)
3. Stage 3:
     - Add login and sign up screen (iOS)
     - Create a follow user function (iOS)
     - Request videos from people user follows (iOS)
     - Create appealing UI (iOS)
     - Handle login and signup requests and respond (Server)
     - Create follow and user databases (Server)
     - Handle requests for follow and unfollow (Server)
</content>

</snippet>
