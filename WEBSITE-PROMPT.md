# Khan Al Harir website prompt

Build or update the complete responsive bilingual website for **Khan Al Harir — خان الحرير**, a Syrian and Middle Eastern restaurant in New Cairo, Egypt.

The complete approved image library is included beside this prompt inside the `assets` folder. **Use these exact local image files. Do not generate replacements, remove them, rename them, or use external image URLs.** Preserve all existing menu photographs in `assets/menu/`.

## Required visual assets

- Logo: `assets/khan-logo.webp`
- Hero: `assets/hero-shawarma.webp`
- Charcoal & Grills tile: `assets/cuisine-grills-3840.webp`
- Mezze tile: `assets/cuisine-mezze-3840.webp`
- Syrian Kitchen tile: `assets/cuisine-kitchen-3840.webp`
- About/table image: `assets/arabic-table.webp`
- Hummus feature: `assets/hummus-bowl.webp`
- Kunafa: `assets/kunafa-illustrative.webp`
- Soup: `assets/cream-soup-illustrative.webp`
- Dasani Egypt: `assets/dasani-egypt-official-3840.webp`
- Ayran: `assets/ayran-official-3840.webp`
- V/V7 drinks: every `assets/v7-card-official-*-3840.webp` file
- Complete menu: every photograph inside `assets/menu/`

All displayed photographs are already supplied as 3840 × 2160 WebP files. Keep them in 4K and use `object-fit: cover` where necessary. Keep the square logo undistorted.

## Design

Preserve the elegant existing design: deep green, warm cream, subtle gold accents, editorial food photography, refined English serif headings, and high-quality Arabic typography.

The homepage photography gateway must show exactly three equal responsive tiles:

1. Charcoal & Grills — المشاوي على الفحم
2. Mezze — المقبلات
3. Syrian Kitchen — المطبخ السوري

Do not add the removed Shawarma tile or the removed Cold Drinks tile. The three remaining tiles must fill the full row without blank space and stack correctly on mobile.

## Bilingual behavior

- Provide complete English and Arabic content.
- Add a functional language toggle in the header.
- Translate all visible navigation, headings, buttons, menu categories, dish names, descriptions, search text, accessibility labels, gallery captions, contact details, and footer content.
- English uses LTR; Arabic uses RTL.
- Use strong English typography and Noto Kufi Arabic / Noto Naskh Arabic.
- Remember the selected language.

## Menu

Keep the complete searchable and filterable bilingual menu already represented by the supplied images and content. Menu cards must include English and Arabic names and descriptions, category, local image, Talabat ordering link, and a Talabat price fallback when no verified price is available.

Cold drinks must include:

- Dasani Egypt — مياه داساني مصر
- Ayran — عيران
- V7 Cola — ڤي 7 كولا
- V Cola Diet — ڤي كولا دايت
- V Cola Blueberry — ڤي كولا توت أزرق
- V Cola Pink Lemonade — ڤي كولا بينك ليمون
- V Cola Lemon — ڤي كولا ليمون
- V Cola Pomegranate — ڤي كولا رمان

Use the supplied real Dasani and Ayran product photographs and the supplied official V/V7 product photographs.

## Required functionality

- Responsive header and mobile navigation
- English/Arabic toggle
- Searchable menu
- Category filters
- Show-more menu behavior
- Talabat links
- About section
- Responsive gallery and lightbox
- Contact section and Google Maps link
- Keyboard navigation and visible focus states
- Reduced-motion support
- No horizontal overflow

## Deployment structure

Keep this exact structure at the GitHub repository root:

```text
Khan-al-harir/
├── assets/
│   ├── menu/
│   ├── khan-logo.webp
│   └── all supplied website images
├── index.html
├── style.css
├── script.js
└── CREDITS.md
```

Use relative paths such as `assets/khan-logo.webp`. Do not move the website into a nested `app` folder. Verify that every referenced image exists with the exact filename and capitalization. Test on a case-sensitive environment before publishing to GitHub and Vercel.
