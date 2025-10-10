# Spot the Phish Summary
Summary of identifying phishing red flags and malicious domains.
# Spot the Phish Summary

## 🧠 Objective
This exercise focused on identifying phishing email red flags and understanding how attackers use social engineering to deceive users. It provided hands-on experience evaluating suspicious emails and URLs to determine whether they were legitimate or malicious.

---

## 🔍 What I Analyzed
During the activity, I reviewed multiple email examples to evaluate:
- **Sender legitimacy** – Whether the domain or address matched the organization.
- **Message tone and urgency** – If the email used fear or urgency to trick the recipient.
- **Suspicious links and attachments** – Whether URLs matched the company’s official domain or redirected elsewhere.
- **Grammar and formatting** – Poor spelling, unusual logos, or inconsistent branding.
- **Requests for sensitive information** – Attempts to obtain passwords or payment details.

---

## 🚩 Common Phishing Red Flags
| Category | Description | Example |
|-----------|--------------|----------|
| **Suspicious Sender** | Fake or slightly misspelled domains | `support@yourbank-secure.co` |
| **Urgent Language** | Creates fear or time pressure | “Your account will be suspended in 24 hours!” |
| **Unusual Links** | URLs don’t match legitimate domain | `http://login-yourbank.security.net` |
| **Attachments** | Unexpected files from unknown senders | `Invoice_1032.zip` or `.exe` |
| **Generic Greetings** | Not personalized | “Dear Customer” instead of using your name |

---

## 🧰 Tools and Techniques Used
- **Email header analysis** – Reviewing sender IPs and mail routes.
- **Hovering over URLs** – Verifying where a link actually leads before clicking.
- **Sandbox testing** – Opening suspicious attachments in a controlled environment (conceptual simulation).
- **Domain reputation check** – Using WHOIS or VirusTotal to assess domain safety.

---

## 💡 Key Takeaways
- Always **verify before you click** — a single mistake can compromise entire networks.
- **Humans are the first line of defense.** Technical controls can’t stop someone from clicking a malicious link.
- Training users to recognize phishing attempts significantly reduces incident response cases in SOC environments.
- Phishing remains one of the top initial access methods in cyberattacks — continuous awareness training is essential.

---

## 🧩 Real-World Relevance
As a future SOC Analyst, this exercise reinforced how critical **email security awareness** is. Most breaches start with a simple phishing message, so analysts must understand how to investigate and mitigate these threats quickly.  
In real operations, analysts use **SIEM tools** (like Splunk or Chronicle) to correlate phishing incidents, alert on mass phishing campaigns, and flag compromised accounts for remediation.

> *“A single click can open the door — but awareness can keep it locked.”*
