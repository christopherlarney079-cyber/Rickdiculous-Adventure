# The-Rick-Game
For Friends

# How to Play Rickdiculous Adventure

Oct 29, 2026 · @Sir

## Before you start

The game runs on your own computer in your web browser. It takes about 5 minutes to set up the first time. You don't need a Claude account or a GitHub account.

You need:

- The zip file **rickdiculous-adventure-2026-10-29.zip** 
- Chrome, Edge or Safari
- Python 3 (free; the steps below show how to get it)
- An Xbox controller for two-player air support (optional for solo)

Don't double-click `index.html`. The game won't load that way. Follow the steps for your computer below instead.

Multiplayer online doesn't work in this version. Single-player runs normally.

## Mac

1. **Unzip the game.** Double-click **rickdiculous-adventure-2026-10-29.zip** in your Downloads folder. A folder called **rickdiculous-adventure** appears next to it.
2. **Open Terminal.** Press **Command + Space**, type `Terminal`, and press **Return**.
3. **Go to the game folder.** Type this and press **Return**:

   ```
   cd ~/Downloads/rickdiculous-adventure
   ```

   If you unzipped it somewhere else, type ` cd  ` (with a space after it), drag the folder into the Terminal window, and press **Return**.
4. **Start the game server.** Type this and press **Return**:

   ```
   python3 -m http.server 8000
   ```

   You'll see `Serving HTTP on :: port 8000`. If a pop-up asks to install developer tools, click **Install**, wait for it to finish, then run the command again.
5. **Play.** Open your browser and go to:

   ```
   http://localhost:8000
   ```
6. **Stop when you're done.** Click the Terminal window and press **Control + C**, or just close it.

Next time, repeat steps 2 to 5.

## Windows

1. **Install Python (first time only).** Go to [python.org/downloads](https://www.python.org/downloads/) and click the yellow **Download Python** button. Open the installer. On the first screen, **check the box "Add python.exe to PATH"**, then click **Install Now**.
2. **Unzip the game.** In your Downloads folder, right-click **rickdiculous-adventure-2026-10-29.zip** and choose **Extract All…**, then click **Extract**.
3. **Open the game folder.** In the folder that opens, keep double-clicking into **rickdiculous-adventure** until you see `index.html`, `sfa.js` and `sfd.js`.
4. **Open Command Prompt in that folder.** Click the address bar at the top of the File Explorer window (where the folder path shows), type `cmd`, and press **Enter**. A black window opens.
5. **Start the game server.** Type this and press **Enter**:

   ```
   python -m http.server 8000
   ```

   You'll see `Serving HTTP on :: port 8000`. If it says Python wasn't found, or the Microsoft Store opens, type this instead:

   ```
   py -m http.server 8000
   ```
6. **Play.** Open Chrome or Edge and go to:

   ```
   http://localhost:8000
   ```
7. **Stop when you're done.** Click the black window and press **Ctrl + C**, or just close it.

Next time, repeat steps 3 to 6.

## If something goes wrong

| What you see | Fix |
| --- | --- |
| Black or blank screen | Make sure the address is `http://localhost:8000`, not a file path. The Terminal or Command Prompt window must stay open while you play. |
| `No such file or directory` (Mac) | The folder isn't in Downloads. Use the drag-the-folder method in Mac step 3. |
| `Address already in use` | The game is already running in another window. Close that window, or change `8000` to `8001` in the command and the browser address. |
| Python not found (Windows) | Use the `py` command, or reinstall Python with "Add python.exe to PATH" checked. |
| A Windows Firewall pop-up | Click **Cancel**. The game still works because it only runs on your computer. |
| Controller doesn't respond | Plug it in, then refresh the browser page and press a button. |
| Game loads slowly | It's about 20 MB. The first load can take several seconds. |
