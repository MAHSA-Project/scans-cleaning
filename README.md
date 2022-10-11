## scans-cleaning

In MAHSA project, the team has been receiving significant number of scans both from the British Library and the Cambridge University Library. 
These scans are transferred in individual folders from the libraries to the MAHSA SharePoint regularly. 
To keep SharePoint organized and updated the scans need to be checked and sorted to their corresponding folders once are sent by the libraries. Usually this is a tedious task as it requires manual work.  

This script has been created to simplify the maintenance of the historic maps within MAHSA directory.

The functionality of this script is the following:
- Checking folders transferred to SharePoint and looking for possible missing scans.
-	Returning CSV file with name of folders containing no scan inside (missing scans)
-	Getting scans out of the folders  
-	Deleting empty folders once the scans are out.
