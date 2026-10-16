# Aurelio Avila — Official Product Directory

Find the official websites, Windows downloads and public project documentation
for software by Aurelio Avila.

**[Open the official links directory](https://aurelioavila.github.io/links/)** ·
[GitHub profile and security projects](https://github.com/AurelioAvila)

## Products

| Product | Purpose | Official links |
| --- | --- | --- |
| PC Tweaker | Windows tuning, privacy controls, hardware monitoring and restore options. | [Website](https://pctweaker.app/) · [Releases](https://github.com/AurelioAvila/pc-tweaker-app/releases/latest) |
| PC Tweaker Uninstaller | Review removal risks, uninstall software and retain a local removal ledger. | [Website](https://pctweaker.app/uninstaller/) · [Releases](https://github.com/AurelioAvila/pc-tweaker-uninstaller/releases/latest) |
| Tweaky Driver | Review detected devices, driver offers and package sources before making changes. | [Website](https://pctweaker.app/tweaky-driver/) · [Releases](https://github.com/AurelioAvila/Tweaky-Driver-Releases/releases/latest) |
| Redaxa | Check sensitive data in prompts and possible exposed credentials in public repositories. Processing depends on the selected surface. | [Website and privacy details](https://redaxa.getcertsprint.com/) · [Releases](https://github.com/AurelioAvila/redaxa/releases/latest) |
| Redexa Social | Private YouTube analytics for Windows. Instagram and TikTok require your own developer apps. | [Website](https://redexa.getcertsprint.com/) · [Releases](https://github.com/AurelioAvila/redexa-social/releases/latest) |
| Frame Witness | Photo and video recovery with visual triage, source offsets, hashes and dated findings. | [Website](https://framewitness.pages.dev/) · [Releases](https://github.com/AurelioAvila/frame-witness/releases/latest) |
| Glarion | Website security monitoring and client reporting for digital agencies, with ownership checks for full scans. | [Website](https://glarion.app/) · [Source and security model](https://github.com/AurelioAvila/glarion) |
| CertSprint | Independent certification practice with original questions, explanations and readiness feedback. | [Website](https://getcertsprint.com/) · [Sample questions](https://getcertsprint.com/samples) |

Redaxa and Redexa Social are separate products: prompt and repository checks,
and creator analytics, respectively. Product websites and release notes state
current features, requirements, prices and limitations.

## Verify a Windows download

Use the product's official release page and check the exact file's **Aurelio
Avila** publisher signature, trusted timestamp and SHA-256 where provided.
The [version-specific signing inventory and verification guide](https://github.com/AurelioAvila/.github/blob/master/CODE_SIGNING.md)
explains what was checked. A recorded verification applies to that artifact;
it is not a guarantee about every historical or future download or the absence
of SmartScreen warnings.

## Authorization callback compatibility

Static authorization completion pages for existing Redexa Social installations.
These routes preserve the registered Instagram and TikTok callback URLs after
the application repository was renamed to `redexa-social`.

The callback pages do not redirect, run scripts, collect data or change the URL. The
desktop application reads the authorization response from its own login window.

The directory lives at `/links/`. Existing `/social-dashboard/` authorization
routes are retained for compatibility; this README update does not change them.
