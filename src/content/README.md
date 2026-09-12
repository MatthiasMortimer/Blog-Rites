# Content Directory

This folder contains the editable content for the website. Update these files when you want to change the words, contact details, projects, services, or other site information.

| File | Edit this to change |
| --- | --- |
| `site.json` | Name, title, bio, email, location, availability, logo, avatar, social links, and SEO metadata |
| `projects.json` | Development projects, teaching projects, project descriptions, tags, images, demo links, and GitHub links |
| `services.json` | Development services, teaching services, pricing, descriptions, and deliverables |
| `testimonials.json` | Client and student testimonials |
| `stats.json` | Experience, completed projects, students mentored, ratings, tech stack, and response time |
| `skills.json` | Development skills and teaching topics |
| `pages/contact.md` | Contact page FAQs |

## Where the content appears

- `site.json` is used across the navigation, footer, home page, about page, contact page, and page metadata.
- `projects.json` appears on the home page and portfolio page.
- `services.json` appears on the home page, services page, and contact form options.
- `testimonials.json` appears on the home page.
- `stats.json` appears on the about page.
- `skills.json` appears on the services page.
- `pages/contact.md` appears on the contact page.

Keep the existing field names and JSON structure when editing. Image paths should point to files inside `public/`, such as `/media/project-dev.svg`.
