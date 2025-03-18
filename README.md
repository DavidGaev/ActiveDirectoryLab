<h1>Active Directory Home Lab </h1>

<h2>Description</h2>
In this Lab, I will showcase how to create Active Directory through a Virtual Machine. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Virtual Box </b>

<h2>Environments Used </h2>

- <b>Windows Server 2022</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launching Active Directory: <br/>
<img src="https://i.imgur.com/TfJGYnF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now you Must promote this to a domain controller:  <br/>
<img src="https://i.imgur.com/tEOnXjI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use the "Add a new Forest" <br/>
<img src="https://i.imgur.com/Go7wvQN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then Install it:  <br/>
<img src="https://i.imgur.com/AFEjLns.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now find User and Computers under "Administrative Tools":  <br/>
<img src="https://i.imgur.com/eghuXue.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
As you can see, our domain controller now shows up:  <br/>
<img src="https://i.imgur.com/d51aWUg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If we want to add Users,Right click in your OU and click NEW and then User:  <br/>
<img src="https://i.imgur.com/wWe7FfC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You can then fill out information and on the next page set up the password:  <br/>
<img src="https://i.imgur.com/flKEP8Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
With the Users, you can do things like Reset Passwords. All you do is go into the Users and Computers and right click on your user:  <br/>
<img src="https://i.imgur.com/NpIbw4r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This is how the password reset window looks like:  <br/>
<img src="https://i.imgur.com/ddalsOW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
How Group Policies are Setup:  <br/>
<img src="https://i.imgur.com/ZwsBfac.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This is the Group Policy Page: <br/>
<img src="https://i.imgur.com/ItRTSxD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You can now Right click on your domain name and click on "Create a GPO":  <br/>
<img src="https://i.imgur.com/fZZwtX1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If we want to See for example a Password Policy, We select Policies, then Windows Settings, Security Settings: <br/>
<img src="https://i.imgur.com/nTleuA6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To Edit the policy we Right Click and click Properties:  <br/>
<img src="https://i.imgur.com/X8QLXh7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If we want to add our Group Policy to an Organization Unit, we can simply drag our Policy into the Organization Unit we need them in:  <br/>
<img src="https://i.imgur.com/jV7Yez4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
There are all types of Interesting things to do in Active Directory. I wish to one day be able to be in an organization where I can do some of these things. 

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
