# DualPaw - e621 client for the Nintendo 3DS
<sub>Why would anyone use this?</sub>

DualPaw (haha, get it? Two paws? Two screens?... I'll see myself out.) is a homebrew application for the Nintendo 3DS which allows you to search and view images from e621's API, completely on-device! Currently, the app supports searching posts by tags, as well as buttons for viewing newest and most popular posts, just like e6's website! 

# Screenshots!

<img width="400" height="480" alt="DualpawHomepage" src="https://github.com/user-attachments/assets/1f74fd7c-73de-4c6e-b2dc-ac1269721d44" /> <img width="400" height="480" alt="DualpawSettings" src="https://github.com/user-attachments/assets/5ad0b8af-d003-4667-9957-54d5a8fd14f2" />

# How does it work?
Upon entering search tags (or pressing the "new" or "popular" buttons), DualPaw calls e621's API and fetches a .json containing info for the 6 most recent (or most popular, if using the popular button) posts. Images are then decoded and displayed on screen, inside the spaces on the image grid. .json info is then cleared from memory before fetching more posts, to accomodate the limited RAM of the Nintendo 3DS (seriously, this is important! If memory wasn't cleared in between retrievals, the app would crash within 2-3 searches).

# Current Working Features
- Home page
- Semi-decent UI? (~~not really~~)
- Random mascot images, stored locally to improve speed
- Search posts (with multiple tag support!)
- New button (fetches newest posts)
- Popular button (fetches popular posts)
- 6x2 image grid

# Okay, but... Why?
Simply because I thought it would be funny :D I'm fully aware that there are better ways to access e621, but come on! Viewing on a 3DS with a dedicated app? Now THAT'S funny!

# Alright, you've convinced me... How do I install?
Awesome, I'm glad you asked!
You'll need:
- A modified Nintendo 3DS/2DS/New 3DS/New 2DS, whatever. As long as it can run 3DS software, it'll work! If your device is not modified yet, check out 3ds.hacks.guide
- A computer or some other device which can transfer files to an SD card. ~~this won't be required once I stop being lazy and make a .cia with a QR code~~
- A working internet connection! We can't just pull images out of thin air, sadly...

You'll need to download the latest .3dsx and .smdh files from [here](https://github.com/ZerdaDev/DualPaw/releases). Once those are downloaded, plug in your SD card and drop them in your 3ds/ folder. Put your SD back in your 3DS, connect your 3DS to wifi, open the app with your homebrew launcher of choice, and... Things *should* work.

Alternatively, use a 3DS emulator. But that kind of defeats the purpose of this app, doesn't it?~

# Now, for some disclaimers...
This project is NOT affiliated with e621, Bad Dragon, or Dragon Fruit Ventures, LLC. This is an **unofficial** client for e621. If you're having issues with this software, please do not ask or harass e621 developers. Instead, open an issue [here!](https://github.com/ZerdaDev/DualPaw/issues) This app is intended for personal use. Viewer discretion is advised, please view **responsibly!**
