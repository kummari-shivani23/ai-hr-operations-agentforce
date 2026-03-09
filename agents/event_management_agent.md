# Event Management Agent

## *Overview*

The **Event Management Agent** helps HR automatically organize internal events by assigning employees based on their **interests and hobbies**.  
Instead of manually selecting participants, the agent retrieves employee preference data and recommends the most suitable employees for each event.

---

## *Inputs*

* **Event Name**
* **Event Theme**
* **Event Date**
* **Event Location**
* **Employee Interests**
* **Employee Hobbies**

---

## *Processing*

* HR creates a new **Event** and provides the **event name and theme**.
* The agent retrieves employee records from the **Employee object**.
* It analyzes employee **interests and hobbies**.
* The agent compares employee preferences with the **event theme**.
* Employees whose interests match the event theme are selected.
* The system assigns or invites these employees to the event.

---

## *Output*

* List of employees matched to the event
* Event invitations or notifications sent to selected employees
* Updated event participation records

---

## *Impact*

* Reduces manual effort for HR when organizing events
* Improves employee engagement by recommending relevant activities
* Encourages participation in social and networking events
