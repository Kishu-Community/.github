# My Work

This file records public Kishu Community recovery, cleanup, archive, and maintenance work I have personally completed or coordinated.

It is not a roadmap, investment pitch, official token-control claim, or promise that past losses can be reversed.

## Standing Limits

- I do not control the original KISHU token contract.
- I do not control the legacy KISHU owner Safe.
- I do not control legacy team wallets.
- I cannot force migrations, move legacy staking contracts, or update old NFT contracts without the proper contract ownership.
- Any rebuild work here is opt-in, public, and limited to assets, domains, repos, documentation, and deployments I can actually access.

## 2026-05-13

### GitHub Organization

- Maintained the public Kishu Community GitHub profile as an independent rebuild and public record effort.
- Added this public work log so daily recovery and cleanup work can be tracked without relying on private claims.
- Kept the public safety language focused on seed phrase safety, official links, and the limits of current contract control.

### Website Frontend

- Added the current Telegram community link to the website Apps dropdown.
- Added the Kishu Community GitHub link to the website Apps dropdown.
- Updated the archive popup so "Open archive" points to the Kishu Community GitHub organization.
- Removed the TechRate audit link for now because the PDF still references an old `kishuinu.finance` URL.
- Updated mobile navigation so public links are available from the mobile menu.
- Removed third-party CDN JavaScript from the recovered frontend.
- Added local copies of required frontend assets, including jQuery and a Webflow background image.
- Added Cloudflare Worker security headers, including CSP, content type protection, referrer policy, and permissions policy.
- Updated the local verification script so remote script tags fail future checks.

Frontend security commit:

- [`76fc7b6` - Harden frontend script loading](https://github.com/Kishu-Community/kishu-inu-web-frontend/commit/76fc7b68c7ea210b27bf5d76a72d711a93df29aa)

### Verification

- Ran the local clean-site verifier.
- Ran the Cloudflare Worker dry-run check.
- Confirmed the Worker returns the new security headers on asset and redirect responses.

### Notes

- No token contract ownership changed.
- No legacy wallet access changed.
- No claim is being made that this organization controls abandoned legacy systems.
- The purpose of this work is to make public evidence, recovered code, current limits, and active cleanup visible.
