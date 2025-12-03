RBT 40-Hour Training — Hugo Site Scaffold
========================================

What this package contains:
- Minimal Hugo project scaffold with sample modules, assessments, quizzes, local progress tracking, and certificate generator.

Compliance notes:
- Trainings for applicants on/after Jan 1, 2026 must align with BACB 2026 curriculum and include the required provider statement on certificates.
- Trainers must meet BACB qualifications and documentation retention rules.

How to build:
1) Install Hugo (https://gohugo.io/)
2) Place this folder as a Hugo site or put into your existing Hugo repo.
3) Replace the sample content with your full lesson text, videos, and assessments that map to the BACB 2026 sections.
4) Build: `hugo` (will generate public/). Host `public/` on Netlify/GitHub pages.

Customization:
- Replace placeholder video files in static/videos/
- Replace and expand quiz banks in content/ and static/js/quiz.js if you want a richer quiz system
- Consider server-side certificate issuance for signed certificates; current certificate generator is client-side and for estimates only.

