## RCVD: Resilient Cryptographic DNS

One static binary. RFC-standardized DNS encryption only: DoQ, DoT, DoH2 / DoH3  
Zero cleartext DNS

### Highlights  

- Forwarding resolver and upstream service in one engine (dual-mode, shared cache)
- Automatic TLS certificates via ACME (certmagic), SPKI pinning
- DNSSEC chain-of-trust validation
- Blocklists (plain domain lists, hosts files, wildcards)
- Allowlists (optional default-deny for strict environments and sandboxing)
- DDR / SVCB discovery for iOS and Android clients

### Install  

- Alpine Linux: `apk add rcvd` (testing)
- Homebrew: `brew install rcvd-dns/rcvd/rcvd`
- NetBSD pkgsrc: `net/rcvd`
- Source: https://github.com/rcvd-dns/rcvd

### Learn more  

- Website: https://rcvd.net
- Whitepaper: https://rcvd.net/whitepaper/
