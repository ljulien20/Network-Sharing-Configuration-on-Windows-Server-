# Network-Sharing-Configuration-on-Windows-Server-

<h2>Description</h2>
Configured network file and folder sharing on a Windows Server environment. Set up shared resources, managed access permissions, and verified client connectivity to demonstrate practical server resource distribution.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Prompt</b> 

<h2>Environments Used </h2>

- <b>CISCO packet tracer</b> 

<h2>Program walk-through:</h2>

<p align="center">
Both departments were cabled in correctly: <br/>
<img src="https://reasonable-fuchsia-thx1ds7cio-vqd46fow67.edgeone.dev/Screenshot%202025-11-30%20194813.png" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Static addresses were given to each PC and printer in both departments: <br/>
<img src="https://unfortunate-magenta-y6oadwtsh3-fx4d5ig140.edgeone.dev/Screenshot%202025-12-01%20213614.png" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Here I configured the router to be enabled with each Ethernet cable going to each department switch to have them powered on and processed static IP addresses for each device after the switch: <br/>
<img src="https://i.imgur.com/jfa1icJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A simple ping test from PC1 to all printers was performed for connectivity: <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253184468811927/Screenshot_2025-11-30_194913.png?ex=694c04aa&is=694ab32a&hm=42bace6035560268351783d2097949fa77be62fa9b9a739b0f2c376d52a8968f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Here I tested connectivity from one department to another pc in another department (PC0 TO PC2): <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445255963463520386/Screenshot_2025-12-01_212808.png?ex=694c0741&is=694ab5c1&hm=41979923c156db9611931e57a4ed6d3ed4064e053b742feaba495c24e5c35298" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I assigned a static IP address range here in the router to receive traffic, and a subnet mask is assigned as well for each department:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445256985133187072/Screenshot_2025-12-01_213317.png?ex=693ed934&is=693d87b4&hm=5f0595a2494f0fc22670ce7619b5d8f6cd92d349a12ea83eced7f790bae32894"/>
<br />
 <br />
This is an example of a static address used for the delivery department (PC2) as follows. Each department obtains 2 pcs and a printer:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445257958404522045/Screenshot_2025-12-01_213614.png?ex=694c091c&is=694ab79c&hm=5324f35ee5877e28c1d666adc02b63e5e0fc12f8327dbfe9ccbbc608e003ccfd"/>
<br />
 <br />
 This is a full-scale look at all connections on the enterprise network:  <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1445253629840855143/Screenshot_2025-11-30_194813.png?ex=694c0514&is=694ab394&hm=0d6783e892c30c51c445cae9eda17ad9d361ecdc7dfbcdde4d125ed993d882a7"/>
<br />
<br />
</p>
