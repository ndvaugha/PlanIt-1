# PlanIt
Barrett honors thesis application that allows user to create an event and receive reminders as event approaches.
Version #
Description

0.1
Create an "Event" object that contains the following information:

-Associated Group (Filler for now; will be utilized at a later date)
-Event Type
-Privacy Level
-Time 
-Date
-Location
-Comment box for details.
-Ask if user wants to set a reminder. Won't be functional until version .5.
-A button that saves an instance of the Event object.


In addition, a UI must also be created for the "Add Event" screen.

0.2
Create a "Day" object which will hold a UI list of "events" made in version .1

For UI lists, I recommend referring to BigNerdRanch's iOS guide (they have several chapters (I believe it's Chapters 8-9) on the subject).

0.3
Create a "Week" object which will hold a list of (7) "Days" made in version .2.

This will also be UI lists, so once again I recommend referring to BigNerdRanch's guide (they have several chapters (I believe it's Chapters 8-9) on the subject).

We'll need to start thinking of how we can make the days/weeks into a calendar year, and do some research on what Apple offers as far as a calendar functionality.

0.4
Create a Calendar menu which will hold a calendar that allows the user to access any day of the year and input their events.

We'll need to do some further research on the calendar functionality and how it can be implemented with our code. 

0.5
Interface with user’s phone to send notifications the on the days of events or X minutes before an event.

This shouldn't be too much work - just need to interface with Apple's preexisting calendar, which already has reminders built in.

0.6
Allow user to create a profile, including adding a picture of themselves, change the color of the texts of the events they create, add a profile name and personal name.

This will be saved locally at this time, but will later be saved to a server which will store their information. We will also want users to have a username/password so that they have to sign in.

0.7
Allow a user to create “groups”. Information about the group will be included, such as privacy levels, descriptions, and picture. The user can then submit an event under that group name.

0.8
Design a logical and intuitive interface that is visually appealing, easy to use, and results in a positive user experience.

We should be developing this interface as we go along, so maybe we can just brush up the interface here and make it visually appealing.


1.0
Complete database functionality – able to create and upload/share groups & their associated events with other members. Also requires users to sign into their own unique profile.
