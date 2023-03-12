Issue Summary:

Duration: March 9, 2023 8:00 AM - March 10, 2023 2:00 PM EST (30 hours)
Impact: The online shopping service was down, and customers were not able to access the website. The outage affected 80% of the users.

Root cause: The root cause of the outage was a database issue that occurred due to a disk failure.

Timeline:

March 9, 2023, 8:00 AM EST: The issue was first detected when a monitoring alert triggered, indicating that the database was not responding correctly.
The team started investigating the issue and found that the website was not loading for users.
They tried restarting the server, but it did not fix the issue.
Assumptions were made that the database had some configuration issues, so the team tried adjusting some settings but did not see any improvement.
March 9, 2023, 11:00 AM EST: The team escalated the incident to the senior database engineer.
March 9, 2023, 12:00 PM EST: The senior database engineer identified the root cause of the issue as a disk failure.
March 9, 2023, 1:00 PM EST: The team replaced the faulty disk and restored the database from the backup.
March 10, 2023, 2:00 PM EST: The issue was resolved, and the online shopping service was back up and running.
Root cause and resolution:

The root cause of the outage was a disk failure that caused the database to stop responding. The faulty disk was replaced, and the database was restored from the backup. The issue was resolved by fixing the hardware failure and restoring the database.

Corrective and preventative measures:

To prevent future outages, the following measures will be taken:

Regular hardware maintenance will be performed to ensure that all disks are functioning correctly.
Additional monitoring will be set up to detect disk failures and prevent data loss.
The backup strategy will be reviewed and updated to ensure that the most critical data is backed up frequently.
The team will perform a postmortem to identify any additional steps that can be taken to prevent similar issues from happening in the future.
Tasks to address the issue:

Replace faulty disks promptly to prevent data loss and service disruption.
Review and update backup strategy to ensure that critical data is backed up frequently.
Implement additional monitoring to detect disk failures and prevent data loss.
Perform a postmortem to identify any additional steps that can be taken to prevent similar issues from happening in the future.
