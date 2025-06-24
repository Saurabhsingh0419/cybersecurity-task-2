# 📧 Phishing Email Analysis - Task 2

## 📌 Sample Email 1
**From:** security@paypai.com  
**Subject:** Urgent: Your account will be suspended!  

**Phishing Indicators:**
- Sender address spoofed: `paypai.com` instead of `paypal.com`
- Suspicious link: `http://paypai-login.com/verify`
- Threatening language: "Your account will be suspended"
- Generic greeting: "Dear User"
- Spelling error in domain

---

## 📌 Sample Email 2
**From:** info@amazonn-support.com  
**Subject:** Important: Order Cancelled due to payment issue!  

**Phishing Indicators:**
- Spoofed domain: `amazonn-support.com`
- Fake link: `https://amazon-payment-verify.com`
- Urgent language: "avoid account restrictions"
- No order details
- Generic greeting: "Dear Customer"

---

## 📌 Sample Email 3
**From:** accountsupport@microsoft-support.online  
**Subject:** Action Required: Unusual sign-in activity detected  

**Phishing Indicators:**
- Fake domain: `microsoft-support.online`
- Suspicious link: `http://secure-microsoft-login.net`
- Urgent: "Failure to act will result in suspension"
- Generic greeting: "Hello"
- Unofficial domain extension: `.online`

---

## 📌 Header Analysis Summary:
- Return-Path differs from actual domain
- Received header line shows suspicious IP or server
- Reply-To set to spoofed address  
(*see screenshot: `header_analysis_screenshot.png`*)

---

## 📌 Conclusion:
These emails use classic phishing techniques like spoofed sender addresses, fake URLs, urgent language, spelling errors, and generic greetings to manipulate recipients and steal personal data.
