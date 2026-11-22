# Paradox Relay

Kerberos relay toolkit focused on unconstrained delegation abuse and related attacks.

**Upstream:** [dirkjanm/krbrelayx](https://github.com/dirkjanm/krbrelayx)

---

## What it does

- Kerberos relay attacks
- Unconstrained delegation abuse
- Tools for printing, DNS, and other relay scenarios
- Pairs extremely well with Impacket and Responder

---

## Install

```bash
git clone https://github.com/dirkjanm/krbrelayx.git
cd krbrelayx
pip install -r requirements.txt
```

Works on Linux and Termux (Python).

---

## Common Flow

Often used with:
- Responder / ntlmrelayx for initial access
- Then krbrelayx for Kerberos-specific escalation paths

---

## Notes

Advanced AD attack tooling. Requires solid understanding of Kerberos and delegation.

Use responsibly and only with authorization.
