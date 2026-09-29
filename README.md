# Arslan Fayyaz — Master Portfolio

Permanent, data-driven portfolio. Future updates do **not** require a new website.

## Update future work yourself
- Projects: `src/data/projects.js`
- Jobs / internships: `src/data/experience.js`
- Skills: `src/data/skills.js`
- Education: `src/data/education.js`
- Certifications: `src/data/certifications.js`
- Awards / leadership: `src/data/awards.js`
- Social links: `src/data/socials.js`

Copy an existing object/row, change the text, save, and run/build again.

## Photo
Put your photo at `public/profile.jpg`, then in `src/App.jsx` change `/profile-placeholder.svg` to `/profile.jpg`.

## CV
Put your CV at `public/Arslan-Fayyaz-CV.pdf`. The Download CV button is already connected.

## Contact form
The contact form is prepared for EmailJS. Copy `.env.example` to `.env` and add your EmailJS Service ID, Template ID and Public Key. Never put a Gmail password in the frontend. Destination email: `arslanfayyaz1997@gmail.com`.

## Run
`npm install` then `npm run dev`

## Build
`npm run build`
