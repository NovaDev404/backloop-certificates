# backloop.dev certificates

This repository contains multiple SSL/TLS certificate and key files produced from [perki/backloop.dev](https://github.com/perki/backloop.dev).
All files are automatically generated every two days by a GitHub Actions workflow.

---

## 🔑 Passwords
- PKCS#12 (`.p12`), PFX (`.pfx`), and Java Keystore (`.jks`) password: `backloop.dev`

---

## 📁 Files Included

### Private Key
- `backloop.dev-key.pem` — Combined private key split into two parts:  
  - `backloop.dev-key.pem/backloop.dev-key.pem.part1`  
  - `backloop.dev-key.pem/backloop.dev-key.pem.part2`  

### Certificates
- `backloop.dev-cert.crt` — Server certificate split into:  
  - `backloop.dev-cert.crt/backloop.dev-cert.crt.part1`  
  - `backloop.dev-cert.crt/backloop.dev-cert.crt.part2`  
- `backloop.dev-ca.crt` — CA / intermediate certificate split into:  
  - `backloop.dev-ca.crt/backloop.dev-ca.crt.part1`  
  - `backloop.dev-ca.crt/backloop.dev-ca.crt.part2`  
- `backloop.dev-fullchain.pem` — Server certificate + CA split into:  
  - `backloop.dev-fullchain.pem/backloop.dev-fullchain.pem.part1`  
  - `backloop.dev-fullchain.pem/backloop.dev-fullchain.pem.part2`  
- `backloop.dev-bundle.crt` — Bundle copied from the `gh-pages` branch split into:  
  - `backloop.dev-bundle.crt/backloop.dev-bundle.crt.part1`  
  - `backloop.dev-bundle.crt/backloop.dev-bundle.crt.part2`  
- `backloop.dev-all.pem` — Private key + server certificate + CA split into:  
  - `backloop.dev-all.pem/backloop.dev-all.pem.part1`  
  - `backloop.dev-all.pem/backloop.dev-all.pem.part2`  

### PKCS#12 / PFX
- `backloop.dev.p12` — Private key + certificate + CA split into:  
  - `backloop.dev.p12/backloop.dev.p12.part1`  
  - `backloop.dev.p12/backloop.dev.p12.part2`  
- `backloop.dev.pfx` — Same as `.p12` split into:  
  - `backloop.dev.pfx/backloop.dev.pfx.part1`  
  - `backloop.dev.pfx/backloop.dev.pfx.part2`  

### Binary / DER
- `backloop.dev-cert.der` — DER-encoded certificate (binary) split into:  
  - `backloop.dev-cert.der/backloop.dev-cert.der.part1`  
  - `backloop.dev-cert.der/backloop.dev-cert.der.part2`  
- `backloop.dev.cer` — Copy of DER certificate split into:  
  - `backloop.dev.cer/backloop.dev.cer.part1`  
  - `backloop.dev.cer/backloop.dev.cer.part2`  

### Java Keystore
- `backloop.dev.jks` — Java Keystore split into:  
  - `backloop.dev.jks/backloop.dev.jks.part1`  
  - `backloop.dev.jks/backloop.dev.jks.part2`  

---

## 📦 List of All Files

- `backloop.dev-key.pem` — Private key (PEM, split `.part1` / `.part2`).  
- `backloop.dev-cert.crt` — Server cert (PEM, split).  
- `backloop.dev-ca.crt` — CA / intermediate (PEM, split).  
- `backloop.dev-fullchain.pem` — Chain for servers (cert + CA, split).  
- `backloop.dev-bundle.crt` — Bundle (from gh-pages, split).  
- `backloop.dev-all.pem` — Everything in one PEM (key + cert + CA, split).  
- `backloop.dev.p12` / `backloop.dev.pfx` — PKCS#12 container (key + cert + CA, split), password: `backloop.dev`.  
- `backloop.dev-cert.der` / `backloop.dev.cer` — DER-encoded certs (binary, split).  
- `backloop.dev.jks` — Java keystore (JKS, split), password: `backloop.dev`.

---

## 🔗 Links
- Original Source: https://github.com/perki/backloop.dev/tree/gh-pages

---
