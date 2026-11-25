# FormSathi

FormSathi is a mobile-first React + TypeScript app styled with Tailwind CSS. It helps students find official portals, follow application guides, track checklists on their own device, discover scholarships, and prepare files locally.

## Run it locally

```bash
npm install
npm run dev
```

Create a production build with `npm run build`. The ready-to-serve build is in `dist/`.

## Included features

- English and Bengali navigation and a Bengali-aware portal search, including common spellings such as “Adhar” and “Digilock”.
- Official portal cards for Aadhaar, PAN, DigiLocker, voter services, driving licence, JEE Main, and WBJEE, with a dedicated searchable SSC exam center for CGL, CHSL, MTS, GD Constable, CPO, JE, and Selection Post.
- A searchable schemes finder for Annapurna Yojana, PMGKAY, Sukanya Samriddhi, Ayushman Bharat PM-JAY, PM Ujjwala, PM-Kisan, PM Fasal Bima, PM Awas (Urban and Gramin), PM SVANidhi, PM Mudra, PM Vishwakarma, PM Surya Ghar, Atal Pension, Lakshmir Bhandar, Krishak Bandhu, Yogyashree, and Mukhyamantri Abhyudaya Yojana.
- Scholarship listings across national, state, private, university, research, and study-abroad opportunities, with filters and official source links.
- Field-by-field guides with fictional examples, document checklists, saved progress, stage-based correction guidance, and final review.
- On-device image resize/conversion, image-to-PDF, PDF page export, previews, actual output size, and download controls.

Checklist progress is stored in local storage on the device. Files are processed in the browser. The site does not ask for identity numbers, passwords, or OTPs.

## Scholarship data note

Scholarship availability and academic-year labels were checked on 24 November 2026. The live official provider page is the source of truth. Aikyashree’s live portal did not expose a current academic year in the material checked, so the listing says “Not confirmed on portal”. NSP and OASIS are labelled 2026–27, SVMCM 2025–26, and Reliance Foundation UG 2026–27 based on their respective official pages.

