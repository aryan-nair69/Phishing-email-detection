# Phishing-email-detection
This module detects phishing , spam , malicious emails through a variety of inspections on the attachments, headers and the contents of the email. It works in real time and can be deployed on any custom server or work along side other email providers.

Checks include: 
DMARC, DKIM, SPF, Domain name matching, malicious file attachment, email content, url analysis using an ML model,hash detection and analysis of the file attachment, Blacklisted domain check

Architecture:
Multi threaded, Mongodb database for login, Subprocess implementation in each therad, Auto blacklist.csv file pulldown, Heuristic ML model that updates itself at regular intervals, Encryption for the data stored in the mongodb collection
