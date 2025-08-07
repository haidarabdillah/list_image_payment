# Payment Method Icons Collection

A curated collection of Indonesian bank and payment method logos in SVG format.

## 📋 Overview

This repository contains high-quality SVG icons for various Indonesian banks and payment methods. These icons are perfect for use in web applications, mobile apps, and other digital platforms that need to display payment options.

## 🏦 Available Banks

### Conventional Banks

- **BCA** (Bank Central Asia)
- **BNI** (Bank Negara Indonesia)
- **BRI** (Bank Rakyat Indonesia)
- **Mandiri**
- **CIMB Niaga**
- **Danamon**
- **Permata Bank**
- **Panin Bank**
- **Bukopin**
- **BTPN**
- **HSBC Indonesia**
- **Citibank**

### Syariah Banks

- **BCA Syariah**
- **BNI Syariah**
- **BRI Syariah**
- **Mandiri Syariah**
- **BSI** (Bank Syariah Indonesia)
- **BTPN Syariah**

### Digital Payment

- **Jenius** (BTPN Digital)

## 📁 File Structure

```text
sources/
├── bca.svg
├── bca-syariah.svg
├── bni.svg
├── bni-syariah.svg
├── bri.svg
├── bri-syariah.svg
├── bsi.svg
├── btpn.svg
├── btpn-syariah.svg
├── bukopin.svg
├── cimb.svg
├── citibank.svg
├── danamon.svg
├── hsbc.svg
├── jenius.svg
├── mandiri.svg
├── mandiri-syariah.svg
├── panin.svg
└── permata.svg
```

## 🚀 Usage

### Direct File Access

```html
<img src="sources/bca.svg" alt="BCA" width="100" height="50">
```

### CSS Background

```css
.bank-logo {
  background-image: url('sources/mandiri.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
```

### React/JSX

```jsx
import BCALogo from './sources/bca.svg';

function PaymentOption() {
  return <img src={BCALogo} alt="BCA Bank" />;
}
```

## 🎨 Icon Specifications

- **Format**: SVG (Scalable Vector Graphics)
- **Quality**: Vector-based, infinitely scalable
- **Optimization**: Optimized for web usage
- **Compatibility**: Works across all modern browsers

## 🔧 Development

This project includes a .NET build configuration for potential future development needs.

### Build

```bash
dotnet build
```

## 📄 License

Please ensure you have the proper rights to use these logos in your projects. Bank logos are typically trademarked and should be used in accordance with each bank's brand guidelines.

## 🤝 Contributing

1. Fork this repository
2. Add new payment method icons in SVG format
3. Follow the naming convention: `bank-name.svg` or `bank-name-syariah.svg`
4. Ensure icons are optimized and maintain consistent quality
5. Submit a pull request

## 📧 Contact

For questions or suggestions, please open an issue in this repository.

## ⚠️ Disclaimer

This collection is for development purposes. All logos and trademarks belong to their respective owners. Please ensure compliance with each institution's brand guidelines when using these icons in production.
