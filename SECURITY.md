# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in Remio, please report it responsibly:

📧 **Email**: [security@remio.net](mailto:security@remio.net)

Please include:
- Description of the vulnerability
- Steps to reproduce (if applicable)
- Impact assessment

We take all security reports seriously and will respond within **48 hours**.

## Security Architecture

Remio uses industry-standard security practices:

- **End-to-End Encryption** — All streams are encrypted using DTLS-SRTP via WebRTC
- **Peer-to-Peer** — Video data goes directly between your devices when possible
- **No Data Storage** — We never see, store, or have access to your screen content
- **Secure Pairing** — QR code-based device pairing with cryptographic verification

For more details, read our [Security Whitepaper](https://remio.net/security-whitepaper.html).
