# Layercraft Privacy Policy

**Effective date:** November 3, 2026  
**Product:** Layercraft — Layered TIFF & PSD (Figma plugin)  
**Developer:** Paweł Sławski  
**Support:** [layercraft.figma@gmail.com](mailto:layercraft.figma@gmail.com)

## Overview

Layercraft converts selected Figma frames, groups and layers into Photoshop-compatible TIFF and PSD files on your device. **The plugin does not upload your designs to a developer-operated server and does not include analytics, tracking, advertising or user accounts.**

## Design data processed

When you run an export or request a preview, Layercraft reads relevant design data through Figma's Plugin API, including layer names and structure, text, fonts, images, dimensions, visibility and visual attributes. If you select a page-wide export, it may read frames on that page. The information is processed in the plugin environment to create TIFF/PSD documents and on-screen export notices.

## Data collection and transmission

Layercraft does not transmit your design files, document content, personal information or diagnostics to the developer or an external conversion service. It does not use a remote backend and declares `networkAccess.allowedDomains: ["none"]` in its Figma manifest.

Use of the Figma platform is separately governed by [Figma's privacy policy](https://www.figma.com/privacy/).

## Local storage and downloads

Layercraft saves export preferences, manual font mappings and optional imported font-list metadata through Figma's plugin storage. Exported TIFF/PSD files or batch ZIP files are downloaded to the location you choose. Conversion notices and diagnostic information remain within the plugin session; the developer does not remotely store them.

The optional imported Photoshop font list can be cleared in the plugin's advanced settings. Plugin preferences can be managed using the controls supported by Figma.

## Optional Photoshop font-list helper

If you use the optional helper script, it reads installed font names in your local Photoshop environment and saves a JSON file to a location you choose. It does not copy font files, edit your designs or upload data. The helper is not required for standard exports.

## Third-party components

Layercraft includes third-party open-source libraries with their respective license notices. It does not rely on external conversion services.

## Privacy-policy website

This policy is published via GitHub, which may process standard website access information under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Visiting this page is separate from running the offline Layercraft plugin.

## Contact and updates

For questions about Layercraft or this policy, email **[layercraft.figma@gmail.com](mailto:layercraft.figma@gmail.com)**. This page may be updated as Layercraft changes; the effective date will be updated when appropriate.
