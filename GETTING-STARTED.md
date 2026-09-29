# Welcome to Verif-ID Docs

Thanks for stopping by. This is the public content hub for **Verif-ID**,
an identity assurance platform for the AI age. We turn fragmented
authenticity signals into an evidence-backed result that helps people and
organizations decide whether digital content, identities, and interactions
can be trusted.

## Start here

1. **Read [how content forensics works](./content-forensics.md)** — the
   submit → analyze → prove → verify pipeline, in plain language.
2. **Read [certificates and public verification](./certificates.md)** —
   SHA-256 anchoring, QR-anchored lookup, and why third parties never need
   an account to check a result.
3. **Try it yourself** — verify a certificate at the
   [Public Verification page](https://myverif-id.base44.app/public-verification),
   no signup required.
4. **Building an integration?** — code samples live in our sister repo,
   [verif-id-api-samples](https://github.com/Judgefnmueller/verif-id-api-samples).

## The Forensics API at a glance

- **Format:** JSON / REST
- **Base URL:** `https://api.verif-id.com/v1`
- **Auth:** API key (`Authorization: Bearer vfid_live_...`), available in
  your account dashboard
- **Endpoints:** `POST /v1/certificates/verify` (verify by SHA-256 content
  fingerprint), `GET /v1/certificates/:id` (certificate metadata),
  `POST /v1/analyze` (forensic analysis without a liveness check)

Full developer docs: https://myverif-id.base44.app/api-docs

## What you can do here

- **Ask questions or report doc inaccuracies** — open an issue on this repo.
  Docs claim only what the product does today, and we fix stale claims fast.
- **Suggest improvements** — PRs welcome for clarity, examples, and
  use-case writeups. Keep claims verifiable: if the product can't do it
  yet, we describe it as direction, not capability.
- **Share how you'd use it** — fraud prevention, onboarding, marketplace
  trust, journalism verification, remote interactions: open an issue
  titled "Use case: ..." and tell us your workflow.

## A note on claims

Forensic analysis is probabilistic. We report AI-probability scores and
confidence levels, and results are designed to inform trust decisions —
they don't replace human judgment in high-stakes cases. Anything you read
in this repo reflects the live product, nothing aspirational.

## Links

- Live product: https://myverif-id.base44.app
- API samples: https://github.com/Judgefnmueller/verif-id-api-samples
- Support: via the site's Support Center
