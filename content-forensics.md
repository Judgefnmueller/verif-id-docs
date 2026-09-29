# How content forensics works

Verif-ID's forensic pipeline turns submitted content into an evidence-backed result:

1. **Submit** — text, image, audio, or video is submitted for analysis.
2. **Analyze** — the content is assessed for AI-generation signals and manipulation markers. Each result includes an AI-probability score and a plain-language analysis summary.
3. **Prove** — the result is anchored to a SHA-256 hash of the analyzed content and issued as a certificate.
4. **Verify** — anyone can independently verify the certificate through its public verification URL, QR code, or content hash. No Verif-ID account is needed to check a certificate.

Liveness checks add a live human-presence signal where supported, binding the analysis to a real person at the moment of verification.

Use cases include fraud prevention, digital onboarding, remote interactions, high-value transactions, account security, and KYC re-verification.

> Accuracy note: forensic analysis is probabilistic. Verif-ID reports confidence levels rather than binary guarantees, and results are designed to inform trust decisions — not replace human judgment in high-stakes cases.
