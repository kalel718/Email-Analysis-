<h1>Email Analysis </h1>
<img src="https://i.imgur.com/1kQPPLK.png" height="80%" width="80%" alt=/>

<img src="https://i.imgur.com/AvYI29h.png" height="80%" width="80%" alt=/>

<img src="https://i.imgur.com/2je4Ldi.png" height="80%" width="80%" alt=/>

- First three questions were pretty straight forward, all info is in the email

<img src="https://i.imgur.com/pPWFwax.png" height="80%" width="80%" alt=/>

- so for the next couple of questions you had to dig deep into the email
- Time to play dectective by looking at the source of the File

<img src="https://i.imgur.com/BXyLBT2.png" height="80%" width="80%" alt=/>

<img src="https://i.imgur.com/wVNTZDo.png" height="80%" width="80%" alt=/>

- for question 7, we had to use tool called Abuseipdb.com
- question 8, once filed is unzipped name is revealed


<img src="https://i.imgur.com/abFBawK.png" height="80%" width="80%" alt=/>

- we are going to open the zip file downloader folder
- then open a Powershell window and you the Get-FileHash cmdlet to retrieve the SHA256 hash

<img src="https://i.imgur.com/C1owckd.png" height="80%" width="80%" alt=/>


<img src="https://i.imgur.com/mB2P5Ln.png" height="80%" width="80%" alt=/>

- Let us upload the file by using the tool Virustotal to see the attachments reputation

<img src="https://i.imgur.com/AyKeGDx.png" height="80%" width="80%" alt=/>
- Uploading the file to VirusTotal shows that the file is extremely malicious. 

- It is detected by 60/70 vendors and 3 sandboxes flagged this file as malicious.
   
- In the top right, we can see that it is a .exe file that is commonly used for malicious purposes.
  
- Also we can see its size and hashes.
  
<img src="https://i.imgur.com/4PoegSg.png" height="80%" width="80%" alt=/>

- Based on the above analysis we can see the attachment is extremely malicious.
  
-  We can also see it contains Trojan malware.

<h2>Analysis Tool</h2>

- Text Editor

- Mozilla ThunderBird

- VirusTotal

- Abuseipd

- Powershell



Great example of what a SOC ANALYST will face................






 







  




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
