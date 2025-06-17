# How to add custom text to Super Paper Mario

## Prerequisites
For this tutorial, you will need to install and set up [Dolphin Emulator](https://dolphin-emu.org/) and [Notepad++](https://notepad-plus-plus.org/), and you will need a Super Paper Mario ROM file. You can either dump a legally-obtained game from a real Wii using the [Homebrew Channel](https://wiibrew.org/wiki/Homebrew_Channel), or you can find a ROM online somewhere.

## Once you have everything set up, you need to extract the ROM's files. In Dolphin Emulator, right-click on Super Paper Mario and select "Properties".
In the Properties menu, scroll over to the "Filesystem" section. You may have to click the arrow buttons at the top of the menu to find it.
Right-click on "Disc", click "Extract Entire Disc...", and choose a folder to save the files in. Then, navigate to DATA/files/msg/\[the language folder of your choice]/\[the text file of your choice]. 

## To be able to test your changes in-game, you need to let Dolphin know that you want to use this editable copy of the game.
In Dolphin, click the "Config" button at the top of the screen and go to the "Paths" tab.

Click "Add" in the bottom right, and navigate to DATA/sys in your ROM's folder. A new Super Paper Mario should appear in your Dolphin games list. (To check which is which, right-click one of them, choose "Properties", and look at the file name.)

## You can now experiment with Super Paper Mario's text in the text file of your choice!
Be careful not to delete the "NULL" characters in the files, because removing any of them causes all the in-game text from that file to not work correctly. This is why you need to use Notepad++. 

To quickly experiment with Super Paper Mario's formatting, you can use my [Super Paper Mario text editor](https://thecomputercrasher.github.io/spm-text-editor), or you can test them in-game each time you make changes by following the rest of the steps. 

## Now, boot up the game and look for the text you changed!
Make sure to open the "main.dol" version of the game, otherwise it will not load your custom text. Also, note that you will have to close and re-open the game to see your latest changes in-game. 
