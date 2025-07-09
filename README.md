# WordPress First Automation Workflow

This repository contains the files of my n8n workflows to automate sermon publishing when the sermons are uploaded to WordPress. 

My workflow consists of getting the information from the post, sorting through the HTML code, converting the audio link in the WP post into a usable file, transcribing the sermon file, breaking it into paragraphs, creating a summary, and reuploading the sermon post to WP with the added transcript and summary.
My workflow also has functionality to split up the audio file into smaller chunks in order to bypass the 25MB limitation set by most transcription services.

My workflow will hopefully have functionality to automatically detect when a post is uploaded to WordPress in the near future, along with a way to create social media posts and youtube shorts.
