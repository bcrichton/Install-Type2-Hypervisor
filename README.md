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
