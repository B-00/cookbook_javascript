<h1>MySQL for Windows Installation Guide</h1>

<h2>Step 01 - Download the installer</h2>

1) Access the website: https://dev.mysql.com/downloads/ to download **MySQL Server - Community**.

2) Click on the **MySQL installer for Windows** link, as indicated in the figure below:

<div align="center"><img  src="https://i.imgur.com/wP42ICv.png" title="source: imgur.com" /></div>

3) Click on the second link, **Windows (x86, 32-bit), MSI Installer**, as indicated in the figure below:

<div align="center"><img src="https://i.imgur.com/CM8f3nz.png" title="source: imgur.com" /></div>

| <img src="https://i.imgur.com/hOgWvSc.png" title="source: imgur.com" width="120px"/> | <p align="justify"> **ATTENTION:** At the time this guide was written, the latest version of MySQL was 8.0.26.0. When using this guide in the future, the latest version may be different* </p> |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

4) Click on the link **No thanks, just start my download**, to start the download immediately without registration, as indicated in the figure below:

<div align="center"><img  src="https://i.imgur.com/lpG1eSl.png" title="source: imgur.com" /></div>

5) Save the file.

<div align="center"><img src="https://i.imgur.com/zA2drj2.png" title="source: imgur.com" /></div>

6) Open the downloads folder and run the installer by double-clicking the file.

<div align="center"><img src="https://i.imgur.com/SIqI29z.png" title="source: imgur.com" /></div>

<h2>Step 02 - Installation and configuration</h2>

1. In the **Choosing a Setup Type** window, select the **Custom** option and click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/FhyD8L8.png" title="source: imgur.com" /></div>

2. In the **Select Products** window, select the **MySQL Server** option (latest version), as shown in the figure below, and click the <img src="https://i.imgur.com/GTcQ4fK.png" title="source: imgur.com" /> button to add it to the list of products to be installed.
<div align="center"><img  src="https://i.imgur.com/1DNaL8e.png" title="source: imgur.com" /></div>

3. Still in the **Select Products** window, select the **MySQL Workbench** option (latest version), as shown in the figure below, and click the <img src="https://i.imgur.com/GTcQ4fK.png" title="source: imgur.com" /> button to add it to the list of products to be installed.
<div align="center"><img  src="https://i.imgur.com/k243e8F.png" title="source: imgur.com" /></div>

4. Verify that the list of products to be installed is correct and click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/eB3OVTP.png" title="source: imgur.com" /></div>

5. In the **Installation** window, click the **Execute** button to start the installation.
<div align="center"><img  src="https://i.imgur.com/CACoYmO.png" title="source: imgur.com" /></div>

6. When the product installation is complete, click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/JKS7dd4.png" title="source: imgur.com" /></div>

7. In the **Product Configuration** window, click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/4DzBPNl.png" title="source: imgur.com" /></div>

8. In the **Type and Networking** window, keep the default settings and click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/Qj9cDvs.png" title="source: imgur.com" /></div>

9. In the **Authentication Method** window, keep the default settings and click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/Jy5t7Tt.png" title="source: imgur.com" /></div>

10. In the **Accounts and Roles** window, enter a password for the **root** user (MySQL Administrator User) and click the **Next** button to continue. We recommend that you set the MySQL password as **root** (See the note on the next page).

<div align="center"><img  src="https://i.imgur.com/PAgdDkH.png" title="source: imgur.com" /></div>

<div align="center"><h2> *** Important *** </h2></div>

We recommend using the password **root** as the MySQL password because it is a standard password, easy to remember, and can be freely shared on Github.
If you choose another password, write it down in a safe place and/or use a password that you will not forget in the future.
Another important precaution is **do not use a personal password such as email, social networks, etc.** Remember that you will share code through Github and your password will be exposed in Github repositories.
**If you forget your password, you will need to reinstall MySQL to set a new password**.

11. In the **Windows Service** window, keep the default settings and click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/jJNGMCi.png" title="source: imgur.com" /></div>

12. In the **Apply Configuration** window, click the **Execute** button to apply the settings.
<div align="center"><img  src="https://i.imgur.com/phCVyrC.png" title="source: imgur.com" /></div>

13. When the configuration is complete, click the **Next** button to continue.
<div align="center"><img  src="https://i.imgur.com/68DkOKZ.png" title="source: imgur.com" /></div>

14. In the **Product Configuration** window, click the **Next** button to apply the settings.
<div align="center"><img  src="https://i.imgur.com/hNomVqz.png" title="source: imgur.com" /></div>

15. In the **Installation Complete** window, click the **Finish** button to finalize the installation.
<div align="center"><img  src="https://i.imgur.com/20Odl4I.png" title="source: imgur.com" /></div>

16. Upon completion of the installation, **MySQL Workbench** will be launched.
<div align="center"><img  src="https://i.imgur.com/5BYFXRe.png" title="source: imgur.com" /></div>

<h2>Step 03 - Testing the connection in Workbench</h2>

1. In <b>MySQL Workbench</b>, click on the <b>Local instance MySQL80</b> connection.

<div align="center"><img src="https://i.imgur.com/HBdNTkU.png" title="source: imgur.com" /></div>

2. If prompted for a password, <b>enter the root user password</b> and check the <b>Save password in vault</b> option to save the password and not be asked again.

<div align="center"><img src="https://i.imgur.com/xC6JFoe.png" title="source: imgur.com" /></div>

3. The main <b>MySQL Workbench</b> window will open. To test MySQL, type the command <b><code>select @@version</code></b> in the query1 window, as shown in the figure below (marked in blue). Then, click the <img src="https://i.imgur.com/3Bl39ca.png" title="source: imgur.com" /> icon to execute the statement. The version of MySQL installed on your computer will be displayed, as shown in the figure below (marked in red).

<div align="center"><img src="https://i.imgur.com/R3rCWjn.png" title="source: imgur.com" /></div>

<h2>Error: Workbench disconnected</h2>

If the Query Editor Toolbar is disabled, as shown in the figure below, it means that you have not connected to the MySQL Server on the MySQL Workbench home screen.

<div align="center"><img src="https://i.imgur.com/g85JKEL.png" title="source: imgur.com" /></div>

Note that the word **unconnected** appears in the Query Editor Tab, as shown in the figure below:

<div align="center"><img src="https://i.imgur.com/74Wap0e.png" title="source: imgur.com" /></div>

To fix this problem, click the <img src="https://i.imgur.com/8hu9zjU.png" title="source: imgur.com" /> icon next to the Query Editor tab to return to the Workbench home screen.

<div align="center"><img src="https://i.imgur.com/5CtdmCs.png" title="source: imgur.com" /></div>

On the home screen, double-click the **Local instance MySQL80** connection (Local connection), as shown in the figure below, to connect to the MySQL Server.

<div align="center"><img src="https://i.imgur.com/HBdNTkU.png" title="source: imgur.com" /></div>

If prompted for the root user password, as shown in the figure below, enter the password and check the **Save password in vault** option to save the password and not be prompted again.

<div align="center"><img src="https://i.imgur.com/xC6JFoe.png" title="source: imgur.com" /></div>
 
Note that after connecting to the MySQL Server, the Toolbar will be enabled, the word **unconnected** will be replaced by **Local instance MySQL80** in the Query Editor Tab, and MySQL will function normally again.

<div align="center"><img src="https://i.imgur.com/qNjLvqW.png" title="source: imgur.com" /></div>

<h2>Disable Daily Update at 12 AM</h2>

MySQL configures a daily update at 12 AM during installation. Every day at this time, a **Windows Command Prompt** window appears, executing a series of commands, and then closes automatically upon completion. To disable this option, follow the steps below:

1. In the Search Box, locate the <b>Task Scheduler</b> (Marked in red in the image), and click on <b>Task Scheduler</b> (Marked in blue in the image).

<div align="center"><img src="https://i.imgur.com/s5xnlGG.png" title="source: imgur.com" /></div>

2. In the Task Scheduler window, locate the <b>MySQL</b> folder as shown in the figure below:

<div align="center"><img src="https://i.imgur.com/OJ1aM3f.png" title="source: imgur.com" /></div>

3. Right-click on the <b>ManifestUpdate</b> task and click the <b>Delete</b> or <b>Disable</b> option.

<div align="center"><img src="https://i.imgur.com/zXuiYZh.png" title="source: imgur.com" /></div>

<br /><br />

<div align="left"><a href="README.md"><img src="https://i.imgur.com/XMgF3gl.png" title="source: imgur.com" width="3%"/>Back</a></div>
