# Portfolio Website

Static portfolio website built with HTML, CSS, and JavaScript.

## Files
- `index.html`
- `about.html`
- `services.html`
- `portfolio.html`
- `contact.html`
- `styles.css`
- `script.js`

## Fix Log
This section tracks implemented fixes/changes.

### 2026-02-16
1. Header Contact CTA active text color fix
- Problem: Active nav links use blue text, which also affected the `Contact` CTA in the header.
- Fix: Added a specific override so active CTA text stays white.
- File updated: `styles.css`
- Selector added:
```css
.nav-link-cta.active {
    color: var(--white);
}
```
