# CCMS monitoring

Password-protected page comparing patient arrival (prequeue) with registration in CCMS, per klinik kesihatan, per half-hour.

- `index.html` is encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt) (AES-256, PBKDF2). Nothing in it is readable without the passphrase.
- The page holds aggregated counts only. Raw CCMS exports and patient-level files are never committed to this repo.
