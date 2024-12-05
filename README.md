# **Automating Conference Schedule Notifications**


## **Case Study**


### **Client: Non-Profit Organization Supporting Tech Education**

The non-profit organization **Techsgiving **needed a scalable and automated solution to manage its event schedule for an annual conference. The challenge was to extract session details from the event’s HTML-based schedule, structure the data for use in Google Sheets, and automate reminders via calendar invites and SMS notifications.


### **Objective:**



* Extract and parse session details from the conference schedule webpage.
* Organize the data into a structured Google Sheet for easy management.
* Automatically create calendar events and send SMS/email reminders to attendees who opt in.


### **Impact:**



1. **Streamlined Data Management:** Eliminated manual processing of session schedules.
2. **Improved User Engagement:** Automated reminders ensured attendees were informed and engaged.
3. **Enhanced Accessibility:** Enabled users to integrate schedules seamlessly into personal calendars.


---


## **Solution Overview**
![alt text](https://github.com/TeneikaAskew/automating-web-scraping-text-calendar-notifications/blob/main/front-end.png)

### **Workflow:**



1. **HTML Parsing:** Extract session details from the event webpage.
2. **Data Structuring:** Organize parsed data into Google Sheets.
3. **Automation:**
    * Create Google Calendar events for sessions attendees plan to attend.
    * Send SMS/email reminders for confirmed sessions.


---


## **Implementation Details**


### **1. HTML Parsing and Data Extraction**

The schedule HTML was parsed using regular expressions to extract key session attributes such as:



* **Date**
* **Start and End Time**
* **Session Title**
* **Track**
* **Speakers**
* **Description**
* **Location**


## **Technical Features**



1. **Regular Expressions:** Used for precise data extraction from HTML.
2. **Google Apps Script:**
    * Managed data in Google Sheets.
    * Automated Google Calendar and SMS functionality.
3. **Scalability:** Capable of handling schedule updates and additional notifications seamlessly.


---


## **Results**



* **Reduction in Manual Effort:** Session details and reminders were handled automatically, saving hours of manual work.
* **Higher Attendance:** Timely reminders led to an increase in attendee participation.
* **Reusability:** The solution can be adapted for future events or other non-profits.


---


## **Future Enhancements**



1. **Error Handling:** Improve resilience to malformed HTML or missing fields.
2. **Customization:** Allow users to select specific sessions of interest.
3. **Integration:** Extend functionality to integrate with additional communication channels like Slack or WhatsApp.


---

This case study demonstrates how technical automation can empower non-profits to focus on their mission by reducing operational overhead while enhancing user experience.
