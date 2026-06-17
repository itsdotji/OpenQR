# OPEN QR

*Enterprise-grade, fully offline QR code generator that runs entirely in the browser.*

OPEN QR is a single-file web app for creating, styling, and exporting QR codes without sending any data to a server. Everything - text encoding, styling, logo embedding, and PDF export - happens locally on the user's device.

# Why OPEN QR ❓

* "100% client-side" - no backend, no database, no telemetry.
* No cookies, no analytics scripts, no third-party tracking.
* Works for everyday links as well as more structured data like WiFi credentials and contact cards.
* Safe for offline or air-gapped environments since nothing leaves the browser.

# Supported QR Data Types

* *Text / URL* - plain text or any link.
* *WiFi* - generates a scannable network join code (SSID, password, encryption type, hidden network toggle).
* *Contact (vCard)* - name, organization, title, phone, email, and website.
* *Phone* - direct dial QR using a `tel:` link.
* *Email* - pre-filled recipient, subject, and body.
* *SMS* - pre-filled number and message.
* *WhatsApp* - opens a chat with a pre-filled message via `wa.me`.

# Styling & Customization

* 11 preset *themes* for quick corporate-style branding.
* 10 *geometric pattern profiles* for the QR dot/corner shapes.
* 11 preset *brand colors*, plus manual color pickers for pattern fill, canvas background, and frame/corner color.
* Adjustable *margin buffer* and *center scale* sliders for fine-tuning layout.
* Logo / brand mark upload, processed entirely offline using the browser's `FileReader` API.
* Selectable *error correction level* (L / M / Q / H) — higher levels recommended when embedding a logo.

# Export Options

* Save as a *PNG image*.
* Save as a formatted *PDF report* (via jsPDF), including a corporate-style header and footer.
* *Share* the generated QR directly using the native Web Share API, with a clipboard-copy fallback on unsupported browsers.

# Tech Stack

* Vanilla HTML, CSS, and JavaScript - no build step required.
* "qr-code-styling" - handles QR generation and visual styling.
* "jsPDF" - handles PDF report generation.
* Google Fonts ("Inter") for typography.

# Getting Started

* Download or clone "index.html".
* Open it directly in any modern browser - no installation, server, or dependencies needed.
* Choose a data type, customize the style, and export your QR code.

# Project Pages

The footer of the app links to dynamically generated info pages, opened as standalone documents:

* *About* - project background and development principles.
* *Privacy Policy* - explains the local-only, trackless data handling.
* *Terms of Use* - usage rights and a scannability disclaimer.
* *License* - MIT License.
* *Open Source* - lists core dependencies and notes on contributing.

# 🤝 Contribution 

Contributions, feature requests, and bug reports are welcome.

If you'd like to improve OPEN QR, feel free to fork the repository and submit a pull request.


# 📄 License

Released under the *MIT License*. See the in-app "License" page for full terms.

# ❤️ Support 

If you find this project useful, consider giving it a ⭐ on GitHub and sharing it with others.

# 💻 Author

Developed by *itsdotji (Nikhil Kumar)*.

# 🌐 LIVE ON INTERNET 

https://openqrdev.vercel.app
