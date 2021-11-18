# Zabbix Mysql Partitioning using Stored Procedures
These scripts aren't mine but try to preserve them from being lost in space. These scripts will create partitions for your history and trends tables. I have tested them in Oracle's Mysql version 5.7 and 8.0 and they work. Just make sure the event_scheduler is set to ON in your Mysql instance!

Use the scripts in the following order:

1. Stored Procedure Partition Create.
  
2. Stored Procedure Partition Drop.

3. Stored Procedure Partition Verify.

4. Stored Procedure Partition Maintenance.

5. Stored Procedure Partition Maintenance all
    Check the values in this file because this will be used to determine how long data will be preserved!
    
