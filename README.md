# YouTube Player Application using Kotlin

 ![](https://miro.medium.com/max/840/1*oyjW0tejW_oiznAo4hNThA.png)<br><br>


* In this project we will learn how to integrate and play a video using YouTube API in Android with Kotlin.<br>

* The YouTube Android Player API enables you to incorporate video playback functionality into your Android applications. <br>
* The API defines methods for loading and playing YouTube videos (and playlists) and for customizing and controlling the video playback experience.<br>
* Using the API, you can load or cue videos into a player view embedded in your application’s UI. You can then control playback programmatically. For example, you can play, pause, or seek to a specific point in the currently loaded video.<br>
* You can also register event listeners to get callbacks for certain events, such as the player loading a video or the player state changing. Finally, the API has helper functionality to support orientation changes as well as transitions to fullscreen playback.<br>

### Creating an Android Project:
### Step 1- Creating a new file project with an empty activity

Go to Files
Create a New Project
Select a Project Template- Basic Activity


### Step 2- Setting up YouTube Library and Manifest
In this part, we will see how to set up the YouTube API Client library for the project.

Go to YouTube Android Player API and download YouTube Android Player API jar file — Link
Extract the jar files and add them to the “libs” folder.
Integration of YouTube Android Player in Screen using Kotlin
### Step 1: Go to Google Developer Console — https://console.developers.google.com/apis/library/
### Step 2: Enable YouTube Data API

### Step 3: Go to “Help me choose” option

### Step 4: Select the credentials as shown below

### Step 5: Go to Credentials





1. In the place of “Name” enter your package name
2. Generate the SHA-1 certificate fingerprint by running “signingReport”
3. Copy the generated SHA-1 certificate fingerprint and place it as shown above
