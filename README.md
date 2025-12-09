# Hades II Auto Backup

## Features:
- Create a backup of save files during a run
- Load latest backup
- Load specific selected backup from the list
- Set hotkeys for create and load

***NOTE:** You do not need to close the game to create or load a backup. You can create one at any time in game, but you need to return to the main menu in order to load.*

## How to Install and Use:
1. Download the archive for your system
2. Extract the folder to any place
3. Run hades2_auto_backup executable from the root folder

The app is fully portable, no installation needed, and all its backups, temp files and settings are contained in its folder.

## How to Use (Detailed):
1. Start the game or the program, order doesn't matter
2. Start your run
3. Either alt-tab to the program or use hotkey that you can set in settings to save the game at any point you want. You can make as many backups as you want and they will all be listed in the program UI.

   I recommend creating backups before or after entering a room. You can even make a backup while a boss is talking and it will load you in the boss room.

4. When you want to load a backup, you first need to return to the main menu, and then you can either switch to app and click the button, or you can use hotkey for load latest backup. From the app UI you can also load specific backup from the list.
5. Then you just click play again and you will see on your save file that you are back where you were
6. After the run is over, I recommend you delete all backups using "Clear all backups" button, since this program was meant to be used as checkpoint system rather than long term saving backups. This will help you avoid problems like "accidentally loaded old backup and lost progress".

**⚠️ IMPORTANT NOTE:** On Windows if you extract the archive using standard Windows method, it will have MotW, which means it will not be trusted because it was downloaded from the internet and the executable is not signed. That doesn't mean app is malicious, it's just I couldn't figure out how to make it trusted without buying an expensive signing certificate. You need to click "More info" and then "run anyway" if you want to use the app.

## How to Uninstall:
Just delete the folder

---

## FAQ

### ❯ Do I need to disable Steam synchronization?
No! You do not need to do it nor should you. If you load backup while the game is not running, Steam might ask you which files you want to use, local or cloud. In this case you choose local if you want to use the backup. But I recommend you always use the program while in game for both save and load. This way you will not see any conflicts.

### ❯ Can it corrupt or delete my saves?
No, it can't corrupt or break your saves. However, you have to be careful when restoring backup since it will override whatever current save file you had. That means, if you create backup, then play further and then restore this old backup, you might lose this new progress. But even in that case, Steam cloud will still have your latest save file and ask if you want to use local or cloud, you can just choose cloud.

### ❯ Can I use it for different profiles at the same time?
Yes! The program keeps backups separate for different profiles, you can tell by P1, P2 etc before the date of backup in the list (see screenshots). This way, you don't have to worry about overriding your save files from a different profile, it will never happen.

### ❯ Is it a virus?
Nope.

### ❯ What happens if I create backup in the middle of the fight?
It will just load you wherever it was last possible.

### ❯ Game doesn't let me quit while in a fight, do I have to finish it before loading?
No, you can just use the Undo Night from the game menu whenever you want.

### ❯ After loading a backup, it didn't load me where I thought it would. Why?
Normally, game allows you to quit after the fight in a room. The "Quit" button is not grayed out. If you create a backup at this moment, it will work as expected. But sometimes for some reason I don't fully understand, even after fight is finished and reward collected, button "Quit" is still grayed out which means you can't quit yet and have to move to the next room. If you create backup at this point, then quit and load it, it might roll you little bit back. At the start of the latest room at max. This works basically same as the original game save system, it has nothing to do with backups themselves.

### ❯ Does it work on Steam Deck/Linux/Mac?
Honestly, I don't have any of those above, but it should work. I just didn't test them.
