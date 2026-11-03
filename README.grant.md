# Nettacker — Forked for Grant's Toolkit

**Original:** OWASP Nettacker — https://github.com/OWASP/Nettacker
**Forked:** 2026-11-03
**Language:** Python
**Stars (upstream):** ~5,700

## What it is

OWASP's automated penetration testing framework. Module-based vuln scanning and management with database-backed result tracking.

## Why it's here

Structured, repeatable scanning for authorized engagements. Database output makes it easy to diff findings across retests and feed into reporting.

## Quick start

```bash
python3 nettacker.py -m ping_scan -i 192.168.1.0/24 -o results.html
```

## Related forks

- afrog — faster template-based alternative
- redforge — Grant's own security ops platform
- redbox — modular toolkit by the RedForge fleet

## Scope note

Authorized engagements and CTF labs only.
