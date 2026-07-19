# Verve N Veda

**Compassionate, privacy-respecting resource hubs and learning tools for families, students, community helpers, and people seeking support.**

Verve N Veda is a growing collection of free-access, browser-based public resource tools designed to help people find practical help, learn safely, and move through difficult moments with clarity. The project brings together national resource pathways, community education tools, and local-first web apps that can be used without accounts, tracking, or complicated setup.

The guiding purpose is simple:

> Help people pause, learn, find resources, and take the next safe step.

---

## Project Mission

Verve N Veda exists to make helpful information easier to reach. Many people need support but do not know where to begin. A parent may be looking for food, child care, health care, school help, or utility support. A person experiencing homelessness may need shelter, documents, legal aid, mental health support, veteran services, or a local hotline. A student or community member may need digital safety education, scam-awareness tools, or a calm place to explore trusted resources.

This repository is intended to support those needs through simple, portable, human-centered web tools.

---

## Current Focus Areas

### Community Resource Hubs

- **Verve N Veda Homeless Hub**  
  A national resource directory for shelter, food, crisis help, health care, legal aid, documents, veterans, youth, domestic violence support, and local navigation.

- **Verve N Veda Family Resource Hub**  
  A parent and caregiver support directory for child care, Head Start, SNAP, WIC, school meals, Medicaid, CHIP, housing, utilities, special education, safety hotlines, and family support services.

### Digital Safety and Education

- **ARSHIF Atlas of Online Human Deception**  
  A privacy-respecting learning portal for recognizing patterns that may appear in scams, coercion, impersonation, financial grooming, emotional manipulation, and social engineering.

- **Pattern Literacy Tools**  
  Local-only educational tools that encourage people to pause, verify through trusted sources, and avoid acting under pressure.

### Learning and Public Education

- Resource pathways connected to **Khaemenes Academy**
- Public learning tools for students, parents, and community members
- Free-access educational portals and printable support materials

---

## Design Principles

Verve N Veda tools are built with the following principles:

- **Local-first whenever possible** — tools should run in the browser without requiring accounts or servers.
- **Privacy-respecting by default** — no hidden tracking, no unnecessary data collection, and no selling user data.
- **Accessible and readable** — clear language, mobile-friendly layouts, strong contrast, and practical navigation.
- **Non-accusatory safety design** — warning signals are presented as invitations to pause and verify, not as verdicts.
- **Human dignity first** — resource tools should support people without shame, stigma, or unnecessary barriers.
- **Portable and sovereign** — single-file or static web apps should be easy to download, preserve, host, and share.

---

## Technology Stack

The project is intentionally simple and portable.

- HTML
- CSS
- Vanilla JavaScript
- LocalStorage for optional local user preferences or saved items
- Static hosting support through platforms such as Cloudflare Pages, Netlify, GitHub Pages, or similar static hosts

No build system is required for the core tools unless future versions add optional advanced features.

---

## Suggested Repository Structure

```text
verve-n-veda/
  README.md
  LICENSE.md
  THIRD_PARTY_NOTICES.md
  SECURITY.md
  CODE_OF_CONDUCT.md

  apps/
    homeless-hub/
      index.html
    family-resource-hub/
      index.html
    arshif-atlas/
      index.html

  assets/
    images/
    icons/
    posters/

  docs/
    deployment.md
    contributing.md
    resource-review-policy.md
```

---

## Running Locally

Because the tools are static HTML apps, most can be opened directly in a browser.

1. Download or clone the repository.
2. Open the desired `index.html` file in a modern browser.
3. Use the app locally.

For a local development server, you can use any simple static server. For example:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

---

## Deployment

This project can be deployed as a static website.

Recommended hosting options:

- Cloudflare Pages
- Netlify
- GitHub Pages
- Other static hosting providers

A clean deployment structure could look like:

```text
vervenveda.com/
vervenveda.com/apps/homeless-hub/
vervenveda.com/apps/family-resource-hub/
vervenveda.com/apps/arshif-atlas/
```

---

## Resource Review Standard

Verve N Veda resource hubs should prioritize trusted, durable pathways such as:

- Official government resources
- Public health and safety agencies
- National nonprofit resource locators
- Crisis hotlines and established support networks
- Legal aid and benefit navigators
- Educational institutions and public learning resources

When possible, each resource should be reviewed for:

- Accuracy
- Accessibility
- National or local relevance
- Clear contact path
- Privacy and safety considerations
- Last-known availability

---

## Safety Notice

Verve N Veda tools are educational and informational. They are not a substitute for emergency services, legal advice, medical care, crisis counseling, law enforcement, professional case management, or direct support from qualified providers.

If someone is in immediate danger, they should contact local emergency services or an appropriate crisis hotline in their area.

---

## Privacy Notice

The core Verve N Veda apps are designed to run locally in the browser. When a tool uses browser storage, saved information remains on the user’s device unless the user chooses to export, copy, clear, or share it.

Future contributors should avoid adding analytics, trackers, third-party scripts, or server-based data collection unless the change is clearly documented, optional, privacy-preserving, and approved by the project maintainer.

---

## Accessibility Goals

The project aims to support:

- Mobile-friendly layouts
- Clear navigation
- Strong text contrast
- Large tap targets
- Keyboard-accessible controls
- Plain-language instructions
- Printable and saveable resources

Accessibility improvements are welcome.

---

## Contributing

Contributions should support the mission of dignity, safety, education, and access. Helpful contributions may include:

- Updating resource links
- Improving mobile layouts
- Enhancing accessibility
- Adding printable checklists
- Reviewing safety language
- Creating new local-first tools
- Fixing bugs
- Improving documentation

Please avoid adding features that collect sensitive personal information, encourage surveillance, make accusations about individuals, or create barriers for vulnerable users.

---

## Related Sites

- **Verve N Veda:** VervenVeda.com
- **Khaemenes Academy:** KhaemenesAcademy.org

---

## Maintainer

Created and maintained by **Jennifer Pearl** as part of the Verve N Veda and Khaemenes Academy public resource ecosystem.

---

## License

Add the project license here, or see `LICENSE.md` if included in this repository.

Suggested options depend on the project’s goals:

- Use an open-source license for code if you want others to reuse and improve the apps.
- Use a Creative Commons license for written educational content if you want controlled public sharing.
- Use a custom license if you want public access while preserving stronger stewardship and attribution requirements.

---

## Closing Statement

Verve N Veda is built for people who need a calm place to begin. Whether someone is seeking shelter, supporting a child, protecting a family member from an online scam, or looking for trustworthy educational resources, this project is designed to offer a clear first step.

**Pause. Learn. Verify. Find support. Move forward with dignity.**
