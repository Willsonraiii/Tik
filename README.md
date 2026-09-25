# TikTok Quality — iPhone MVP 0.1

This is a static, mobile-first PWA prototype.

## What it does
- Selects a video from iPhone Photos/Files.
- Reads resolution, duration, size and type locally.
- Does not upload the file to our server.
- Does not resize, compress or re-encode it.
- Uses the iOS Web Share API to share the original File object.

## Run it
A PWA needs HTTPS (or localhost) for normal installation/use. Upload these static files to any HTTPS static host, then open the URL in Safari on iPhone.

On iPhone:
Safari → Share → Add to Home Screen.

## Important
The MVP cannot control TikTok's server-side transcoding. It preserves the original file up to the point where it is handed to the iOS share/upload flow.
