# chirp-next-mirror

Partial mirror of unmodified [upstream CHIRP releases](https://archive.chirpmyradio.com/chirp_next/). Each release here is composed of a source archive (`chirp-${pkgver}.tar.gz`), an AppImage (`Chirp-next-${pkgver}.AppImage`), and checksums (`SHA1SUM` & `checksums.txt`). This mirror is provided for use by the ArchLinux User Repository (AUR) `chirp-next` and `chirp-next-bin` packages. `${pkgver}` is of the form `20260814`, as used in the upstream CHIRP releases.

This repository exists because the host of the [upstream CHIRP archive](https://archive.chirpmyradio.com/chirp_next/) currently prevents reliable automated retrieval of released files by command-line package-building tools.

CHIRP release files provided here are copied without modification from the [upstream CHIRP archive](https://archive.chirpmyradio.com/chirp_next/). Before publication, both the source archive and the AppImage of each release are verified against the checksum published by CHIRP. Since SHA1 checksums are no longer considered reliable cryptography, SHA256 checksums computed locally are also provided to support proper verification of the files provided here.

Upstream project:  
https://chirpmyradio.com/

Upstream release archive:  
https://archive.chirpmyradio.com/chirp_next/

Arch Linux AUR packages:  
https://aur.archlinux.org/packages/chirp-next  
https://aur.archlinux.org/packages/chirp-next-bin

Checksums:  
**SHA1SUM** &mdash; copy of the file published for each release by https://chirpmyradio.com/  
**checksums.txt** &mdash; locally published file containing both upstream SHA1 checksums and locally computed SHA256 checksums of the mirrored files.

This repository is not a fork of CHIRP and contains no modified CHIRP source code. CHIRP licensing information is contained in each upstream source archive.
