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

- Create a virtual machine in Microsoft Azure
- Enable IIS in Windows with CGI and Common HTTP Features
- Install PHP Manager, Rewrite Module, C++ Redist, HeidiSQL, and MySQL
- Install osTicket and setup osTicket

<h2>Installation Steps</h2>

<p>
<<img width="916" alt="image" src="https://github.com/jaimerobles1/osticket-prereqs/assets/147941741/1da623a4-3ab2-4abc-820d-7d867dd6da47">
>
</p>
<p>
The image shows the creation of a resource group and virtual machine that was used to install and configure osTicket.  The next step would be to connect to the virtual machine in a remote desktop connection so I can install everything needed to get osTicket up and running.
</p>
<br />

<p>
<img src="https://i.imgur.com/w5yzEwi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I went in and enabled IIS by making sure that CGI and Common HTTP Features were enabled under World Wide Web Services.  Also making sure that IIS Management Console is also enabled in IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/8ZRPIcx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The image above shows IIS Manager set up with PHP Manager and CGI. It also shows osTicket is setup and ready to be configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/wTnJcHp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I went into PHP Manager on IIS, found the osTicket folder and while in the folder clicked on "Browse *:80" to enable php_opchache.dll, php_imap.dll, and php_intl.dll.
</p>
<br />

<p>
<img src="https://i.imgur.com/tnpK7Rp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is osTicket fully installed and ready to use.
</p>
<br />
