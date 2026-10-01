ClipLocal v0.1.0

# Download YouTube and Instagram videos directly in your browser. 
### No servers. No backends. Just yt-dlp compiled to WebAssembly.
---


**_Features_**

**Zero server downloads**
 Everything runs in your browser. Nothing leaves your device.
 
**YouTube support**
Videos, Shorts, and Live streams

**Instagram support**
Reels and posts

**Quality selection**
Up to 4K, with automatic video+audio muxing

**Advanced mode**
Pick separate video and audio streams

**How it works**
We compiled yt-dlp to WebAssembly. Your browser does all the extraction and downloading. No proxies, no middlemen.

### Install
---
Download the .zip from this release
Go to chrome://extensions
Enable "Developer mode"
Drag and Drop the zip

### Update metadata

Keep `latest.json` updated whenever a new release is published. The extension
checks this public file and shows an in-app update banner when its version is
newer than the installed version.

Example:

```json
{
  "version": "0.2.0",
  "notes": "Improved video extraction",
  "downloadUrl": "https://github.com/BapunHansdah/cliplocal-releases/releases/download/v0.2.0/cliplocal-0.2.0.zip"
}
```
