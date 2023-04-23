# QR Code React Component

This is a lightweight and customizable React component for generating QR codes. It allows you to create QR codes with different sizes, colors, error correction levels, and encoding modes, and provides a simple API to integrate them into your React applications.

## Features

- Simple and flexible API
- Customizable QR code size, color, and error correction level
- Support for different encoding modes (numeric, alphanumeric, byte, and kanji)
- Compatible with all modern browsers and devices
- Lightweight and fast rendering performance

## Usage

To use this component in your React application, simply import it and pass the required props:

```jsx
import React from 'react';
import QRCode from 'qr-code-react';

function MyComponent() {
  return (
    <QRCode value="https://example.com" size={128} />
  );
}
