# Verso Video Editor — Windows downloads

Binary distribution channel for **Verso Video Editor**, a local multitrack editor for video and rendered image sequences. The development repository is not published here.

## Install

Download the Windows x64 **Setup.exe** from [Latest release](https://github.com/pollo-xyz/Verso-Video-Editor-Releases/releases/latest), run it once, then launch **Verso Video Editor** from Start.

The installed app checks this channel automatically, downloads updates in the background and offers **Restart to update**. Save the project before updating. No GitHub account, Node, Python or VSequencer installation is needed. FFmpeg and the native OpenImageIO/OCIO worker are bundled.

## Windows pins

Pin **the installed Verso Video Editor app**, not a development Electron window or the downloaded installer. Updates retain its executable path and AppUserModelID (`com.versostudio.videoeditor`). Existing development shortcuts are not automatically migrated.

## Current scope

Local alpha: multitrack editing, numbered EXR/SDR sequences, missing-frame warnings with black placeholders, source versions/custom metadata, resizable panels and H.264/Rec.709 export. Default ACES view is **ACES 1.0 - SDR Video**.

## Security and third-party software

The installer is currently **unsigned**; Windows may show a SmartScreen warning. Update downloads use GitHub HTTPS and SHA-512 integrity metadata, not Authenticode publisher verification. Third-party licenses/notices are included with the installed application. The public installer necessarily contains the application runtime; this repository does not publish the development history, tests or production media.
