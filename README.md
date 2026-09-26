# ApexBill Pro - Smart GST Commercial Billing & Invoicing Software

ApexBill Pro is a modern, responsive, and commercial-grade GST billing web application designed for small-to-medium businesses, freelancers, and enterprises. It provides real-time tax calculations, company logo placement, buyer and supplier management, digital rubber stamps, signature capture, and pixel-perfect A4 printing/PDF export.

![ApexBill Pro Banner](logo-placeholder.svg)

---

## 🌟 Features

- **Company Logo (Top Middle Space)**: Prominently centered space for your company logo with height and alignment adjustments.
- **Supplier & Consignor Details**: Business name, 15-digit GSTIN (with auto format validation), PAN, phone, email, address, state & state code.
- **Buyer & Consignee Details**: Customer name, GSTIN, contact info, billing address, and optional separate shipping address.
- **Dynamic Line Items**: Add, edit, or remove products and services with HSN/SAC code, quantity, unit, unit rate, discount %, and GST slab rates (0%, 5%, 12%, 18%, 28%).
- **Dual GST Modes**:
  - **Inter-State**: Single IGST calculation.
  - **Intra-State**: 50/50 split CGST and SGST calculation.
- **Total Amount in Words**: Real-time conversion into Indian numbering format (*Lakhs, Crores, Thousands, Hundreds, Rupees & Paise*) and international currency formats.
- **Seller Signature & Digital Stamp**:
  - **Interactive Signature Canvas**: Draw signatures using mouse, stylus, or touch screen, or upload a signature image.
  - **Official Rubber Stamp**: Dynamic circular rubber stamp with customizable business name, ink colors (Ruby Red, Navy Blue, Royal Purple, Forest Green), tilt angle, or custom PNG stamp upload.
- **Instant UPI QR Code**: Automatically generated dynamic UPI payment QR code on the invoice for instant scan-and-pay.
- **Bank & Remittance Details**: Bank name, account number, IFSC code, branch, and UPI ID.
- **Terms & Notes**: Editable terms of sale and customer notes.
- **Standard A4 Print & PDF**: Immaculate `@media print` styling that hides app controls and produces a clean, high-contrast A4 commercial tax invoice.
- **Save & Load History**: Store multiple invoices locally with JSON backup export and import.
- **Theme Support**: Seamless toggle between sleek Dark Mode and clean Light Mode.

---

## 🚀 Quick Start

ApexBill Pro runs directly in any modern web browser without heavy server dependencies.

### 1. Clone the repository
```bash
git clone https://github.com/Namansinghal800/billing-software.git
cd billing-software
```

### 2. Run Locally

You can open `index.html` directly in your browser, or serve it using Python's built-in HTTP server:

```bash
python -m http.server 8080
```

Now open:
👉 **http://localhost:8080**

---

## 📂 Project Structure

```
billing-software/
├── index.html              # Main application markup & A4 invoice template
├── style.css               # Modern design system, dual-pane UI & print styles
├── app.js                  # Reactive calculations, number-to-words, canvas signature
├── logo-placeholder.svg    # Default vector company logo
├── stamp-default.svg       # Default circular rubber stamp asset
└── README.md               # Documentation
```

---

## 📄 License

This project is licensed under the MIT License.
