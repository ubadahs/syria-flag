# Syrian Flag Replacer

A browser extension that replaces the old regime flag with the flag of the Syrian revolution.

## Credits

The revolution flag image used in this extension was created by [Mayas on emoji.gg](https://emoji.gg/user/mayas).

## About This Flag

While Syria's future governance remains to be determined at the time of this extension's creation, the revolution flag represents the aspirations and dreams of free Syrians. It stands as a symbol of the Syrian people's struggle for liberty and dignity, and honors the immense sacrifices made over many years in the pursuit of a free Syria.

## What It Does

This extension automatically replaces any instance of the old regime flag (🇸🇾) with the revolution flag across all websites, including:
- Social media (Twitter/X, Bluesky, etc.)
- News websites
- Any other webpage

## Installation Instructions for Beginners
[[Arabic instructions for install](https://ubadahsabbagh.com/ar/flag.html)] تعليمات التثبيت بالعربي ([link](https://ubadahsabbagh.com/ar/flag.html))

### Firefox Users
1. Download the extension ZIP file from Github above.
2. Open Firefox and type `about:debugging` in the address bar
3. Click "This Firefox" in the left sidebar
4. Click "Load Temporary Add-on"
5. Find and select the ZIP file you downloaded

Note: In Firefox, you'll need to reload the extension each time you restart the browser. This is a limitation of self-distributed extensions.

### Chrome Users
1. Download the extension ZIP file (same as above)
2. Unzip/Extract the downloaded file
3. Open Chrome and type `chrome://extensions` in the address bar
4. Turn on "Developer mode" in the top right corner
5. Click "Load unpacked" in the top left
6. Select the folder you just unzipped

Note: In Chrome, you'll need to enable Developer mode to keep using the extension. You may see warnings about using developer mode extensions - this is normal for self-distributed extensions.

## Technical Details

This extension uses:
- Manifest V2 for maximum browser compatibility
- MutationObserver to handle dynamically loaded content
- Universal URL matching to work across all websites
- Efficient node traversal for performance
- CSS scaling to match surrounding text size

## Troubleshooting

If the flag replacement stops working:
- Firefox users: Go back to `about:debugging` and reload the extension
- Chrome users: Go to `chrome://extensions` and click the refresh icon on the extension

If you see the old flag on Twitter/X:
- Refresh the page
- Make sure the extension is still loaded (see above)

## Contributing

Found a bug or want to suggest an improvement? Please open an issue on GitHub.

## License

MIT License 