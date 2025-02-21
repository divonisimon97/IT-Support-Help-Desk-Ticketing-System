# <h1>IT Support Help Desk Ticketing System </h1>

<h2>Description</h2>
In this project, I focus on creating a ticketing system using MariaDB on a Apache web server assigned to a localhost. The goal is to set up a help desk ticketing system to track and manage IT support requests.
<br />


<h2>Languages and Utilities Used</h2>
- <b>GLPI </b> (10.0.18) 
<br />
- <b>MariaDB </b> (11.4.4) 

<h2>Environments Used </h2>

- <b>Linux</b> (6.11.2)

<h2>Program walk-through:</h2>

<p align="center">
Updating System w/ Dependencies: <br/>
<img src="https://i.imgur.com/vo8TcsF.png" height="80%" width="80%" alt="Updating System w/ Dependencies"/>
<br />
<br />
Ensuring the LAMP stack is installed: <br/>
<img src="https://i.imgur.com/VnGcQqn.png" height="80%" width="80%" alt="Ensuring the LAMP stack"/>
<br />
<br />
Ensuring the MariaDB is installed:  <br/>
<img src="https://i.imgur.com/0D4jUiI.png" height="80%" width="80%" alt="Ensuring the MariaDB"/>
<br />
<br />
Checking if PHP is Installed: <br/>
<img src="https://i.imgur.com/RDDVaI8.png" height="80%" width="80%" alt="Checking PHP"/>
<br />
<br />
Installing PHP Extentions for GLPI:  <br/>
<img src="https://i.imgur.com/IUYaJrx.png" height="80%" width="80%" alt="Installing PHP Ext."/>
<br />
<br />
Starting and Enabling the Maria Database Service:  <br/>
<img src="https://i.imgur.com/f0s9VIV.png" height="80%" width="80%" alt="Start and enable the Maria database"/>
<br />
<br />
Opening MariaDB & Creating a Database:  <br/>
<img src="https://i.imgur.com/hgFsBIo.png" height="80%" width="80%" alt="Open MariaDB & Create a Database"/>
<br />
<br />
Creating a Dedicated User & Granting Permissions to the GLPI User:  <br/>
<img src="https://i.imgur.com/Tfm511x.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Go to /var/www/html Directory and List Permissions:  <br/>
<img src="https://i.imgur.com/uD5ATva.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Download GLPI in /var/www/html Directory:  <br/>
<img src="https://i.imgur.com/PjkQKPS.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Checking Directory Permissions:  <br/>
<img src="https://i.imgur.com/ARhxMCU.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Changing Ownership & Permissions in GLPI Directory:  <br/>
<img src="https://i.imgur.com/hs4qYGE.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Restarting Apache2:  <br/>
<img src="https://i.imgur.com/DgQQ0l5.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Checking IP Address:  <br/>
<img src="https://i.imgur.com/DgQQ0l5.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
*** MAJOR UPDATE *** (the GLPI web server refused to connect until I...):  <br/>
<img src="https://i.imgur.com/csvTCVn.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Inside the Configuration File, Ensure the Document Root Matches the Directory that the GLPI is in:  <br/>
<img src="https://i.imgur.com/mcLclTK.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Then Fix Permissions:  <br/>
<img src="https://i.imgur.com/rOYvBa8.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
NOW You Have Access to GLPI:  <br/>
<img src="https://i.imgur.com/55QQz2X.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Install & Ensure PHP Installations:  <br/>
<img src="https://i.imgur.com/a5EdS50.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Database Connection Setup:  <br/>
<img src="https://i.imgur.com/vGI4vVk.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Inside the config_db.php file, add the MariaDB connection details:  <br/>
<img src="https://i.imgur.com/Z9ZoJD8.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Set Permissions on config-db.php & glpicrypt.key Files:  <br/>
<img src="https://i.imgur.com/fzhUDv0.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Enable Permissions Match the User & Type USE (your_database_name_here):  <br/>
<img src="https://i.imgur.com/YTnkPKh.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Proceed to Last Installation Page:  <br/>
<img src="https://i.imgur.com/MDfIBCr.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Login to GLPI w/ Default Credentials:  <br/>
<img src="https://i.imgur.com/ytvmR9D.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<img src="https://i.imgur.com/UKrexYf.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Remove the install.php File in the Install Directory & Restart Apache:  <br/>
<img src="https://i.imgur.com/ztt2gk0.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>
<br />
<br />
Done!:  <br/>
<img src="https://i.imgur.com/0HqHzax.png" height="80%" width="80%" alt="Create & Grant Permissions to User"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
