Project name :Automated Network Request Management in ServiceNow
Description :This project focuses on automating network request management in ServiceNow to improve efficiency and reduce manual effort. A Service Catalog item called “Network Request” is created to capture user inputs such as request type, access level, device, and justification. Using Flow Designer, requests are automatically routed for approval and, once approved, tasks are generated and assigned to the network team. The system updates request status in real time and sends notifications at each stage. This automation ensures faster processing, better tracking, and improved accuracy in handling network-related requests within an organization.
Here are the **simple steps of your project** in correct order 👇

✅ STEPS OF THE PROJECT
 1. Create Catalog Item

* Go to **Maintain Items**
* Create **Network Request**

2. Add Variables

* Add fields:

  * Request Type
  * Access Level
  * Device
  * Justification
 3. Add Choices

* For Request Type → VPN, Firewall, Access
* For Access Level → Read, Write, Admin

4. Create User Groups

* Network Team
* Approvers

5. Create Flow

* Open **Flow Designer**
* Create new flow

6. Add Trigger

* Table → Requested Item
* Condition → Catalog Item = Network Request

7. Add Approval

* Use **Ask for Approval**
* Set Approvers group

8. Create Task

* Add **Create Task** action
* Assign to Network Team

9. Activate Flow

* Click **Activate**

10. Test in Service Portal

* Open portal
* Submit Network Request

 11. Check Output

* Request created
* Approval sent
* Task created

 12. Complete Task

* Open task
* Change state → Closed Complete

FINAL FLOW

👉 Submit → Approval → Task → Complete

Screenshots
.catalog.png
.variables.png
.clientscript.png
.flow.png
.form.png
.request.png
.approval.png
.task.png
.completed.png

