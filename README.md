# Log4J Vulnerability Notes and Scripts

### Articles
[Bleeping Computer Blog Post](https://www.bleepingcomputer.com/news/security/new-zero-day-exploit-for-log4j-java-library-is-an-enterprise-nightmare/) \
[Affected Products list](https://gist.github.com/SwitHak/b66db3a06c2955a9cb71a8718970c592) \
[Java Security Post](https://logging.apache.org/log4j/2.x/security.html)

### Mitigations
[Log4j Be Gone](https://github.com/nccgroup/log4j-jndi-be-gone)

### Scan For Log4j Files
[Qualys Scan](https://github.com/Qualys/log4jscanwin) \
[Invoke-Log4ShellScan](https://github.com/TheTaylorLee/Log4J/blob/main/Invoke-Log4ShellScan.ps1) - [Credit goes to omrsafetyyo](https://github.com/omrsafetyo) \
[Cyberdrain Script](https://www.cyberdrain.com/monitoring-with-powershell-detecting-log4j-files)

### [POC] Proof Of Concept
https://github.com/aalex954/Log4PowerShell

### Find Indicators of Compromise
- Download the portable version of [Everything](https://www.voidtools.com/downloads/)
- Run everything as an administror
- Generate a search string such as `.log C:\ content:"jndi:ldap"` and run a scan. Modify the path as needed.
