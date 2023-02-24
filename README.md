# update-file-date
Update the date and time for Google Takeout Photos and/or Videos, based on json file.

## SYNOPSIS
   upd-date-file -b path [-f outcome csv file] -h 

## Description:
    This scripts update the date and time for pictures and videos based on .json information that is 
    normally create when a backup is made from Google Photos via google takeout.

    -b, --base-dir=PATH
        Base directory where all files should be updated, it will include all files in sub-dir as well.

    -f, --file-name
        Build a csv file with the files informations.

    -h, --help
        Display this help and usage of the command.

> Example:
	upd-date-file -b . -f outcome.csv

Version: R1A  
Powered by: julio.araujo@jgtechserv.com.br
