# <u>***Will reformat and apply style guide after instructions are reviewed.***</u>
- [ ] 1. Review instructions
- [ ] 2. Add images
- [ ] 3. Reformat
- [ ] 4. Apply style guide

# How to Setup An External Email Client

---
## What Is An External Email Client?
> placeholder

!!! warning 
    This walkthrough will be assuming that your external email client of choice is **Outlook**.  
    ***Gmail will not work for this method of setting up an external client.***

## 1. Enable Native Client
1. Sign in to your BCIT Email in Webmail.
2. Go to the **Settings** tab in the top right of the screen.
3. Go to the settings section **Preferences**.

    !!! info
        It should be automatically selected.

4. Go to the Section **Native Client**.
5. Next to *Enable Native Client* click the slider.

    !!! success
        The slider should now be coloured blue.

## 2. Configuring Outlook
1. Click the **Add account** button in Outlook.
2. Under the *Suggested accounts* header, add your BCIT Email, then continue.
3. Click the **IMAP** option in the list.
4. Under the *Password* header enter your BCIT Email password
5. Ensure that the *IMAP Incoming server* is **imap.my.bcit.ca**, the *Port* is **993**, and the *Secure connection type* is **SSL / TLS**. 
6. Ensure that your *SMTP username* is your BCIT Email.
7. Ensure that the *SMTP Outgoing server* is **smtp.my.bcit.ca** and the *Port* is **587**.

    !!! warning
        These should be the default values. If ***any*** of these are not the suggested values, correct them.

8. Under the *Secure connection type* change the value to **StartTLS**.

    !!! warning
        This will not be the default value, make sure to change it.

9. Press **Continue** twice.