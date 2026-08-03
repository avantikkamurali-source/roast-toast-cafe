# Roast Toast Coast Cafe — AI-Assisted Website Build & Debug

A simple, responsive website for a fictional café, built and debugged with the help of an AI coding assistant.


## What this project demonstrates
 This project demonstrates that I can use an AI assistant to build, troubleshoot, and ship a working website by:

- Writing clear, structured prompts to diagnose problems in existing code
- Reviewing AI-suggested fixes before applying them (not just accepting output blindly)
- Verifying the result actually works in the browser
- Adding small, real improvements on top of a working baseline
- Deploying the finished site so it's publicly accessible

## The process

**1. Started with a broken version of the site.**
The original file had two bugs:
- A malformed CSS `url()` (missing a closing parenthesis) that stopped the background image from loading.
- A mismatch between a CSS class name in the HTML (`menu-items`) and the one referenced in the JavaScript (`menu-item`), which broke the "Our Menu" toggle button.

**2. Used an AI assistant to analyse the code.**
Prompted it to review the file and report all  functional errors, grouped by severity and type, rather than just asking "what's wrong with this."

**3. Reviewed the AI's fixes and applied them.**
Compared the original and corrected code side by side to understand exactly what changed and why it fixed the problem, instead of just accepting a rewritten file.

**4. Extended the site with new features**, again by describing what I wanted in plain English and having the AI implement it:
- A "Visit Us" section with hours, address, and a "Book a Table" button
- Mobile-responsive layout (site reflows to a single column on small screens)

**5. Deployed the site** using GitHub Pages for free static hosting.

## Files

- `index.html` — the complete site (HTML, CSS, and JavaScript in one file)

## Further progress I have made

- Add real menu pricing and a photo gallery
- Swap the placeholder contact details for a real booking form
- Improve accessibility (alt text, keyboard navigation for the menu toggle)
