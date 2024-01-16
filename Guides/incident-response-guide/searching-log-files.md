
_see [incident-response-guide](../incident-response-guide.md)_ to return to full steps

```toc
```

## How to Check and Make Sense of Logs on Different Operating Systems
### Mobile: iOS
1. **Use Analytics & Improvements**:
   - Go to **Settings** > **Privacy** > **Analytics & Improvements**.
   - Select **Analytics Data** to view system and app logs.
2. **Identify Suspicious Activity**:
   - Look for entries such as `sysdiagnose`, `stacks+appName`, indicating app crashes or system issues.
   - Search for terms like `privacy`, `location`, `permission` to find logs related to privacy settings changes.
   - Check for any entries with `daemon` or `process` that indicate background activities.

### Mobile: Android
1. **Enable Developer Options**:
   - Go to **Settings** > **About phone**.
   - Tap **Build number** seven times to enable Developer Options.
2. **Access Logs through Developer Options**:
   - Go to **Settings** > **System** > **Developer options**.
   - Scroll to **Debugging** and select **Take bug report** or **Log viewer**.
3. **Check for Suspicious Activity**:
   - Look for frequent app crashes or unexpected system behavior in the logs.
   - Identify any unusual network activities or connection attempts.
   - Check for logs indicating changes in security settings or permissions granted to unfamiliar apps.
   - Look for repeated attempts to access secure features or data without authorization.
### Windows
1. Open the **Event Viewer**:
   - Press the Windows key + R to open the Run dialog box.
   - Type `eventvwr.msc` and press Enter.
   - The Event Viewer will open.
2. Look for Error or Warning logs related to security:
   - Navigate to Windows Logs > Security.
   - Sort the logs by Event ID, Level, or Source.
   - Look for Event IDs `4624` (successful logon), `4625` (failed logon), and `4648` (explicit login).
   - Look for Warnings or Error logs related to security software such as antivirus or firewall.
3. Search for suspicious activity:
   - Look for repeated failed login attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.

### MacOS
1. Open Console:
   - Launch the **Console** application from the **Utilities** folder within the **Applications** folder.
	   - The Console will open.
1. Look for Error or Warning logs related to security:
   - Look for logs related to security software such as antivirus or firewall.
   - Look for logs with the keywords `error` or `warning`.
2. Search for suspicious activity:
   - Look for repeated failed logon attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.

### Linux
1. Open **Terminal**:
   - Launch the **Terminal** application.
2. Look for Error or Warning logs related to security:
   - Use the command `sudo grep -E 'error|warning' /var/log/auth.log` to view security logs.
   - Look for logs related to security software such as antivirus or firewall.
3. Look through users
   - Use the command `sudo getent passwd | grep '/home' | cut -d: -f1` to see all users with a home directory
   - Use the command `sudo getent passwd | cut -d: -f1` to see all users even those without a home directory
3. Search for suspicious activity:
   - Look for repeated failed login attempts from the same source IP.
   - Look for logon attempts from unfamiliar locations or at unusual times.
   - Look for logs indicating changes to security settings or software.
   - Look for logs indicating new software installations or changes to existing software.


