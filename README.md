
<h1>Windows Remote Connection in IT Homelab</h1>

<p>
  A Remote Connection in Windows allows users or administrators to access and control another Windows computer or server from a different location, as if they were sitting directly in front of it. This capability is essential for IT management, troubleshooting, remote work, and system administration in both enterprise and homelab environments.
</p>

<br>

<img width="1364" height="739" alt="image" src="https://github.com/user-attachments/assets/64794316-1008-46b4-981b-28c290e6609e" />

<br>

<p>
  This image shows a Remote Desktop connection being made to a Windows computer in my HuskyTech homelab. The Remote Desktop feature is turned on in Windows Settings, which allows the system to accept connections from other devices on the same network or domain. In the Remote Desktop Connection window, the user is connecting to DESKTOP-0TRL91E.HuskyTech.local using the domain account HUSKYTECH\Helpdesk.

This setup lets me manage and control my virtual machines from one workstation instead of logging into each one directly. It’s a great way to simulate how IT administrators handle remote access in real business environments—perfect for testing Active Directory authentication, performing system updates, or troubleshooting client machines inside my homelab network.
</p>


<img width="972" height="598" alt="image" src="https://github.com/user-attachments/assets/8817b965-b02a-470d-9024-05ab214772de" />

<br>

<p>
I am connecting to DESKTOP-0TRL91E.HuskyTech.local using the HUSKYTECH\Helpdesk domain account. At this stage, Windows asks for the account password to verify credentials before granting access.

This step is part of establishing a secure remote session through Remote Desktop Protocol (RDP). It’s a common process in IT environments, where administrators or support technicians remotely log in to servers or client machines for troubleshooting, software updates, and general system management.
</p>


<br>

<img width="810" height="602" alt="image" src="https://github.com/user-attachments/assets/ab2ee3f7-aec8-46f9-8e82-19da963945e0" />

<br>


<p>As the Domain Controller is connecting to the other virutal machine, the other virtual machine will logout.</p>

<br>

<img width="1361" height="702" alt="image" src="https://github.com/user-attachments/assets/50966a27-859d-4781-b97a-f4fbdf229f83" />
<br>
<hr>

<p>
After successfully entering the credentials, the Remote Desktop session connects to the target computer DESKTOP-0TRL91E.HuskyTech.local. The desktop background displays the custom HuskyTech logo, confirming that the connection to the domain environment was established successfully.

This final screen demonstrates a completed remote session inside the HuskyTech homelab, showing that Remote Desktop Protocol (RDP) is fully functional across the network. From here, the user can manage applications, perform administrative tasks, or test remote access tools like RustDesk and Microsoft Edge.

Overall, this setup highlights how Remote Desktop can be used to simulate real-world IT environments—allowing administrators to securely connect, configure, and control systems within a virtual lab network.
  
</p>
