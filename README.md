# FileFlow releases

Installers and updates for **FileFlow**, a native macOS file-transfer client (SFTP, SCP,
FTP/FTPS, WebDAV, S3).

- **Download:** the newest disk image is under [Releases](../../releases/latest). Open it and
  drag FileFlow onto Applications.
- **Updates:** FileFlow 1.0.1 and later check this repository's `appcast.xml` (if you allow
  it) and install new versions themselves. Every update is signed; FileFlow refuses one whose
  EdDSA signature does not match the key built into the app.

FileFlow is not notarised by Apple: the first time you open it, allow it once in
System Settings › Privacy & Security. The disk image's "Read Me First" explains how.

This repository holds releases only. Nothing about your Mac is sent when FileFlow checks it.
