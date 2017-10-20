# node-red-ssh-hackertracker
A fun little SSH honey pot for node-red, with data graphs of IP, Geo Location, common username attempt info and option to setup a tweet out of the activity.

Option to block after certain amount of attemps.

Uses Dashboard http://localhost/ui

Linux based only as listens to tail of /var/log/auth.log file for failed SSH activity.

Originally built and ran on a Raspberry Pi 3 machine.

This 'tail' reads the auth.log for any failed attempts and parses and processes the info. 
