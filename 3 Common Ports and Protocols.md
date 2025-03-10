# Common Ports and Protocols

## What is a Port?
A **port** is like a doorway for data. Some doors are open for specific things, while others stay closed.

## What is a Protocol?
A **protocol** is a set of rules that devices follow to talk to each other over a network.

## Secure vs Insecure Ports and Protocols
- **Ports:** Some doors have locks (secure), others don’t (insecure).
- **Protocols:** Some messages are easy to read, while others are encrypted for security.

## Common Protocols
- **IP (Internet Protocol):** Finds where to send data.
- **TCP (Transmission Control Protocol):** Makes sure data is sent and received correctly.
- **UDP (User Datagram Protocol):** Sends data quickly but doesn’t check if it arrived. Used for streaming.

## Secure vs Non-Secure Ports & Protocols
Some can be secure or non-secure, depending on encryption.

| Non-Secure Ports/Protocols    | Secure Ports/Protocols         |
|------------------------------|--------------------------------|
| 21 - FTP (File Transfer)      | 22* - SFTP (Secure File Transfer) |
| 23 - Telnet (Remote Login)    | 22* - SSH (Secure Remote Login) |
| 25 - SMTP (Send Email)        | 587 - SMTP (Encrypted Email) |
| 143 - IMAP (Access Email)     | 993 - IMAP (Encrypted Email) |
| 37 - Time Protocol            | 123 - NTP (Network Time Protocol) |
| 53 - DNS (Website Lookup)     | 853 - DoT (DNS over TLS) |
| 80 - HTTP (Web Browsing)      | 443 - HTTPS (Secure Web Browsing) |
| 161/162 - SNMP (Network Management) | 161/162 - SNMP v3 (Secure) |
| 389 - LDAP (Directory Services) | 636 - LDAPS (Secure Directory Services) |

## FTPS and SFTP
- **FTPS:** FTP with SSL encryption for security.
- **SFTP:** FTP with SSH encryption, making it more secure.

## What is a Shell?
A **shell** lets you control a computer using text commands instead of a graphical interface.

### SSH (Secure Shell)
SSH is a secure way to remotely control a computer or server. Hackers try to steal SSH credentials, so they must be well protected.

### Web Shell
A **Web Shell** is a script hackers use to control a web server remotely.
