# backloop.dev certificates

This repository contains multiple SSL/TLS certificate and key files produced from [perki/backloop.dev](https://github.com/perki/backloop.dev).
All files are automatically generated weekly by a GitHub Actions workflow.

---

## 🔑 Passwords
- PKCS#12 (`.p12`), PFX (`.pfx`), and Java Keystore (`.jks`) password: `backloop.dev`

---

## 📁 Files Included

### Private Key
- `backloop.dev-key.pem` — Combined private key from `backloop.dev-key.part1.pem` + `backloop.dev-key.part2.pem`.

### Certificates
- `backloop.dev-cert.crt` — Server certificate (PEM).  
- `backloop.dev-ca.crt` — CA / intermediate certificate (PEM).  
- `backloop.dev-fullchain.pem` — Server certificate + CA (PEM). Use for nginx, Apache, Caddy, etc.  
- `backloop.dev-bundle.crt` — Bundle copied from the `gh-pages` branch.  
- `backloop.dev-all.pem` — Private key + server certificate + CA (PEM). Useful for quick imports.

### PKCS#12 / PFX
- `backloop.dev.p12` — Private key + certificate + CA in PKCS#12 format.  
- `backloop.dev.pfx` — Same as `.p12` (some Windows apps expect `.pfx`).

### Binary / DER
- `backloop.dev-cert.der` — DER-encoded certificate (binary). Useful for Java, embedded devices, and Windows.  
- `backloop.dev.cer` — Copy of DER certificate (commonly used by Windows trust stores).

### Java Keystore
- `backloop.dev.jks` — Java Keystore created from `.p12`. Use for Java servers (Tomcat, Jetty, etc.).

---

## 📦 List of All Files

- `backloop.dev-key.pem` — Private key (PEM).  
- `backloop.dev-cert.crt` — Server cert (PEM).  
- `backloop.dev-ca.crt` — CA / intermediate (PEM).  
- `backloop.dev-fullchain.pem` — Chain for servers (cert + CA).  
- `backloop.dev-bundle.crt` — Bundle (from gh-pages).  
- `backloop.dev-all.pem` — Everything in one PEM (key + cert + CA).  
- `backloop.dev.p12` / `backloop.dev.pfx` — PKCS#12 container (key + cert + CA), password: `backloop.dev`.  
- `backloop.dev-cert.der` / `backloop.dev.cer` — DER-encoded certs (binary).  
- `backloop.dev.jks` — Java keystore (JKS), password: `backloop.dev`.

---

## 🔗 Links
- Original Source: https://github.com/perki/backloop.dev/tree/gh-pages

---
