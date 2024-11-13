<h1>BlackBoxPentrationTest</h1>

<h2>Description</h2>
This project involved performing a black box penetration test on a Linux-based virtual machine to identify and exploit potential security vulnerabilities. Using Kali Linux and the WMAP Web Scanner, the assessment revealed a directory traversal vulnerability in a web application, which was further exploited to access an internal employee directory. Subsequently, an SQL injection attack was carried out to retrieve sensitive employee information. This project showcases practical expertise in ethical hacking, focusing on vulnerability discovery, exploitation, and documentation.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b>
- <b>Kali Linux</b>
- <b>WMAP Web Scanner</b>

<h2>Environments Used </h2>

- <b>Linux</b> (Debian)
- <b>Kali Linux</b>

<h2>Program walk-through:</h2>

<p align="center">
Webserver being found on the target machine: <br/>
<img src="https://i.imgur.com/1NB6QCO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Went to the web server by typing in the IP address of the target machine in the search bar:  <br/>
<img src="https://i.imgur.com/MSH84n0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QmfA6t8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Found multiple sensitive directories within the webserver: <br/>
<img src="https://i.imgur.com/tnvDUcw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Discovered a directory transversal vulnerability by typing in other directories within the search bar:  <br/>
<img src="https://i.imgur.com/FdaSqfX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Found an employee directory:  <br/>
<img src="https://i.imgur.com/3MoUJEL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successfully executed an SQL injection onto the employee directory:  <br/>
<img src="https://i.imgur.com/S1ejdCX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successfully reached the php page for the Apache Web server :  <br/>
<img src="https://i.imgur.com/G8tEKes.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
