## Secure Linux Server Infrastructure Implementation

This project demonstrates the deployment and configuration of core enterprise network services using a Rocky Linux server and Ubuntu client environment within VirtualBox.

The implementation includes Domain Name System (DNS), Email Server (Postfix & Dovecot), Apache Web Server with SSL/TLS encryption, VPN connectivity, Fail2ban intrusion prevention, and Lynis security auditing.

DNS services were configured using BIND for domain name resolution, while Postfix and Dovecot were deployed to provide secure SMTP and IMAP email communication with SSL encryption. Apache HTTP Server was implemented to host web services over HTTPS.

Additional security measures such as Fail2ban were applied to protect against brute-force SSH attacks, and WireGuard VPN was configured to enable secure remote connectivity. Lynis was used to perform system security auditing and vulnerability assessment.

This project simulates a production-like Linux server environment integrating essential enterprise services with security hardening techniques.
