# Accessible Personal Portfolio

A four-page beginner portfolio demonstrating semantic HTML5, keyboard accessibility, responsive CSS, and basic SEO.

## Project structure

```text
accessible-portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Run locally

1. Open this folder in Visual Studio Code.
2. Install the Live Server extension if you do not already have it.
3. Right-click `index.html` and choose **Open with Live Server**.
4. Use the top navigation to test all four pages.

You can also open `index.html` directly in a browser, though a local server is recommended.

## Personalize it

- Replace `Your Name` and `My Portfolio` with your preferred portfolio name.
- Update the Education section with accurate details.
- Replace sample projects with your real projects and links.
- Update the descriptions and page titles to match your content.
- Only add images if you have appropriate image files; provide useful alternative text for informative images.

## Accessibility checks

- Use Tab and Shift+Tab to navigate.
- Confirm the focus outline is visible.
- Test the skip link.
- Test all contact form fields with empty, invalid, and valid values.
- Check color contrast and mobile layouts.
- Run Lighthouse Accessibility and SEO audits on each page.
- Automated scores do not replace manual keyboard and screen-reader testing.

## Contact form limitation

The contact form currently validates fields and displays a demonstration message. It does **not** send email or save submissions. Connect a backend or trusted form service before using it for real contact messages.

## Publishing

You can publish the static site using GitHub Pages or another static hosting provider. Test all links and audits again after publishing.
