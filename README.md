# incident-response-debian
# Incident Response – Debian Linux Server

This project documents the analysis, containment, remediation and validation of a compromised Debian GNU/Linux server.

## Contents
- **informe/** – Final incident response report in PDF
- **evidencias/** – Screenshots proving the applied security controls
- **comandos/** – Commands used to harden the system

## Incident Summary
The server was compromised via SSH root access using password authentication.  
Multiple additional vulnerabilities were discovered, including FTP anonymous access, exposed WordPress directories and insecure file permissions.

All issues were remediated and validated using real technical controls and external scans.

## Key Security Actions
- Disabled SSH root login and password authentication
- Removed FTP service
- Hardened Apache directory access
- Secured WordPress configuration files
- Implemented firewall (UFW)
- Verified exposure with Nmap

This repository provides full transparency and technical evidence of the remediation process.
