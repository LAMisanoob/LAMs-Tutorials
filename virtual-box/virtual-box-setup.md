## What is a Virtual Machine?

Software that creates a virtual hardware enviroment, thereby allowing one to run an operating system ontop of whatever operating system you are currently using.

**Benefits of using a Virtual Machine**

 - Abilility to easily try new operating systems and their related software.

 - Seperation; It is useful to have a space sandboxed from the space which one uses for normal personal computer tasks which is specifically for learning programming.

 - Disaster Recovery; Save the state of a virtual machine and revert back to that state, and travel back and forward in virtual machine time.

## Virtual Box Installation

For this tutorial I will be using Virtual Box an open source, multiplatform, virtualisation machine. 

For more information on Virtual Box and to download directly for the website click [here](https://www.virtualbox.org/). 

Follow the instructions on the website to install Virtual Box on your operating system.

## Virtual Box Set-Up

Run Virtual Box. A wizard will open to assist you in setting up a new virtual machine. 

Click 'New' to create a new virtual machine.

You will be asked to name your new virtual machine. 

I have called mine 'lisp', this is helpful to remind oneself why one has set up the machine.

Machine Folder is where this new machine will be saved in your filesystem.

From the 'Type' dropdown select Linux.

From the 'Version' dropdown select Ubuntu (64-bit).

Click 'Next'.

You will be asked to select a Memory size. 

I suggest making it about half of your avaliable ram, otherwise it will run very slow.

Click 'Next'.

You will be asked to create a virtual hard disk. 

Click 'Create a virtual hard disk now'.

Click 'Create'.

You will be asked to select a hard disk file type.

No need to change this setting. Leave it as it is.

Click 'Next'.

You will be asked to select between Dynamically or Fixed size. 

Select dynamically allocated.

Click 'Next'.

You will be asked where you would like to save your virtual hard disk. 

Select where you would like to save it.

Click 'Create'.

You have now created your virtual machine, the next step is to install Ubuntu on it.

## Installing Ubuntu on a Virtual Machine

In Virtual Box click the newly created virtual machine tab on the left, then click settings.

Click the 'Storage' tab on the left

Click on the empty cd icon underneath 'Controller: IDE'.

Click the little CD icon next to 'Optical Drive' on the right

Choose 'Choose/Create a Virtual Optical Disk' in the drop down.

Navigate to where you saved the Ubuntu .iso file.

Double click it to creating a optical disc.

Click the little CD icon next to 'Optical Disk' again.

Select this Ubuntu .iso in the drop down. 

Click 'OK' to save these settings.

Double click on the tab for your virtual machine it should now load into the Ubuntu installer.

Installing Ubuntu is a straighforward process, just follow the wizard.

You should now have a fresh install of Ubuntu running on a virtual machine.

