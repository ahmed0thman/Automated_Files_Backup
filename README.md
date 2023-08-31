A script called `backup.sh` which runs every day and automatically backs up any encrypted password files that have been updated in the past 24 hours.
The script command line arguments, as follows:
1. `targetDirectory` as the first command line argument
2. `destinationDirectory` as the second command line argument
> **Note**: To Schedule the Script to run every day.
> use the fillowing command `crontab -e` to open the editor then add the line `0 0 * * * [Sript abs path] [target dir] [dest dir]`
