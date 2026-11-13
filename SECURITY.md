# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.0.x   | ✅        |

## Archive Integrity

| File | SHA‑256 |
|------|---------|
| `MW4-Optimizer-v1.0.zip` | `PASTE_SHA256_HASH_HERE` |

**Before running any build, always verify the SHA‑256 hash of the archive. If the hash does not match the value above, do not execute the file.**

## Safety Guarantees

- **No game file modification** — the game directory is never touched.
- **No anti‑cheat interaction** — no memory read/write access.
- **No telemetry** — no outbound calls except an optional update check.
- **All changes reversible** — every tweak is logged and can be restored with one click.

## Reporting a Vulnerability

If you discover a security issue, please **do not open a public issue**.  
Instead, contact the maintainer directly via GitHub: [@PartBusinessSignify](https://github.com/PartBusinessSignify).  
You will receive a response within 48 hours.

## Responsible Disclosure

We follow a coordinated disclosure model. Please allow up to 90 days for a fix before publicly disclosing any vulnerability.

## Code Signing

The executable is **not** code‑signed. You are encouraged to inspect the source or run the tool in a sandboxed environment if you have concerns.
