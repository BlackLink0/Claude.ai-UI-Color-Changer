# Claude Theme Customizer

A browser extension that lets you customize the background and accent colors of the Claude.ai interface.

 Features
 Custom background color for the entire Claude.ai interface
   Custom accent color for buttons, links, and interactive elements
   Colors persist across sessions
   Easy reset to default colors
  Works on both Chrome and Firefox

  Installation For Chromium 
  1. Open your browser and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in top-right corner)
3. Click "Load unpacked"
4. Select the `claude-theme-extension` folder
5. The extension is now installed!

Installation For Firefox
1. Open your browser and navigate to `about:addons/`
2. Enable "Developer mode" (toggle in top-right corner)
3. Click "Load unpacked"
4. Select the `claude-theme-extension` folder
5. The extension is now installed!

 For Permanent Installation in Firefox
1. Navigate to `about:config` and search for `xpinstall.signatures.required`
2. Set it to `false` (not recommended for security reasons, only for development)
3. Or, package and sign the extension through Mozilla's Add-ons Developer Hub

How to use? 
1. Navigate to [claude.ai](https://claude.ai)
2. Click the extension icon in your browser toolbar
3. Use the color pickers or enter hex codes to choose your colors:
   Background Color: Changes the main background of the interface
   Accent Color: Changes buttons, links, and interactive elements
4. Click "Apply" to save your changes
5. Click "Reset to Default" to revert to original colors

Example: <img width="1913" height="914" alt="Screenshot 2026-03-18 114424" src="https://github.com/user-attachments/assets/5a5946ac-728b-4995-a05c-7e20c8928149" /> vs old: <img width="1915" height="907" alt="Screenshot 2026-03-18 114452" src="https://github.com/user-attachments/assets/8f046c0a-4a5e-4a7f-898b-6e0a5b6d7351" />


You can modify `content.js` to target different elements or add more styling options. The CSS selectors are designed to be broad to catch most UI elements, but you can make them more specific if needed.
Important Note:  Colors must be in hex format (#RRGGBB)
 The extension only works on claude.ai domains
Some UI elements may not change color due to inline styles or higher specificity CSS
 The extension uses CSS `!important` to override existing styles

 Potential features to add:
 More granular color controls (sidebar, chat bubbles, etc.)
 Preset themes
 Font customization
 Export/import color schemes

 The License for this is in the "LICENSE" file.
 
