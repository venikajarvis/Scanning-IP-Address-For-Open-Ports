<h1>Scanning-IP-Address-For-Open-Ports</h1>

<h2>Description</h2>

- Simple CLI port scanner (Python) — imports: sys, socket, datetime, threading.

- Reusable scan_port(target, port) function with exception handling, socket timeouts, and banner parsing.

- Hostname → IPv4 resolution, argument validation, and clear usage/error messages.

- Concurrent port scanning using threading with proper thread lifecycle management (start + join) and graceful interrupt handling.


<h2>Language Used</h2>

- Python

<h2>Environment Used </h2>

- Local machine (macOS)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
