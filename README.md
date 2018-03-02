# Invoke-Pbind
Powershell SMB Named Pipe Bind Shell

<div style="text-align:center"><img src ="https://github.com/b4ggio-su/Invoke-Pbind/blob/master/pbind-help.png" /></div>

The implant starts a named pipe on the target machine, allowing the client to pass commands over the named pipe and have them executed. Comms are carried out all within one SMB connection, therefore there is no beaconing. The pipe remains a very stable method of comms and has been tested beyond 24 hours. All comms are encypted with a randomly generated key, using AES 256 encryptions. A pipe name can be hardcoded on the command line, if this is not done the implant will start on a randomly generated named pipe.

Examles:
<div style="text-align:center"><img src ="https://github.com/b4ggio-su/Invoke-Pbind/blob/master/examples.png" /></div>



