📱 Contact Manager

VIDEO: 
Following the creation of my app, the app crashed and I haven't been able to log in or use the app any longer. I spoke with professor Wolber and showed him the app, and he said it was okay if I couldn't get a full video of it functioning.

Project Overview:

Many people struggle to keep track of professional contacts. This app serves as a central hub for people to store contact information and stay organized with how they know people. For my own purposes, it was a useful way to keep track of professors I’ve had, and contacts at different museums. I could add someone to multiple groups- i.e. my supervisor's info can be stored in both “Potential References” and “Asian Art Museum.” 

Run the app at:
https://dulcet-cocada-2dd9a8.netlify.app/ 

Initial Prompt and Bolt Response

Initial Prompt to Bolt: 
I started with the MyPeeps app tutorial, which included the following prompts:

Create a web app that lets the user keep track of important persons they come across in their research. The home page should list the persons already entered. The home page should also have a + button that when clicked opens a second window, which allows a new person to be added. 
Add user registration and login to the app, and change the app to use persistent data with a Firebase Firestore database. Make it so the data is user specific-- each user has their own list of persons that they can record. Use the following Firebase project settings: ‘’
Change the app so that the user can add groups and put persons into groups. The app should have tabs for 'People' and 'Groups'. When the user clicks on a group it should open a page showing the group title and a list of the persons in the group. Clicking on a person should generate a popup that allows the user to add the person to any of the groups.

And my own prompt: 
Add the ability for a user to upload a photo for people. They should be able to enter an image url and have it show up next to the name of the person. Add the ability to edit people's information cards, and the ability to delete people. Also, save the data between sessions for a user's people and groups

Bolt’s Response:
The initial prompts generated a very clear and functional app, with a simple UI. I had some issues connecting to the firebase, but when I asked Bolt for help it gave me a simple solution, within the firebase website. The app also has some UI issues, like a persistent lag between creating a group and being able to add a person to it. 

Was it what you expected?
Yes, Bolt built a good foundation, which allowed me to create people, add information about them, and sort them into groups. It wasn’t particularly geared towards professional development, so I had to adjust things like the available fields in each person’s page.

Followup Prompts Regarding Features, and Bolt Responses

Here are five feature-related prompts I gave to Bolt and what happened:
1.        Prompt: “Add the ability to edit and delete groups.”
Response: Bolt added an edit icon, and a delete one. These show up when you hover over the person’s listing.

2. 	Prompt: “When the user selects a group, open a separate category of “group 
members.”
Response: Clicking the group name while on the Group tab now opens a list of members. 

3.   	Prompt: “In the person’s info card, add fields for a linkedin profile link, phone 
numbers, and email addresses.”
Response: That worked successfully, but the new index card profile fills the screen past where the user can close the window, and isn’t able to scroll. Without me expecting it to, the app connected to my phone, email, and browser, so that clicking the phone number, email, or browser information on a person’s card opens the respective window. 

4. 	Prompt: “Enable the user to easily scroll through the person profile, and close 
the window. Automatically save the user’s additions to the person profile” Response: This made the index card profile fit the screen much better, and closing the window possible

5. 	Prompt: “add the ability to export the list of information into a google doc or 
spreadsheet” 
Response: Bolt added the ability to download all the saved information, but the format is unclear, and it didn’t actually connect to google docs. 

6. 	Prompt: “Add the ability to send an individual contact card to an email address, 
or save it as a pdf.
Response: Bolt added another button that appears when hovering, which enables the exporting of just a single contact. 

Followup Prompts Regarding User Interface, and Bolt Responses
Here are five UI prompts I gave to Bolt:

Prompt: “when the user downloads the file, make the exported information a pdf, more clearly organized under the heading of the person's name”
 Response: Now when the file is downloaded the format is easier to move from one space to another

Prompt: “Color code the background of a person’s information by group, using primarily pink, orange, and light blue shades.”  
Response: 

Prompt: “Add a button for adding people to a group” 
Response: Now, rather than just clicking the person, there’s a button to add people to the group.

Prompt: “Add the ability to create a new group from within add to group button screen” 
Response: This worked, but the UI is a little clunky, so I prompted to simplify the visuals.

Prompt: “Change UI to be light blue and orange backgrounds.” 
Response: Made the app as a whole more colorful and interesting to look at. 

Summary
Final App Description:

The final app is a flexible contact book, which allows users to add people, and their contact information. They can be tagged in groups, and the information can be exported on an individual level, or as a full list of contacts. 
What I liked about Bolt:
My requests generally worked without needing any intervention on my part.
When errors did appear, fixing them was generally simple through additional prompts, or the site’s own updates
I learned how to prompt more effectively, and the limits of what the site can do.
Challenges / Issues:
Styling things is difficult, as the site doesn’t have any particular tools for customizing beyond trying to describe the look I want.
Sometimes a feature I put in would disappear, and would need to be reprompted
Despite multiple attempts to fix it, data retention continues to be an issue when logging back in
Updates and prompts are very slow.
I had to pay for a subscription ($20 a month) to have enough prompting available to create my full app.
Overall, this project enabled me to create a much more complex site than I would have been able to make coding on my own, and Bolt was much more functional on my particular device, given that it’s web-based. 
