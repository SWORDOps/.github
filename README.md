# 🛡️ SWORD Intelligence

**Independent private intelligence firm specializing in Web3 and cyber threats.**

> Adversaries don’t play fair. Neither do we — the law’s on our side.

---

## 🎯 Mission

SWORD Intelligence helps funds, founders, enterprises, and government clients prevent loss, hunt threat actors, and respond to high-stakes incidents across Web3 and traditional cyber infrastructure.

### Core Focus Areas
- **Cyber Threat Intelligence** — APT tracking, nation-state operations, infrastructure analysis (yes, APT41 gets attention).
- **Counter-Narcotics Intelligence** — Synthetic opioids and precursors mapped end-to-end.
- **Web3 & Crypto Crime** — Asset tracing, ransomware negotiation, sanctioned red-team ops.
- **Executive Protection** — OPSEC, identity fragmentation, and digital protection for UHNWI and C-suite.
- **Bespoke Services** — From laboratory design and logistics to private jet charter for rapid movement.

---

## 🧠 Technical Stack

**Frontend**
- Next.js 15 (App Router), React 18 + TypeScript
- Tailwind CSS with custom theme system
- shadcn/ui + custom components

**Backend & Infra**
- PostgreSQL with Prisma ORM
- WebSocket server with Redis pub/sub
- Redis caching for multi-instance coordination
- NextAuth with MFA

**Security**
- Post-Quantum: ML-KEM-1024 and ML-DSA-87 (NIST FIPS 203/204, Level 5)
- AES-256-GCM with forward secrecy (double ratchet)
- WebAuthn/FIDO2 (YubiKey, CAC, platform biometrics)
- Steganography (LSB), HMAC-based searchable encryption
- Strict CSP/HSTS/COOP/COEP and referrer controls

**Privacy & Compliance**
- U.S./Iowa baseline with regional switches
- Tamper-evident audit logging
- KYC/KYB and sanctions screening

---

## 🚀 Public Site Highlights

- **Dual Theme System** — Special-Ops (dark) and Advisory (light) with instant switching
- **Service Pages** — Intelligence, Response, Resilience with capability breakdowns
- **Live Threat Intel Feed** — Nation-state ops, critical infrastructure, Web3/DeFi exploits, narcotics logistics, supply chain weaknesses
- **Animated Stats** — Operational track record without oversharing
- **Methods & Compliance** — Lawful methodologies and client vetting
- **Secure Contact** — PGP-first intake with progressive profiling

**Strategic Capabilities (Public)**
- **Shenzhen Supply Chain Intelligence** — Electronics manufacturing ecosystem access (NATO-vetted routing)
- **Russian Technology Access** — Dual-use tech procurement and analysis (lawful, rigorously vetted)
- **Global Rapid Response** — UK-based; **wheels-up via private jet** when time is blood
- **IC Coordination** — Established relationships; specifics remain compartmented

---

## 🔐 Client Portal — Secure Operations Center

**Authentication & Access Control**
- ML-KEM-1024 key encapsulation + ML-DSA-87 signatures
- WebAuthn/FIDO2 with hardware keys and biometrics
- MFA options, token rotation, session hardening
- Full lifecycle for authenticators: register, list, revoke

**Encrypted Document Vault**
- Client-side AES-256-GCM + PQ hybrid encryption
- Tags, metadata, versioning, time-limited shares
- Canary tokens for breach detection

**Secure Messaging (APT-Level Tradecraft)**
- Real-time messaging with database persistence
- Double ratchet with forward secrecy
- Traffic obfuscation inspired by what the better APTs actually do:
  uniform message sizes, decoy traffic, timing jitter, constant-rate shaping
- Private rooms, ephemeral messages, obfuscated typing, presence privacy
- Client-side monitoring for screenshots/clipboards/recorders

**Dead Drop System**
- Time-based release, heartbeat triggers, geo triggers (Haversine)
- Composite AND/OR logic, self-destruct, optional acknowledgments
- Full audit trail of trigger evaluations

**Steganographic Attachments (LSB)**
- PNG carriers, encrypted payloads, capacity checks
- SHA-256 integrity, metadata preservation, clean extraction path

**Encrypted Search**
- HMAC-based SSE; server never sees plaintext terms
- Stemming, phonetic matching, Levenshtein fuzz, stop-words, Bloom filters

**Admin Panel**
- RBAC across user/analyst/admin/super_admin
- 25+ granular permissions, 40+ audited events
- Risk scoring, canary oversight, metadata analytics only
- Ops dashboards and alert console

**OSINT / DIRECTEYE**
- 18 integrated feeds across malware, phishing, infra, darknet, narcotics, crypto
- PostgreSQL-cached indicators, deduplication, feed health telemetry

**Intelligence Reporting**
- ICD-203 structure, ML-DSA-87 digital signatures
- Confidence levels, SIGINT/OSINT/HUMINT tagging, TLP markings

---

## 🏗️ Production Infrastructure

**Database Layer**
- PostgreSQL with Prisma ORM (22+ models)
- Users, authenticators, messages, search indexes, dead drops, locations, docs, canaries, audit logs, OSINT feeds and indicators
- Connection pooling, health checks, in-memory fallback for dev

**WebSocket Server**
- Standalone service (port 8080)
- JWT auth, Redis pub/sub scaling
- Rate-limits, heartbeats, persistence, graceful shutdown, backoff

**Scalability & Reliability**
- Horizontal scaling, sticky or Redis-routed
- Offline queuing, paginated history
- DB read replicas, Redis Sentinel

---

## 🔒 Security & Privacy

**Crypto Primitives**
- ML-KEM-1024, ML-DSA-87, AES-256-GCM, ChaCha20-Poly1305 (alt)
- SHA-256/SHA-512, HMAC-SHA256, PBKDF2

**Forward Secrecy**
- Double Ratchet, per-message keys, chain/root rotations

**Traffic Analysis Resistance**
- 1024-byte padding, decoys (~10%), 100–300 ms jitter,
  constant-rate shaping, antifingerprint headers

**Security Headers**
- Strict CSP (nonce), HSTS (preload), COOP/COEP,
  strict-origin-when-cross-origin referrers, locked-down permissions

**Privacy Compliance**
- Regional GDPR/CCPA switches, first-party analytics,
  DNT/GPC respect, tamper-evident consent logs

**Client Vetting**
- Identity and beneficial ownership checks
- Sanctions screening (OFAC, UK, EU, BIS)
- Business legitimacy and end-use assessment
- **Threat Actor Protocol**: hostile acquisition attempts are treated as hostile, full stop

**Client-Side Security Monitoring**
- Screenshot/clipboard/recording detection
- Real-time server alerts and logs

---

## 🌍 Operational Posture

- **Independent** — not under secrecy obligations; operate under confidentiality and applicable law
- **NATO-aligned** mindset and methods
- **Global** — engagements worldwide (including difficult regions) subject to compliance
- **UK-Based** — 24-hour deployment readiness
- **IC Coordination** — ongoing, lawful, and discreet

---

## 🛣️ Roadmap Snapshot

**Done**
- Public site, dual themes, privacy/compliance pages
- Live threat feed including narcotics tracks
- PQC uplift (ML-KEM-1024 + ML-DSA-87), MFA, WebAuthn, biometrics, CAC/PIV
- Encrypted vault, secure sharing, canaries
- Real-time messaging with APT-grade obfuscation
- Dead drops, LSB stego, SSE search, admin oversight
- DIRECTEYE OSINT with 18 feeds and DB caching

**In Progress**
- HSM integration for cryptographic operations

**Planned**
- More feeds, PRC cyber ops focus, fentanyl/nitazenes seizure telemetry
- Crypto tracing, blockchain analytics for ransomware
- ML-assisted threat correlation
- E2E voice/video (WebRTC + PQC), immutable audit trail
- Air-gapped key ceremonies, zero-knowledge auth
- SIEM integrations, mobile apps with PQC, API and webhooks
- SOC 2 and ISO 27001 tracks, automated reporting

---

## 🏆 Technical Achievements

- PQC (FIPS 203/204 Level 5) running in production
- WebAuthn/FIDO2 with hardware keys and biometrics
- Double ratchet forward secrecy and APT-style traffic camouflage
- SSE private search and LSB steganography with AEAD
- Production WebSocket cluster with Redis, offline support, comprehensive auditing
- DIRECTEYE: 18-feed OSINT, deduplicated and queryable at speed

---

## ⚖️ Legal

SWORD Intelligence operates as an independent private intelligence firm. Not affiliated with any government entity. All services comply with applicable UK and U.S. law. E
