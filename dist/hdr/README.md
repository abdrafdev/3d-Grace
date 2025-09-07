# HDR Environment Maps

This folder should contain HDR environment maps for enhanced lighting and reflections.

## Recommended HDR Files

You can download free HDR environment maps from:
- [Poly Haven](https://polyhaven.com/hdris) (formerly HDRI Haven)
- [HDRIHaven](https://hdri-haven.com/)
- [sIBL Archive](http://www.hdrlabs.com/sibl/archive.html)

## Setup Instructions

1. Download an HDR file (preferably studio lighting or neutral environment)
2. Rename it to `studio.hdr`
3. Place it in this folder (`/static/hdr/`)

## Recommended HDRs for this project:
- Studio lighting setups for clean reflections
- Soft indoor lighting for subtle ambiance
- Gallery or museum environments

## File Format
- Preferred format: `.hdr` or `.exr`
- Resolution: 2K (2048x1024) is usually sufficient for web
- For better performance, you can use lower resolutions like 1K

## Alternative
If you don't have an HDR file, the project will still work but without environment reflections. The custom shader material will still provide a beautiful marble appearance.
