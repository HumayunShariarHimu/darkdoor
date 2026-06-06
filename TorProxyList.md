# Tor2Web & Tor Proxies Public List

A comprehensive, community‑maintained list of services that provide access to the Tor network — especially `.onion` hidden services — through a standard web interface (clearnet).  
We track the availability, logging policy, technology used, and potential malicious behaviour (injection, phishing, or content modification) of each service.

> **Warning**  
> Tor2Web gateways break the end‑to‑end encryption model of Tor. The gateway operator can see your traffic and modify the content.  
> **Never use Tor2Web for sensitive or personal activities.**  
> For anonymous browsing always use the [Tor Browser](https://www.torproject.org/download/).

---

## Important Update (June 2026)

**Almost all known Tor2Web gateways are currently unreachable.**  
The ecosystem is extremely volatile — services appear and disappear within hours. The table below is **automatically updated every 24 hours** by a CI/CD script. The status column reflects the latest check.

**Do not rely on any gateway being permanently available.** Use the self‑check script (provided below) to test a gateway instantly, or run your own Tor instance for guaranteed access.

---

## Full Service Directory

<!-- STATUS_TABLE_START -->
| URL | Status | Domain | Log Policy | Technology | Scam / Inject |
|:----|:------:|:------|:-----------|:-----------|:-------------:|
| `https://www.4everproxy.com/tor-proxy` | UP | 4everProxy.com | full | custom | no |
| `https://www.browserling.com/tor-testing` | UP | browserling.com | full | custom | no |
| `https://onion.re/` | DOWN | onion.re | full | custom | no |
| `https://onion.foundation/` | DOWN | onion.foundation | full | custom | no |
| `https://onion.gg` | DOWN | onion.gg | full | custom | no |
| `https://onion.pet` | DOWN | onion.pet | unknown | unknown | no |
| `https://onion.ly/` | DOWN | onion.ly | unknown | unknown | no |
| `https://onion.rip` | DOWN | onion.rip | minimal | custom | no |
| `https://onion.nz/` | DOWN | onion.nz | — | — | — |
| `https://onion.to/` | DOWN | onion.to | — | — | — |
| `https://onion.city/` | DOWN | onion.city | — | — | — |
| `https://onion.cab/` | DOWN | onion.cab | — | — | — |
| `https://onion.direct/` | DOWN | onion.direct | — | — | — |
| `https://tor2web.io/` | DOWN | tor2web.io | — | — | — |
| `https://onion.link/` | DOWN | onion.link | — | — | — |
| `https://onion.nu` | DOWN | onion.nu | — | — | — |
| `https://onion.sh` | DOWN | onion.sh | — | — | — |
| `https://onion.moe` | DOWN | onion.moe | — | — | — |
| `https://onion.ws` | DOWN | onion.ws | — | — | SCAM |
| `https://onion.xyz` | DOWN | onion.xyz | — | — | SCAM |
| `https://cyber-hub.pw/tor2web.php` | DOWN | — | — | — | SCAM |
| `https://oniontube.com` | UNKNOWN | oniontube.com | unknown | unknown | no |
| `https://tor2web.su` | UNKNOWN | tor2web.su | unknown | unknown | no |
| `https://onion.glass` | UNKNOWN | onion.glass | unknown | unknown | no |
<!-- STATUS_TABLE_END -->

**Legend:**
- `UP` — Service reachable and responding correctly to `.onion` proxying.
- `DOWN` — Service unreachable (DNS failure, timeout, or permanent shutdown).  
- `UNKNOWN` — Yet to be checked (will be updated by next automated run).
- `SCAM` — The gateway was caught injecting ads, malware, or modifying page content.

If you discover a **working** gateway, please open an issue and the table will be updated immediately.

---

## How to Use a Tor2Web Gateway (When Available)

Replace `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx` with the real 56‑character v3 onion address and append one of the gateway domains.

```bash
# Original .onion URL:
http://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion/

# Access via gateway:
https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion.re/
https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion.foundation/
