# QvCard - Global Digital Business Card Generator (v6.0)

QvCard is a privacy-first, client-side Single Page Application (SPA) that generates vCard 3.0 compliant QR codes with **Custom Branding** capabilities.

🔗 **Live Demo:** [https://original-qvcardapplication.netlify.app/](https://original-qvcardapplication.netlify.app/)

## Key Features

* **Branding & Logo Support:** Users can upload their company logo, which is embedded into the QR code (High Error Correction) and the downloadable vCard file.
* **Cross-Platform "Line Folding":** Solves the legacy issue where Windows/Outlook crashes on long Base64 strings. The app automatically formats the vCard code to strict RFC 2426 standards.
* **Multi-Language Support (i18n):** Native support for English (EN), Turkish (TR), and German (DE).
* **Strict Validation:** Regex-based real-time validation prevents invalid data entry.
* **Privacy First:** Zero backend. All data is processed locally in the browser using FileReader API.
* **Smart Persistence:** Uses `LocalStorage` to save user inputs seamlessly.

## Tech Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Libraries:** EasyQRCodeJS (for advanced canvas manipulation), FontAwesome
* **Architecture:** Serverless / Client-Side SPA

## How It Works

1.  **Logo Processing:** The app converts uploaded images to Base64 strings using the FileReader API.
2.  **QR Generation:** Generates a High-Correction-Level QR code with the logo centered.
3.  **vCard Formatting:** Creates a `.vcf` file, handling complex Base64 image data with proper line folding (75 chars limit) for legacy software support.

## Developer Note

This project demonstrates proficiency in **Canvas Manipulation**, **File API**, **Regex Validation**, and solving complex **Cross-Platform Compatibility** issues.

---
*Developed with ❤️ by Dilara Kesgun*
