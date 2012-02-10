Three utilities for finding applications in iOS.

1. lsa - Lists all applications.
2. cda - Changes to the directory of the applications.
3. rebuild_app_db - rebuilds the application database.

Dependencies:

1. sqlite3

Install Info:

Install sqlite with:
	sudo apt-get install sqlite3

Note: Requires APT7-Strict package being installed in Cydia.

Make /usr/local/db for the database to live in.
	
	mkdir -p /usr/local/db

Source cda in bashrc.

	echo "source /usr/local/cda_source" >> ~/.bashrc

Make sure bashrc is actually sourced with:

	echo "source ~/.bashrc" > ~/.profile

Move lsa cda_source and rebuild_app_db to /usr/local/bin.

You're good to go.
