# Hi, I'm Italo

Software engineer in Finland.

## Security fixes I've contributed

Fixes for publicly reported issues in open-source projects:

- [Majorfi/immich-places#70](https://github.com/Majorfi/immich-places/pull/70) (merged): bump Next.js to 16.4.1 and pin the Docker images to Node.js 22.23.4 to pick up fixes for known CVEs in Next.js, Node.js and its bundled tar.
- [depado/goploader#509](https://github.com/depado/goploader/pull/509) (open): serve uploaded files with a safe Content-Type and `nosniff`, so an uploaded HTML file can't run on the site's origin.
- [cupcakearmy/cryptgeon#226](https://github.com/cupcakearmy/cryptgeon/pull/226) (open): stop CLI downloads from writing outside the working directory through names like `../x`.
- [adam-rms/adam-rms#1055](https://github.com/adam-rms/adam-rms/pull/1055) (open): escape audit log action data to prevent stored XSS in the server audit log.
- [UpCloudLtd/upcloud-csi#137](https://github.com/UpCloudLtd/upcloud-csi/pull/137) (open): build with Go 1.26.10 to pick up the crypto/x509 fix for CVE-2026-111943.
- [Koenkk/zigbee2mqtt#33545](https://github.com/Koenkk/zigbee2mqtt/pull/33545) (open): restrict device icon uploads to image extensions so the file can't be written outside `device_icons`.

## Projects

- [fixdossier](https://github.com/itulo/fixdossier): a free, MIT-licensed GitHub Action that turns a repo's published security advisories and fix history into a dated record of which release shipped each security fix. [Docs](https://fixdossier.dev/docs/) · [Sample records](https://fixdossier.dev/docs/samples/)
