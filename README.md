#### Game Plan
1. Identify Services - Application & Version & Operating System
2. Basic Configuration of Services - areas of concern
   * Anonmous Auth
   * Allows access to too many directories
   * Allows file uploads
   * Excessive user privileges
3. Google all apps & versions with remote access for public exploits & vulns.
4. Patches to culn services
5. If a service is active but not scored
   * Stop it
   * Block it
6. Bakcup copies of email, dbmx, web applications, Domain Controlls, IPAM

#### Useful Commands
* Monitoring Users
  * Windows - net users
  * Windows - net localgroup administrators
  * Linux - journalctl -f
* Monitoring Network Connections
  * Windows - 
  * Linux - 
  
  
#### Windows Hardening
* Local Computer Policy
  * Windows Settings
    * Security Settings
      * Local Policies
        * LDAP requries

#### Antivirus
* Windows
  * Windows Defender
* Linux
  * sshguard

#### High Risk Ports
#### Windows
* TCP
  * 135
  * 137 - 139
  * 445
  * 2319

* UDP
  * 161 - snmp

#### Linux
* TCP
  * 23
  * 514 - rsh
  * 2049 - nfs
  * 3632 - DISTCC
  
* UDP
  * 161 - snmp
  
<img src="CCDChint.jpg">
