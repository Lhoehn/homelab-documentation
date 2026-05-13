# Pi-hole
Installed Pi-hole for network-wide ad blocking. It is limited to filtering only at the DNS level, but it is a useful alternative to installing browser extensions on every device on the network.

## Password Issue
The set WEBPASSWORD did not work when trying to sign in to the Pi-Hole admin dashboard.

*Fix:* Reset password with:  
**docker exec -it pihole pihole setpassword**
