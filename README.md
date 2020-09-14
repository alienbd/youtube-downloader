# youtube-downloader

You will need python 3.3+ to run this module.

First Instal the dependencies using this command:

$ pip install -r requirements.txt


# Individual videos

If you want to download individual youtube videos 

put the links in a text folder (i.e. url.txt as provided)

Then run this command

$ python y2d.py <url> <folderName>

or
 
$ python3 y2d.py url folderName

where folderName is the folder name where you wish to put your downloaded videos.

If the folder doesn't exist a new folder with the provided name (folderName) will be created

# Playlist

To download a whole playlist run this command

$ python y2d.py -p <playlistURL>
  
  or
  
$ python3 y2d.py -p <playlistURL>
