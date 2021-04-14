# Blood Bank Management Application (Java)

A console based app using OOPS, Core Java and Java Database Connectivity concepts. Provides options for donor registration, eligibility check, seeker demand check and staff member activities.

The project is made using Netbeans 8.2 IDE. The database used is Oracle XE 18.0. The project is developed and compiled 
using jdk 8. 

Following tables have been used:-

1. Donor table - It contains the information of all registered donors.
2. Seeker table - It contains the information of all registered seekers
3. BloodInv table - It contains stock information of each blood group packet.

The src folder contains the source code.
It contains 15 files:-
1. AddDonor.java - for Adding a donor ecord in the database
1. AddSeeker.java - for Adding a seeker ecord in the database
3. Client.java - the main user interface
4. Create_Inv.java - for Creating Blood Inventory table
5. CreateDonor.java - for Creating Donor table
6. CreateSeeker.java - for Creating Seeker table
7. Delete.java - for deleting a record from the database
8. Display.java - to display eligibility conditions for Blood Donation in India
9. Donor_Reg.java - for registering a new potential donor
10. GenerateUID.java - to generate unique identification number for donors and seekers
11. Inv_Init.java - to Initialize the Blood Inventory.
12. MedCheck.java - to verify medical details in order to identify eligible donors
13. Search.java - to search the Blood Inventory for requested blood packets
14. Seeker_Reg.java - for registering all seekers
15. Update - to Update details of donor/seeker 

To run the code:-
1. Clone the github repo to your local machine
2. Extract the BloodBank.rar file 
3. Open Netbeans IDE 8.2
4. Go to File > Open Project and go to the location where you have extracted your BloodBank.rar file and select 
   BloodBank folder and select open.
5. First of all go to run and build the application. Then open CreateDonor.java and click on run and run this file. 
   Repeat the same for CreateSeeker.java, Create_Inv.java and Inv_Init.java
6. Now, run the Client.java file.

NOTE:

The BloodBank.pptx powerpoint presentation conatins useful information such as the class diagrams, use cases, database design and flow diagram.
 
