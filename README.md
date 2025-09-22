# html-qrcode

Lightweight demo repository showing client-side QR code scanning using the bundled `html5-qrcode.min.js` script.

## What this project contains

- `index.html` — a minimal web page that demonstrates scanning QR codes from the camera using `html5-qrcode`.
- `html5-qrcode.min.js` — the library used by `index.html` (bundled copy).

## Usage

1. Open the `index.html` file in a modern browser that supports camera access (Chrome, Edge, Firefox).
   - On Windows, double-click `index.html` or open it from the browser (`File > Open File...`).
2. When prompted, allow the page to access your camera.
3. Point the camera at a QR code — the page will display the decoded text.

Notes:
- For best results use a laptop or desktop with a rear camera, or run the page on a phone.
- If camera access is blocked, check browser permissions and try again.

## Development

This is a static demo — no build tools or servers required. If you prefer to run a local server (recommended for camera permissions on some browsers), you can use Python or Node.js:

Python 3 (built-in http.server):

```cmd
cd "%CD%"
python -m http.server 8000
# Then open http://localhost:8000/index.html
```

Node.js (http-server):

```cmd
npm install -g http-server
http-server -c-1
# Then open the printed local URL in a browser
```

## License

This repo contains the `html5-qrcode.min.js` bundle. Please refer to the bundled library for its license terms and attribution requirements.

## Contact

If you need changes or want this project extended (e.g., integrate with a backend, add build steps, or improve UI), open an issue or request changes.
