# NextUI Font Component Template

This repository contains a template for creating font components for NextUI devices.

## What are Font Components?

Font components replace the system fonts used throughout the NextUI interface. You can provide custom fonts for both the OG font (font2.ttf) and the Next font (font1.ttf).

## Directory Structure

- `manifest.json` - Component metadata and font path mappings
- `preview.png` - Component preview image (replace with your preview)
- `OG.ttf` - Replacement for font2.ttf (original system font)
- `Next.ttf` - Replacement for font1.ttf (alternative system font)
- `OG.backup.ttf` - Backup of the original font2.ttf
- `Next.backup.ttf` - Backup of the original font1.ttf

## Getting Started

1. Replace the placeholder `preview.png` with a preview that demonstrates your fonts
2. Update the `manifest.json` with your component information (name, author, etc.)
3. Replace `OG.ttf` and `Next.ttf` with your custom font files
4. If you have backups of the original system fonts, include them as:
   - `OG.backup.ttf` - Backup of the original font2.ttf
   - `Next.backup.ttf` - Backup of the original font1.ttf
5. When complete, commit your changes and update the `NextUI-Themes` catalog

## Important Notes

- Font files must be in TTF format
- Make sure your fonts are readable at small sizes
- Test your fonts with various UI elements to ensure they display correctly
- Always include backups of the original system fonts if possible
- Users can switch between OG and Next fonts in the system settings

## Font Settings in manifest.json

In the content section of manifest.json:
- `og_replaced`: Set to true if you've included a replacement for font2.ttf
- `next_replaced`: Set to true if you've included a replacement for font1.ttf

## For more information, see the full component documentation
