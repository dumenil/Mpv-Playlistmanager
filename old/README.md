# Mpv-Playlistmanager - OUTDATED
Mpv lua script to create and manage playlists. Customize script in the settings array in the top of the lua file.
  
See demo of script in here: https://r.kyaa.sg/fkslzw.mp4

## Features
- __remove old__ 
  - Removes entries from the start of the playlist when moving forward keeping the playlist list readable and navigatable. Edit settings to change ranges, or if you want files to be appended at end of playlist instead of removed.
- __sort playlist__(CTRL+p)  
  - Sorts the current playlist alphabetically. Stops currently playing file and starts playlist from start of new playlist. Option to run at mpv start automatically in settings.
- __Loadfiles__(P)
  - Attempts to load all files after the currently playing file to the playlist from the currently playing files directory
  - Ex. Open 5th file from a 12file directory, press P, the remaining 7 are loaded to playlist
  - change boolean in settings for linux/windows
- __Save playlist__(p)
  - Saves the current playlist to m3u file, change filepath in settings to a path in your system
- __Move up__(UP)
  - Moves the currenly playing file backwards in the playlist queue
- __Move down__(DOWN)
  - Moves the currenly playing file forwards in the playlist queue
- __Remove current file__(Shift+UP)
  - Removes the currently playing file from the playlist, and resumes playing the next file
- __Remove next file__(Shift+DOWN)
  - Removes the file after currently playing file from playlist
  - This allows you to use currently playing file as a cursor to remove other files from playlist seamlessly
- __Move previous file up__(CTRL+UP)
  - Moves the file before currently playing file backwards
  - This allows you to use currently playing file as a cursor to move other files in the playlist seamlessly
- __Move next file down__(CTRL+DOWN)
  - Moves the file after currently playing file forwards
  - This allows you to use currently playing file as a cursor to move other files in the playlist seamlessly

  

#### My other mpv scripts
- [unseen-playlistmaker](https://github.com/donmaiq/unseen-playlistmaker)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[manager+maker combined](https://github.com/donmaiq/unseen-playlistmaker/blob/master/unseen%2Bplaylistmanager.lua)
- [nextfile](https://github.com/donmaiq/mpv-nextfile)
