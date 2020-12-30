# MaintenanceDatabase
use MS access to migrate data from the excel and build a database based on client's needs
Main:

There are totally 8 forms for user to get the data entry. They are login form for login, machine management, maintenance management, vendors management, parts management form with add, search and delete. Dictionary for keeping other forms data to improve management. Near Miss Report is used to record misact in daily work. There are two reports showing machine and maintenance.

![Goal](/Slide2.png)

## Login：

Reason: For security and keeping data validation, I provide a login form so users can share the same account. In case, any unrelated people change the records unconsciously.

Password: 123456.

## Dictionary:

Definition: A Form used to simplify the management of multi-value fields.

Usage: If user wants to add new value in process or any other attribute of Near Miss Report, he or she could open the form of dictionary and go to the same name column. Then add new value at the end of the column.

## Maintenances Management:

Definition: Used to add, search, delete and update maintenances of machines. Before adding new maintenance, user should make sure the parts, machines and processes value are already in the database.

## Machines Management:

Definition: Used to add, search, delete and update machines. Before adding new machines, user should make sure the relative parts’ values are already in the database, which will automatically provide a range of parts in the maintenance management.

## Parts Management:

Definition: Used to add, search, delete and update parts.

## Vendors Management:

Definition: Used to add, search, delete and update Vendors, who provide parts.

Improvements in the future:
Add Junk table to faciliate tracking status with columns Scheduled, Repaired, Maintenanced with enum data type (Y/N).
