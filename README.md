# Microsoft Sentinel - ChatCGP Demo


Use case description
The following use case describes an incident trigger in Microsoft Sentinel, where a comment is added to the incident to explain the Mitre Att&ck Tactics and Techniques used by the attacker, and a task is added to suggest how to investigate the incident. Additionally, it leverages previous tasks to suggest a KQL query.
Incident trigger: The incident trigger is defined as a specific event or condition in Microsoft Sentinel, such as a security alert or a log entry that meets certain criteria. For example, the trigger could be triggered when a suspicious network connection is detected.
Add comment to incident: Once the incident trigger is activated, a comment is added to the incident to explain the tactics and techniques used by the attacker. This could include information such as the specific malware used, or the methods used to evade detection.
Add task to incident: A task is added to the incident to suggest how to investigate the incident. This could include tasks such as collecting additional data, running automated investigations, or taking specific actions to contain or remediate the incident.
Leverage previous task: The previous task's outcome is used to suggest a KQL query to investigate the incident. The KQL query allows searching for specific events or log entries in the Microsoft Sentinel data to help in the incident investigation. This query can be used to gather more information about the incident and help identify the cause and scope of the attack.

To upload this playbook in Azure Sentinel please follow the below instructions:
- From the Azure portal menu, in the search box, type Template, and then select Templates
- Select +Add and give it a Name and Description
- copy and paste the json file in the previous folder in the ARM template layout.
- click add
- your logic app is created and ready to be deployed
- From the Azure portal menu, in the search box, type Sentinel 
- click on Azure Sentinel and then in the left hand-side menu click automation 
- click on Add
- Add new playbook
- on the bottom select download custom template
- fill in the requested fields
- at completion you'll see it available among the playbooks

Thank you!

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fformat81%2FMicrosoftSentinel-ChatGPT-playbook%2Fmain%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fformat81%2FMicrosoftSentinel-ChatGPT-playbook%2Fmain%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>

**Additional Post Install Notes:**

