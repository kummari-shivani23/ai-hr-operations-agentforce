### Birthday Email Scheduled Flow

This scheduled automation flow ensures that employees receive personalized birthday wishes automatically without manual HR intervention.

**Trigger**

Scheduled Flow – Runs every day at 8:00 AM.

**Inputs**

- Employee birthday
- Employee role
- Employee interests
- Employee hobbies
- Employee skill set

**Process**

1. The scheduled flow runs every morning at the configured time.
2. It checks the Employee records in Salesforce to identify employees whose birthday matches the current date.
3. For each matching employee, the system retrieves their profile information such as role, interests, hobbies, and skills.
4. The flow calls an AI prompt to generate a personalized birthday message.
5. The system automatically sends an email to the employee with the generated message.

**Output**

- Personalized birthday email sent to employees
- Optional notification to HR about birthdays of the day

**Impact**

This automation ensures that every employee receives personalized birthday greetings, improving employee engagement and strengthening workplace culture while reducing manual effort for HR teams.
