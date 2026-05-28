# bm-qr-code-maker

A lightweight, browser-based QR code generator that creates QR codes from URLs and lets you download them as PNG.

## Features

- Generate QR codes from any valid URL
- Preview the QR code instantly in the browser
- Download the generated QR code as a PNG file
- Copy the source URL to clipboard
- Clean, responsive single-page UI
- Zero build tools required — just open `index.html`

## Usage

1. Open `index.html` in your browser.
2. Enter a URL in the input field.
3. Click **Generate** to render the QR code.
4. Use **Download** to save the QR code as `qr-code.png`.
5. Use **Copy URL** to copy the entered link to your clipboard.

## Development

- The project is a static HTML app with embedded CSS and JavaScript.
- QR code generation is powered by the `qrcode` library loaded from CDN.
- Edit `index.html` to customize text, styling, or behavior.

## Contributing

Contributions are welcome! If you want to improve the project:

1. Fork the repository.
2. Create a new branch for your change.
3. Make your edits in `index.html`.
4. Open a pull request with a description of your improvements.

## License

This project is open source and distributed under the terms of the `LICENSE` file.
