# Backup-Script

## Create a Backup Script
sudo nano backup-sh
![new-script1](new-script1.PNG)

## Make the Script Executable
chmod +x backup.sh
![new-script2](new-script2.PNG)

## Run the Script
./backup.sh /home/user/projects /mnt/backups
![new-script3](new-script3.PNG)

## Schedule the Script with Cron
crontab -e
![new-script4](new-script4.PNG)

## Verify the Backup
ls -l /mnt/backups
![new-script5](new-script5.PNG)