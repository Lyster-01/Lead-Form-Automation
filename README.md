# Lead-Form-Automation

Below is the assignment of the workflow. 
1. Create a new workflow.
2. Add a trigger to capture form submission 
3. Use the filter node to only allow budgets above 100,000.
4. Send a gmail notification with the captured lead details.
5. Test the workflow with the high and low budget.
 

### The lead form Workflow

This workflow is a selective alert pipeline. It doesn’t just react; it decides what deserves attention.
It starts with “On form submission,” where each new entry triggers the workflow automatically.
Instead of processing every submission blindly,  a Filter node was introduced to enforce logic. Only qualified data is allowed to move forward.Once the data passes the filter, a Gmail alert is triggered.

![Lead Form Workflow](leadform.png)

### Purpose of workflow 
1. Send real-time alerts for important submissions
2. Eliminate noise from irrelevant data
3. Enable faster and more focused decision-making

### Why This Is Powerful?
1. Prevents alert fatigue by sending only relevant emails
2. Adds control and intelligence to automation workflows
3. Easily scalable by adjusting filter conditions

### Use Cases
1. Lead qualification systems
2. Customer support triaging
3. Job application filtering


