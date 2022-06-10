** Always backup wallet.dat before making any changes **

To install the latest database files do the following:

1. Shut down the Qt/Client wallet if it is open
2. Open your BitBay data folder located in the following directory (depending on your computer OS):

- Windows users: users/“yourusername”/appdata/roaming/Bitbay folder (make sure you have “show hidden files” selected)
- Mac users: ~/Library > Application Support > BitBay
- Linux users: ~/.bitbay (make sure you have “show hidden files” selected)

3. Remove all files from inside the data folder EXCEPT FOR wallet.dat.

4. Place the downloaded bootstrap.dat file into the BitBay data folder.
5. Restart the QT/Client wallet

The wallet will begin to resync, which will take 2-4 hours. Once synced, you will be on the right chain and good to go.
