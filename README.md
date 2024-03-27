<h1>EIGRP</h1>

<h2>Description</h2>
This lab will configure the EIGRP routing protocol. All IP addresses have beeen configured on the router interfaces.
<br />

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Lab Topology:</h4>
In this Lab topology there are 6 routers. EIGRP will be configred between the routers and connection will be established between the subnets. <br/>
<img src="https://i.imgur.com/GiFng3X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Before EIGRP is configured:</h4> 
R6 only has it's connected routes and local routes in it's routing table.<br/>
<img src="https://i.imgur.com/XQz0x12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
PC1 cannot ping the end devices in the other subnets.<br/>
<img src="https://i.imgur.com/hteQNx3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<h4>EIGRP Configuration:</h4> 
<img src="https://i.imgur.com/mIahSH3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<h4>After EIFRP is configured:</h4> 
R6 now has all the routes to the subnets in the private network. <br/>
<img src="https://i.imgur.com/NKeza40.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
PC1 cannot ping the end devices in the other subnets. <br/>
<img src="https://i.imgur.com/PGpwcZf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

