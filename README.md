# Nuno José Barata Alves

**IT Technician | Computer Engineering Student | Networking · Cybersecurity · Linux**

IT Technician at Fundação Salesianos, responsible for the IT infrastructure of a school environment — systems, networks, security and user support. Member of the Portuguese Order of Engineers (Ordem dos Engenheiros). Currently pursuing a BSc in Computer Engineering at Universidade Aberta, having completed Harvard's CS50.

### What I work on

- IT infrastructure: servers, networks, workstations and support for ~2,000 users
- Networking and security: firewalls, network segmentation, dual-WAN failover, SIEM, incident response
- Email authentication and deliverability: SPF, DKIM, DMARC, DNS on Cloudflare
- Virtualization: Proxmox VE, VMware, LXC containers
- Automation and scripting in Python

### Homelab — what is running right now

I keep a homelab to put theory into practice. It is not a lab that sits idle: the router below carries the household's live traffic.

| Project | Stack | Status |
|---|---|---|
| **Virtualized edge router** | pfSense 2.8.1 as a VM on Proxmox VE | **Production** — routes the entire home network |
| **Dual-WAN failover** | Gateway group, fibre as Tier 1, 5G as Tier 2 | Active, with automatic transition |
| **Local RAG assistant** | PrivateGPT + Ollama in an LXC container, Qdrant vector store, systemd service | **Production**, self-hosted, no data leaves the network |
| Previous edge appliance | Sophos XG 86 repurposed with OPNsense | Retired Aug 2026 — the basis of the guide below |

The migration from a bare-metal appliance to a virtualized router was done with a planned cutover: same LAN addressing, gateway group rebuilt, and the old appliance kept powered as rollback until the new one proved itself.

### Published work

- **Dual-WAN Failover on OPNsense** — step-by-step guide, EN and PT → [njba.gumroad.com](https://njba.gumroad.com/l/opnsense-dual-wan-failover)
- **Portfolio** → [vr5.net](https://vr5.net)

### Tech & tools

`Python` · `C` · `SQL` · `Linux (Ubuntu/Debian)` · `Windows Server` · `Proxmox VE` · `pfSense` · `OPNsense` · `LXC` · `Cloudflare DNS` · `Networking` · `Virtualization (VMware/KVM)` · `SIEM` · `Incident Response`

### Currently

- Studying for my BSc in Computer Engineering at Universidade Aberta
- Building a FortiGate SD-WAN lab to compare vendor approaches to multi-WAN routing
- Deepening networking, cybersecurity and Python

### Connect

- LinkedIn: https://www.linkedin.com/in/nunobarataalves
- Email: nunobarataalves@gmail.com
