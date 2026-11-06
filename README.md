# IPSC Overlay Studio — downloads

Burns shot count and split times into IPSC match videos. Website, instructions and the download buttons:
https://www.rc-technologies.be/ipsc-overlay/

This repository only holds the release files; the source code is not public.

- `IPSC-Overlay-Studio-<version>-setup.exe`: installer for Windows 10/11 (downloads FFmpeg during setup).
- `IPSC-Overlay-Studio-<version>-win-x64.zip`: portable, without FFmpeg.
- `ffmpeg-*` releases: unchanged copies of the FFmpeg builds by gyan.dev
  (https://github.com/GyanD/codexffmpeg) that the installer downloads. FFmpeg is licensed under the GPL v3; its
  licence and a link to the source are in each archive.

Check a download: compare its SHA-256 with the `.sha256` file next to it (or the website), or with the
GitHub CLI: `gh release verify-asset v<version> <file> -R RC-Technologies/ipsc-overlay-studio`.

Questions and bug reports: tom.wuyts@rc-technologies.be
