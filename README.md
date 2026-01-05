# Network-Sharing-Configuration-on-Windows-Server-

<h2>Description</h2>
Configured network file and folder sharing on a Windows Server environment. Set up shared resources, managed access permissions, and verified client connectivity to demonstrate practical server resource distribution. Mapping network drives through GPOs helps automatically make the drives accessible for users on their computers.
<br />


<h2>Languages and Utilities Used</h2>

- <b>File Explore</b> 
- <b>NTFS Security Permissions</b>
- <b>DNS services</b>
- <b>Network Configuration Utilities</b>
- <b>Server Manager</b> 
<h2>Environments Used </h2>

- <b>Virtual Machines</b>
- <b>Windows Server</b> 

<h2>Program walk-through:</h2>

<p align="center">
A folder is made labeled "SHARED" and everyone in the domain has permission to read this file now: <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1456433900308922418/Screenshot_2026-01-01_133051.png?ex=695c4dc5&is=695afc45&hm=7a37d24c36fb6b3ab9d40667fa406661b3719e646e0c954b7656d1c3db27dad7" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
I configured the SHARED file to the "S" drive on the Drive Maps page after the group policy was made for Mapped Drives: <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1456436149135478845/Screenshot_2026-01-01_173527.png?ex=695c4fdd&is=695afe5d&hm=112be2b55629ee1fc8a2a8633c1ff5404db58796bd7ffda97dfa4c9c3cedaa40" height="80%" width="80%" alt="Network enterprise"/>
<br />
<br />
Once the group policy is configured completely, I then added the policy to each user group under Asia, Europe, and USA. In these situations, changes and configurations to users' computers that will be able to easily access the S drive will be completed once each user's PC is updated: <br/>
<img src="https://cdn.discordapp.com/attachments/1445251151896248323/1456437442793181234/Screenshot_2026-01-01_175850.png?ex=695c5111&is=695aff91&hm=5b77af92abb85104432644c2e26a684fbdd0f9a6792ab47e97d38b87009ed33c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>
