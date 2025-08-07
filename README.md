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
- **OCBC NISP**
- **Maybank Indonesia**
- **Bank Mega Tbk**

### Syariah Banks

- **BCA Syariah**
- **BNI Syariah**
- **BRI Syariah**
- **Mandiri Syariah**
- **BSI** (Bank Syariah Indonesia)
- **BTPN Syariah**
- **Bank Mega Syariah**
- **Bank Muamalat**

### Regional Development Banks

- **Bank DKI** (Jakarta)
- **Bank DIY** (Yogyakarta)
- **Bank Jateng** (Central Java)
- **Bank Jatim** (East Java)
- **Bank BJB** (West Java)

### Digital Banks & Payment Methods

- **Jenius** (BTPN Digital)
- **Jago** (Bank Jago)
- **SeaBank** (Sea Limited)
- **GoPay** (Gojek)
- **Allo Bank**

## 📁 File Structure

```text
sources/
├── allo.png
├── bca.svg
├── bca-syariah.svg
├── bca_syariah.png
├── bcad.png
├── bjb.png
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
├── diy.png
├── dki.png
├── gopay.png
├── hsbc.svg
├── jago.png
├── jateng.png
├── jatim.png
├── jenius.svg
├── mandiri.svg
├── mandiri-syariah.svg
├── maybank.png
├── mega_syariah.png
├── mega_tbk.png
├── muamalat.png
├── ocbc.svg
├── panin.svg
├── permata.svg
└── seabank.png
```

## 🚀 Usage

### Direct File Access

```html
<!-- SVG files -->
<img src="sources/bca.svg" alt="BCA" width="100" height="50">
<img src="sources/mandiri.svg" alt="Mandiri" width="100" height="50">

<!-- PNG files -->
<img src="sources/gopay.png" alt="GoPay" width="100" height="50">
<img src="sources/jago.png" alt="Jago" width="100" height="50">
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

- **Format**: SVG (Scalable Vector Graphics) and PNG
- **Quality**: Vector-based SVG files for infinite scalability, PNG for raster images
- **Optimization**: Optimized for web usage
- **Compatibility**: Works across all modern browsers

## 🔧 Development

This project includes a .NET build configuration for potential future development needs.

## 📄 License

Please ensure you have the proper rights to use these logos in your projects. Bank logos are typically trademarked and should be used in accordance with each bank's brand guidelines.

## 🤝 Contributing

1. Fork this repository
2. Add new payment method icons in SVG or PNG format
3. Follow the naming convention: `bank-name.svg`, `bank-name.png`, or `bank-name-syariah.svg`
4. Ensure icons are optimized and maintain consistent quality
5. Submit a pull request

## 📧 Contact

For questions or suggestions, please open an issue in this repository.

## ⚠️ Disclaimer

This collection is for development purposes. All logos and trademarks belong to their respective owners. Please ensure compliance with each institution's brand guidelines when using these icons in production.
