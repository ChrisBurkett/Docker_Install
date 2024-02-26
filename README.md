<h1>Docker Install on Proxmox (EASY) </h1>


<h2>Description</h2>
Installing Docker on Proxmox.

<h2>Sever Used </h2>

- <b>Proxmox</b>

<h2>Add VM ISO to PROMOX:</h2>

<p align="center">
Navigate to Proxmox and open the Shell:  <br/>
Type "cat /etc/os-release" press enter/return and verify what version of Debian running: <br/>
<img src="https://i.imgur.com/JOsRGyb.png" height="80%" width="80%" alt="RMA"/>
<br />
<br />
Navigate to Proxmox and use the System dropdown:  <br/>
Click Network and see copy the name of Linun Bridge: <br/>
Docker will use this name to connect to the internet <br/>
<img src="https://i.imgur.com/jMH28mJ.png" height="80%" width="80%" alt="RMA"/>
Navigate https://tteck.github.io/Proxmox/: <br/>
Use the dropdown and open the Docker tab: <br/>
Copy the bash script: <br/> 
<img src="https://i.imgur.com/QVpoP03.png" height="80%" width="80%" alt="Creating"/>
<br />
<br />
Navigate back to your Proxmox server shell:  <br/>
Paist bash script and press enter/return:  <br/>
<img src="https://i.imgur.com/KulnsSR.png" height="80%" width="80%" alt="ERD"/>
<br />
<br />
Use space to select Debian (Proxmox runs on Debian):  <br/>
Use tab to highlight OK and press enter/return <br/>
<img src="https://i.imgur.com/3PJ6pql.png" height="80%" width="80%" alt="RMA"/>
<br />
<br />
Select the version of Debian running: <br/>
<img src="https://i.imgur.com/2nbHyNr.png" height="80%" width="80%" alt="Keys"/>
<br />
<br />
Always run as Unprivileged unless you have a very specific need:  <br/>
<img src="https://i.imgur.com/LRcrSLE.png" height="80%" width="80%" alt="Records"/>
<br />
<br />
Create a Root password:  <br/>
Do not leave the Root password blank unless you have very specific use case:  <br/>
Click Next:  <br/>
<img src="https://i.imgur.com/lZ8mV4T.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Set a container ID:  <br/>
Do not use a container ID that is already in use <br/>
<img src="https://i.imgur.com/K1naVll.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Set a Docker hostname:  <br/>
<img src="https://i.imgur.com/lQfWb4K.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Set how many Gbs allocated to Docker:  <br/>
<img src="https://i.imgur.com/Ivbc9bO.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Allocated cores to Docker:  <br/>
<img src="https://i.imgur.com/VDFzi8b.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />

Allocate RAM:  <br/>
Recommended 2 Gbs to 4 Gbs:  <br/>
<img src="https://i.imgur.com/ES5S94l.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />

To shutdown your VM use the shutdown drop down at the top of the page. <br/> 
Reboot will restart the VM, STOP will end the VM immediately:  <br/>
<img src="https://i.imgur.com/uJv3a3y.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />


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
