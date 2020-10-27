Backup Azure SQL Databases to Blob storage
==========================================

            

This Azure Automation runbook automates Azure SQL database backup to Blob storage and deletes old backups from blob storage.


You should use this Runbook if you want manage Azure SQL database backups in Blob storage. 
This runbook can be used together with Azure SQL Point-In-Time-Restore.

**Before running script you most probably need to update your modules (AzureRM.SQL 1.0.12 or newer is needed)**


  *  Open your Automation account 
  *  Go to Assets and then to Modules 
  *  Click 'Update Azure Modules'. It takes about 15 minutes. 

You can also use [Powershell Runbook from Microsoft](https://github.com/azureautomation/runbooks/blob/master/Utility/ARM/Update-ModulesInAutomationToLatestVersion.ps1).

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
