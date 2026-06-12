# Network Security Labs

Hands-on labs across enterprise network security operations — firewall policy management, VPN setup and troubleshooting, proxy/web filtering, Zero Trust access, SSL inspection, firewall migration, cloud integration, packet capture, and incident response.

This repo documents practical security work I've done as a Network Security Engineer across multi-vendor firewall, proxy, and Zero Trust environments.

---

## What's covered

### Firewall Management
- **Policy & rule management** — created, modified, and reviewed firewall rules across multi-vendor platforms (Palo Alto, Fortinet, Cisco ASA).
- **Migration & policy optimization** — reviewed existing rule bases, removed redundant/overly permissive rules, and tightened access control during cleanups and migrations.

### VPN
- **Setup & troubleshooting** — configured and troubleshot IPSec and SSL VPNs, including site-to-site tunnels and remote-access connectivity issues.

### Proxy & Web Security
- **Proxy / web filtering** — configured URL filtering and acceptable-use policies on proxy platforms (Blue Coat ProxySG, Zscaler).
- **SSL inspection & certificate troubleshooting** — set up SSL/TLS inspection and resolved certificate trust and handshake issues on endpoints.

### Zero Trust
- **Zscaler ZIA/ZPA access** — configured Zero Trust application access and secure web gateway policies (see also the dedicated Zscaler Labs repo).

### Cloud Security
- **AWS integration** — extended network security controls into AWS (security groups, VPC, secure connectivity).

### Operations & Analysis
- **Packet capture** — used **Wireshark** to capture and analyze traffic, diagnose connectivity problems, and confirm policy behavior.
- **Incident response practice** — triaged simulated security incidents, performed root cause analysis, and applied corrective actions.

---

## Topics / Keywords
`Network Security` · `Firewall` · `Palo Alto` · `Fortinet` · `Cisco ASA` · `VPN` · `IPSec` · `SSL VPN` · `Proxy` · `URL Filtering` · `SSL Inspection` · `Zero Trust` · `Zscaler` · `AWS` · `Wireshark` · `Packet Capture` · `Incident Response` · `Root Cause Analysis`

---

## Repository structure
```
network-security-labs/
├── README.md
├── firewall/
│   ├── policy-management-notes.md
│   └── migration-optimization-notes.md
├── vpn/
│   └── ipsec-ssl-vpn-notes.md
├── proxy-web/
│   ├── url-filtering-notes.md
│   └── ssl-inspection-troubleshooting.md
├── cloud/
│   └── aws-integration-notes.md
├── packet-capture/
│   └── wireshark-analysis-notes.md
└── incident-response/
    └── ir-playbook-notes.md
```

---

## Notes
- Labs and notes are sanitized — no real device names, IPs, policy names, or organization data.
- Descriptions of production work are conceptual and do not expose any confidential configuration.

---

**Author:** Miriyala Durga Rao — Network Security Engineer
[Portfolio](https://mdurgarao-tech.github.io) · [LinkedIn](https://www.linkedin.com/in/miriyala-durgarao)
