# Optimized Encode/Decode Tool

A web-based file encoding and decoding utility that supports **Base64**, **Hex**, and **Base32** formats. Optional features include gzip compression and password-based encryption for secure processing.

## Usage

1. Download or clone this repository.
2. Open `index.html` in a modern web browser (no server required).
3. Select a file and choose the desired encoding or decoding options.

## Key Features

- **Large file handling** through chunked processing.
- **Batch operations** for encoding or decoding multiple files concurrently.
- **Checksum verification** to ensure file integrity.
- Optional **compression** (gzip) and **encryption** using the Web Crypto API.
- Progress indicators and persistent settings stored in the browser.

## Prerequisites & Browser Compatibility

- Works in modern browsers that support the File API, `CompressionStream`, and the Web Crypto API.
- Best experienced in the latest versions of Chrome, Firefox, or Edge.

