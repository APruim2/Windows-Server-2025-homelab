# Troubleshooting Log

## Issue 1

### Problem

Windows Server installation stalled at 92%.

### Resolution

Allowed the Active Directory installation to complete and verified services after reboot.

---

## Issue 2

### Problem

DNS returned "Server Unknown."

### Resolution

Verified static IP configuration and rebuilt the Domain Controller using the correct network configuration before promoting it.

---

## Issue 3

### Problem

Windows 11 Home could not join the domain.

### Resolution

Reinstalled the client using Windows 11 Pro.

---

## Issue 4

### Problem

PC01 could not resolve homelab.local.

### Resolution

Verified DNS settings, confirmed the DNS service was running, and rebuilt the Domain Controller after identifying an IP configuration issue during Active Directory installation.
