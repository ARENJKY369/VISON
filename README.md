# VISION

Real-time vision disability simulator. One `index.html` file — no build step.

Open it over HTTPS or `localhost` (camera and WebXR refuse `file://`):

```bash
python3 -m http.server 8080
```

On a phone, use HTTPS (`npx serve --ssl` or ngrok) so the rear camera can start. On a passthrough headset, open the hosted URL and tap **Enter AR**.

Nothing is recorded.
