# Medistra COE Page

Responsive, mobile-first pages showcasing Medistra Hospital’s Centers of Excellence (COE) and corporate profile.

## Available Pages

- `about.html` – Hospital overview, services, technology, certifications, and COE links
- `cardiology.html`
- `orthopedy.html`
- `oncology.html`
- `hepatology.html`
- `infection.html`

## Features

- **Mobile-first approach UI**
- **Expandable content sections**
- **Optimized for mobile devices**
- **Multi-language support (English & Indonesian)**
- **Interactive accordion sections**
- **Doctor profiles with photos**

## Project Structure

```
medistra-coe-page/
├── about.html
├── cardiology.html
├── hepatology.html
├── infection.html
├── oncology.html
├── orthopedy.html
└── assets/
    ├── gedung_medistra.jpg
    ├── iso_15189.png
    ├── logo_brand.png
    ├── medistra_laboratory.png
    └── mri_tech.jpg
```

To view the complete list of uploaded assets and images, please refer to the following spreadsheet:

** [Medistra COE Assets Spreadsheet](https://docs.google.com/spreadsheets/d/1VPP1rm3YmZpp6q4gnp97fPeU70MJ9Nq4X0sbfTkhJbE/edit?gid=0#gid=0)**

This spreadsheet contains information about:
- Hero images for each COE
- Icons for each specialty
- Doctor photos with corresponding file names
- Accordion content images

## Multi-Language Support

This website supports **English (en)** and **Indonesian (id)** languages. The language selection is managed via URL query parameters

### Usage

#### Switch Language via URL Parameter

Add `?lang=en` for English or `?lang=id` for Indonesian

#### Example URLs:

**English:**
```
about.html?lang=id
cardiology.html?lang=en
```

After the first visit, the chosen language persists via `localStorage` until changed explicitly.