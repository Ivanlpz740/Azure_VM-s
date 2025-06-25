<p align="center">
<img src="https://i.imgur.com/FMk5wwX.png" alt="Microsoft Azure"/>
</p>

<h1>Deployment of Azure VM's </h1>
This tutorial outlines proccess of deploying Azure VM's.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy and Connect to Azure Virtual Machines](https://youtu.be/m8qJhGcZmOY)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Prerequisites </h2>

- Microsoft Azure Account
- Windows Laptop
- Remote Desktop

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/CNTrRqN.png" height="80%" width="80%" alt="Azure"/>
</p>
<p>
Locate the resource group icon on your Azure home page. It should look like whats circled in the image above.
</p>
<br />

<p>
<img src="https://i.imgur.com/0R2s4dR.png" height="80%" width="80%" alt="resource"/>
</p>
<p>
Now click on the create button. You be prompted to type in a resource group name and region. You can choose whatever name pleases you (I'll name mine practice), but for the region choose one near you. For me I will choose East US 2. Now click create
<br />

<p>
<img src="https://i.imgur.com/767Ta6k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now after your resource group finishes deploying, open it by going to the home page and clicking the resource group Icon like you did before. You should see your resource group. Click on it and your screen should look like the image above. Click on the create resources.
</p>
<br />

<p>
<img src="https://i.imgur.com/S37YSrG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Your screen should look like the image above with all the different resources you can make.On the Microsoft Windows 10 box click create. A long list of different versions of Windows should pop up. Theoretically you can choose whichever version of windows you like, but for today click on Windows Version 10 PRO, 22H2. 
</p>
<br />

<p>
<img src="https://i.imgur.com/trZdbvK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
By default the Virtual Machine will be in the resource group we created. You're free to choose what ever name you please (Mine will be called Practice aswell). Scroll down till you see the size box. Click on it. You can choose whatever size you would like (The more VCPU's it has the faster it will run. I will be choosing one with 2 VCPU's). 
</p>
<br />

<p>
<img src="https://i.imgur.com/Amhj0aO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Below the size box you should see a "Administrator account" subheading. This will be your credentials to log onto the Virtual Machine. I would suggest writing these down on a notepad. Make your credentials (For this demonstration the username will be Ivanlpz  and the password will be Cyberuser123!. After you make your credentials, check the Licensing check box and Review + Create.
</p>
<br />

<p>
<img src="https://i.imgur.com/GtVib1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should be able to see how much you will be charged for running the VM. Click create and wait till your VM finishes deploying. Click on your home page.
</p>
<br />

<p>
<img src="https://i.imgur.com/dqH2Hh9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your home page click on the Virtual Machine Icon. You should be able to see your Virtual Machine and its public IP address. Copy your public IP address
</p>
<br />

<p>
<img src="https://i.imgur.com/NBwCWx5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Look up Remote desktop on the search bar on your taskbar and open it up.
</p>
<br />

<p>
<img src="https://i.imgur.com/Tl2hbAs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy and paste your VM's public IP address into the box. Then click on the "Show Options" icon. Type in or copy and paste the username you chose into the box. Then Click connect.
</p>
<br />

<p>
<img src="https://i.imgur.com/enJH3nr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Type in or copy and paste your password you chose. Click yes on the next pop up.
</p>
<br />

<img src="https://i.imgur.com/BtcoDiW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you have successfully connected to your VM!
</p>
<br />

