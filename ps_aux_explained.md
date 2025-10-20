# ps aux | grep vnc

### Description
`ps aux` lists all running processes, and `grep vnc` filters for any process containing "vnc".

### Breakdown
- **ps**: process status command.
- **a**: show processes for all users.
- **u**: show the user running each process.
- **x**: include processes without a terminal.

### Example Output
user 1214 0.0 0.3 49512 12456 ? Ssl 10:23 0:00 /usr/bin/x11vnc -rfbport 5901

### Why It’s Useful
Helps identify which VNC service is running, its port, and process ID.
