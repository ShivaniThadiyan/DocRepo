### Creating and Managing Event

The event registration page looks as below  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/event-registration-page.png"/>

**A** : The users can register for the event here with the required details and click on **Submit**.  
**B** : The name of the event is displayed here, which is same as the event name given at the time of event creation.  
**C** : This is the short description of the event, which is same as the description given at the time of event creation.  
**D** : This is the date at which the event is scheduled, which is same as the date given at the time of event creation.  
**E** : This is the time and time zone at which the event is scheduled, which is same as the time given at the time of event creation.  
**F** : This shows that the event will be held online. An event type can be either Online or In person depending on the choice we provide at the time of event creation. If we choose In person option, the address at which the event will be held will be displayed here.  
**G** : This is the language in which the event will be held, which is same as the language choose at the time of event creation.  
**H** : This is the email ID of the contact at which the event is scheduled, which is same as given at the time of event creation.  
**I** : Clicking on this will take you back to Events calendar.  

- Now we will create an **Event**
- Navigate to the portal using the link https://experience-azure-mgmt.azurewebsites.net/#/main and login with your AEC credentials.  
-Once logged in, click on **Events** on the left pane of the portal. This will list the events if any.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/select-event.png"/>

-Click on **ADD** at the top right corner of the events page, to add a new event.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/add-event.png"/>

- Now the Add Event Details window comes up, where you can provide the following details.  
•	Event Title : Enter the Name of the event, which should be displayed on the event registration page.  
•	Template : Select the template which will be used to pre-deploy the resources required for the workshop.    
•	Description : Enter a description of the event which will be displayed on the event registration page as description.  
•	Tags(optional) : Enter tags such as Azure, checkpoint. Not being used as of now  
•	Event Type : Choose either of the following type  
	Virtual : Choose this type when the event is to be conducted online  
   <br>a.	Link to online meeting : Provide a link on which the Attendees can join the event  
	In Person : Choose this type when the event is to be conducted offline  
   <br>a.	Address : Enter the required details so that the Attendees gets to know where the event is held. It will be displayed on the event registration page.  
•	Sponser(optional) : Choose the sponser of the event from the list.    
•	Channels(optional) : Specify the channel to which the event belongs to.   
•	Email Template : Choose the template for emails sent out to event participants. This template defines the structure and content of the emails.  
•	Suscription Group : Specify the Azure subscription detail to be used while deploying the resources required for the event.    
•	Is Private : Check this option if you do not want to show up this event on public pages. This can be checked for test or dry run events.  
•	Time Zone : Scroll and select the time zone from where you are setting up the event. This will be displayed on the event registration page.    
•	Start Date and Start Time : Specify Start date and time of the event.  This will be displayed on the event registration page.    
•	End Date and End Time : Specify end date and expected time on which the event will end. This will be displayed on the event registration page.    
•	Approval Type : Specify how the participant registrations should get approved  
	Manual : Will have to manually approve participant registrations.  
	Automatic : Will automatically approve the registration until the total limit is met.  
•	Maximum number of users : Define the maximum number of participants for the event. Any registration after reaching this number would be marked in waitlist category.  
•	Allow personal email addresses : Checking this option will allow sign up to the event from social accounts such as gmail,yahoo,etc, Business/Work emails address are always allowed.  
•	Contact Email : Specify the email address that will appear on the event registration page for any support/questions about the event.  
•	Survey URL(optional) : This is to collect feedback post event, you can leave this blank to start with and enter survery url later on if required.  This will be sent to participants in thank you email after the completion of event.  
•	Recorded Session URL(optional) : Provide the link to recorded session. you can leave this blank to start with and enter survery url later on if required. You can choose to send this to participants after training.  
•	Language(optional) : Specify the language to be used in workshop. This will be displayed on the event registration page.    
•	Additional Notes(optional) : Type in additional notes if any, which will be shown on the public event page.  
•	Schedule Remainder Email : Check the options below to send event remainder email automatically.  
	Before Two Weeks  
	Before Two Days  
	Before Two Hours  
  Click on Submit.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/event-creation.png"/>

-Now you can see the event that you just created, in the Event page.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/event-list.png"/>

### Archieve an Event

Navigate to the portal using the link https://experience-azure-mgmt.azurewebsites.net/#/main and login with your AEC credentials.  
-Once logged in, click on **Events** on the left pane of the portal. This will list the events if any.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/select-event.png"/>

-Now click on **Archive** icon coreesponding to the evnet you want to archive.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/archive-event.png"/>

-Now you can find the archived event by clicking on **Archived Events** options at top right corner of events page.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/Archive-list.png"/>

### Manage Registrations


-Now we will **Approve/Reject** the attendees registration from AEC portal.  
-Navigate to the portal using the link https://experience-azure-mgmt.azurewebsites.net/#/main and login with your AEC credentials.  
-Once logged in, click on **Events** on the left pane of the portal. This will list the events if any.  

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/select-event.png"/>

-Now click on **Manage this event**  button corresponding to your event, in the Events Page.

<img src="https://github.com/Suraj2093/Azure-Experience-Centre/blob/master/Images/open-event-settings.png"/>

-Now inside event page, scroll down and under the registration section, click on **Manage Attendees**.

