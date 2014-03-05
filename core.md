Core Notes

-Users
  - When specific users are created it creates a login for them (teacher, distributor, sales rep).  These users need a way to login.  How will we get the password (the username is their email) to that user.
    - Send an email to the email address with a temporary password that needs to be changed?
  - Some users won't have all their information (email address, phone number, etc) necessarily from the start. How do we want to handle this?
    - Student/Parent
      - My suggestion is to have a process that allows the teacher to pass out cards/information with an ID of some sort that the student can go home and go to the site and sign in with and their parent can put in their information to be used for that user.  This will also provide a way for the teacher to see who in their class is actually participating via the website.
    - Donor
      - I know we had discussed at one point that donors should be able to log on to the website and pay for their donation.  Is this still something that is planned for this phase?  If so we need to discuss what minimum information is necessary for this to happen.  I think the process for getting the Donor login information would be very similar to the teacher/distributor/sales rep process.
  - If we go the Email route for the above items we will need to get some verbiage for each of these emails.
  - We need to territory information so we can convert all of the territories to drop downs instead of open text boxes.
  - I changed around some of the heirarchy a little bit with Schools -> Teachers -> Students.  I added a new layer: Classes.  
    - Classes will allow teachers to participate if they have multiple classes 
    - Teachers will also be able to participate over multiple years and keep their same account information
    - Note: Right now when you create a teacher it creates a single class behind the scenes and that is what students get added to. If you guys agree that classes are an acceptable addition I'll add UI to be able to add and manage classes and filter your students on what class they are in.
    - Additionally students can be in multiple classes but there "actions" and donors are the same for every class they participate in (this will have to be resolved if we decide to give them the ability to manage classes; this needs an internal discussion)

- Program Management
  - I added another dashboard that allows "someone" to manage the programs (default prizes, and some of the configuration items for the program itself)
  - I just need to know who this someone is (Distributor, Sales Rep, School, or a combination of the 3) so I can place it in the appropriate location

- Sales Rep/School Editable Areas
  - How are we allowing these to edit their specific editable areas?
  - Are we wanting Sales Reps to add information on a per school basis? per teacher basis?
  - Are we wanting Schools to add information on a per teacher basis? per student basis?
  - As a side note, the more granular we make this control the more that is involved in building the UI for being able to manage it.