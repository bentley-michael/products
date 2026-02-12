# LeadLine AI Phone Intake Landing Page

One-page landing site for an AI Phone Intake & Lead Generation service built on Vapi + n8n. Designed for fast load, high conversion, and easy deployment on GitHub Pages.

## Project Structure

- index.html
- styles.css
- script.js

## Pre-Launch Checklist

Before deploying, complete these steps:

- [ ] Replace all UPPERCASE_PLACEHOLDER links with real URLs
- [ ] Create and add favicon.png (32x32px)
- [ ] Record 2-minute demo video and add URL
- [ ] Create social-preview.png (1200x630px) for social sharing
- [ ] Update [Your Company Name] in footer
- [ ] Update support@yourcompany.com with real email
- [ ] Test all buttons and links
- [ ] Test on mobile (resize browser or use DevTools)
- [ ] Check FAQ accordion works
- [ ] Verify smooth scroll navigation

## Deploy to GitHub Pages

1. Push the `phone-intake-landing/` folder to a GitHub repository.
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, select:
   - Source: Deploy from a branch
   - Branch: `main` (or `master`), folder `/phone-intake-landing`
4. Save. GitHub will provide your public URL.

## Replace Placeholder Links

Update these placeholders in index.html:

- LOOM_VIDEO_URL
- CALENDLY_URL
- STRIPE_PAYMENT_LINK_STARTER
- STRIPE_PAYMENT_LINK_PRO
- STRIPE_PAYMENT_LINK_WHITEGLOVE
- ONBOARDING_FORM_URL
- PRIVACY_POLICY_URL
- TERMS_OF_SERVICE_URL
- CONTACT_URL

## Test Locally

Open `index.html` directly in a browser, or run a simple local server:

- Python: `python -m http.server`
- Node: `npx serve`

Then visit `http://localhost:8000/phone-intake-landing/` or the URL shown by your server.

## Basic Customization

- Branding: update the company name, tagline, and footer info in index.html.
- Colors: edit CSS variables at the top of styles.css.
- Copy: adjust headlines, guarantees, and pricing text to match your offer.
- Media: swap LOOM_VIDEO_URL with your demo video link.
- Favicon: Create a 32x32px PNG with your logo/initials and save as favicon.png in the same directory.
