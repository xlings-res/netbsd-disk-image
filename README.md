# netbsd-disk-image

NetBSD 10.2 (amd64), the official live image with a serial console, as a qcow2 disk for emulator runners

From NetBSD-10.2-amd64-live.img.gz (cdn.netbsd.org), checked against the release's SHA512; /boot.cfg names the serial console.

Packaged for xlings by the recipe `pkgs/*/netbsd-disk-image.lua` of
[openxlings/xim-pkgindex](https://github.com/openxlings/xim-pkgindex), whose
`.agents/tools/` holds the script that assembled it. Each release's
`PROVENANCE.md` (inside the archive) states the upstream files, their digests and every change.
