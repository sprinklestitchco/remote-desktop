<p align="center">
<img width="980" height="560" alt="image" src="https://github.com/user-attachments/assets/56b97719-19ef-44f7-933a-3c95edd3ec9b" />
<img width="542" height="303" alt="image" src="https://github.com/user-attachments/assets/e5b0b716-b0f6-4b05-934d-defd612815e3" />

</p>

<h1>Remote Desktop into your virtual machine in Azure</h1>
This project explains how to connect to a virtual machine (VM) in Microsoft Azure using Remote
Desktop using a Windows PC. Assuming you have already created your virtual machine in Azure. The Remote Desktop application allows you to remotely access and control a computer from a different location using an internet connection. 
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop App
- Windows PC

<h2>Operating Systems Used </h2>

- Windows 11
  
<h2>Login to Azure Portal</h2>
<p>
Go to https://portal.azure.com and sign in with your account. Your home page should look something like this when you login to Azure portal. 

</p>
<p>
<img width="1708" height="923" alt="image" src="https://github.com/user-attachments/assets/946036be-8ade-47e4-8e2a-26e692b9c71f" />

</p>

<h2>Find your Virtual Machine Created</h2>
<p>
Find the virtual machine you previously created. You can click on the 3 lines on the left side of the homepage and click on Virtual Machines or you can also just type virtual machines in the search toolbar. Make sure the virtual machine you want to remotely desktop into has a status of running and not stopped in Azure.
</p>
<p>
<img width="1700" height="862" alt="image" src="https://github.com/user-attachments/assets/5267c33e-5487-40d8-92f5-8f05ab927c40" />
  
<h2>Make sure the virtual machine you want to remotely desktop into has a status of running and not stopped in Azure.  </h2>

<img width="1713" height="645" alt="image" src="https://github.com/user-attachments/assets/f01c4bfa-03f7-4d21-aeab-17296249d78e" />

</p>
<h2>Get Virtual Machine Public IP Address</h2>
<p>
Copy the public IP address in Azure that you want to remotely desktop into.
</p>
<p>
<img width="1902" height="651" alt="image" src="https://github.com/user-attachments/assets/fced0ecc-63e7-44cf-83a7-75ee1f6b6fab" />

<h2>Find Remote Desktop Application</h2>
<p>
Find the Remote Desktop Application or download that application if you do not have it. Then, put the same public IP address of the virtual machine we copied from Azure into the Remote Desktop application, and click Connect to log in.
</p>
<p>
<img width="1575" height="637" alt="image" src="https://github.com/user-attachments/assets/7732e7e2-4522-48dc-9a40-c134bf8cd488" />

<h2>Login to Virtual Machine</h2>
<p>
Now use the same username and password you created when setting up your virtual machine in Azure and click okay. Accept any certificate warnings that may appear.  
</p>
<p>
<img width="580" height="721" alt="image" src="https://github.com/user-attachments/assets/2b52625a-69f1-41b9-8b89-683f535721db" />

<h2>Successfully Login</h2>
<p>
You are now connected to the Virtual Machine Windows desktop. You are controlling another computer from your own computer. Congratulations you did it!
</p>
<p>
<img width="1262" height="662" alt="image" src="https://github.com/user-attachments/assets/0d2ae18e-8330-4835-bc17-f0d80e51c3df" />
<img width="1196" height="703" alt="image" src="https://github.com/user-attachments/assets/6c82f154-9428-4593-944a-6e22f6cbd1b8" />





<br />
