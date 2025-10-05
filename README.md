# Color Fingerprint Generator

A random visual fingerprint generator (lines and colored circles) with a random name. Suitable for UI demos, placeholder avatars, or as a lightweight decorative/identifying layer for non-sensitive applications.

## What does this project do?
Generates an SVG/PNG image containing a random arrangement of lines and circles, and assigns it a **unique, human-readable random name** (e.g., `sunny-river-42`). Each run produces a new, unpredictable fingerprint.

## Features
- Generates random fingerprints (SVG/PNG) ready for web embedding.
- Human-readable random names as identifiers.
- Lightweight setup: run locally via CLI or as a simple API.
- Customizable: number of shapes, color palette, image size, and name style.

## Example usage (CLI)
```bash
# Generate a 512x512 PNG fingerprint
python generate.py --format png --width 512 --height 512 --output ./fingerprint.png
