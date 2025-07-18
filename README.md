# AssemblyAI Audio to Text Transcription

The AssemblyAI Audio to Text Transcription n8n workflow uses AssemblyAI to transcribe an audio file when given the audio link. There is functionality to split the transcript into paragraphs so that it is easier for the user to read. This is one part of a larger workflow that me and my colleagues are designing, but it is possible to make it function by itself.


# WordPress First Automation Workflow

This is my n8n workflows to automate sermon publishing when the sermons are uploaded to WordPress. 

My workflow consists of getting the information from the post, sorting through the HTML code, converting the audio link in the WP post into a usable file, transcribing the sermon file using OpenAI, breaking it into paragraphs using OpenAI, creating a summary using OpenAI, and reuploading the sermon post to WP with the added transcript and summary.
My workflow also has functionality to split up the audio file into smaller chunks in order to bypass the 25MB limitation set by most transcription services.

## OpenAI Audio to Text Transcription

This is one part of the WordPress First Automation Workflow, separated out to work on more thoroughly. It currently has some sort of problem when trying to split the files, but otherwise it should work.

The WordPress First Automation Workflow could have functionality to automatically detect when a post is uploaded to WordPress in the near future, along with a way to create social media posts and youtube shorts if I decide to work on this workflow one more.
