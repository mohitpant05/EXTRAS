An guide how to activate Windows 11 Pro for free
## Why?
Because you will get some more features like an Bitlocker and host your device as an External Desktop which can be accessed through the internet
## Am i also able to switch from any other edition to Pro?
The answer is yes! You can switch from almost any edition to Pro completely for free!
## Note for users with unactivated Pro edition
People which already have Pro, but not activated, can skip to activating windows step.
## Getting started
What you first need to do is open CMD (Command Prompt) as Administrator using this keyboard key:

Windows-logo key+ R

And now type in "cmd.exe" in the box

It should now look as something like this:

![image](https://user-images.githubusercontent.com/66115754/134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2.png)

Now press this keys on your keyboard:

ctrl+shift+enter

Now you have something like this:

![image](https://user-images.githubusercontent.com/66115754/134801445-9b90e121-350b-42ea-afec-b499f1fbfae9.png)

Now, click on "yes"

Now you have something like this:

![image](https://user-images.githubusercontent.com/66115754/134807479-53ccdaf9-feb0-49a3-9843-5bb4db016128.png)

### The commands
Now, type the following command:
``slmgr.vbs /upk``
Now it will give an message, click on OK

And now this command:
``slmgr.vbs /cpky``
It will give an message once again, and click on OK again

And now type this command:
``slmgr.vbs /ckms``
Once again click on OK when you get an message
### Edition upgradable check command
Now we are gonna check of your edition is supported to upgrade to Pro, run the following command to check this:
``DISM /online /Get-TargetEditions``
If you see "Professional" in the list, then you can upgrade your Windows edition to Pro for free!
### Running Windows Pro installer
Now, copy and paste this complete command:

``sc config LicenseManager start= auto & net start LicenseManager``

``sc config wuauserv start= auto & net start wuauserv``

``changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T``

``exit``

It will run an installer and you will see an message:"% complete"

Now wait until it's 100% and it's not weird that you will get an error

When you get the error, just click Exit and then reboot your pc.

You will now see an message that he is running updates and is installing features, just wait until its done and check "info" in settings, You will see that Windows 11 Pro is installed! 

But we are not done, You will see that it isn't activated and that you can't change some settings, now we are gonna fix that!
## Activating Windows Pro
To activate windows open powershell as an administrator and enter the command below: 

``irm https://massgrave.dev/get | iex``

now a window will show up and enter 1 to activate your windows for lifetime and if ever needed in future repeat the same steps as above.


# Last Words
I hope you enjoy it!
If you have any further questions, you can email me at "poxex@outlook.com" or comment on this guide.
