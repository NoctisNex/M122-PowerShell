About: enumerate startup entries system and user.
Goal: spot unwanted autostarts.
Practice: registry reads and review.

Example
-------

HKLM\Software\Microsoft\Windows\CurrentVersion\Run
"OneDrive"="C:\Program Files\Microsoft OneDrive\OneDrive.exe /background"
"Teams"="C:\Users\Robin\AppData\Local\Microsoft\Teams\Update.exe --processStart ""ms-teams.exe"""

HKCU\Software\Microsoft\Windows\CurrentVersion\Run
"Spotify"="C:\Users\Robin\AppData\Roaming\Spotify\Spotify.exe"
