<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
This Lab explains how to successfully execute a password reset on Active directory
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory/ System Management</b>

<h2>Active </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Navigate to your Active Directory: <br/>
<img src="Screenshot 2025-05-18 140256.png" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to your users and Computers section, find the group that the intended user is in, then naviagte to the intended user.  <br/>
<img src="Screenshot 2025-05-18 143855.png"80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Powershell, enter the information of the user, enter command as follows: Set-ADAccountPassword username -reset -NewPassword (Read-Host -AsSecureString -Prompt 'New Passord')-Verbose: <br/>
<img src="Screenshot 2025-05-18 162253.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the new desired Password and press enter.  <br/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<br />
<br />
Sign Out and Log back in to confirm  <br/>
<br />
<br />
</p>
