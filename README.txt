PINK & WHITE GAMEPADVIEWER SKIN

This is a GamepadViewer CSS skin, NOT a standalone HTML overlay.
It uses your approved pink-white DualSense render as the body, and original
GamepadViewer sprite geometry for the active controls.

INSTALLATION
1. Extract the ZIP. Keep all PNGs and pink_white_dualsense.css together.
2. Upload these files to a public GitHub repository.
3. Enable GitHub Pages: Settings > Pages > Deploy from a branch > main / root.
4. When published, get the URL for pink_white_dualsense.css, such as:
   https://YOURNAME.github.io/REPO/pink_white_dualsense.css
5. Open https://overlay.gamepadviewer.com/?p=1&s=5&editcss=YOUR_ENCODED_CSS_URL
   (URL-encode the CSS URL, e.g. via encodeURIComponent in browser console).
6. Add that full GamepadViewer URL to an OBS Browser Source.

IMPORTANT
- Your original supplied controller image has a different visual button layout
  from the GamepadViewer CSS sprite geometry. The mapping may need small
  positional adjustments after a real preview. The overlay has not been
  tested against your specific controller.
- The cyan controls are driven by GamepadViewer's own input state classes.
- No local file path can be passed to editcss; the CSS and PNGs must be hosted.
- GamepadViewer's existing gamepad recognition is used, not a custom input system.
