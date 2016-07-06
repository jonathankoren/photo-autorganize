#photo-autorganize

A simple script for organizing photos and videos based on date.

This script copies image and video files from one directory into another
and organizes them based on the date the photo or video was taken. Dates are
determinied by looking at EXIF data (if available) and an analysis of
filenames. If a plausible date can not be determined, the photo / video is
filed into a directory named \_invalid\_date\_.

##Requirements
Pillow
imagehash

##Bonus Script
rsync-photos copies the most recent year's photos to your local disk.
