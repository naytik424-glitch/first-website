# Web Divider Website: Project Archive

Exported 17 November 2026.

This archive holds the source files of the Web Divider website, as designed in a Claude Design canvas.

## What's inside

| File | Page |
|---|---|
| `project/Main.dc.html` | Home |
| `project/About.dc.html` | About Us |
| `project/Services.dc.html` | Services |
| `project/Work.dc.html` | Our Work (portfolio, filters, project details) |
| `project/Contact.dc.html` | Contact Us (project inquiry form) |
| `project/ProjectArt.dc.html` | Shared component that draws the 8 portfolio visuals |
| `project/canvas.json` | Canvas layout: page order, sizes and titles |

## Important: these are design-canvas files

The `.dc.html` files are written in the Design canvas format. They need the canvas runtime to display. **Opening one directly in a browser will not show the finished page.**

- **To view the working website:** use the canvas share link. Everything works there: navigation, the mobile menu, the portfolio filters, the FAQ and the form.
- **To keep developing it:** give these files to Claude, or to a developer, as the starting point. Each file is plain HTML and CSS with a small JavaScript logic block, so it can be converted into React + Tailwind or a standard static website.

## Placeholders still to replace

- Business email, phone number and location: `[your@email.com]`, `[YOUR BUSINESS EMAIL]` and the others in the footer and on the Contact page
- Social media links (Instagram, LinkedIn, X, Facebook)
- Privacy Policy link on the Contact form
- Statistics on the Home page (`[00]+`)
- Sample testimonials, placeholder brand names and the "Next milestone" card on About Us

## Contact form

The form is in **demo mode**: it validates every field but sends nothing. To connect it, set `inquiryEndpoint` in the `config()` method near the top of the script block in `Contact.dc.html`. Use a form service URL (for example Formspree or Web3Forms) or your own backend.

## Portfolio projects

All 8 projects on the Our Work page are concept or demo projects. They are not client work. To add or edit one, change the list in the `projects()` method in `Work.dc.html`.
