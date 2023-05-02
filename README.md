<p align="center">
 <img src="https://i.imgur.com/DfR8wiF.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Creating an IP exclusion scope</h1>


<h2>Description</h2>

Get ready to level up your networking skills! In today's lesson, we'll be diving into the exciting world of DHCP exclusion scopes. With this powerful tool, you'll be able to prevent pesky IP conflicts, reserve IP addresses for critical network devices, and even lock down your network by reserving a range of unused IP addresses. So buckle up and get ready to master one of the most essential techniques in the network administrator's toolkit!
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2019 </b> <p>
 <b>Hyper-V</b></p>

<h2>Program walk-through:</h2>

<p align="center">

<br/>

<br />
<br />
From Hyper-V Manager, select  your host server, in this example ours is CORPSERVER. We are going to be double clicking on our DHCP Virtual Machine to connect to it.
 <br/>
<img src="https://i.imgur.com/EVXAv46.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Once our DHCP VM connects. Open server manager then select tools> DHCP
 <br/>
<img src="https://i.imgur.com/LE4izeo.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
In the DHCP dialogue box expand DHCP> Your Domain> IPV4> Scope. Right click address pool and select "exclusion range".

 <br/>
<img src="https://i.imgur.com/tDBn0VB.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Enter your desired exclusion range.
<br/>
<img src="https://i.imgur.com/EGqLtiT.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
You will then see your results posted in the prompt. You are finished, close all open boxes.

 <br/>
<img src="https://i.imgur.com/JorxxRM.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
You will then see your results posted in the prompt. You are finished, close all open boxes.

 <br/>
<img src="https://i.imgur.com/JorxxRM.png" height="80%" width="80%" alt="DHCP/>
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
