# node-red-flow-hackertracker
A fun little SSH honey pot for node-red, with data graphs of IP, Geo Location, common username attempt info and option to setup a tweet out of the activity.

Option to block after certain amount of attemps.

Uses Dashboard http://localhost/ui

Linux based only as listens to tail of /var/log/auth.log file for failed SSH activity.
