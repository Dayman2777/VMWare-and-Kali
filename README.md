# VMWare-and-Kali
How to install VMWare Workstation. Then install Kali Linux
<br />
<br />
<h1>Installing VMWare Workstation and then installing Kali Linux</h1>


<h2>Description</h2>
Workstation is a complimentary service provided by VMware, which I'll primarily use for setting up my new home lab on Windows 10. I'll guide you through the installation process and walk you through the steps to create a Kali virtual machine.

<br />


<h2>Languages and Utilities Used</h2>

- <b>VMWare Workstation</b> 
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> VMWare Workstation

<h2>Program walk-through:</h2>

<p align="center">
Search for “VMWare Workstation free” or visit:
<br />
https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html
<br />
<img src="https://i.imgur.com/ne4mdZE.png" height="80%" width="80%" alt="Virtual Box download."/>
<br />
<br />
Scroll down to “Try Workstation 17 player for "Windows” and select “DOWNLOAD NOW”:
<br/>
<img src="https://i.imgur.com/IiKVR6E.png" height="80%" width="80%" alt="Run exe."/>
<br />
<br />
Locate your download and open “VMware-player-ful-x.x.x.exe”, I’m using “VMware-player-full-17.0.0-20800274.exe.”:
<br/>
<img src="https://i.imgur.com/410otva.png" height="80%" width="80%" alt="Wizard steps"/> 
<br />
<br />
You must proceed through the installation wizard. After reaching the "Welcome" screen, click on the "Next" button.:  
<br/>
<img src="https://i.imgur.com/yssJLws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Read the “VMWARE END USER LICENSE AGREEMENT”. Select “I accept the terms in the License Agreement” and click “Next”.: 
<br />
<br />
<img src="https://i.imgur.com/JAXRGjh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I have Hyper-V installed (Windows Hyper visor), so we received a message that we need to “Install Windows Hypervisor Platform (WHP) automatically.”:
<br />
Click “Install Windows Hypervisor Platform automatically” and click “Next”.
<br />
<img src="https://i.imgur.com/GOBVoNP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On the “Custom Setup” screen, I’m installing the “Enhance Keyboard Driver” and “Add VMWare Workstation console tools into system PATH.” Select “Next”:
<br />
<img src="https://i.imgur.com/sKniD3u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In the "User Experience Settings" section, make sure to select the option "Check for product updates on startup." You also have the option to participate in the VMware customer experience, but I'm unchecking that box and then clicking "Next"
<br/>
<img src="https://i.imgur.com/haa8Z3o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, you'll be prompted to choose your shortcut preferences. I'll be selecting both "Desktop" and "Start Menu Programs Folder: 
<br />
<img src="https://i.imgur.com/I05u4nM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now you can click “Install”:  
<br />
<img src="https://i.imgur.com/mlfXG4r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for your installation to be completed.:
<br/>
<img src="https://i.imgur.com/kM79VOx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When finished you’ll see the “Completed the VMWare Workstation 17 Player Setup Wizard.”. Click “Finish”:
<br />
<img src="https://i.imgur.com/VUeenhz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
You’ll be prompted to restart your machine, click “Yes”: 
<br/>
<img src="https://i.imgur.com/ewkdeGY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After reboot you should have the “VMWare Workstation” icon. Open VMWare: 
<br/>
<img src="https://i.imgur.com/Yn3RSch.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
You’ll be asked what version you want to use. I’m using the free version so select “Use VMWare Workstation 17 Player for free for non-commercial use” and click “Continue”:
<br />
<img src="https://i.imgur.com/LDJ0f8f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “Finish” on the thank you screen:
<br/>
<img src="https://i.imgur.com/xW5q7bh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Because I chose the update at start-up, we receive the software is available screen. Click “Download and Install”:
<br />
<img src="https://i.imgur.com/3ESeD4b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Give it a few moments click install updates.
<br />
<img src="https://i.imgur.com/UsCcVic.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You will be prompted for a reboot, select “Yes”. If you boot up VMWare Workstation and have more updates, just follow the same steps as before.
<br />
<img src="https://i.imgur.com/2QNcb7a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When you’re completed with updates you’ll see the main screen where we can add virtual machines: 
<br/>
<img src="https://i.imgur.com/Ph8feWW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I’m going to select “Create a New Virtual Machine”:
<br />
<img src="https://i.imgur.com/KC7reYY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In the "New Virtual Machine Wizard," click on "Browse..." to locate the ISO you want to use, and then click "Next." We'll be using a Kali Linux ISO from:
<br />
https://www.kali.org/get-kali/#kali-platforms
<br />
<img src="https://i.imgur.com/ODNY23b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On the “Select a Guest Operating System” I’m choosing “Linux” and latest version of Debian. In this case “Debian 12.x 64-bit” and select “Next”. Remember Kali is a Debian version of Linux:
<br/>
<img src="https://i.imgur.com/gjM5GQH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your VM and click “Next”:
<br />
<img src="https://i.imgur.com/cAVpIJb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now I’m going to “Specify Disk Capacity”. On “Maximum disk size” I’m going to give it 20gb. Because I’m using a home lab I’m going to select “Split virtual disk into multiple files.” Select “Next”:
<br />
<img src="https://i.imgur.com/n8HYD9Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You can customize more hardware, once you’re ok with your choice select “Finish”:
<br />
<img src="https://i.imgur.com/L7E1Os0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now the machine is built, we’re going to select “Play virtual machine”:
<br />
<img src="https://i.imgur.com/cY7NwRV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You may be prompted to go over side channel mitigation. I’m going to leave it on for the first machine. Select “OK”:
<br />
<img src="https://i.imgur.com/LCYdhE3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we’re going to install Kali Linux, you should see the Kali boot up screen. I’m selecting the “Graphic Install”. If you click in the machine and want your mouse and keyboard back click Ctrl+ALT:
<br />
<img src="https://i.imgur.com/nhDqcqM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the language you would like to use and click “Continue”:
<br />
<img src="https://i.imgur.com/HZZRZyL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select you location and click “Continue”:
<br />
<img src="https://i.imgur.com/0XDid3I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select you Keyboard and click “Continue”:
<br />
<img src="https://i.imgur.com/qdUAI7k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After this you’ll go through install screens:
<br />
<img src="https://i.imgur.com/fGMaXg0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your VM, I’m going with “VMkali”, and click “Continue”:
<br />
<img src="https://i.imgur.com/7Yr2YpF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If you have a domain here is where you can add the machine. If you don’t just click “Continue”:
<br />
<img src="https://i.imgur.com/i9TiGvD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I’m going to name my user “VMkali”, then click “Continue”:
<br/>
<img src="https://i.imgur.com/45hRnlJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create the password for your user, you will need to reenter the password and click “Continue”:
<br />
<img src="https://i.imgur.com/hY8Succ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose your time zone, then click “Continue”:
<br />
<img src="https://i.imgur.com/IVVB7dj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I’m going to choose the “Guided – use entire disk” and click “Continue”:
<br />
<img src="https://i.imgur.com/gzKfA4A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I’m using a brand new disk so I’m going to click “Continue”:
<br />
<img src="https://i.imgur.com/WvopJZQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I’m going to use the recommended option for partitioning. Click “All files in one partition” and select “Continue”:
<br />
<img src="https://i.imgur.com/KlX3BoB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check to make sure the partition is correct and select “Finish partitioning and write changes to disk” and select “Continue”:
<br />
<img src="https://i.imgur.com/5itomsV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If you’re ok with the changes click “Yes” and select “Continue”:
<br />
<img src="https://i.imgur.com/ol717Fs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For software selection choose “Desktop environment” and click “Continue”:
<br/>
<img src="https://i.imgur.com/RCSmmAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
You will be asked to install GRUB boot loader. I’m going to select “Yes” and click “Continue”:
<br />
<img src="https://i.imgur.com/NP9L2a1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the drive you created and click “Continue”:
<br />
<img src="https://i.imgur.com/TQnBYz7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After installation is complete you’ll be prompted to reboot, click “Continue”:
<br />
<img src="https://i.imgur.com/SSF5tzQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now the installation is complete, you’ll need to use the username and password created earlier:
<br />
<br />
<img src="https://i.imgur.com/5itomsV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now you should see the Kali Linux desktop. I recommend running updates, to do this pull up you CLI and type-:
<br />
sudo apt update
<br />
<img src="https://i.imgur.com/EVRD10n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You are going to be prompted for your password. Then you’ll see the updates completed:
<br />
<img src="https://i.imgur.com/xhY4qAO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Kali is now updated and prepared for program installation and execution. To summarize, I have completed the following steps:
<br/>
1. Downloaded and installed VMWare Workstation 17.
<br />
2. Updated VMWare.
<br />
3. Installed Kali Linux.
<br />
4. Updated Kali Linux.
</p>

</p>


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
