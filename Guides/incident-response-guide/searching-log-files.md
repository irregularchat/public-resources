---
title: searching through log files
description: 
published: true
date: 2023-04-09T04:56:40.201Z
tags: dfp, signature reduction, digital force protection, android, mobile, account authentication, hacked, scammed, scam, leak,
editor: markdown
dateCreated: 2023-04-09T00:02:17.203Z
---
_see [incident-response-guide](../incident-response-guide.md)_

```toc
```

## How to Check Logs and Make Sense of It on Different Operating Systems
### Mobile: iOS
### Mobile: Android

### Windows
1. Open the Event Viewer:
   - Press the Windows key + R to open the Run dialog box.
   - Type `eventvwr.msc` and press Enter.
   - The Event Viewer will open.
2. Look for Error or Warning logs related to security:
   - Navigate to Windows Logs > Security.
   - Sort the logs by Event ID, Level, or Source.
   - Look for Event IDs 4624 (successful logon), 4625 (failed logon), and 4648 (explicit login).
   - Look for Warnings or Error logs related to security software such as antivirus or firewall.
3. Search for suspicious activity:
   - Look for repeated failed login attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.

### MacOS
1. Open Console:
   - Launch the Console application from the Utilities folder within the Applications folder.
   - The Console will open.
2. Look for Error or Warning logs related to security:
   - Look for logs related to security software such as antivirus or firewall.
   - Look for logs with the keywords `error` or `warning`.
3. Search for suspicious activity:
   - Look for repeated failed logon attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.

### Linux
1. Open Terminal:
   - Launch the Terminal application.
   - The Terminal will open.
2. Look for Error or Warning logs related to security:
   - Use the command `grep 'error\|warning' /var/log/secure` to view security logs.
   - Look for logs related to security software such as antivirus or firewall.
3. Search for suspicious activity:
   - Look for repeated failed login attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.
