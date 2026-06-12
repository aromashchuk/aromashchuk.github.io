# QA Landing Page

Single self-contained `index.html` — no build step, no dependencies. Open it in a browser to preview.

## Before you publish — fill in the `{{...}}` placeholders

Search the file for `{{` and `TODO` and replace:

- [ ] `{{Your Name}}` — your name / brand (appears in title, logo, footer)
- [ ] `{{YN}}` — your initials in the avatar block (or swap for a real photo: `<img class="avatar" src="me.jpg">`)
- [ ] `{{you@email.com}}` — your contact email
- [ ] Calendly URL — `https://calendly.com/your-handle/qa-audit`
- [ ] Formspree form ID — `YOUR_FORM_ID` (see below)
- [ ] LinkedIn URL in the footer
- [ ] **Case study numbers** — replace the placeholder metrics with a REAL project. Even one free/discounted engagement to earn the first case study is worth more than the rate.
- [ ] About section — your years of experience, background, tech stack

## Contact form (already wired up)

The form posts to [FormSubmit](https://formsubmit.co) — free, no account. Emails go to `artromqa@gmail.com`.
**One-time activation:** submit the form once after deploy; FormSubmit emails an activation link to that
address — click it, and all future submissions forward to the inbox.

Calendly free tier covers the "book a call" button.

## Hosting — see the chat for the full breakdown
Recommended: **Cloudflare Pages** or **Netlify** (free, custom domain, HTTPS, drag-and-drop).
