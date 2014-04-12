Notifications Lab (week 5)
==================================

Experimenting with User Notifications, BroadcastReceivers, AsyncTasks and Networking, by creating a simple application 
that downloads and displays tweets. 


It checks if the fake tweets have been downloaded within the last two minutes, and if not, it will begin the download again. It performs this download in an AsyncTask in the background. When the download is complete, if the user still has the main activity open, nothing happens. However, if the user has left the application before the tweets finished downloading, then the DownloaderTask creates a notification which gets sent to the user.

