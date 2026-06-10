# SecureVault — Desktop Password Manager

A cross-platform desktop password manager. AES-256-GCM encryption,
master password protection, and fully offline — no internet required.
Sponsered by **ITC INDIA**

---

## Features
- AES-256-GCM encryption with integrity verification (HMAC-SHA256)
- Master password with PBKDF2 key derivation (200,000 iterations)
- Add, edit, delete password entries
- Support for Passwords, Credit Cards, Bank Accounts, Identities, Secure Notes
- Password generator (cryptographically random)
- Password strength indicator
- Categories: Work, Social, Finance, Other
- Favourites, Search, Filter, Sort
- Dashboard with stats and activity log
- Export/Import encrypted backup
- CSV import from Google Password Manager, Bitwarden, etc.
- Auto-lock vault after inactivity
- Dark mode
- Password reveal with shoulder-surfing warning
- Keyboard shortcuts: `Ctrl+N` (new), `Ctrl+L` (lock), `Esc` (close modal)


## Vault Storage

Your encrypted vault is stored at:
- **Linux:** `~/.config/securevault/vault.enc`
- **Windows:** `%APPDATA%/securevault/vault.enc`

**Important:** There is no password recovery. If you forget your master password,
the vault cannot be decrypted. Keep your master password safe.

---
## Installation Process

```bash
#Windows
visit release and download the .exe file and run it by double clicking it.
```
```
#Linux
sudo dpkg -i securevault_1.0.0_amd64.deb
```


