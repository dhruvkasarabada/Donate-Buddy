# Donate-Buddy
The Donate Buddy is an app to help donation drive organizers and volunteers to execute on their drives efficiently and effectively. 
It has been built on top of the Microsoft's Power Platform technology. So the app was designed using Power Apps, and data is stored in Dataverse

The file structure in this repository was created by running the below command on the DonateBuddy.msapp file

pac canvas unpack --msapp <name of .msapp file> --sources <output folder>
  
For more information, please refer to the [Power Apps Language Tooling Documentation](https://github.com/microsoft/PowerApps-Language-Tooling/blob/master/README.md)
  
The app includes [custom logic](https://github.com/dhruvkasarabada/Donate-Buddy/blob/main/customlogic.txt) written in PowerFx, that is used to -
  * Set global variables
  * Customize the startup experience
      * Welcome screen is different for Organizer vs. Donation Volunteer
      * Auto-creation of entries into the Volunteer table at first-time login
  * Control visibility (Only Organizer can create new donation drives)
  * Search, Sort, Filter, Group on data
  * Calculating shortest distance from the device's current location to each of the collection centers and donation centers
  * Generating setup data for report generation
  
  The .yaml files located under [Src](https://github.com/dhruvkasarabada/Donate-Buddy/tree/main/Src) has the App start logic as well as the various screens used in the app.
  
  


