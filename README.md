# Elevate_Labs_Task_2
 Identify phishing characteristics in a suspicious email sample. <br>
 Key Characteristics of a Phishing Email<br>
 1.Urgency or Threats<br>
 2.Generic Greetings<br>
 3.Spoofed Email Addresses or Domains <br>
 4.Suspicious Links or Attachments <br>
 5.Requests for Sensitive Information <br>

 Phishing Sample Email:
 ![image](https://github.com/user-attachments/assets/d874fe7e-f2ae-4534-a536-a8d38775cb0f)<br>

 Email Header file:<br>
 ![image](https://github.com/user-attachments/assets/119d604c-cfde-4ae9-80c5-c08cd9cdc2dd)


 We Use Following Online Email Header Analyzer Tools:<br>
 Name:MxToolbox Header Analyzer <br>
 Website: mxtoolbox.com<br>
 Google Admin Toolbox Messageheader

 ![image](https://github.com/user-attachments/assets/b6500d4e-1cad-4f97-a32b-cec4d8dd5cc7)

 After Analzing header using MxToolbox :
 ![image](https://github.com/user-attachments/assets/6cb14149-0b94-44aa-9f52-1d9861a7257e)

 This is SPF/DKIM/DMARC/RBL report:<br>
 Report_LinK:-https://github.com/varsha-asawale2010/Elevate_Labs_Task_2/blob/main/DKMI-test-report.txt

 Suspicious Link:
 http://securebank-alerts.com/verify-login
or
http://securebank.security-authenticate.com<br>
Why It’s Suspicious:<br>
Generic anchor: text	"Click here" hides the true destination of the link.<br>
Fake domain:	The email comes from securebank-alerts.com, not the official securebank.com.<br>
Urgent call to action:	Used to rush the victim into clicking without verifying.<br>
No HTTPS mentioned: Most phishing pages use unsecured HTTP or self-signed HTTPS certs.<br>




