Developed a system to automatically back up essential Linux files.That
stores backups in HDFS to enhance fault tolerance and scalability. By
implementing an automated scheduling mechanism to perform backups
periodically and maintain detailed logs for backup monitoring and
auditing.

The system archives designated directories into a compressed .tar.gz file.
•The backup file is transferred to HDFS.
•A log entry is generated to document the backup operation.
•The process repeats based on a schedule.
