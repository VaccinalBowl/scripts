Repository of scripts I find useful

# Backup.rb
This scripts main purpose is to make it easier to securely use
cloud storage such as Dropbox, Box, sync.com and google drive
among other things. The simple idea is that before putting something in a cloud storage
area to encrypt it using stong symmetric encryption first. This way we can be relatively
confident that third parties and that the cloud service providers themselves cannot read
our data while stored in the cloud.

This version just will loop through a directory and any folders found within the directory
will be encrypted using Gnu Privacy Guard. The script will then push the encrypted data
to the Cloud storage folder in the home directory.

Features to add:
 - Non Hard Coded Paths
 - Split large files over multiple storage platforms
