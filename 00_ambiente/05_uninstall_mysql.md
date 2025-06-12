<h1>MySQL Server for Windows Reinstallation Guide</h1>

<h2>Step 01 - Uninstalling MySQL Server</h2>

1.  In the Search Box, locate <b>MySQL</b> (Marked in red in the image), and click on <b>MySQL Installer - Community</b> (Marked in blue in the image).

<div align="center"><img src="https://i.imgur.com/WlUINih.png" title="source: imgur.com" /></div>

 2. In the <b>MySQL Installer</b> window, click the <b>Remove</b> button.

<div align="center"><img  src="https://i.imgur.com/KOG3dxo.png" title="source: imgur.com" /></div>

 3. In the <b>Select Products to Remove</b> window, check the **MySQL server** option and click the <b>Next</b> button.

<div align="center"><img  src="https://i.imgur.com/uB4p6T6.png" title="source: imgur.com" /></div>

 4. In the <b>Remove Server</b> window, check the **remove the data directory** option and click the <b>Next</b> button.

<div align="center"><img src="https://i.imgur.com/BjUh44B.png" title="source: imgur.com" /></div>

 5. In the <b>Remove Selected Products</b> window, click the <b>Execute</b> button.

<div align="center"><img  src="https://i.imgur.com/OGkDMFr.png" title="source: imgur.com" /></div>

 6. Upon completing the MySQL Server uninstallation, click the <b>Finish</b> button.

<div align="center"><img  src="https://i.imgur.com/0I2E1N7.png" title="source: imgur.com" /></div>

 7. The <b>MySQL Installer</b> window will open. Notice that MySQL Server has been uninstalled and no longer appears in the list of installed products.

<div align="center"><img src="https://i.imgur.com/2EPrQlq.png" title="source: imgur.com" /></div>

<h2>Step 02 - Reinstallation and configuration</h2>

1. In the <b>MySQL Installer</b> window, click the <b>Add</b> button.

<div align="center"><img  src="https://i.imgur.com/mnK1Jui.png" title="source: imgur.com" /></div>

2. In the <b>Select Products</b> window, select the <b>MySQL Server</b> option (latest version), as shown in the figure below, and click the <img  src="https://i.imgur.com/GTcQ4fK.png" title="source: imgur.com" /> button to add it to the list of products to be installed.

<div align="center"><img  src="https://i.imgur.com/g9aKLtH.png" title="source: imgur.com" /></div>

3. Verify that <b>MySQL Server</b> has been added to the list and click the <b>Next</b> button to continue.

<div align="center"><img src="https://i.imgur.com/mINLofV.png" title="source: imgur.com" /></div>

4. In the <b>Installation or Download</b> window, click the <b>Execute</b> button to start the installation and/or download of MySQL Server.

<div align="center"><img  src="https://i.imgur.com/ZJAOMZH.png" title="source: imgur.com" /></div>

5. If the installer has downloaded a new version of MySQL, the <b>Download</b> window will indicate the end of the download. Click the <b>Next</b> button to start the MySQL Server installation.

<div align="center"><img  src="https://i.imgur.com/mzpJ9iz.png" title="source: imgur.com" /></div>

6. In the <b>Installation</b> window, click the <b>Execute</b> button to start the installation.

<div align="center"><img  src="https://i.imgur.com/0aXvcNW.png" title="source: imgur.com" /></div>

7. When the product installation is complete, click the <b>Next</b> button to continue.

<div align="center"><img width="500px" src="https://i.imgur.com/p6TRBlY.png" title="source: imgur.com" /></div>

8. In the <b>Product Configuration</b> window, click the <b>Next</b> button to continue.

<div align="center"><img  src="https://i.imgur.com/OLd6vbW.png" title="source: imgur.com" /></div>

9. In the <b>Type and Networking</b> window, keep the default settings and click the <b>Next</b> button to continue.

<div align="center"><img  src="https://i.imgur.com/Qj9cDvs.png" title="source: imgur.com" /></div>

10. In the **Authentication Method** window, keep the default settings and click the <b>Next</b> button to continue.

<div align="center"><img  src="https://i.imgur.com/Jy5t7Tt.png" title="source: imgur.com" /></div>

11. In the <b>Accounts and Roles</b> window, enter a password for the <b>root</b> user (MySQL Administrator User) and click the <b>Next</b> button to continue. We recommend that you set the MySQL password as <b>root</b> (See the note on the next page).

<div align="center"><img  src="https://i.imgur.com/PAgdDkH.png" title="source: imgur.com" /></div>

<div align="center"><h2> *** Important *** </h2></div>

We recommend using the password **root** as the MySQL password because it is a standard password, easy to remember, and can be freely shared on Github. 
If you choose another password, write it down in a safe place and/or use a password that you will not forget in the future. 
Another important precaution is **not to use a personal password such as email, social networks, etc.** Remember that you will share code through Github and your password will be exposed in Github repositories. 
**If you forget your password, you will need to reinstall MySQL to set a new password**.

12. In the <b>Windows Service</b> window, keep the default settings and click the <b>Next</b> button to continue.

<div align="center"><img width="500px" src="https://i.imgur.com/jJNGMCi.png" title="source: imgur.com" /></div>

13. In the **Apply Configuration** window, click the **Execute** button to apply the settings.

<div align="center"><img  src="https://i.imgur.com/phCVyrC.png" title="source: imgur.com" /></div>

14. When the configuration is complete, click the <b>Next</b> button to continue.

<div align="center"><img  src="https://i.imgur.com/68DkOKZ.png" title="source: imgur.com" /></div>

15. In the **Product Configuration** window, click the <b>Next</b> button to apply the settings.

<div align="center"><img  src="https://i.imgur.com/hNomVqz.png" title="source: imgur.com" /></div>

16. In the <b>Installation Complete</b> window, click the <b>Finish</b> button to finalize the installation.

<div align="center"><img  src="https://i.imgur.com/20Odl4I.png" title="source: imgur.com" /></div>

17. Upon completion of the installation, the installer will return to the **MySQL Installer** window. Close the window to finish.

<div align="center"><img  src="https://i.imgur.com/ZrsgSMS.png" title="source: imgur.com" /></div>

<h2>Step 03 - Testing the connection in Workbench</h2>

1. In the Search Box, locate <b>MySQL</b> (Marked in red in the image), and click on <b>MySQL Workbench</b> (Marked in blue in the image).

<div align="center"><img src="https://i.imgur.com/zsr8Om7.png" title="source: imgur.com" /></div>

2. In <b>MySQL Workbench</b>, click on the <b>Local instance MySQL80</b> connection.

<div align="center"><img  src="https://i.imgur.com/HBdNTkU.png" title="source: imgur.com" /></div>

3. If prompted for a password, <b>enter the root user password</b> and check the <b>Save password in vault</b> option to save the password and not be asked again.

<div align="center"><img src="https://i.imgur.com/xC6JFoe.png" title="source: imgur.com" /></div>
<i>Don't forget to write down the password so you don't forget it</i>

4. The main <b>MySQL Workbench</b> window will open. To test MySQL, type the command <b><code>select @@version</code></b> in the query1 window, as shown in the figure below (marked in blue). Then, click the <img src="https://i.imgur.com/3Bl39ca.png" title="source: imgur.com" /> icon to execute the statement. The version of MySQL installed on your computer will be displayed, as shown in the figure below (marked in red).

<div align="center"><img src="https://i.imgur.com/R3rCWjn.png" title="source: imgur.com" /></div>

<br /><br />

<div align="left"><a href="README.md"><img src="https://i.imgur.com/XMgF3gl.png" title="source: imgur.com" width="3%"/>Back</a></div>
