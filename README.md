# s60v3-obex
Mount filesystem of s60v3 phone through bluetooth in Debian 11 (bullseye)

Put the s60v3-obex script in ~/bin or some other directory in the path, and make it executable (chmod +x s60v3-obex)

Put yourself in the sudoers group: e.g. for user john: "usermod -aG sudo john" (for this to be effective you need to log out and log in again)

Pair your phone with your computer; set the computer as "authorised" in the bluetooth menu of the phone

Run "s60v3-obex phone_name" in a terminal to mount the filesystem of the phone with bluetooth name "phone_name" at /media/phone_name

