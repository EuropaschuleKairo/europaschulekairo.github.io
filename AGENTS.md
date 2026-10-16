# Repository Guidelines for Agents

## Primary Sources & Internal Submodule
- All primary source materials and inspiration sources are stored privately in `internal/quellen/` (inside the `internal` submodule). Treat `internal/quellen/` as the primary source of truth.
- Internal generation utilities and developer tools are in `internal/Tools/`.

## URL & Path Safety (GitHub Pages)
- This repository is published at **https://europaschulekairo.github.io**.
- **URL-safe naming**: All folder names, subfolder names, file names, and asset paths MUST be URL/HTML-safe.
- **No spaces**: Never use spaces in folder or file names. Always replace spaces with underscores (`_`) (e.g., use `Grundbegriffe_der_Geometrie` instead of `Grundbegriffe der Geometrie`).
- **Character set**: Avoid special characters and umlauts in folder and file paths (e.g., prefer `ae`, `oe`, `ue`, `ss`, or standard ASCII characters, such as `Groessen`, `Franzoesisch`).
- **Consistent links**: All internal hyperlinks (`href`, `src`, etc.) in HTML, CSS, and JavaScript must use exact case-sensitive, URL-safe paths without spaces.