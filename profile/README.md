End-to-end encrypted messaging and authentication, with no third-party cryptographic dependencies.

We're a UK cybersecurity company. These are our two open-source products – find out more about what we do at [attomus.com](https://attomus.com/).

## Signet – authenticator

TOTP and HOTP done correctly. `attomus-otp` is our open-source Swift library implementing RFC 6238 and RFC 4226 from the standards documents, validated against the RFC test vectors. It is the cryptographic core of Signet on iOS and Android.

The Signet mobile apps build on this library and add biometric-protected secret storage, encrypted backup, and zero-telemetry operation.

[att.ms/signet](https://att.ms/signet)

## SemaFore – end-to-end encrypted messaging

Operational messaging for organisations that need uncompromised privacy. SemaFore implements X3DH key agreement and Double Ratchet – protocols that provide forward secrecy and post-compromise security – built from scratch on infrastructure we control.

[semafore.io](https://semafore.io)

Public components:

- `semafore-crypto` – TypeScript implementation of SemaFore's cryptographic wire format. Wire-compatible with the iOS Swift and Android Kotlin clients.
- `semafore-github-action` – GitHub Action that sends end-to-end encrypted notifications from your workflows into your SemaFore organisation. Encryption happens in the GitHub Actions runner – message contents never leave your trust boundary.

---

- Website: [attomus.com](https://attomus.com/)
- X: [@AttomusHQ](https://x.com/AttomusHQ)
- GitHub Discussions are open – questions about the cryptography or the products welcome.
- Security disclosures: [Vulnerability Disclosure Policy](https://attomus.com/security/). Quick reference in [SECURITY.md](https://github.com/Attomus/.github/blob/main/SECURITY.md).
