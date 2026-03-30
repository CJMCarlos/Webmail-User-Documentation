# How to Setup An External Email Client
This walkthrough will be assuming that your external email client of choice is **Outlook**.

**Gmail will not work for this method of setting up an external client.**

## 1. Enable Native Client
1. Sign in to your BCIT Email in Webmail.
2. Go to the **Settings** tab in the top right of the screen.
3. Go to the settings section **Preferences** (it should be automatically selected).
4. Go to the Section **Native Client**.
5. Next to *Enable Native Client* click the slider so that it turns blue.

## 2. Configuring Outlook
1. Click the **Add account** button in Outlook.
2. Under the *Suggested accounts* header, add your BCIT Email , then continue.
3. Click the **IMAP** option in the list.
4. Under the *Password* header enter your BCIT Email password
5. Ensure that the *IMAP Incoming server* is **imap.my.bcit.ca**, the *Port* is **993**, and the *Secure connection type* is **SSL / TLS**. If any of these are not the suggested values, correct them.
6. Ensure that your *SMTP username* is your BCIT Email.
7. Ensure that the *SMTP Outgoing server* is **smtp.my.bcit.ca** and the *Port* is **587**.
8. Under the *Secure connection type* change the value to **StartTLS**.
9. Press **Continue** twice.