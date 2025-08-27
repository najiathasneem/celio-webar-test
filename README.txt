# Celio WebAR Test (Model-Viewer)

This folder contains a minimal WebAR page using <model-viewer>.

## Files
- index.html         → landing page
- models/gift_box.glb→ GLB model (Android/Scene Viewer + WebXR)

## iOS AR (USDZ)
For AR on iOS/Safari you need a USDZ:
1) Convert your GLB to USDZ using Apple's free "Reality Converter" (Mac) or any GLB→USDZ converter.
2) Put the file at: models/gift_box.usdz
3) Edit <model-viewer> tag in index.html to include:
     ios-src="./models/gift_box.usdz"

## Deploy (pick one)
- GitHub Pages: put these files in a repo → Settings → Pages → main:/ (root).
- Netlify/Vercel: drag-and-deploy this folder; default settings work.
- Any web host: upload the folder; ensure HTTPS is enabled.

## Create a QR
Generate a QR to your URL (e.g., https://yourdomain.com/webar/index.html).

## Tips
- Keep models small (<15–20 MB total). Use 1–2k textures.
- Name files with no spaces; host under HTTPS.
