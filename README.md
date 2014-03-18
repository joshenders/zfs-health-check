## About
Variation on [Sfynx's script](https://forums.freebsd.org/viewtopic.php?p=197113#p197113) on the FreeBSD forums

## Setup
Run this script via cron at an acceptable interval.

Here's a suggestion:

    0,15,30,45 * * * * /path/to/zfs-health-check
