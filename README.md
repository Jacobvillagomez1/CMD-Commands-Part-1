# CMD-Commands-Part-1
<p align="center">
<img src="https://www.wallpaperflare.com/static/79/573/83/code-minimalism-microsoft-windows-command-lines-wallpaper.jpg"/>
</p>

<h1>CMD Virtual Machine Installation Commands</h1>
This tutorial outlines the installation of a virtual machine running Windows 10, then using commands in CMD.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop Connection
- CMD

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Resource Group for Virtual Machines
- Create Virtual Machine in Windows
- Log into VM in Windows through Remote Destop Connection  
- Open CMD in the Virtual Machine
- CMD Commands in the command line

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/803a9676-3265-46cd-b9c8-b8c415790936"/>
</p>
<p>
First once you are in Azure, click on Resource Groups or you can search it up in the search bar.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/5618569a-c31c-475f-9399-3e9e0bb4a092"/>
</p>
<p>
Next we are going to click create resource group
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/90cc2256-4cbe-4cde-ba96-dad2857a2baf"
<p>
The next page we are going to make sure its under a Azure subscription, then the name of the resource group will be rg-1 and the region in US West US 3
</p>
<br />
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/916d6edd-e342-4411-8907-7f2fd8fd05d6"
<p>
  
Next we are going to make sure on the top left it says Validation passed with a green check then at the bottom click create and the resource group will be created.
</p>
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/37bf517e-d482-49f1-b418-bf15cb81c961"
<p>
  
Then once you go back into the Resource Group you will see that it was created under name and in the top right corner of the page.
</p>
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/cf8c942b-f07a-4b33-ae3a-71fddf3e43ca"
<p>
  
Next type in virtual machine in the azure search bar and we are going to create a virtual machine you can click create on the top left or create in the middle of the screen.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/a63a0255-c90c-4ce5-bc91-603b0f689d4c"
<p>
  
Now click Azure virtual machine as shown in the image above.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/c170a3ea-a7a4-4f60-a5fa-57930f8ae3bf"
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/71b52e5c-787e-49cc-901d-d45b93534d3f"  
<p>
  
Next click the Resource Group and click rg-1 (Remember this is the one we made)
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/f5017b82-09fe-4c4d-af28-d6e336944788"
<p>
  
Now under Virtual Machine Name type VM1, Region needs to be US West US 3, Image needs to be Windows 10 Pro version 22H2 x64 Gen2, and the Size needs to be Standard E2s_v3.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/021c5768-419b-4086-8312-ec876b3648f5"
<p>
  
For Username type labuser and Password can be similar to the special characters, and capitals as shown 907405FIRE$green. After the password you need to check the box by Licensing. 
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/41db6636-cd26-4647-a3eb-3e047d23d126"
<p>
  
Once its done go the Networking tab and make sure virtual network, subnet, and public ip all says (new). 
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/51c065d6-d30a-4f64-aa7c-d783ac32c63d"
<p>
  
Then you can go to review and create, when it passes through it will say Validation passed in the top left then you can press Create at the bottom left to make the Virtual Machine. 
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/316f24ba-b566-4901-b7e3-5094f7f6a446"
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/3c14da8f-5217-4d45-9fb2-bf19e3d49a07" 
  
You know the Virtual Machine is created once it Say Your Deployment is Complete. Then go to search bar and type Virtual Machine and you should see VM1 that we created on the screen overview page.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/c18e850e-bd29-431e-956d-704e5232ee01"
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/8960dd09-ec12-4777-8696-ca637b406fcd"
<p>
  
Click VM1 and then go to the right side where the Public IP addresses is and click the copy symbol on the right. Then go to your search bar on your PC and type Remote Desktop Connection and open the app. 
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/6f9f2f60-524d-43d1-8203-1f810a09b4d5"
<p>
  
Next you paste VM1 public IP in the computer section in the Remote Desktop Connection (You can press Ctrl + V to paste the IP address in the computer section). and then type yes to allow the connection
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/51a8a636-5511-4ca1-b24f-8eb778ca331b"
<p>
  
Then type the user name labuser and the password you made.  
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/1e29a059-7bf2-4092-9a18-0a7e37cc38eb"
<p>
  
It should look like the image above.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/1e29a059-7bf2-4092-9a18-0a7e37cc38eb"
<p>
  
It should look like the image above.
  
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/30b657b4-8b45-46f7-8ad2-2bec8699ed35"
<p>
  
Your screen should load Virtual Machine 1 like the image above.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/301a256c-ad44-414a-92d0-14311af964b1"
<p>
  
Next all of the following click no.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/338a5665-86e0-4ee6-b610-b5df37809df2"
<p>
  
Then press Yes for the Networks tab that appears on the right side of the Virtual Machine.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/0470a2c6-2207-4831-b4bb-69f8b1fda187"
<p>
  
Type Command Prompt in the search bar and press enter to open the app.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/607d1b85-5616-4036-9d62-52f7fcc0af77"
<p>
  
Once the app opens the user should be the one we created labuser.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/b7dd2cf4-3978-4447-8980-791d1f4ac075"
<p>
  
Next click the command line and type ipconfig this is going to find your computer IP address.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/fbabbf02-2aa0-47f6-8ade-0c5ca987e7b4"
<p>
  
We can also type ipconfig /all this will show your MAC address and your DNS server.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/ee774161-c20e-4b30-86d3-2b5c8e4528a6"
<p>
  
Then type ipconfig /all | findstr DNS this will find a specific string of data of DNS which is in ipconfig to find what you need.
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/18c9f2d5-ddaf-4615-9d87-5216fa771d23"
<p>
  
We can also give us a new IP address by using ipconfig /release
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/969a8262-cb70-40a0-b444-a7bc603a4fe9"
<p>
  
Then type ipconfig /renew this is going to reach out to DHCP server to get a new IP address
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/a8790ac6-c93f-45bd-85b3-07bbcec913a0"
<p>
  
Then type ipconfig /displaydns this shows all the websites and there IP address
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/85f6255a-eea6-4da2-bdd5-d0ca1a85dceb"
<p>
  
After the command it will show all the websites as show above 
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/7e1fe35f-99f9-4739-8582-b73265956f1e"
<p>
  
Next to copy the output of a command to your clipboard type the following ipconfig /displaydns | clip
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/38c3506a-9bc5-424b-bdea-1c914642d181"
<p>
  
To delete your DNS resolver cache on your computer type ipconfig /flushdns in the command line this will remove any old DNS entries
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/a5282f44-0b74-4fc2-8329-c2c7bf17ca94"
<p>
  
Next to troubleshoot DNS type nslookup www.google.com this will show www.google.com IP address
<p>
<img src="https://github.com/Jacobsushi54/CmdCommandsPart1/assets/142194385/5d2d4ee7-3ecc-4f2a-ba5a-329510adbc21"
<p>
  
Then finally we can clear the screen of the command line by typing cls
