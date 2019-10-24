
# YouTube-Video-in-Android

Integrate youtube videos in android app

Steps

- First find SHA 1 Certificate from Android Studio
 Click on Gradle right hand side -> app > task > android -> signing report 
 you'll get your SHA 1 certificate in logcat
 
 
 - Google -> Android YouTube API
 Downlod zip file from below link
 https://developers.google.com/youtube/android/player/downloads
 Unzip it -> lib -> copy jar file -> paste in libs folder in android studio
 
 
 - Open Google Developer Console
 https://console.developers.google.com/apis/dashboard?project=fir-storage1-e99be&supportedpurview=project
 Create api key from above link.
 You have to add your package name and SHA-1 certificate here.
