# How to Create Virtual Machines with VirtualBox
1. Click the "New" button to create a virtual machine. <br>_If you cannot see it, another method is click on the Machine tab and a drop-down menu will appear. Click on New._</br>
2. Next, create a file name, type, and version. The type I am using is Microsoft Windows and the version that I picked is Windows 10 64-bit.

![Image](https://github.com/user-attachments/assets/bdf8826e-785a-4477-97c4-f564cd43357f)

3. Next, we have to choose the Memory size and how many Processors to use for our Virtual Machine.

<br>The easiest way to figure out how much memory you should use would be by opening Task Manager clicking the Performance tab and selecting Memory. You will see how much memory you are using right now.</br>
<br>I am using 7.4 GB out of 16 GB of available memory so I would like to pick an amount that will fit the available memory. I will pick around 4 GB, which will put me around 11.4 GB of memory in use out of 16 GB.</br>

4. Create a virtual hard disk and choose a size. I have selected 80 GB.
5. Click on Finish.

![Image](https://github.com/user-attachments/assets/d8358ee1-5383-433c-9325-7a47d8b37a69)

6. Right-click on the Virtual Machine and choose Settings.
7. From Settings, we can do a lot of things to modify the Virtual Machine. We can go through all the settings but it is not something we need to do. One thing we can do is set Shared Clipboard to Bidirectional and Drag and Drop to Bidirectional under General > Advanced tab. This allows us to Copy and Paste and Drag and Drop from your Host Computer to your Virtual Machine and vice versa.

![Image](https://github.com/user-attachments/assets/3f3235ff-aaca-4ba1-a9f9-c99d7ebffc28)

8. Click on Network on the left options. We can change from NAT to Nat Network and we want to make sure we select the Nat Network we created called My IT Lab. <br> For the rest of the options, there’s no need to modify them unless needed. </br>
9. Click OK to close the Windows Server 2016 Settings window.

**That’s all we have to do to Create and Configure a Virtual Machine with VirtualBox!** 
