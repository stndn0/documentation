# Create a folder
	mkdir foldername

# Delete a folder
	rmdir foldername

# Delete a folder with files
	rmdir foldername -r
	(-r = recursive)

# Rename a folder
	mv foldername newname

# Move a folder to another folder
	mv sourcefolder targetfolder

# Move a folder up one level
Move /misc/folder/nestedfolder into /misc/folder
i.e. we want nested folder to be in /misc

	Note: current directory is /misc/folder
	mv nestedfolder ..

# Move folders in general
	mv pathToFolder pathToMoveTo

Note that these commands support relative paths. Don't need to type the entire dir.

