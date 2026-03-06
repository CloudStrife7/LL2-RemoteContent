# LL2 Remote Content

Static assets for Lower Level 2.0 VRChat world.

## Purpose

This repo hosts content on `*.github.io` which is a **VRChat trusted domain**. This allows the world to load remote content without requiring users to enable "Allow Untrusted URLs".

## Structure

```
/images/world/   - Poster images for theater and decorations
/data/           - JSON and text data files (weather, changelog, etc.)
```

## URLs

Assets are served at:
- `https://cloudstrife7.github.io/LL2-RemoteContent/images/world/[filename]`
- `https://cloudstrife7.github.io/LL2-RemoteContent/data/[filename]`

## GitHub Pages

This repo uses GitHub Pages to serve static files. **Do NOT add a CNAME file** - the `*.github.io` domain must remain for VRChat trusted URL support.
