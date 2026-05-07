# Suspicious Email Investigation

## Overview
This project involved analyzing a suspicious email header to identify potential phishing indicators and trace the path of the message through multiple mail servers. The investigation focused on examining SMTP headers, sender information, authentication results, IP addresses, and reply-to behavior to determine whether the email appeared legitimate or malicious.

## Objectives
- Analyze email headers
- Identify spoofing indicators
- Investigate sender infrastructure

## Skills Demonstrated
- Phishing Detection
- Email Header Analysis
- SMTP Investigation

## Tools Used
- Text editor for header review
- Manual email header analysis
- SMTP and email authentication concepts

## Key Findings

- The email failed SPF authentication checks, indicating the sending server was not authorized to send messages on behalf of the claimed domain.
- The sender requested replies be sent to a different Hotmail account, which is a common phishing tactic used to hide the sender’s true identity.
- Multiple mail servers and routing headers were identified, allowing the message path to be traced through the email infrastructure.
- The sender reputation score indicated suspicious activity associated with the originating IP address.
- The email used urgent and vague wording (“READ !!!”) along with a financial incentive (“grant claim”), which are common social engineering techniques.

## What I Learned

Through this project, I gained hands-on experience analyzing email headers and identifying phishing indicators within SMTP metadata. I improved my understanding of SPF authentication failures, sender reputation analysis, mail server routing, and how attackers use misleading reply addresses to avoid detection. This investigation also strengthened my ability to examine suspicious emails manually and document cybersecurity findings clearly and professionally.

## Disclaimer
Educational purposes only.
