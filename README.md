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

- Create a VM with windows 10 pro 
- Enabling IIS with CGI 
- Installing rewrite module for osTicket 
- Install PHP Manger 
- Install both HediSQL and MySql 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enabling IIS with CGI(this allows us to use friendly redirects in the url), then install PHP Manager for the IIS (PHP is a background dependency for osTicket and will allow us to manage the database)  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we want to install rewrite module. According to ChatGPT rewrite allows us to have clean, flexible and secure Url's. By previding helpful redirect, increase security, while also precent broken links while using osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 MySql is used to store all of our data in, while HediSql allows us to connect to our database
</p>
<br />
