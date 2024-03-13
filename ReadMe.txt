README
Contact List
Summer 2020

Summary:
This is a fully functional contact list which enables users to keep track of favorite and recently accessed contacts. This was developed to be a networking tool to remember mutual connections between contacts. The program reads contacts from an input file in CSV format and allows users to input pictures for each contact. Clicking the star in the top corner of the contact adds the contact to the Favorites list and changes the star from a black/white star to a yellow-filled-in star. Selecting a specific contact brings the user to a more in-depth contact profile with notes and other information on the contact. Selecting favorites from the drop-down menu opens a new favorite-only screen. Selecting recent opens a screen with recently selected contacts.

Each line in the CSV must have one of the following formats
	1. lastName, firstName, phoneNumber
	2. lastName, firstName, phoneNumber, pictures/photoName (all images must be placed inside the pictures folder and be typed into the cvs in this format)

Limitations:
The program does not yet add or remove contacts from the source file yet. The input file also does not support adding other information at the start of program yet (such as: school, major, work, date of birth). If a source file name that does not exist inside the project folder, the GUI will popup an alert that tells the user that the file does not exist. If the format is incorrect a similar popup will appear. [place any comments or notes that will help the grader here]
Input files must be inside the project folder but not inside the application folder.

Bug Report
When clicking on a star from the recents list, the corresponding ContactShallow object in the main contacts section will not update the star until the contact is clicked in the main contacts section.

Future Works
The original idea for this project was to make an interactive graph of contacts. In the future, the application will contain a graph with contacts that point to their mutual friends. The contacts will also all save to a new output file as a local database. Additionally, there will be more formats to type in contact information instead of only allowing name, phone number, and photo to be in the input file. I would also like to make the project look nicer in the future after learning more about css styling.

