## EX 6: MOVING FILES BETWEEN VIRTUAL MACHINES

# NAME: AKSHAYA S
# REGISTER NUMBER : 212223220006

# AIM:
To move the files between virtual machine. You can move files between virtual machines in several ways: • You can copy files using network utilities as you would between physical computers on your network. To do this between two virtual machine: • Both virtual machines must be configured to allow access to your network. • Any of the networking methods (host-only, bridged and NAT) are appropriate. • With host-only networking, you copy files from the virtual machines to the host and vice-versa, since host-only networking only allows the virtual machines see your host computer. • With bridged networking or NAT enabled, you can copy files across your network between the virtual machines. • You can create a shared drive, either a virtual disk or a raw partition, and mount the drive in each of the virtual machines.

# PROCEDURE:

How to Enable File sharing in VirtualBox.
Step 1. Install Guest Additions on the Guest machine. Step 2. Configure File Sharing on VirtualBox.

Step 1. Install Guest Additions on the Guest machine.

Start the Virtuabox Guest Machine (OS).
From Oracle's VM VirtualBox main menu, select Devices > Install Guest Additions *
a. Open Windows Explorer b. Double click at the "CD Drive (X:) VirtualBox Guest additions" to explore its contents.

<img width="776" height="622" alt="435364047-d3dbb341-38c1-4f3e-92f7-0cfe1084e679" src="https://github.com/user-attachments/assets/3c7cb546-80af-429d-b589-c0640382b56c" />

C.Right click at "VBoxWindowsAdditions" application and from the pop-up menu, choose "Run as administrator".

<img width="1005" height="484" alt="435364130-35be1b73-df5c-445e-bb24-94d71f7898e4" src="https://github.com/user-attachments/assets/1f95cc01-3b78-4e52-a6f7-e3e3d692b9b9" />

3.Press Next and then follow the on screen instructions to complete the Guest Additions installation.

<img width="792" height="523" alt="435364150-066c93ef-f2fa-40e8-a8f2-041ca2758db1" src="https://github.com/user-attachments/assets/fe0994f9-3cab-47d0-a121-99540f7b3ab7" />


4.When the setup is completed, choose Finish and restart the Virtuabox guest machine. Step 2. Setup File Sharing on VirtualBox Guest Machine.
5.From VirtualBox menu click Devices and choose Shared Folders -> Shared Folder Settings.

<img width="905" height="530" alt="435364179-c58d8e37-8a75-47ad-bdc8-800ff55b2ccf" src="https://github.com/user-attachments/assets/b51e04c3-6f4d-4d41-aa85-370db79986c9" />


2.Click the Add new shared folder icon.

<img width="908" height="527" alt="435364190-b7cb3277-4fce-4267-8916-04f94a41a2f8" src="https://github.com/user-attachments/assets/7b944763-89c3-4335-a91f-910a549566ea" />


3.Click the drop-down arrow and select Other.


<img width="931" height="653" alt="435364214-50268dcf-8b14-4592-9a69-439b0639db43" src="https://github.com/user-attachments/assets/713a6667-7fcd-4259-9574-fcb164c46039" />


3.Locate and highlight (from the Host OS) the folder that you want to share between the VirtualBox Guest machine and the Host and click Select Folder. *
.Note: To make your life easier, create a new folder for the file sharing, on the Host OS and give it with a recognizable name. (e.g. "Public")

<img width="880" height="448" alt="435364232-076d8f8f-93cc-478e-902b-8d3d0b1474e6" src="https://github.com/user-attachments/assets/523d8218-419b-4ff4-89f3-bb467cfca98e" />


4.Now, in the 'Add Share' options, type a name (if you want) at the 'Folder Name box, click the Auto Mount and the Make Permanent checkboxes and click OK twice to close the Shared Folder Settings.


<img width="925" height="461" alt="435364241-3f2c7dc1-5781-43e3-8e36-4e0706d603e0" src="https://github.com/user-attachments/assets/0a377740-d6fb-41d7-acd9-29e1657277f5" />

5.You 're done! To access the shared folder from the Guest OS, open Windows Explorer and under the 'Network locations' you should see a new network drive that corresponds to the shared folder on the Host OS.

# RESULT:
Thus the virtual machine files are moved to another VM.







