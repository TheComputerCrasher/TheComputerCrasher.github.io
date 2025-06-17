# How to add custom songs to Super Paper Mario

## Prerequisites 
For this tutorial, you will need to download and set up [Dolphin Emulator](https://dolphin-emu.org/download/) if you don't have it installed already, download the [Super Paper Mario HD Audio mod](https://youtu.be/IvLNpXvohTw),* and get a Super Paper Mario ROM file. You can either dump a legally-obtained game from a real Wii using the [Homebrew Channel](https://wiibrew.org/wiki/Homebrew_Channel), or you can find a ROM online somewhere.

You also need to have the song(s) you want to add as music files (MP3, WAV, or OGG). If you want a song from a YouTube video, I recommend either [yt-dlp](https://ytdlp.online/) (more options) or [CNVMP3](https://cnvmp3.com) (easier to use).

\* Note: The HD Audio mod is not *technically* required, but it makes this process a lot easier. For example, you don't need to extract your ROM and you don't have to make your songs double-speed (which would make it much harder to edit in the BRSTM maker).

## After you set up Dolphin, you need to use the HD Audio mod to change the original music to your custom music.
Unzip the HD Audio mod and take note of where you put its folder. Then go back to Dolphin, right-click on Super Paper Mario, and select "Start with Riivolution Patches". 

Dolphin will then tell you to find an XML file. Go to your HD Audio mod folder and select riivolution/SPMHDSound.xml. Choose "Enabled" from Dolphin's dropdown menu, click "save as preset", give it a title of your choosing, and save the resulting JSON file to your Dolphin ROMs folder.

## Now you have to convert your music into a format the game understands. 
Super Paper Mario uses BRSTM files for its music, and most computers don't recognize that file type. Thankfully, some people on the internet have made it easy for us to change common music files to BRSTM.

Go to [mu-wave BRSTM Maker](https://kazuki-4ys.github.io/web_apps/mu-wave/), click the big button in the center of the screen to upload your song, and optionally drag the arrows around to trim the audio. If you're changing background music, make sure to check the "Loop?" checkbox and set the loop's starting point by dragging the top-left arrow. Once you're satisfied, download the BRSTM file and give it a temporary name.

## Time to finally put your custom music into the game!
Use [Nikku BRSTM Player](https://kenrick95.github.io/nikku/) to play the BRSTM files in the "SPMHDAudio" folder of the HD Audio mod. Once you find the song you want to replace, change your song's filename to the EXACT filename of the original song, copy your song to the "SPMHDAudio" folder, and choose to replace the original song. Repeat this step as many times as you need to build your custom soundtrack.

If you've done everything correctly, you should now be able to start the game through your custom-named JSON and listen to your custom music! You can also easily revert back to the default music by starting the game without the Riivolution patch or changing the setting back to "Disabled".
