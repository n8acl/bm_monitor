# Brandmeister Last Heard Monitor
Brandmeister Last Heard Monitor/Notifier

###### Forked from [mclemens/pyBMNotify](https://codeberg.org/mclemens/pyBMNotify) and modified.

This Python script will listen to the Brandmeister Last Heard API endpoint for any callsign or Talkgroup (or both) that you configure and it will send you a notification when there is activity for those callsigns and/or talkgroups.

This script is really just a refactoring using a newer socketIO python library from what the orginal pyBMNotify script was using. Brandmesiter updated the protocol that their API was using a few months ago and the old script did not support the newer protocol, so I just refactored the script for this newer protocol. The actual logic and guts of the script are still the same as the original pyBMNotify script that [Michael Clemens, DK1MI](https://qrz.is/) wrote and that is all HIS work. That is why this is a fork, not an original work. I wanted to make sure that was clear. I did not do the heay lifting for this project, I just refactored the connection. Everything else is his work.

This script is for use by Amateur Radio Operators Only.

---

## Supported Services

This script will push a notification to the following services:

- Discord
- Telegram
- Pushover
- DAPNET

---

## Installation/Setup Instructions

[Click here to see the installation and setup steps](https://github.com/n8acl/bm_monitor/blob/master/installation-setup.md). Then come back here. This is a bit of a long document, so read it all carefully.

---
## Contact
If you have questions, please feel free to reach out to me. You can reach me in one of the following ways:

- Twitter: @n8acl
- Discord: Ravendos#7364
- Mastodon: @n8acl@mastodon.radio
- E-mail: n8acl@qsl.net

Or open an issue on Github. I will respond to it, and of course you, when I can. 

If you reach out to me and have an error, please include what error you are getting and what you were doing. I may also ask you to send me certain files to look at. Otherwise just reach out to me :).

---

## Change Log

* 12/23/2022 - Minor Update Release 1.1 - Fixed logic for ignoring Noisy calls (Callsigns to ignore)

* 07/12/2022 - Inital Release