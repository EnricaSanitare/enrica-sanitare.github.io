# Calino Ceramics — GitHub Pages website

This package contains the current static website for **calino.ro**.

## Structure
- `index.html` — English (default)
- `it/index.html` — Italian
- `ro/index.html` — Romanian
- `style.css` — shared styling
- `images/calino-logo.png` — main website logo
- `images/favicon-*.png` — browser favicon files

## Upload to GitHub Pages
Upload/replace the files in the root of your existing GitHub Pages repository. The English version remains at the root, so `https://calino.ro/` stays the default language.

## Product photography
The current product and facility areas intentionally use placeholders. They can be replaced later with your real photographs and detailed product information.


## Contact form
The site now includes a styled contact form in English, Italian and Romanian. It is prepared for Formspree, which works with static GitHub Pages sites. Formspree's HTML integration uses a form action such as `https://formspree.io/f/{form_id}` and requires named form fields.

### Connect the form
1. Create a free Formspree account and a new form.
2. Set the notification/target email to `contact@calino.ro`.
3. In Formspree, open the form's Integration section and copy the endpoint.
4. The contact form is already connected to the provided Formspree endpoint: `https://formspree.io/f/xrpgover`.
5. Commit the files to GitHub Pages and test the form.

The current form collects name, company, email, phone and message. The second company phone number has been removed from the website.
