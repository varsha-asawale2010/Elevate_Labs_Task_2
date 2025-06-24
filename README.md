# Elevate_Labs_Task_2 Phishing 
## Identify phishing characteristics in a suspicious email sample. <br>
 Key Characteristics of a Phishing Email<br>
 1.Urgency or Threats<br>
 2.Generic Greetings<br>
 3.Spoofed Email Addresses or Domains <br>
 4.Suspicious Links or Attachments <br>
 5.Requests for Sensitive Information <br>

 ## 1. Phishing Sample Email:
 ![image](https://github.com/user-attachments/assets/d874fe7e-f2ae-4534-a536-a8d38775cb0f)<br>

  ## 2. The Spoofed Sender Email Address
  security-update@securebank-alerts.com 

## 3.Email headers for discrepancies by using different tools:<br>
 ![image](https://github.com/user-attachments/assets/119d604c-cfde-4ae9-80c5-c08cd9cdc2dd)


## We Use Following Online Email Header Analyzer Tools:<br>
 Name:MxToolbox Header Analyzer <br>
 Website: mxtoolbox.com<br>
 Google Admin Toolbox Messageheader
## Analzing header using MxToolbox :
 ![image](https://github.com/user-attachments/assets/b6500d4e-1cad-4f97-a32b-cec4d8dd5cc7)

 ![image](https://github.com/user-attachments/assets/6cb14149-0b94-44aa-9f52-1d9861a7257e)

 ## This is overall infomation about SPF/DKIM/DMARC/RBL report:<br>
 Report_LinK:-https://github.com/varsha-asawale2010/Elevate_Labs_Task_2/blob/main/DKMI-test-report.txt

## By Using Another Tool Google Admin Toolbox Messageheader 
 Header:![image](https://github.com/user-attachments/assets/18bf545b-871d-4fa9-b1c2-f0a56133618b)
 Output:![image](https://github.com/user-attachments/assets/5e4835d4-205f-410d-855f-e7290d762e91)



##  4. Suspicious Link OR Attachment:
 http://securebank-alerts.com/verify-login<br>
 Click here to verify your account
 
## We found following reason of it is Suspicious:<br>
Generic anchor: text	"Click here" hides the true destination of the link.<br>

Fake domain:	The email comes from securebank-alerts.com, not the official securebank.com.<br>

Urgent call to action:	Used to rush the victim into clicking without verifying.<br>

## 5. Urgency & Threats:	<br>
Unusual login attempt, verify immediately, account will be permanently restricted
## 6. Mismatch URL
 Fake-Domain:securebank-alerts.com 

 Original-Domain:secure-bank-alerts.com
 ## 7.Verify Grammar & Spelling:	No errors<br>
   Description:Well-written, which shows phishers are improving quality
  
## 8. Phishing Traits Summary<br>
1. Sender Email:	security-update@securebank-alerts.com	<br>
   Description:The Spoofed domain trying to look like a real bank <br>
 
2. Urgency & Threats:	Unusual login attempt, verify immediately, account will be permanently restricted	<br>
   Description:Creates fear and pressure to act without thinking.<br>
 
3. Suspicious Link:	 Click here to verify your account	<br>
   Description:Likely points to a malicious or fake login page (URL is hidden).<br>
 
4. No Personalization: "Dear Customer"	<br>
   Description:Real companies typically address you by name.<br>
 
5. Generic Signature:	SecureBank Security Team <br>
   Description:No real contact info or verifiable signature.<br>
 
6. No Attachments:	N/A	<br>
   Description:This phishing email relies on link-based deception, not files.<br>
  
7. Grammar & Spelling:	No errors<br>
   Description:Well-written, which shows phishers are improving quality.




