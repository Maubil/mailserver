## hardware/debian-mail-overlay

This overlay base image contains Debian 10 "Buster" slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.9.1.0 : https://skarnet.org/software/skalibs/
* Execline 2.5.3.0 : https://skarnet.org/software/execline/
* s6 2.8.0.1 : https://skarnet.org/software/s6/
* Rspamd 2.4 : https://rspamd.com/
* Gucci 1.2.2 : https://github.com/noqcks/gucci/

This image comes oringially from [https://github.com/hardware/debian-mail-overlay] with the latest updates from [https://github.com/mailserver2/debian-mail-overlay]
Not trying to reinvent the wheel, just integrate the overlay image into the mailserver project