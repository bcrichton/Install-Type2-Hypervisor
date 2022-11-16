<h1>[Tutorial] How to Install Type 2 Hypervisor with Oracle VirtualBox</h1>


<h2>Description</h2>
Project will guide the user through creating a virtual machine on Oracle VirtualBox. The operating system that will be demonstrated is Linux Ubuntu, but can be interchanged for other versions of Linux, as well as versions of Windows.
<br />


<h2>Operating Systems and Software Used</h2>

- <b>Windows 11</b> 
- <b>Linux Ubuntu 20.04.01</b>
- <b>Oracle VM VirtualBox 6.1.32

<h2>Important Notes</h2>
  
- <b>There may be limited support for Apple Silicon processors. Please ensure that your computer is compatible during the creation of this project, only Intel and AMD processors were supported for VirtualBox.</b>
- <b>Virtualization must be enabled in your BIOS. If not, you will receive an error upon starting the VM saying that Virtualization is not enabled for the computer’s chipsets. See your motherboard manual for information on how to access your BIOS to enable virtualization.</b>

<h2>Tutorial:</h2>

<p align="left">
Step 1: Install Oracle VM VirtualBox onto Computer: <br/>
https://www.virtualbox.org/wiki/Downloads
<br />
<br />

<p align="left">
Step 2: Install Oracle VM VirtualBox onto Computer: <br/>
  - Open the .exe file that you have downloaded from virtualbox.org (the link above).</br>
  - Run through the steps that will lead you to the install of VM VirtualBox until you get to the screen below, then click Finish.</b>

<p align="center">
<img src="https://i.imgur.com/hxTuRQP.png" height="60%" width="60%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />
  
<p align="left">
Step 3: Download .iso File: <br/>
  - https://releases.ubuntu.com/20.04.1/ubuntu-20.04.1-desktop-amd64.iso?</br></br>

<p align="left">
Step 4: Open Oracle VM VirtualBox Manager: <br/>
  - Click the New button.</br>
  - Give your operating system a name.</br>
  - Set the file path to where you want the VM to be saved to.</br>
  - Make sure the type and version of the VM that you are creating match the .iso file that you are going to be using.</br>
  - Press next.</b>

<p align="center">
<img src="https://i.imgur.com/2kGTR8S.png" height="60%" width="60%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />


<p align="left">
Step 5: Allocate Memory: <br/>
  - Type in the amount of memory that you want the VM to have.</br>
  - You can adjust the slider, or you can type directly into the text box.</br>
  - For this case, we are just going to leave it at the default, whenever you have selected the amount of memory that you want allocated, then click Next.</br>

<p align="center">
<img src="https://i.imgur.com/4aWPVn9.png" height="50%" width="50%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />


<p align="left">
Step 6: Hard Disk: <br/>
  - Make sure that Create a virtual hard disk is bubbled in, then click Create.</br>

<p align="center">
<img src="https://i.imgur.com/kYLHT09.png" height="50%" width="50%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />


<p align="left">
Step 7: Hard Disk File Type: <br/>
  - Select VDI, then click Next.</br>

<p align="center">
<img src="https://i.imgur.com/ebFSjEp.png" height="50%" width="50%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />


<p align="left">
Step 8: Storage on Physical Hard Disk: <br/>
  - Select whether you want the disk space to be dynamically allocated, or if you want to have a fixed size.</br>
  - For this example, we are going to use dynamically allocated.</br>
  - Selecting dynamically allocated will use up only the amount of storage that is needed in the VM. A fixed size will give you a certain amount of storage to use.</br>
  - Example: if you install a 3GB file in the VM, it will take up only 3GB of space on your hard disk.
    If you set a fixed size, you will give the VM only, say, 10GB of storage capacity to work with.</br>

<p align="center">
<img src="https://i.imgur.com/U79HItn.png" height="50%" width="50%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />
  
  
<p align="left">
Step 9: Click Next, twice.<br/><br/>
  

<p align="left">
Step 10: Click the Settings button, then on the side bar, click Storage.<br/><br/>
  
<p align="left">
Step 11: Import .iso file:<br/>
  - Under Controller: IDE, click the empty disk.</br>
  - To the right, there is a drop down menu right next the words Optical drive.</br>
  - To the right of the drop down menu, there is a disk icon. Click this icon, then click Choose a disk file and locate the .iso file that you downloaded in the beginning of the tutorial.</br>
  - Click OK </br><br/>


<p align="left">
Step 12: Start the VM<br/>
  - Click the Start icon.</br>
  - The VM will boot up and configure itself.</br><br/>


<p align="left">
Step 13: Try or Install<br/>
  - Select whether you want the disk space to be dynamically allocated, or if you want to have a fixed size.</br>
  - Select your language</br>
  - Select where you want to try Ubuntu without making any changes to your local PC, or whether you want to install Ubuntu directly onto your local PC.</br>
  - Note: if you select Try Ubuntu, you will still have the option to install later.



<p align="center">
<img src="https://i.imgur.com/RfOhJCE.png" height="50%" width="50%" alt="Type 2 Hypervisor Steps"/>
<br />
<br />

  
<p align="center">
You now should be able to use the VM that you have created.<br/>  
  
  
  
  
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
