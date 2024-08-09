<h1>Phishing Attack Simulation with Gophish</h1>

<h2>Description</h2>
A step-by-step guide to phishing attack simulation and employee awareness using Gophish.
This repository offers a robust phishing attack simulation framework using Gophish, an open-source phishing toolkit. It provides a streamlined approach to simulate phishing attacks, assess organizational vulnerabilities, and enhance security awareness.

<h2>Utilities Used</h2>

- <b>Gophish</b>

<h2>Environments Used </h2>

- <b>Kali</b>

<h2>Summary and Setup Guide</h2>

- <b>What is Phishing ?</b>


Phishing is a cyber-attack where attackers deceive individuals into providing sensitive information, such as login credentials, financial details, or personal data, by pretending to be a trustworthy entity. The goal is to steal confidential information or gain unauthorized access to systems and accounts.

Organizations rely heavily on user awareness and preparation for the eventual attacks. By running phishing simulations, organizations can educate their employees about the tactics used in phishing attacks and test their resilience to them. This helps to ensure that employees are aware of the risks, and know how to identify and report suspicious emails, texts, or other forms of communication. 


<img src="https://i.imgur.com/t3qE9aw.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



- <b>What is Gophish ?</b>


Gophish is an open-source phishing framework that makes it easy to test your organization's resilience to real-world phishing attacks. You can create phishing templates using a full HTML editor, launch scheduled email campaigns to groups of users, and track the responses in near real-time.

<img src="https://i.imgur.com/o6EQZ6E.jpeg" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


- <b>Install</b>


Installation of Gophish is very simple - just download and extract the zip containing the release for your system, and run the binary. Gophish has binary releases for Windows, Mac, and Linux platforms: https://github.com/gophish/gophish/releases/

- <b>Build From Source</b>


If you are building from a source, please note that Gophish requires Go v1.10 or above!

To build Gophish from source, simply run git clone https://github.com/gophish/gophish.git and cd into the project source directory. Then, run go build. After this, you should have a binary called gophish in the current directory.


- <b>Setup</b>



After running the Gophish binary, open an Internet browser to https://localhost:3333 and log in with the default username and password listed in the log output. 


<h2>Program Walkthrough</h2>


<p align="center">
Signed In with default Credentials: <br/>
<img src="https://i.imgur.com/xWOiZpV.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/B0PNam9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
It will prompt you to reset the default password:  <br/>
<img src="https://i.imgur.com/We44bqI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Dashboard: <br/>
<img src="https://i.imgur.com/OP2k32P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<br />
<br />
Create New Group:  <br/>
<img src="https://i.imgur.com/7RB3qMV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Users to the Group:  <br/>
<img src="https://i.imgur.com/oAeIHgV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Email Template:  <br/>
<img src="https://i.imgur.com/D8AjCRZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ecfeant.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/8V8QZAH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/qkYrNP8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Sending Profiles:  <br/>
<img src="https://i.imgur.com/d4aOZZe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/sFqWgjz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/8n4xXGD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Landing Page:  <br/>
<img src="https://i.imgur.com/00MZ17j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/LtEnFMz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Campaign:  <br/>
<img src="https://i.imgur.com/H69f0Yg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch Campaign:  <br/>
<img src="https://i.imgur.com/p2skluV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Vnnl0kd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Results:  <br/>
<img src="https://i.imgur.com/mmL93Iv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/STogZoL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



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
