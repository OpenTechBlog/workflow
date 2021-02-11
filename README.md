# workflow
The workflow concept of OpenTechBlog
1. An blog entry is written to the hugo static site repository
2. An server builds the hugo static site
3. An server creates a video for the blog entry
	* Text to speech for the audio
	* Video
		* Pictures from an videopicture repository
		* The pictures are displayed text line based
			* Info from an VCONFIG file
4. Blog/Video gets automatically shared on social media
	* Twitter via tweepy
	* Reddit via api
	* Instagram via unknown api
	* Telegram via api
	* Discord via bot
	* Matrix via api
	* Mastodon via api	
	* YouTube via api
	* LBRY via api
	* Vimeo via api
5. Sent email to email subscribers
6. Add to rss feed
7. Sent push notification
