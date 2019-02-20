# QuickAudio
iOS Shortcut that instantly starts recording high quality WAVs when activated and automatically saved to iCloud Drive when finished recording.

                  •••••••••••••••••••••••••••••
                   - - - - QuickRecord - - - - 
                  •••••••••••••••••••••••••••••
                         QuickRecord v1.2
                  Created by: /u/ThatPineapple
                       Last updated: 2/20/19
                                ♥️



                  •••••••••••••••••••••••••••••
                  - - - - - FEATURES - - - - -
                  •••••••••••••••••••••••••••••

- Immediately starts recording audio when launched (saved as highest quality WAVs to iCloud Drive: /Shortcuts/QuickAudio/)

- Automatically creates an index file that logs each recording formatted as: (File Name) (File Size) (Duration) (Date/Time Created) (Location)

- Log file stored in: /Shortcuts/QuickRecord/log/RecordLog.txt

- File name protection: If a recording is deleted, the next recording's file name continues to be unique so that the log file remains accurate. 
E.g., if you have four recordings total and 'AudioFile-4.wav' is delete, a new recording is automatically named 'AudioFile-5.wav' so that the log file does not have any duplicate file names. 

- Location is stored in the RecordLog (E.g., location logged after recording an interaction with law enforcement, etc.)

- Complete changelog stored in : /Shortcuts/QuickAudio/log/ChangeLog.txt



                  •••••••••••••••••••••••••••••
                      ⚠️⚠️  ATTENTION  ⚠️⚠️
                  •••••••••••••••••••••••••••••
                               ⚡️
DO NOT modify/delete 'identifier.txt'. File naming scheme and log records will become inaccurate.

Location data is used to log an approximate location for each recording. Location(s) are only saved in the log file on your iCloud Drive. 
Location via Weather is used instead of 'Get Current Location' since location via Weather is obtained substantially faster.  

There is a prompt where you can opt-in/out of using location data. This is a single instance prompt. Once answered, it will not be asked again (even when updating to a newer version). 

If want to change your response, you can safely delete 'LCheck.txt' in the log folder and the prompt will come up the next time this Shortcut is launched. 






