# Event Management Flow

## *Overview*

The **Event Management Flow** automates the process of assigning employees to internal events based on their **interests and hobbies**.  
When HR creates a new event, the flow retrieves employee data and identifies employees whose interests match the **event theme**.

This reduces manual work for HR and ensures the right employees are invited to the most relevant events.

---

## *Flow Type*

* **Auto-Launched Flow**

---

## *Trigger*

* The flow runs when a new **Event record is created** by HR.

---

## *Processing*

* HR creates an **Event** and enters the **event name, theme, date, and location**.
* The flow retrieves employee records from the **Employee object**.
* Employee **interests and hobbies** are evaluated.
* The flow compares employee preferences with the **event theme**.
* Employees whose interests match the event theme are selected.
* The system assigns or invites the matched employees to the event.

---

## *Output*

* List of employees matched to the event
* Updated event participation records

---

## *Impact*

* Automates event participant selection
* Saves HR time in organizing company events
* Encourages employees to participate in events aligned with their interests
