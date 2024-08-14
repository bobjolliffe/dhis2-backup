# dhis2-backup

The features we are looking for in a logical backup script are:
1.  it should pull the database backup from the postgresql server
2.  it should be able to run unattended via cron
3.  it should not expose postgresql authentication server authentication credentials
4.  it should use the postgresql compressed format (-Fc)

Additional functionality required on the backup server (though not necessarily part of the backup script)
1.  automated testing of restoration
2.  off-site archival storage 
