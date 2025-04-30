# Creating a Virtual Network with Virtual Box
### What is NAT?
NAT (Network Address Translation) is a method used to map private, internal IP addresses to a public IP address before data is sent out to a broader network like the internet. It allows multiple devices (or virtual machines) on a private network to share a single public IP address for communication outside the local network.

**Why NAT is Important When Creating a Virtual Machine**
When you create a virtual machine (VM), it typically resides on a virtual private network within your host machine. Here's why configuring NAT is important:
1. You can run multiple VMs with different private IPs, all sharing the same public IP.
2. NAT hides the internal IP structure of the virtual network from the external world.
3. VirtualBox: Offers a “NAT” network mode that automatically allows the VM to access the internet via the host.

## Walk-through tutorial 
1. Open up VirtualBox if you haven't already.
2. On the top left corner, click on File.
3. Then select Tools.
4. You will see a drop-down menu, click on Network Manager.

![Image](https://github.com/user-attachments/assets/6a22d5ce-05d1-45be-ab0f-121fbd9fbba6)

5. Click the NAT Network tab.
6. Click the green buttin to create a NAT network.
7. Type in whatever name you want, in my case, I have named the NAT network "My IT Lab".
8. Click on the box that says "Enable DHCP". Make sure it is checked.
9. Then click apply.

![Image](https://github.com/user-attachments/assets/1337c4ec-b123-4d17-a086-5ae0c5900f8a)

And that's it! You have now created a NAT network using VirtualBox. 
