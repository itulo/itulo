# Hi, I'm Italo

Software engineer in Finland.

## Security fixes I've contributed

Fixes for publicly reported issues in open-source projects:

- [Majorfi/immich-places#70](https://github.com/Majorfi/immich-places/pull/70) (merged): bump Next.js to 16.4.1 and pin the Docker images to Node.js 22.23.4 to pick up fixes for known CVEs in Next.js, Node.js and its bundled tar.
- [Canop/dysk#126](https://github.com/Canop/dysk/pull/126) (merged): show control characters as `\xNN` escapes in table and CSV output, so disk labels can't inject terminal escape sequences.
- [Koenkk/zigbee2mqtt#33545](https://github.com/Koenkk/zigbee2mqtt/pull/33545) (merged): restrict device icon uploads to image extensions so the file can't be written outside `device_icons`.
- [adam-rms/adam-rms#1055](https://github.com/adam-rms/adam-rms/pull/1055) (merged): escape audit log action data to prevent stored XSS in the server audit log.
- [e-m-b-a/emba#2202](https://github.com/e-m-b-a/emba/pull/2202) (merged): stop interpolating firmware file names into the S15 radare2 command.
- [depado/goploader#509](https://github.com/depado/goploader/pull/509) (open): serve uploaded files with a safe Content-Type and `nosniff`, so an uploaded HTML file can't run on the site's origin.
- [cupcakearmy/cryptgeon#226](https://github.com/cupcakearmy/cryptgeon/pull/226) (open): stop CLI downloads from writing outside the working directory through names like `../x`.
- [rx-angular/rx-angular#1963](https://github.com/rx-angular/rx-angular/pull/1963) (open): keep ISR filesystem cache files inside the cache folder.
- [assimp/assimp#7027](https://github.com/assimp/assimp/pull/7027) (open): reject glTF external buffer and image URIs that leave the asset directory.
- [thoas/picfit#240](https://github.com/thoas/picfit/pull/240) (open): block private addresses when fetching user-supplied URLs.
- [bdecentgmbh/moodle-format_designer#80](https://github.com/bdecentgmbh/moodle-format_designer/pull/80) (open): escape stored custom activity titles and profile fields.
- [open-gsd/gsd-core#6377](https://github.com/open-gsd/gsd-core/pull/6377) (open): confine MCP state read/write tools to the project's `.planning/` folder.
- [nopSolutions/nopCommerce#8478](https://github.com/nopSolutions/nopCommerce/pull/8478) (open): keep favicon and app-icon uploads inside the icons folder.
- [AtalayaLabs/OxiCloud#946](https://github.com/AtalayaLabs/OxiCloud/pull/946) (open): treat uploaded XML types as scriptable and apply the same XSS headers on WebDAV ranged downloads.
- [pollinations/pollinations#20348](https://github.com/pollinations/pollinations/pull/20348) (open): refuse trailing-dot localhost media URLs and follow redirects only when asked.
- [cot-rs/cot#751](https://github.com/cot-rs/cot/pull/751) (open): upgrade lettre to 0.11.24 to fix SMTP command injection (RUSTSEC-2026-0561).
- [exein-io/pulsar#467](https://github.com/exein-io/pulsar/pull/467) (open): upgrade lettre to 0.11.24 to fix SMTP command injection (RUSTSEC-2026-0561).

## Projects

- [fixdossier](https://github.com/itulo/fixdossier): a free, MIT-licensed GitHub Action that turns a repo's published security advisories and fix history into a dated record of which release shipped each security fix. [Docs](https://fixdossier.dev/docs/) · [Sample records](https://fixdossier.dev/docs/samples/)
