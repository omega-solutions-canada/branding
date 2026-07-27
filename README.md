# Omega Solutions – Branding Assets

Welcome to the official branding repository for [Omega Solutions](https://www.omegasolutions.ca/).

This repository provides approved logos, colour references, font references, and other brand assets for use across websites, email signatures, Microsoft 365, documents, presentations, and approved third-party integrations.

> **Repository setup:** Replace every instance of `Omega-Solutions-Canada` below with the final GitHub organization name after the organization is created.

---

## Public Logo URLs

Use the **Raw** links for websites, HTML email signatures, templates, and other integrations.

| Category | Variant | Background | Preview | Direct Link |
|---|---|---|---|---|
| Icon | Light | Dark/colour | Add file | `https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/icon/Omega-Icon-Light.png` |
| Icon | Dark | Light | Add file | `https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/icon/Omega-Icon-Dark.png` |
| Rectangle | Light | Dark/colour | ![Omega Solutions logo](logos/rectangle/Omega-Logo-Rectangle-Light-Trans.png) | `https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/rectangle/Omega-Logo-Rectangle-Light-Trans.png` |
| Rectangle | Dark | Light | Add file | `https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/rectangle/Omega-Logo-Rectangle-Dark.png` |
| Email Signature | Standard | Transparent | Add file | `https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/signature/Omega-Logo-Signature.png` |

Once the image files are uploaded, replace **Add file** in the Preview column with Markdown such as:

```markdown
![Omega Solutions logo](https://raw.githubusercontent.com/Omega-Solutions-Canada/branding/main/logos/signature/Omega-Logo-Signature.png)
```

### Recommended email-signature asset

For the standard email signature, use a transparent PNG optimized for display at approximately 180–250 pixels wide. Keep the original high-resolution file in `logos/source/`.

---

## Brand Colours

See [`colors/brand-palette.md`](colors/brand-palette.md).

Only add colours that have been confirmed as part of Omega Solutions' approved visual identity.

---

## Fonts

See [`fonts/font-references.md`](fonts/font-references.md).

Link to official font sources whenever possible. Do not upload commercial or restricted font files unless Omega Solutions has confirmed that its licence permits public redistribution.

---

## Repository Structure

```text
branding/
├── logos/
│   ├── icon/
│   │   ├── Omega-Icon-Light.png
│   │   └── Omega-Icon-Dark.png
│   ├── rectangle/
│   │   ├── Omega-Logo-Rectangle-Light.png
│   │   └── Omega-Logo-Rectangle-Dark.png
│   ├── signature/
│   │   └── Omega-Logo-Signature.png
│   ├── source/
│   │   └── Approved editable or vector source files
│   └── README.md
├── colors/
│   └── brand-palette.md
├── fonts/
│   └── font-references.md
├── BRAND-USAGE.md
├── REPOSITORY-SETUP.md
└── README.md
```

---

## File Naming Standard

Use predictable, URL-safe names:

```text
Omega-[Asset]-[Shape-or-Purpose]-[Variant]-[Size].[extension]
```

Examples:

```text
Omega-Logo-Rectangle-Light.png
Omega-Logo-Rectangle-Light-Small.png
Omega-Icon-Dark.png
Omega-Logo-Signature.png
```

Use hyphens instead of spaces and avoid changing filenames after they are published, because doing so breaks any email signatures or integrations that use the raw URL.

---

## Brand Usage

See [`BRAND-USAGE.md`](BRAND-USAGE.md).

The files in this repository remain the intellectual property of Omega Solutions. Public availability does not grant unrestricted permission to modify, redistribute, resell, or represent Omega Solutions without authorization.

---

## Contact

For approved asset requests, brand questions, or integration assistance, contact:

**Omega Solutions**  
Website: https://www.omegasolutions.ca/  
Email: info@omegasolutions.ca
