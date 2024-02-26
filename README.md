<h1>Docker Install on Proxmox (EASY) </h1>


<h2>Description</h2>
Installing Docker on Proxmox.

<h2>Sever Used </h2>

- <b>Proxmox</b>

<h2>Add VM ISO to PROMOX:</h2>

Use space to select Debian (Proxmox runs on Debian):  <br/>
Use tab to highlight OK and press enter/return <br/>
<img src="https://i.imgur.com/3PJ6pql.png" height="80%" width="80%" alt="RMA"/>
<br />
<br />
<p align="center">
Navigate https://tteck.github.io/Proxmox/: <br/>
Use the dropdown and open the Docker tab: <br/>
Copy the bash script: <br/> 
<img src="https://i.imgur.com/QVpoP03.png" height="80%" width="80%" alt="Creating"/>
<br />
<br />
Click "Open your Proxmox GUI:  <br/>
Navigate to your server shell:  <br/>
Paist bash script and press enter:  <br/>
<img src="https://i.imgur.com/KulnsSR.png" height="80%" width="80%" alt="ERD"/>
<br />
<br />
Use arrow keys, highlight yes, press enter/return: <br/>
<img src="https://i.imgur.com/bGHjRvr.png" height="80%" width="80%" alt="Keys"/>
<br />
<br />
Use space to select Debian (Proxmox runs on Debian):  <br/>
Use tab to highlight OK and press enter/return <br/>
<img src="https://i.imgur.com/3PJ6pql.png" height="80%" width="80%" alt="RMA"/>
<br />
<br />
Change any storage settings needed here:  <br/>
Note! Storage bandwidth settings can be changed with the bandwidth tab here:  <br/>
Click next <br/>
<img src="https://i.imgur.com/gx9uMfE.png" height="80%" width="80%" alt="Records"/>
<br />
<br />
Change CPU settings here:  <br/>
Take special note on how many Cores you are relocating to this machine, default is 1 core:  <br/>
Click Next:  <br/>
<img src="https://i.imgur.com/ugUmjOE.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Change memory allocation here and click next:  <br/>
<img src="https://i.imgur.com/69Y0G3l.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Choose what network interface card you want your VM to use, click next:  <br/>
<img src="https://i.imgur.com/TB12V0K.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Verify your VM info and click Finish:  <br/>
<img src="https://i.imgur.com/7RJGQpl.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
Locate your VM on the sidebar to the left and right click and left click start:  <br/>
<img src="https://i.imgur.com/5vTYPFM.png" height="80%" width="80%" alt="Desk"/>
<br />
<br />
CLick on your VM on the left panel and click on Console next:  <br/>
Install your VM if required:  <br/>
Click the rigth CTRL button to take your mouse off of the VM:  <br/>
<img src="https://i.imgur.com/q0fxv6a.png" height="80%" width="80%" alt="Desk"/>
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
