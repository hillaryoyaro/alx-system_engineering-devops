# CHANDARANA FOODPLUS LIMITED - MPESA APIs FAILURE

**Issue Summary**
From 5:00 a.m to 9:00 a.m EAT, The POS infrastructure break down,due to upgrade of Mpesa Daraja APIs intergrated to the Desktop POS Aplication.The issue affected 100% of the customer population.All the transaction logs and message retained in the queu.The root cause of the problem was functional testing during the testing phase .

**Timeline (all times East African Time)**
- 3:00 a.m: Transaction failed from multiple computers.
- 5:00 a.m: All client transaction logs and message records are erased
- 5:00 a.m: Pager alerted the portal adminstrator
- 5:15 a.m - 6:30 a.m: Failed login in attempts by admin
- 7:00 a.m: Issue escalated to the onpremise database administrator
- 7:30 a.m: Portal is taken completely offline
- 8:45 a.m: Successful login to portal by the administrator
- 9:00 a.m: infrastructure automation was done using the same image on multiple server.

**Root cause**
At 5:00 a.m EAT, No Function testing was done on APIs.

**Resolution and recovery**
At 5:00 a.m the pager alerted the administrator of the issue and consequent attempts at logging into the portal failed.
At 7:00 a.m the issue is escalated to the database administrator who figures out how the hacker is gaining access to the system
The entire portal is taken offline at 7:30 a.m and using brute force, the team is able to access the portal and change the password and recover the previously lost information
The portal is brought back online at 9:00 a.m

**Corrective and Preventative Measures**
After a thorough investigation the team reviewed and analysed the hack and took the following actions to avoid a future incident:
- The Developer responsible for the unit test was to explain what led to such problem.
- An increase in the verification steps required to access the portal
- An introduction to agile and devops development in the team.
- Increase the number of individuals being paged incase of a failto reduce the mean time to resolution (MTR).
