<h1>Active Directory Domain Environment</h1>

<h2>Description</h2>
This lab details the setup process for an Active Directory Domain environment using a Windows Server 2022 VM and a Windows 10 VM as a client computer.
<br />


<h2>Technologies Used</h2>

- <b>Virtualization</b> 
- <b>Active Directory</b>
- <b>DHCP</b>
- <b>DNS</b>

<h2>Environments</h2>

- <b>Oracle VirtualBox</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Program Walk-Through:</h2>

<p align = "center">
Get Windows Server 2022 up and online through VirtualBox: <br/>
  <br/>
<img src="https://i.imgur.com/kOB73cC.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Clearly identify the internal (for the domain) and external (out to the internet) network adapters:  <br/>
  <br/>
<img src="https://i.imgur.com/o2aWGGU.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Configure the internal network adapter: <br/>
  <br/>
<img src="https://i.imgur.com/2KIHeyY.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Enable these services on the Domain Controller:  <br/>
  <br/>
<img src="https://i.imgur.com/6l4ia5n.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Complete the Post-Deployment configuration for the Active Directory Domain:  <br/>
  <br/>
<img src="https://i.imgur.com/p1yfbOM.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Configure the DHCP Server service:  <br/>
  <br/>
<img src="https://i.imgur.com/VLhN7jq.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />
<br />
Set Up a seperate user for yourself with Domain Admin privilege:  <br/>
  <br/>
<img src="https://i.imgur.com/f68vnln.png" height="80%" width="80%" alt="Active Directory Setup"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
