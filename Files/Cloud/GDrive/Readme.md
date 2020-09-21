# GDriveDownload.sh
## Description
This script can be used to download files from google drive using the shell.
## Usage
Get gdrive fileid (drive.google.com/file/d/**fileid**/) and the filename.

GDriveDownload.sh **fileid** **filename**
# Installation
(Only tested on Ubuntu)
Change **installpath** variable if you want to install elsewhere.
```sh
installpath="/usr/local/bin" && sudo wget https://raw.githubusercontent.com/TheTrueCoder/Useful-Linux-Utilities/master/Files/Cloud/GDrive/GDriveDownload.sh -o $installpath/gdrivepull.sh && sudo chmod +x $installpath/gdrivepull.sh
```
