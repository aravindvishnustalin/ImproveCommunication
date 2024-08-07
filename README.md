**SITUATION:** To manufacture a product, Supply chain planners need to allocate the right material at the right time to Manufacturing team. The Material Planners communicate their material requirements to Supply Chain planners so that the materials get allocated. But Material Planners do not give enough time for Supply Chain planners to allocate the material on time. Also, this communication is through email and so, it is not organized properly.

**TASK:** We should make sure Material Planners notify their material needs to Supply Chain Planners in advance. Also, an efficient platform must be developed for communication between planners.

**ACTION:** 
1. SharePoint site is created to store the DS Material information and edit the requirements in a timely manner
   ![image](https://github.com/user-attachments/assets/74395387-badd-47a1-8e46-4fde469e4468)

2. Excel file is created to store and update the information
![image](https://github.com/user-attachments/assets/78498612-ee8c-4236-9cd4-3f8ee2a350d1)

3.To alert the planners to enter required information 2 months prior to fill date, an email alert system is created in Microsoft Office Power Automate which generates different levels of priority emails based on number of days between current date and fill date.
The flow looks like the below:

