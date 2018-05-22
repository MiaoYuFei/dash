# dash

dash is a tiny shell that is intended for small media like floppy disks.

"dash" is a POSIX compliant shell that is much smaller than "bash". We take advantage of that by making it the shell on the installation root floppy, where space is at a premium.

It can be usefully installed as /bin/sh (because it executes scripts somewhat faster than "bash"), or as the default shell either of root or ofa second user with a userid of 0 (because it depends on fewer libraries, and is therefore less likely to be affected by an upgrade problem or a disk failure). It is also useful for checking that a script uses only POSIX syntax.
