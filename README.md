# Hades II Auto Backup

## Features:
- Create a backup of save files
- Load latest backup
- Load specific selected backup from the list
- Set hotkeys for save and load

## How to Install and Use:
1. Download archive for your system
2. Extract folder to any place
3. Run hades2_auto_backup executable from root folder

The app is fully portable, no installation needed, and all its backups, temp files and settings are contained in its folder.

## How to Use (Detailed):
1. Start the game or the program, order doesn't matter
2. Start your run
3. Either alt-tab to program or use hotkey that you can set in settings to save the game at any point you want. You can make as many backups as you want and they all will be listed in the program UI.
4. When you want to load backup you need to first return to main menu and then you can either switch to app and click the button, or you can use hotkey for load latest backup. From the app UI you can also load specific backup from the list.
5. Then you just click play again and you will see on your save file that you are back where you were
6. After run is over, I suggest you delete all backups using "Clear all backups" button, since this program was meant to be used as checkpoint system rather than long term saving backups. This will help you avoid problems like "accidentally loaded old backup and lost progress".

**⚠️ IMPORTANT NOTE:** On Windows if you extract archive using standard Windows method, it will have MotW, which means it will not be trusted because it was downloaded from internet and executable is not signed. That doesn't mean app is malicious, it's just I couldn't figure out how to make it trusted without buying expensive signing certificate. You need to click "More info" and then "run anyway" if you want to use the app.

## How to Uninstall:
Just delete folder

---

## FAQ

### ❯ Do I need to disable Steam synchronization?
No! You do not need to do it nor you should. If you load backup while game not running, Steam might ask you which files you want to use, local or cloud. In this case you choose local if you want to use the backup. But I suggest you to always run program while in game for both save and load. This way you will not see any conflicts.

### ❯ Can it corrupt or delete my saves?
No, it can't corrupt or break your saves. However, you have to be careful when restoring backup since it will override whatever current save file you had. That means, if you create backup, then play further and then restore this old backup, you might lose this new progress. But even in that case, Steam cloud will still have your latest save file and ask if you want to use local or cloud, you can just choose cloud.

### ❯ Can I use it for different profiles at the same time?
Yes! The program keeps backups separately for different profiles, you can tell by P1, P2 etc before the date of backup in the list (see screenshots). This way, you don't have to worry about overriding your save files from different profile, it will never happen.

### ❯ Is it a virus?
Nope.

### ❯ What happens if I create backup in the middle of the fight?
It will just load you wherever it was last possible.

### ❯ Game doesn't let me quit while in fight, do I have to finish it before loading?
No, you can just use Undo Night from the game menu whenever you want.

### ❯ After loading backup, it didn't load me where I thought it would. Why?
Normally, game allows you to quit after the fight in room. The "Quit" button is not grayed out. If you save backup at this moment, it will work as expected. But sometimes for some reason I don't fully understand, even after fight is finished and reward collected, button "Quit" is still grayed out which means you can't quit yet and have to move to the next room. If you create backup at this point, then quit and load it, it might roll you little bit back. At start of the latest room at max. This works basically same as original game save system, it has nothing to do with backups themselves.

### ❯ Does it work on Steam Deck/Linux/Mac?
Honestly, I don't have any of those above, but it should work. I just didn't test them.
