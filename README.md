# Apexcify-Internship-Task-3-Task-Automation-Moving.JPG-Files
# Task Overview
This project is a Python-based automation script designed to move all .jpg and .jpeg image files from a source folder to a destination folder automatically. The script intelligently detects the user's Desktop directory and organizes image files efficiently.

# Features
Automatically detects Desktop path
Creates source and destination folders if they do not exist
Moves all .jpg and .jpeg files
Provides real-time feedback during execution
Counts and displays number of files moved
# Folder Structure
source_photos/ → Place all JPG images here
destination_photos/ → Moved images are stored here
# How It Works
The program locates the Desktop directory
It checks if the source folder exists
If not, it creates the folder and prompts the user
It scans for .jpg and .jpeg files
Moves the files to the destination folder
Displays the total number of files moved

# Sample Output
Looking for photos in: Desktop/source_photos
Moving them to: Desktop/destination_photos
Done! 3 JPG files moved successfully!

# Tools & Technologies
# Python
# os module
# shutil module
