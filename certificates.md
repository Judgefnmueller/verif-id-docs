# Certificates and public verification

Every Verif-ID certificate includes:

- **SHA-256 anchoring** — the certificate is tied to a hash of the analyzed content, so the result can't be detached from what was analyzed.
- **QR-anchored lookup** — a QR code links to a public verification URL.
- **Public verification** — anyone can verify a certificate by URL or content hash at the [Public Verification page](https://myverif-id.base44.app/public-verification).
- **Liveness attestation** — where supported, a live human-presence check is recorded with the result.

Third parties never need a Verif-ID account to check a certificate — that independence is what turns analysis into evidence.
