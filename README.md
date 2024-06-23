# Simple-Uploader
Simple Uploader For manage vulnerable POCs
-----------------------------------------------------
This is a simple flask-based uploader whose primary purpose is to manage vulnerable POCs, but you can modify it according to your purpose of use.
This upload only allows uploading certain extensions of photos and videos.
It also has session management and you can define a fixed password as a hard code on it.
You need to install ffmpeg and PIL before running
-------------
The way it works is that at first you can define a project along with the version and date, and a directory is created for each project.
After selecting the project - your files will be uploaded to the same directory, but the access link to the file is also available to the user as a click of a button.
