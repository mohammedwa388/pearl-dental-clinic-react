# Pearl Dental Clinic — React rebuild

Redesigned and rebuilt by **Mohamed Ahmed Waly** from [my original HTML/CSS project](https://github.com/mohammedwa388/Pearl-Dental-Clinic).

## Features
- Responsive landing page with services, about, hours and demo appointment request
- Bilingual Arabic / English with RTL support and saved language choice
- Responsive mobile navigation and keyboard accessibility
- Front-end form validates details and saves request to the browser only
- Clear disclosure: this is a portfolio demonstration, **not a real operating clinic**, and no real booking is made
- Uses selected photo assets from the original repository via public raw.githubusercontent.com URLs; a styled tooth placeholder appears if assets cannot load

## Run
```bash
npm ci
npm run dev
npm run lint
npm run build
```

## Cloudflare Pages
Connect a repository containing these files, use `npm run build`, output `dist` and Node.js 22. `_redirects` is included.

## Portfolio relationship
This project replaces Northstar Analytics as the first featured project in Mohamed's portfolio. Aura Commerce and Flowboard remain standalone.
