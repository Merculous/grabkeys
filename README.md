This project was inspired by Matteyeux with his ios-tools repo, this will be a similar project but for my own practice. Also, in native Python 3 code :D

## Note
Due to compatibility, ensure Python 3.6 or newer is installed. Basially this is just due some things being changed like format strings and etc.

## Commands
	--buildid device iOS  | convert an iOS to its buildid
	--baseband device iOS | get baseband version of an iOS
	--codename device iOS | get codename of an iOS
	--download device iOS | download an ipsw
	--keys device iOS     | get keys for an iOS
	--manifest device iOS | download a build manifest from an iOS
	--signed device       | print the signed versions for a device
	--shsh                | (replace your own device with mine in tss.py)
	--split key           | Splits a GID decrypted key 
	
## Prerequisites
	pip install -r requirements.txt
	
## Planned
	foreman: key grabbing/uploading
	template: auto key uploading

## Credits
	Visual Studio Code: Holy! I love this IDE! (better than Pycharm...)
	Matteyeux @matteyeux: inspiration, some techniques from ios-tools
	Noah/32Bites @TheNoahParty: some techniques from PyKeys
	IPSW download progress: https://blog.shichao.io/2012/10/04/progress_speed_indicator_for_urlretrieve_in_python.html (have plans to make my own function that will replace this)
	mcg29 @mcg29_: Helping with this project
