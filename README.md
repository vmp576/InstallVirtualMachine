<p align="center">
<img src="https://i.imgur.com/DP8qFNC.png" width="25%" height="25%" alt="VMware Workstation Logo"/>
</p>

# Installing Virtual Machines in VMware

This project is essential for all future projects and labs. After creating the virtual machine, you can create more virtual machines or use snapshots of the first virtual machine for future labs.

## Environments and Technologies Used

- VMware Workstation
    - [Installation Tutorial](https://knowledge.broadcom.com/external/article?articleNumber=387947)
- Windows 10 Pro ISO
    - [Use the Windows 10 Media Creation Tool and follow the “Using the tool to create installation media…” steps.](https://www.microsoft.com/en-us/software-download/windows10)

## Operating Systems Used
 - Windows 10 (22H2)

## Project Walk-Through
Before working through this lab, ensure you have downloaded and installed all the necessary prerequisites for this project (Installed VMware and Downloaded Windows 10 ISO, Downloaded Exercise Files).

To start working on this project, open VMware Workstation and create a new Windows 10 Virtual Machine.

Choose Typical Configuration and click Next.

<img src="https://i.imgur.com/TeEqZNO.png" height="70%" width="70%"/>

Select the “I will install the operating system later” option and click Next.

<img src="https://i.imgur.com/InT6alg.png" height="70%" width="70%"/>

The following settings should be automatically detected, and the default settings set by VMware are acceptable, so press Next until you Finish. If you have any other preferences, change them in the following sections. In my case, I changed the virtual machine's name to osTicket Lab and changed the location of the virtual Machine.

<img src="https://i.imgur.com/WICJMs3.png" height="70%" width="70%"/>

Now, we will be inserting the Windows 10 ISO. After finishing the configuration, the Virtual Machine should pop up in VMware Workstation. Click “Edit virtual machine settings” > Select “CD/DVD (SATA)” > “Use ISO image file:” > and select your Windows 10 ISO. After ensuring that your settings are similar to mine, press “OK”.

<img src="https://i.imgur.com/E051zZn.png" height="70%" width="70%"/>

After, “Power on this virtual machine” and click inside the VM, your mouse should be “captured” and cannot escape the VM. During this time, it is crucial that you enter an input so that Windows installation can start.

<img src="https://i.imgur.com/1VWBBwv.png" height="70%" width="70%"/>

When you get into the installation page, click on “Next” and “Install Now”. you should be taken into the “Activate Windows” page

<img src="https://i.imgur.com/RGg2TgA.png" height="70%" width="70%"/>

Select “I don’t have a product key,” select the Windows 10 Pro operating system, then press Next.

<img src="https://i.imgur.com/WBWCFQa.png" height="70%" width="70%"/>

Keep going with the installation until you get to the installation type page. Choose Custom.

<img src="https://i.imgur.com/Nd2Nyag.png" height="70%" width="70%"/>

Select Drive 0, press New, and hit Apply, OK, and Next. After that, windows should start installing.

<img src="https://i.imgur.com/jeEBNVv.png" height="70%" width="70%"/>

After that comes the Windows 10 configuration screen. Select your region and keyboard layout. If you want a second keyboard layout, choose “**Offline Account**.” Select **“Limited Experience”.** These steps are crucial for setting up the future labs.

<img src="https://i.imgur.com/lluxvlq.png" height="70%" width="70%"/>

When you get to the “Who’s going to use this PC” page, we are now at the stage of configuring the user. You will need multiple users with different names in future labs involving multiple virtual machines. In this case though, I will be creating the “basic” virtual machine with the following credentials

1. Name: labuser
2. Password: Password123!
3. Secret Questions: Whatever you choose/is memorable to you

<img src="https://i.imgur.com/lP54F9U.png" height="70%" width="70%"/>

When you get to the “Services” tab, click on “Not Now”.

<img src="https://i.imgur.com/o3Sf6QX.png" height="70%" width="70%"/>

Then, you can choose your privacy settings. In my case, I disabled all of them. Then press Accept

<img src="https://i.imgur.com/mbJksVi.png" height="70%" width="70%"/>

With the Customize Your Experience and Cortana pages, press SKIP and Not Now.

<img src="https://i.imgur.com/wqyMMe0.png" height="70%" width="70%"/>

Upon reaching the desktop, do any configurations you would like for the “basic” virtual machine. After, click on “Install Tools.”

<img src="https://i.imgur.com/CDsfM26.png" height="70%" width="70%"/>

After that, you should receive a pop-up about VMware tools. Open Windows File Explorer and navigate to VMware tools. (Or Click on the Pop Up to Install VMware Tools). Follow the installation and follow the Typical installation.

<img src="https://i.imgur.com/CgEleXk.png" height="70%" width="70%"/>

After successfully installing VMware Tools, a popup about the installation setup should appear. Press Yes and Windows should restart with the VMware Tools successfully finalized.

<img src="https://i.imgur.com/Iz2Magm.png" height="70%" width="70%"/>

After restarting, you can log in and do any final preference configurations before we create a snapshot.

In the VMware Workstation window itself (Not the Virtual Machine), select Edit > Preferences > Workspace > Save screenshots to: > Select save to: for wherever it is most convenient to store screenshots.

<img src="https://i.imgur.com/JgXapMb.png" height="70%" width="70%"/>

Finally, in the VMware Workstation window, right-click your Windows 10 virtual machine > Snapshot > Take Snapshot. In my case, I will name it “Basic”. You can use this snapshot to install/practice the various following labs and exercises.

<img src="https://i.imgur.com/UdK9smR.png" height="70%" width="70%"/>
