# YouTube-Transscription-Parser

Do you need a transcription for whatever reason? Great... Here's a step by step way to create a formatted transcript without hassle

1. Upload your video to YouTube (Private or Unlisted)
2. Wait for it to do checks (If copyright's an issue it'll automatically become private or unviewable by the public, if not ad revenue being stolen)
3. 
4. View the video on YouTube (Not Studio or whatever)
5. Check the about section of the video if you do not see "view transcript" then wait and check your subtitle settings in YouTube Studio
6. Once you see the transcript go to the very bottom of the transcription (Ensure you toggle on time stamps)
7. Click & Drag (upwards) and highlight all of the transcript
8. press ctrl C and copy to a txt file name it transcript.txt
9. Ensure you have python installed (I'm not gonna walk you through this)
10. Change the directories for your output and input
11. Run the script YTF.py in CMD, Powershell, VSCODE or whatever you're using. I use VSCODE with python so I just hit CTRL F5 and call it a day but CLI users run: python YTF.py


Errors:
1. If you get error: python is not a bash command or whatever and you're on linux please, for the love of god try python3 instead of python.
2. Did you update the directories? If you're getting "Path/To/transcript.txt/ isn't found" you need to put the directory your transcript.txt is in
2.2 assuming you're like me and you saved it to your desktop it's C:\<username>\Desktop\transcript.txt
