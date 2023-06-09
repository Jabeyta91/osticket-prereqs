<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services 
- Install web platform installer
- Install MySQL
- Install C++ redistributable
- Configure permissions and install osticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/BHfSSFi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First I enabled CGI with Internet Information Services. CGI then enable me to install PHP manager. Osticket runs off php, so I had to install a web server with php. Next I test my web server connection before going forward. By opening a new tab in remote desktop and went to 127.0.0.1 so I know my web server is up and running.
</p>
<br />

<p>
<img src="https://i.imgur.com/4Uxu0PW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MySQL server is installing a database on the computer. This is for Osticket to store the ticket and user data it will utilize in Mysql database. HeidiSQL allows me to connect to MySQL server also referred to as a database client.
</p>
<br />

<p>
<img src="https://i.imgur.com/LdzujAm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Osticket is a widely used and trusted open source support ticketing system. Some features I had to enable such as php_imap.dll, php_intl.dll, and php_opcache.dll. This can be done by going back to IIS, sites -> Default -> osTicket, Double-click PHP Manager, Click “Enable or disable an extension”.
</p>
<br />
