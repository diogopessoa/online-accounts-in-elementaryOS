# online-accounts-in-elementaryOS
Connect your accounts on-line with support two-factor authentication (2FA).

If for some reason you were unable to connect your cloud account, the following tip will probably help you.
After the installation, you should have access to your **Calendar**, **Email**, and **Google Drive** or another account through elementary OS's respective Calendar, Mail, and Files apps.  

## 1. Installation
1. Basically, open the terminal and copy and paste the following command:

```
sudo apt install --no-install-recommends gnome-control-center gnome-online-accounts gnome-online-accounts-gtk
```

2. Now to open **Online Accounts**, copy and paste the command into the terminal:

```
Exec=env XDG_CURRENT_DESKTOP=GNOME gnome-control-center
```

## 2. Account configuration

The currently supported cloud providers are as follows:

- Google: Google Drive, Google Calendar e Gmail.
- Microsoft: OneDrive, email, calendars through Exchange.
- Owncloud: files, calendar and contacts.
- Facebook

### Google
Just follow the steps normally.

### OneDrive

To use OneDrive you must choose the "Microsoft 365" option. Now **ignore all** the text fields and options in the dialog box and click "**Sign in...**"


## Finished!
Now your online accounts can be accessed directly in the Pantheon environment, facilitating access to files, calendars and contacts from different services in one place.

- Screenshot: Synchronized accounts Calendar and Files with Google
![Screenshot: Synchronized accounts calendar and google](https://github.com/diogopessoa/online-accounts-in-elementaryOS/blob/main/images/accounts-sync1.png)

- Screenshot: Gmail account in Mail with 2FA
![Screenshot: Mail with 2FA](https://github.com/diogopessoa/online-accounts-in-elementaryOS/blob/main/images/mail-1.png)

## Thanks to
- https://gitlab.gnome.org/GNOME/gnome-online-accounts/
- https://www.omgubuntu.co.uk/2024/04/set-up-onedrive-file-access-in-ubuntu

## Another cloud sync alternative
- [Celeste](https://github.com/hwittenborn/celeste)

## Support elementary OS ♥️
The development of elementary OS is supported primarily by donations and volunteers. Let's consider supporting elementary OS to bring about positive changes!
- [Support elementary OS](https://github.com/sponsors/elementary) 
