# Donate-Buddy
The Donate Buddy is an app to help donation drive organizers and volunteers to execute on their drives efficiently and effectively. 
It has been built on top of the Microsoft's Power Platform technology. So the app was designed using Power Apps, and data is stored in Dataverse

The file structure in this repository was created by running the below command on the DonateBuddy.msapp file

pac canvas unpack --msapp <name of .msapp file> --sources <output folder>
  
For more information, please refer to this - https://github.com/microsoft/PowerApps-Language-Tooling/blob/master/README.md
  
The app includes a lot of custom logic code (see customlogic.txt) written in PowerFx, that is used to -
  * (a) Set global variables
  * (b) Customize the startup experience
      * (i) Welcome screen is different for Organizer vs. Donation Volunteer
      * (ii) Auto-creation of entries into the Volunteer table at first-time login
  * (c) Control visibility (Only Organizer can create new donation drives)
  * (d) Search, Sort, Filter, Group on data
  * (e) Calculating shortest distance from the device's current location to each of the collection centers and donation centers
  * (f) Generating setup data for report generation
  
  

