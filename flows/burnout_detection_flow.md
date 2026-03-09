### Burnout Detection Flow

This automation is implemented using a Salesforce **Autolaunched Flow**.  
The purpose of this flow is to retrieve the burnout risk score already calculated for employees and provide the data for further analysis and HR decision support.

**Flow Type**

Autolaunched Flow.

**Inputs**

- Employee ID
- Burnout risk score stored in the Employee record

**Process**

1. The flow is triggered when the system needs to evaluate employee well-being data.
2. The flow retrieves employee records from Salesforce.
3. It fetches the burnout risk score that was previously calculated and stored in the employee data.
4. The flow prepares this information for further processing or for use by the Burnout Detection Agent.
5. The agent then analyzes the retrieved data and generates recommendations for HR.

**Output**

- Employee burnout risk information retrieved from records
- Data passed to the Burnout Detection Agent
- HR receives insights and recommended actions

**Impact**

This automation ensures that employee burnout data is easily accessible for AI agents and HR teams, enabling proactive monitoring of employee well-being and supporting timely HR interventions.
