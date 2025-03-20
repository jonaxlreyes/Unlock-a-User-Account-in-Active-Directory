<h1>Unlock a User Account in Active Directory</h1>

 

<h2>Description</h2>
In this phase of my IT helpdesk home lab, I will practice unlocking user accounts in Active Directory (AD)—a common IT support task when users are locked out due to multiple failed login attempts.

Using the Active Directory Users and Computers (ADUC) tool, I will locate locked user accounts, check the account status, and manually unlock them.

By mastering this process, I will gain hands-on experience in user account management, troubleshooting login issues, and providing efficient IT support in a real-world environment.
<br />


<h2>Utilities Used</h2>

- <b>Activer Directory</b> 


<p align="center">
Users Account is locked due to multiple wrong password attempt: <br/>
<img src="https://imgur.com/BFsYmVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Quick Steps to Unlock a User Account in Active Directory <br />
1.Open ADUC – Press Win + R, type dsa.msc, and hit Enter. <br />
<p align="center">
<img src="https://imgur.com/kBUwEPz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p align="center">
2.Find the User – Navigate to the Users container or relevant OU. <br />
<p align="center">
<img src="https://imgur.com/vJdaXWI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p align="center">
3.Check Account Status – Right-click the user, select Properties, go to the Account tab. <br />
<p align="center">
<img src="https://imgur.com/YCiVW1V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p align="center">
4.Unlock the Account – Check "Unlock account", then click Apply and OK. <br />
5.Reset Password (if needed) – Right-click the user, select Reset Password, and set a new one if required. <br />
<p align="center">
<img src="https://imgur.com/lc6IiZ1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p align="center">
6.Inform the User – Confirm with the user that they can log in successfully.  <br/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
