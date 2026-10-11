# PS5 Payloads Catalog

This repository is a small JSON catalog of upstream PS5 payload downloads. It does **not** mirror, store, or re-upload the ELF binaries; every download URL points directly to the original publisher's GitHub release asset.

- Reference catalog: [payloads.json](payloads.json)
- PS5 Payload Manager source: [pldmgr-repository.json](pldmgr-repository.json)
- GitHub Pages URL for PS5 Payload Manager: https://superlolx.github.io/ps5-payloads-mirror/pldmgr-repository.json

Release dates in the catalog are the upstream GitHub release publication dates.

## Pegasus DL requirements

Pegasus DL v1.11.0 requires a jailbroken, payload-capable PS5 and an ELF loader. Its README does not require a particular jailbreak payload or loader. A phone or computer on the same local network can open `http://<PS5-IP>:6970/`; choose a writable download folder in the app settings.

No separate FTP server, Pegasus Resolver, standalone nanoDNS payload, PS5 SDK, or APR Emu package is required to launch Pegasus DL. Catalog sources are only needed for Store browsing; Real-Debrid, TorBox, and APR Emu support are optional integrations. Browser-assisted capture may start the nanoDNS component embedded in Pegasus DL.

## Add the source in PS5 Payload Manager

In Payload Manager, open **Settings → Manage Sources → Add Source** and enter the GitHub Pages URL above. The custom repository JSON uses the required top-level `name` followed by a `payloads` array. Its ELF files remain hosted by their original publishers.
