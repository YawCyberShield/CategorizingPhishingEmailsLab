<h1>YParry - Categorizing Phishing Emails </h1>

<h2>Description</h2>
I accurately classified four distinct types of phishing emails by examining their context, intent, and content. Each email was opened and analyzed using Mozilla Thunderbird.
For credential harvesting, I identified emails that attempted to trick users into revealing personal information, such as passwords and credit card numbers, often by masquerading as trustworthy entities. In the case of malicious attachments, I focused on emails that contained or linked to harmful software designed to compromise the recipient's computer or network. Spam emails were categorized by their unsolicited nature, often promoting irrelevant or unwanted products and services. Lastly, recon emails were recognized as attempts to gather valuable information about an individual or organization for future phishing attacks or other malicious activities.
<br />

<h2>Environments Used </h2>

- <b>Mozilla Thunderbird</b> 

<h2>Program walk-through: Setting Appropriate Access Permissions</h2>

<p align="center">
Checking ''projects'' directory and files: <br/>
<img src="https://i.imgur.com/A3PJH42.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Checking Whether Any Hidden Files Exist: <br/>
<img src="https://i.imgur.com/kQNDUcE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify write permissions for owner or others in projects directory files: <br/>
<img src="https://i.imgur.com/ImTHlQf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove write permission from the owner type of other in the ''project_k.txt'' file: <br/>
<img src="https://i.imgur.com/WwA42CF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Comfirm using Is -I   <br/>
<img src="https://i.imgur.com/HbUlFIc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove group read permissions from project_m.txt using chmod g-r :  <br/>
<img src="https://i.imgur.com/bt17pxr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set .project_x.txt permissions to read-only for user and group :  <br/>
<img src="https://i.imgur.com/D3zfojq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove the execute permission for the group from the drafts directory:  <br/>
<img src="https://i.imgur.com/0Ehxt8t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
