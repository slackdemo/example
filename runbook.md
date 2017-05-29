# Acme Digital - Runbook 2017
## Error: EID123


### Perform a soft reboot

To perform a soft reboot of the server, you must be logged in to the server using an account with superuser or administrator permissions.

For the command you should use to soft reboot your server, see the appropriate section for your server operating system:

#### Linux

```sudo reboot```

#### Windows

Open Settings. Click Power > Restart.
Click Start. Click the arrow next to Shut down, and select Restart from the menu.
Alternatively, you can initiate a soft reboot from the command line by entering the following command:

```shutdown /r```
If a dialog box appears, select Restart from the dropdown menu. Click OK.

###  Perform a hard reboot

If the server is not responding or was shut down manually, perform a hard reboot via the Admin Panel to simulate power cycling the server.

>#### Warning: A hard reboot does not shut down applications gracefully and can result in data loss.

Log in to the Admin Panel.
In the top navigation bar, click Servers > Cloud Servers, and then click the gear icon next to the server that you want to reboot.
Select Reboot.
In the pop-up dialog box, click Reboot Server.
The server status on the Servers page updates while the server is rebooting. When the reboot is complete, check the server to confirm that everything is functioning as expected.
