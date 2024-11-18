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

![image](https://github.com/user-attachments/assets/0c56caa5-9b09-4772-95ee-6cc3060c2319)
<p>
Enabling IIS with CGI(this allows us to use friendly redirects in the url), then install PHP Manager for the IIS (PHP is a background dependency for osTicket and will allow us to manage the database)  
</p>
<br />

![image](https://github.com/user-attachments/assets/42d04f3d-6eb6-4e0c-aa96-1581a9537dfc)


<p>
Next we want to install rewrite module. According to ChatGPT rewrite allows us to have clean, flexible and secure Url's. By previding helpful redirect, increase security, while also precent broken links while using osTicket.
</p>
<br />

![image](https://github.com/user-attachments/assets/1c38ed84-ea55-4275-abc7-7e9f00e93789)

<p>
 MySql is used to store all of our data in, while HediSql allows us to connect to our database
</p>
<br />
