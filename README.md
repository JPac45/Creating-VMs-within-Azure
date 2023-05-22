<img src="https://i.imgur.com/bxunY9z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qC5Pbip.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/LHzLEK4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>Creating Virtual Machines in Azure</h1>
This tutorial outlines how to create Windows 10 VMs, Window Server VMs, and Ubuntu VMs (Linux) in Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows Server 2022
- Ubuntu


<h2>Resource Group</h2>

<p>
A resource group is a container that holds related resources for an Azure solution. VMs are housed within a resource group. Therefore a resource group must be created first in Azure in order to house VMs.
<p>
From the Azure services page:<b>

- Click Resource Groups
- Click Create 
- Name Resource Group and Select a Region
- Click Review + Create
- Click Create once validation is passed
Resource Group is successfully created.</b>
<p>
<img src="https://i.imgur.com/3hjR7KR.gif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Virtual Machines - Windows 10</h2>
<p>
<b>

- Click Create 
- Click Azure Virtual Machine
- Choose an existing Resource Group that you previously created
- Give the VM a name
- Select the region (it should be the same as the resource group)
- Select Windows 10 under Image
- Choose Standard size
- Create username and password; and confirm password
- Click Create once validation is passed VM will be created.</b>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Virtual Machines - Ubuntu and Windows Server 2022</h2>
<p>

To create an Ubuntu VM and a Windows Server VM, follow the same steps as above except <b>Choose either Ubuntu or Windows Server 2022</b> in Image.

<p>
<img src="https://i.imgur.com/dsjXZkE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
<img src="https://i.imgur.com/Nilj5jJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

