<p align="center">
 <img src="https://i.imgur.com/pTW69Cf.jpg" height="80%" width="80%" alt="DHCPexcludelogo"/>
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
Open server manager then select tools> DHCP
 <br/>
<img src="https://i.imgur.com/9oJRJGH.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
In the DHCP dialogue box expand DHCP> Your Domain> IPV4> Scope. Right click address pool and select "exclusion range".

 <br/>
<img src="https://i.imgur.com/E0lfZ2v.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Enter your desired exclusion range.
<br/>
<img src="https://i.imgur.com/D2elj2A.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
You will then see your results posted in the prompt. You are finished, close all open boxes.

 <br/>
<img src="https://i.imgur.com/2grwJN8.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.

 <br/>
<img src="https://i.imgur.com/CvlFI3e.jpg" height="80%" width="80%" alt="DHCP"/>
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
