# How to Install Windows Server 2016 on Your Virtual Machine
Before turning on the virtual machine, we need to download the ISO file.
### Why do we need an ISO file?
A newly created VM is like a blank computer with no OS. The ISO file contains the OS installer (e.g., Windows, Ubuntu, CentOS), which the VM boots from to begin the installation process.
### Downloading the ISO file:
1. Go back to Google and Search for Windows Server 2016 ISO Download and press Enter.

![Image](https://github.com/user-attachments/assets/62365ca2-c7ea-475d-8924-62852f28c030)


<br>It brings me to the Microsoft Evaluation Center exactly to the Windows Server 2016 ISO download.</br>
<br>You can see it provides 180 days of evaluation and we see that the radio button option is set to ISO.</br>
<br>I will click on the Continue button.</br>

![Image](https://github.com/user-attachments/assets/99ecc604-9a9a-4d00-bed6-1d51ea2e5624)

2. Register and download the ISO file.
3. Once the download completes I am going to close the Web Browse and back to VirtualBox Virtual Machine Settings we can Choose the Virtual Optical Disk File.<br>
<br>Navigate to the download location where the ISO file was saved and select the file and click on the Open button.</br>

![Image](https://github.com/user-attachments/assets/c481d6a2-7aca-436d-a856-d8d7a10b2d71)

4. Now the ISO has been mounted to the Virtual Machine. Click OK to close the Settings window.

![Image](https://github.com/user-attachments/assets/fe8ac6a8-1015-42cc-a9d1-eea06993bd0e)

Now we can start our virtual machine! 

### Launching and Installing Windows Server 2016 with VirtualBox:
1. Click on the Start button.

![Image](https://github.com/user-attachments/assets/31a39b23-4fa3-4c47-b411-505cad9f9dd5)

2. The Virtual Machine will launch, and we will be able to install the Operating System.

![Image](https://github.com/user-attachments/assets/e036bf98-45e5-4a9b-95f7-4fef9146c6f2)

3. From the Windows Server 2016 Windows Setup window click the Next button to start the installation making sure the Language, Time, and Keyboard are set to your preferences.

![Image](https://github.com/user-attachments/assets/686fe57f-f95b-436f-b456-6e9c07c20204)

4. Click on the Install now button.

![Image](https://github.com/user-attachments/assets/b6321faa-45d0-4bd9-961e-663b609bb8eb)

<br>Now, these are the basic steps to install Windows Server 2016 but the same steps can apply to other operating systems. You download an ISO, mount it to the Virtual Machine, and then you launch the Virtual Machine and install the Operating System.</br>

5. On the next screen, we choose the Windows Server 2016 Datacenter Evaluation (Desktop Experience) and click Next to continue.

![Image](https://github.com/user-attachments/assets/00ea79b5-8b13-4dce-941c-d09f47b388c4)

6. Accept the license terms and click on Next.
7. Choose Custom: Install Windows only (advanced) because this is the first time we install anything on this Virtual Machine.

![Image](https://github.com/user-attachments/assets/b95b5fc8-f79e-4915-ba10-db7411d52f5e)

8. I selected Drive 0 Unallocated Space. Notice that the size is 80 GB. This is the Virtual Hard Disk drive that we created earlier when we configured the Virtual Machine. Then click Next to continue.

![Image](https://github.com/user-attachments/assets/7432f46a-e6cc-4107-8943-702a70050f18)

<br>The installation should begin</br>

9. Once installation is complete, you will be prompted to create an admin password. Create one.
10. You will now get to the Login screen.
<br>It says that you need to press Ctrl+Alt+Delete to unlock but if I press those key combinations it will execute those commands in my Host machine.</br>
<br>So what I want to do is from the Virtual Machine menu click on Insert > Keyboard > Insert Ctrl+Alt+Delete </br>

![Image](https://github.com/user-attachments/assets/7fdc1863-60a4-4f86-8c92-a9906afc3377)

11. Now, type the password for the Administrator account we just created and press Enter.
<br>What we want to do now is resolve this problem with the screen which is not set correctly and we need to be scrolling up and down with the scrollbar.</br>
<br>Click on the Virtual Machine menu and click on Devices > Insert Guest Additions CD image...</br>
<br>Most virtualization technologies require that you install some kind of software to allow you to fully use the VM or to make it more usable.</br>

![Image](https://github.com/user-attachments/assets/9a9b4b47-2e51-4a61-a510-68427769c2c3)

12. Now with the Guest Additions disk inserted in the VM, I’ll open File Explorer and click on This PC, and double-click on the CD Drive D: that has the Virtual Box Guest Additions.

![Image](https://github.com/user-attachments/assets/107a076e-4f19-402d-bb64-941c927967d0)

13. Double click on the file named VBoxWindowsAdditions.

![Image](https://github.com/user-attachments/assets/585c2084-db5a-44f2-8639-961998467e3a)

14. The installation wizard launches. Click Next to start the wizard.

![Image](https://github.com/user-attachments/assets/6b7ef207-d8ca-4f22-bf36-c02db3a17e3c)

15. Leave everything default and click next.
16. You will be prompted to reboot the machine. Click it and then click finish.

![Image](https://github.com/user-attachments/assets/fd339ef2-5d7d-46ce-9614-264b23f0e175)

<br>Now that the server has rebooted, log in again and you’ll see that the resolution readjust automatically.</br>

![Image](https://github.com/user-attachments/assets/638d53a3-faae-424c-b524-bbde6ee81591)

<br>That is all we need to do to install the Operating System on our VirtualMachine.</br>
<br>In summary, you are going to create the VM, attach it to a network, configure its memory and processing power, and then mount the ISO of the Operating System you want to install on that Virtual Machine. You then start the Virtual Machine, go through the installation, and install the VirtualBox Guest Additions.</br>
<br>That’s all we need to do in this lecture on How to Install Windows Server 2016 on Your Virtual Machine.</br>
