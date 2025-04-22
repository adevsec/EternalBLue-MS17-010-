<h1>Exploiting EternalBlue (MS17–010)</h1>

![image alt]([image_url](https://github.com/adevsec/EternalBLue-MS17-010-/blob/242a01d953c7c5476261490c67c32115ee9f998b/1.png)
 ### [YouTube Demonstration](https://www.youtube.com/watch?v=atdk4paWL8w)


<h2>Description</h2>
<b>EternalBlue is an exploit developed by the NSA and leaked by the Shadow Brokers in 2017.
</b>
<br />
<br />
This exploit targets a flaw in Microsoft’s implementation of the SMB protocol, specifically versions 1.0, enabling attackers to send specially designed packets to a vulnerable system. This exploit gained notoriety due to its use in the WannaCry ransomware attack, which caused widespread damage across the globe.
<br />
<br />
<h2>Key Characteristics</h2>

- Vulnerability ID: MS17–010
- CVE Identifiers:
- CVE-2017–0144: Related to remote code execution through the SMBv1 protocol.
- CVE-2017–0145: Related vulnerability affecting the SMB protocol.
- CVE-2017–0146: Another associated vulnerability.
- Affected Systems: Windows 7, Windows Server 2008, and earlier versions with SMB v1 enabled.
- Impact: Remote Code Execution, allowing attackers to gain full control of the system.

<p align="center">
<img src="https://i.imgur.com/3d3CEwZ.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Initial Reconnaissance</h2>
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
