<table style="width:100%; font-family: Verdana, Tahoma; border: none; border-collapse: collapse;">

  <!-- University Logo -->
  <tr>
    <td colspan="3" style="text-align: center; vertical-align: middle; padding: 10px 0;">
      <img src="https://www.kalasalingam.ac.in/wp-content/uploads/2022/02/Logo.png" 
           alt="Kalasalingam Academy of Research & Education" 
           style="height:80px; display:block; margin: 0 auto;">
    </td>
  </tr>

  <!-- Department and School -->
  <tr>
    <td colspan="3" style="text-align: center; font-size: 18px; font-weight: bold; padding: 5px 0;">
      Department of Computer Science Engineering | School of Computing
    </td>
  </tr>

  <!-- Course and Section -->
  <tr>
    <td colspan="3" style="text-align: center; font-size: 16px; padding: 2px 0;">
      Digital Forensics - 213CSE4307 | Lab Record | Section: 23S19 - Cybersecurity
    </td>
  </tr>

  <!-- Experiment Info -->
  <tr>
    <td style="width:33%; text-align: left; padding-top: 10px;"><strong>Experiment No:</strong> 02</td>
    <td style="width:34%; text-align: center; padding-top: 10px;">
      <h3 style="margin: 0; font-family: Verdana, Tahoma;">Mail Header Analyzer (MHA)</h3>
    </td>
    <td style="width:33%; text-align: right; padding-top: 10px;"><strong>Date:</strong> / /</td>
  </tr>

</table>

<hr style="margin:10px 0;">




## Objective

To analyze email headers using the **Mail Header Analyzer (MHA)** tool and understand how to trace the origin, routing, and security details of an email.

---

## Introduction

Email headers carry vital technical information about the path an email takes from the sender to the recipient.  
The **Mail Header Analyzer (MHA)** simplifies this process by providing a graphical representation of:

- Sender details and originating IP.
- Email routing and hops (servers involved in delivery).
- Authentication checks (SPF, DKIM, DMARC).
- Security-related information (phishing indicators, malicious links).

---

## Tool Information

- **Tool Name:** Mail Header Analyzer (MHA)
- **Tool Type:** Web-based analysis tool
- **Website:** [https://mha.azurewebsites.net/](https://mha.azurewebsites.net/)
- **Platform:** Browser-based (no installation required)

---

## Features of MHA

1. Visualizes email routing paths in an easy-to-read chart.
2. Checks email authenticity with **SPF, DKIM, and DMARC**.
3. Extracts IP addresses and geolocation details of mail servers.
4. Helps in **phishing and spam investigation**.
5. Simple copy-paste interface to analyze headers quickly.

---

## Step-by-Step Procedure

1. **Access the Tool**  
   - Open your web browser and visit:  
     [https://mha.azurewebsites.net/](https://mha.azurewebsites.net/)

2. **Obtain the Email Header**  
   - Open your email application (Gmail, Outlook, etc.).  
   - Find the **View Email Header** or **Show Original** option.  
   - Copy the **entire header text**.

3. **Paste the Header in MHA**  
   - In the Mail Header Analyzer page, paste the copied header into the input box.

4. **Analyze**  
   - Click on **Analyze Header**.  
   - The tool will display:
     - A **timeline of servers** the email passed through.
     - The **originating IP** and server geolocation.
     - Authentication checks (SPF, DKIM, DMARC).
     - Warnings or suspicious elements.

5. **Interpret the Results**  
   - Identify possible spoofed or malicious emails.
   - Check if the email is from a trusted source.
   - Document findings for forensic analysis.

---

## Example Output

| Parameter               | Description                                         |
|-------------------------|-----------------------------------------------------|
| Originating IP          | Shows the IP address of the sender’s mail server.   |
| SPF (Sender Policy)     | Indicates if the sender’s domain is authorized.     |
| DKIM (Domain Keys)      | Verifies that the message has not been altered.     |
| DMARC                   | Policy enforcement for email validation.            |
| Hop Count               | Number of mail servers the email passed through.    |

---

## Advantages

- Easy to use (no installation required).  
- Provides detailed analysis in seconds.  
- Helps detect phishing, spoofing, and spam campaigns.

---

## Applications in Cybersecurity

- **Digital Forensics:** Trace email sources in phishing cases.  
- **Incident Response:** Quickly validate suspicious emails.  
- **Threat Hunting:** Identify spam campaigns and malicious actors.

---

## Conclusion

The **Mail Header Analyzer (MHA)** is an essential tool for cybersecurity professionals, investigators, and IT teams to quickly understand email delivery paths, validate authenticity, and identify threats.  
Its simplicity and visualization make it an excellent choice for both beginners and experts.

---
