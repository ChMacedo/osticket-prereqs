<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Subcription

<h2>Installation Steps</h2>

<p>
<img width="1220" alt="Screen Shot 2023-09-26 at 9 25 45 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/f810d910-9160-4c2c-8da0-ee49c968184e">
</p>
<p>
Create and virtual machine with azure and remote desktop in.
</p>
<br />

<p>
<img width="719" alt="Screen Shot 2023-09-26 at 9 45 55 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/0e76aa5b-d7df-4015-97e9-eb9a480c033a">
</p>
<p>
Once you have you VM up and running, you'll want to Install / Enable IIS(Internet Information Services) with CGI and common HTTP Features. When the installation is complete you can go to 127.0.0.1 in an internet browser.
</p>
<br />

<p>
<img width="501" alt="Screen Shot 2023-09-26 at 10 13 07 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/f1277249-4707-43a1-a970-eb0e6078cac1">
<img width="501" alt="Screen Shot 2023-09-26 at 10 18 33 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/6fae1eb6-8f5a-487a-9199-72bce25d5e5d">
</p>
<p>
Download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi) and Rewrite Module (rewrite_amd64_en-US.msi)
</p>
<br />

<p>
<img width="684" alt="Screen Shot 2023-09-26 at 10 20 10 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/f41d0d1b-d99f-48bd-9c1b-fa13f4606253">
</p>
<p>
Create the directory C:\PHP
</p>
<br />

<p>
<img width="684" alt="Screen Shot 2023-09-26 at 10 42 05 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/34e49d6a-b484-4f0b-a9ad-d984dd939baf">
</p>
<p>
Download PHP 7.3.8 and unzip the contents into C:\PHP
</p>
<br />

<p>
<img width="637" alt="Screen Shot 2023-09-26 at 10 44 40 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/29ce2672-5000-4141-a186-36ce3126dcce">

</p>
<p>
Download and install VC_redist.x86.exe
</p>
<br />

<p>
<img width="493" alt="Screen Shot 2023-09-26 at 10 50 37 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/715f6b22-8529-4ccc-b96f-a5723568af64">
</p>
<p>
Download and install mySQL 5.5.62
- Typical Setup
- Standard Configuration
</p>
<br />

<p>
<img width="583" alt="Screen Shot 2023-09-26 at 11 00 21 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/7448432e-3e74-4629-8b17-488c068ffc09">
</p>
<p>
Open IIS as an Admin from windows menu. Then open PHP Manager and register a new PHP veriseron (C:\PHP\php.cgi.exe)
</p>
<br />

<p>
<img width="465" alt="Screen Shot 2023-09-26 at 11 08 45 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/c72e74a3-6a77-45a3-9efb-14476d674cbc">
<img width="410" alt="Screen Shot 2023-09-26 at 11 09 45 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/89a5818f-6ad4-4845-96fd-172b6be97472">
</p>
<p>
Install os Ticket v1.15.8. from the os ticket zip file extract and copy the "upload" folder to C:\inetpub\wwwroot. Then rename the folder "osTicket"
</p>
<br />

<p>
<img width="583" alt="Screen Shot 2023-09-26 at 11 00 21 AM" src="https://github.com/ChMacedo/osticket-prereqs/assets/103891128/7448432e-3e74-4629-8b17-488c068ffc09">
</p>
<p>
Enable some extensions  <br /> 
  1. php_imap.dll  <br />
  2. php_intl.dll  <br />
  3. php_opcache.dll  
</p>
<br />


