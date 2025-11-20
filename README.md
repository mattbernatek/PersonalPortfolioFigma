Personal Portfolio – Figma Recreation (1280px Fixed Layout)

This project is a faithful, one-to-one recreation of a Figma design provided as part of the Coding Temple HTML/CSS module.
It intentionally replicates the original layout, spacing, typography, and component structure without introducing any new content, branding, or creative deviations.

The goal of this exercise is technical accuracy, not design interpretation.

🚀 About the Project

This portfolio webpage was built from scratch using only HTML and CSS, with every section matched to the Figma specifications:
	•	Exact typography (IBM Plex Mono & Raleway)
	•	Spacing scale defined in CSS variables
	•	Colour tokens recreated from Figma
	•	Component-accurate hero, case studies, testimonials, recent work, and contact form
	•	Navigation and hero placed inside a dark header container with rounded bottom
	•	Logo, image, and illustration placeholders recreated exactly as provided

All layout and styling decisions strictly follow the original Figma intentions.

🎯 Project Constraints

📏 Fixed width: 1280px

This project is intentionally not responsive.

The Figma file was designed at a 1280px desktop frame, and this build locks the layout to that width via:

.container {
    max-width: 1280px;
    margin: 0 auto;
}

The goal was to match the desktop design pixel-for-pixel, not to create a responsive version.

📸 Images & Content
	•	All images, text blocks, tags, and button labels are placeholders copied directly from Figma (apart from the hero image).
	•	No new or original work has been added.
	•	All assets are stored locally under the /Assets/ folder, in the same structure used in the design.

🧱 Tech Stack
	•	HTML5
	•	CSS3
	•	Flexbox
	•	CSS Grid
	•	CSS variables for spacing + colours
	•	Google Fonts

📚 Structure Overview

index.html
├── Header
│   ├── Navigation
│   ├── Hero section
│   └── Collaborations logos
├── Case Studies (3 layouts including reversed variant)
├── Testimonials (2×2 grid)
├── Recent Work (custom Figma padding)
├── Contact Form
└── Footer

📝 What This Project Is (and Isn’t)

✔️ IS
	•	A true, faithful implementation of the provided Figma desktop design
	•	A demonstration of:
	•	semantic HTML
	•	clean CSS architecture
	•	accurate visual recreation skills
	•	grid + flexbox mastery

❌ IS NOT
	•	A responsive website
	•	A personal brand website
	•	A place for original written content
	•	A redesign or interpretation of the mockup

Everything the user sees is directly from the Figma template.

📂 How to View the Project

Simply open index.html in any modern browser, ideally at 1280px width - otherwise some layout elements may break.
All spacing, proportions, and alignment are calibrated for that single viewport size.

📌 Future Improvements (Optional)

Although not required for this assignment, possible enhancements include:
	•	Adding responsive breakpoints
	•	Converting spacing to a more scalable layout system
	•	Replacing placeholder content with personal branding