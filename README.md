<p align="center">
<img src="https://i.imgur.com/ixyDq7r.png" alt="Traffic Examination"/>
</p>

<h1>Virtual Private Networks (VPNs)</h1>
In this tutorial, I setup a VPN with a Azure Windows 10 Virtual Machine (VM). <br />


<!-- h2>Video Demonstration</h2>

 - ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (RDP)
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create a Resoure Group & VM
- Utilize RDP
- Install Proton VPN
- Observe Changes


<h2>Actions and Observations</h2>
<strong>Resource Group & Windows 10 VM</strong> 
<p>
<img src="https://i.imgur.com/AnnhtNE.png" height="80%" width="80%" alt="Resource Group"/>
</p>
<p>
<img src="https://i.imgur.com/FL2QXU1.png" height="80%" width="80%" alt="Windows_10_VM"/>
</p>
<br />

<strong>Remoting Into VM</strong>
<p>
<img src="https://i.imgur.com/edol9xL.png" height="80%" width="80%" alt="RDP"/>
</p>
<br />

<strong>Utilizing What's My IP Address</strong>
<p>
<img src="https://i.imgur.com/i4wmg0b.png" height="80%" width="80%" VM_Whats_my _ip"/>
</p>
<p>
Browsed to www.Whatsmyipaddress.com to verify what the IP Address and the location of the VM is.
</p>
<br />

<strong>Installing Proton VPN & Connecting to the VPN</strong>
<p>
<img src="https://i.imgur.com/nvGrk7k.png" height="80%" width="80%" alt="Installed_ProtonVPN"/>
</p>
<p>
<img src="https://i.imgur.com/hXgUOjo.png" height="80%" width="80%" alt="Connected_VPN"/>
</p>
<p>
Created a free account to gain access to Proton VPN services. Downloaded, installed and connected to the ProtonVPN. 
</p>
<br />

<strong>VPN Results</strong>
<p>
<img src="https://i.imgur.com/eKjwZUc.png" height="80%" width="80%" alt="VPN_Results"/>
</p>
<p>
<img src="https://i.imgur.com/Kp0AGNw.png" height="80%" width="80%" alt="VPN_Results"/>
</p>
<p>
<img src="https://i.imgur.com/ciBDwpU.png" height="80%" width="80%" alt="VPN_Results1"/>
</p>
<p>
<img src="https://i.imgur.com/jfeHLcY.png" height="80%" width="80%" alt="VPN_Results2"/>
</p>
<p>
I observed that the IP address after being connected to the VPN has changed from 23.100.89.152 to 169.150.218.58. Also noted that the language is no longer English but is currently being displayed in Dutch now. Used Google, Netflix and Disney to test and verify changes.
</p>
<br />
