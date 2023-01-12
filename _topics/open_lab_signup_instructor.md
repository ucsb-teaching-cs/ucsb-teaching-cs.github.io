---
topic: "Open Lab Signup: Instructor"
desc: "Process for signing up for open lab hours"
open_lab_hours_cal_url:  https://calendar.google.com/calendar/embed?src=c_63b5996e60394b6a3b1710ad1332901ffe44a7ee8f577acee5f98eb956dfb5cb%40group.calendar.google.com&ctz=America%2FLos_Angeles
cs16_url: https://ucsb-teaching-cs.github.io/calendars/cs16
cs24_url: https://example.org
all_open_lab_office_hours_url: https://example.org
---

<style>
 summary { 
     border: 4px solid #9CBEBE;
     padding: 0.5em;
     background-color:  #DAE6E6;
     margin-bottom: 0.5em;
 }

 summary p {
  margin: 0px;
  padding 0px;
  display: inline-block;
 }
    
 details { 
    margin-top: 0.5em;
    margin-bottom: 0.5em;
    margin-left: auto;
    margin-right: auto;
    width: 95%;
    border: 4px solid #047C91;
    padding: 0.5em;
 }
</style>



Open lab hours refers to the times that these rooms:

* Phelps 3525, 3526, 2510

Are reserved for TAs/LAs/Instructors to hold in-person office hours for these courses:

* CMPSC 5A, 5B
* CMPSC 8 (in-person version)
* CMPSC 9, 16, 24, 32, 40, 64
* CMPSC 40, 130A, 130B
* CMPSC 111, 148, 156

Starting with W23, we are piloting a new process for signing up for these hours.

# Instructor Steps

Note that these steps are for **instructors**, not for TAs/LAs.  TA/LAs should follow these instructions instead:  <https://ucsb-teaching-cs.github.io/topics/open_lab_signup_tas_las/>

You can visit the link below to see the calendar that shows all of the times that the rooms are available.

* [UCSB CS Open Lab Hour Room Availability](/calendars/open)
* [All Open Lab Office Hours](/calendars/all)
   
TAs/LAs are encouraged to sign up for office hours during these times.  If it is helpful or necessary for them to hold office hours at other times,
they may do so either (a) online on zoom, or (b) using the "TA Trailer", or some other location.

Here are the calendars we've received so far:

| Course | Office Hours |
|--------|--------------|
| CS16   | [CS 16 Office Hours](/calendars/cs16) |
| CS24   | [CS 24 Office Hours](/calendars/cs24) |
{:.table .table-sm .table-striped .table-bordered}


# Start by creating a Google Calendar for your course's office hours

Please take the following steps.  There is an animation that shows each step following the list of steps below.

1. Create a Google Calendar called, for example, "CS16 Office Hours" or "CS24 Ofc Hrs".  
2. Make the calendar public; you'll want it to be public so that students in your class can easily find the published schedule.  We'll show
   you how to embed this on a web page or link to it from your website later in these instructions.
3. Add phtcon@ucsb.edu, diba@ucsb.edu to the calendar with the permission "Make Changes and Manage Sharing".
4. Now add all of your TAs and LAs to the calendar with the permission `Make Changes to Events`.  If you have them all in a spreadsheet, you can copy paste a list of emails in and then hit return, as shown in the second animation below.
5. Once the calendar is created, send an email to phtcon@ucsb.edu, diba@ucsb.edu informing them that you created the calendar, and send them a link to it.

![add-new-calendar](https://user-images.githubusercontent.com/1119017/211234283-17a2ff6f-f34e-438b-a039-86732f118710.gif)

# Adding multiple TAs/LAs at once

This animation shows how to copy/paste a whole group of emails from a spreadsheet or list to add multiple TAs/LAs at the same time:

![copy-paste-tas-las](https://user-images.githubusercontent.com/1119017/211238046-7719d997-6994-4a8a-843d-eb0752c53709.gif)


# Then, invite your TAs/LAs to create events on the calendar

Send each of your TAs and LAs a message saying:

> I've invited you to a Google Calendar called "CSxxx Office Hours".
> Please take these steps next:
> * Find the calendar invite in your email; it will look like this:
>   <img width="606" alt="image" src="https://user-images.githubusercontent.com/1119017/211951460-bec4c768-fd17-475e-8afe-718e46ae92b7.png">
> * In the email, click the link where it says `Add this calendar`
> * Please then read and follow these instructions about adding your office hours to the calendar
>   * <https://ucsb-teaching-cs.github.io/topics/open_lab_signup_tas_las/>
> * Please be sure that you add the events in the format requested, e.g. `CSxxx, Name, Location`
> * It is not necessary to write `Office Hours` in your event title; since everything on the calendar is office hours unless otherwise specified.

You may add any additional instructions you like about the number of office hours, etc.

# If you like, add additional events

Instructors may wish to add entries for events such as these so that the calendar is useful for the students in the course.

   * CS8 Staff Mtg
   * CS24 Lecture
   * CS32 Sections

If so, please put details such as location, etc. in the description as opposed to the title.  Also, please follow the naming convention
shown above; this will help us aggregate the individual calendars into one view so that we can get a sense of the room utilization.

# Publish your calendar 

There are at least two ways to publish your calendar:

1. You can get the public link to the calendar and include it on your website.  This animation shows where to find that link, i.e. by clicking
   the three dots next to the calendar, selecting **Settings and Sharing**, then scrolling down to the heading **Integrate calendar**, and
   finding `Public URL to this calendar`

   ![get-cal-link](https://user-images.githubusercontent.com/1119017/211234693-1d03eff0-a93d-4019-96db-a4f04cce2f82.gif)

2. You can embed the calendar in an existing web page.  To do this, go to the same place on the web page as shown in the animation above; 
   right below the public URL there is `Embed code`.  This is an `<iframe>` element that you can copy/paste into the HTML for any web page.
   
   Note that you can customize some aspects of the embedded calendar.
   
   To make the calendar look nicer, you can include the following CSS somewhere on that page before the `<iframe>` element.
   
   ```css
   <style>
     iframe { width: 100%; height: 1400px; }
   </style>
   ```

# Optional: Add the weeks

If you like, you can add "Week 1", "Week 2", etc. to your calendar by doing 10 "Copy to" operations.  

Here's how:

1. Add the Open Lab Calendar to your calendars using this link: 
   * [UCSB CS Open Lab Hours]({{page.open_lab_hours_cal_url}})
2. Open that calendar and your own calendar by selecting them with the check boxes (as shown in the animation below)
3. Select one of the weeks (e.g. `Week 1`)
4. Click on the three dots, and select "Copy to CS24 Ofc Hrs" (for example)
5. Click Save
6. Go to the next week; repeat steps 3 through 6 for each week in the quarter.

![copy-weeks](https://user-images.githubusercontent.com/1119017/211236604-11779761-7cb8-42e3-8203-25e096b1f5fa.gif)
