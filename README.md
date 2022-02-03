# INSE-6630-transcripts
## Transcripts for INSE 6630 Lectures

1. Go to your desired YouTube video via a Web browser.
2. Check to make sure the YouTube video has captions/subtitles added with the “CC” button.
3. Go to “Settings” and click on “Subtitles/CC” to see which subtitle languages are available.
4. On the menu below the video, click the three dots next to “Save” for more options, then select “Open Transcript”.
5. An interactive transcript will appear next to the video on the right side of the window.
6. Click the dropdown menu at the bottom of the transcript to select the language of your subtitles.
7. Click the three dots at the top of the transcript to turn the timestamps in the transcript on or off.
8. Once you’ve selected your desired language and the timestamps fit your preferences, highlight the transcript, copy it, and paste it to a word processor or notepad app of your choice.
9. Put this `sed` command ```s/([a-zA-Z,`])\n([a-zA-Z`])/\1 \2/``` in a file named `sed.cmds`:
10. Run ```sed -e ':a' -e 'N' -e '$!ba' -E -f sed.cmds Input.txt > Output.txt```
11. Et voilà!