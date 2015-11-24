# AudioRecording
MacOS Automator applications for recording audio. 

Requirements:
Sox must be installed with MP3 support. 
I recommend the following procedure for installing SOX:
1. Install Homebrew from http://brew.sh/
2. Install lame via homebrew:
  brew install lame
3. Install Sox via homebrew:
  brew install sox

The default save location for the recordings is ~/Desktop/Recordings. They are named with the date and time when the recording was started.

RecordNow application
This application will ask how long you would like to record your event.
Enter the time and click OK for recording to begin.

RecordEvent application
This application is designed to be used in conjunction with iCal.
1. Create an event with a start and end time that you would like to be recorded
2. Set the reminder to open a file
3. Select the RecordEvent application
4. Set the time of the reminder to be at the time of the event


