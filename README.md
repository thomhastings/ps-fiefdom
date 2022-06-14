## PowerShell Fiefdom

I coded this for a pentest 4 years ago and finally decided to release it.  

It's a very hacky webshell that lets you download and run arbitrary .PS1 files.  

If the Powershell executable is not in the default location, it will search for it.  

It might not work against modern Windows defenses, the target was Windows Server 2012.  

The primary use case was to download and run `Invoke-Mimikatz -DumpCreds`, which it did.  

[![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)](http://www.wtfpl.net/)
