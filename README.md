# Virtual-Box
## How to Install VirtualBox on Ubuntu 20.04 ?

Install VirtualBox Using the APT Package Repository

```
sudo apt update 
```
After updating the system’s APT cache repository, install VirtualBox using the command given below.
```
sudo apt install virtualbox
```

After completing the installation of VirtualBox, you can install the extension package for VirtualBox if you need it to support USB devices, connect the host webcam, control a virtual machine remotely, and more features like this. To install the extension package, issue the following command.

```
sudo apt install virtualbox-ext-pack -y
```

In the VirtualBox Extension Pack Configuration window, read and accept the license by selecting “Ok.”

Once the extension pack has been installed, you can start using VirtualBox by searching for “VirtualBox” in the “Applications” menu and clicking on the VirtualBox icon.

or

Type " virtualbox" in terminal.

### Install Ubuntu 20.04 on VirtualBox

Download Ubuntu 20.04 LTS ISO image, visit the official release page of [Ubuntu 20.04 LTS](http://releases.ubuntu.com/20.04/)

#### In this section, I am going to show you how to install Ubuntu 20.04 LTS in VirtualBox VM.

First, open VirtualBox.

Then, click on **Machine > New…**

Now, type in a name for the VM, select **Linux** from the **Type** dropdown menu, and **Ubuntu (64-bit)** from the Version dropdown menu. Then, click on **Next >**.
