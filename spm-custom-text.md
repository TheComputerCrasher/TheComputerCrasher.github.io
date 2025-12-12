# How to add custom text to Super Paper Mario

## Prerequisites
For this tutorial, you will need to install and set up [Dolphin Emulator](https://dolphin-emu.org/),* a text editor such as [Notepad++](https://notepad-plus-plus.org/) or Luma48's SPM-specific text editor called [Flint](https://github.com/Luma48/Flint), and a Super Paper Mario ROM file. You can either dump a legally-obtained game from a real Wii using a [Homebrew Channel](https://wiibrew.org/wiki/Homebrew_Channel) app, or you can find a ROM online.

\*FOR WII NERDS: Yes, you *can* use original hardware and Wiimm's ISO Tools directly, but it's much simpler to just do everything through Dolphin, so I will be using it in this tutorial.

## Once you have everything set up, you need to extract the ROM's files. In Dolphin Emulator, right-click on Super Paper Mario and select "Properties".
In the Properties menu, scroll over to the "Filesystem" section. You may have to click the arrow buttons at the top of the menu to find it.
Right-click on "Disc", click "Extract Entire Disc...", and choose a folder to save the files in. Then inside that folder, navigate to DATA/files/msg/\[the language folder of your choice]/\[the text file of your choice]. 

## To be able to test your changes in-game, you need to let Dolphin know that you want to use this editable copy of the game.
In Dolphin, click the "Config" button at the top of the screen and go to the "Paths" tab.

Click "Add" in the bottom right, and navigate to DATA/sys in your ROM's folder. A new Super Paper Mario should appear in your Dolphin games list. (To check which is which, right-click one, choose "Properties", and look at the file name. You want the one with the name "main.dol".)

## You can now experiment with Super Paper Mario's text in the text file of your choice!
Be careful not to delete the null characters in the files (usually represented by an empty box or the word "NULL"), because removing any of them causes all the in-game text from that file to not work correctly. If you don't see the null characters, you may need a different text editor.

To quickly experiment with Super Paper Mario's formatting, you can use my [SPM text editor website](https://thecomputercrasher.github.io/spm-text-editor), the [Flint](https://github.com/Luma48/Flint) tool I mentioned earlier, or just test the changes in-game each time you make changes by launching the "main.dol" version of the game. Note that the changes will only load when you close and reopen the game.
