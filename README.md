# -Build-a-Personal-Portfolio-Website
THIS REPO IS THE PROJECT OF ACADEMICS CUSTOMER EXPERINCE  DESIGN AND PROGRAMMING
Project Details and Workflow: NikhilPortfolio
This document provides a comprehensive overview of the NikhilPortfolio project, including its technical stack, architecture, and the recommended development workflow.

Project Overview
A personal professional portfolio website for Nikhil Singh, an AI/ML Engineer. The site showcases his educational background, work experience, technical skills, and a collection of AI/ML projects.

Tech Stack
Core: HTML5, Vanilla JavaScript, CSS3
CSS Framework: Bootstrap v2.1.0
Icons: Boxicons, Icofont, Remixicon
JS Plugins:
owl.carousel: For responsive sliders
venobox: For lightboxes and project details
aos: For scroll animations
typed.js: For the typewriter effect in the header
Analytics: Google Tag Manager & Google Analytics (UA-169007209-3)
File Structure
NikhilPortfolio/
├── index.html            # Main landing page
├── README.md             # Basic project description
├── LICENSE               # MIT License
├── assets/               # Project assets
│   ├── css/              # Custom stylesheets (style.css)
│   ├── js/               # Custom script (main.js)
│   ├── img/              # Images (profile, project thumbnails, certificates)
│   └── vendor/           # Third-party libraries (Bootstrap, jQuery, etc.)
└── projects/             # Detailed project pages (iras.html, ml.html, etc.)
Features
Dynamic Header: Animated typing effect showcasing roles.
About Section: Professional summary and personal details.
Education & Experience: Chronological timelines of academic and professional history.
Interactive Portfolio: Filterable project gallery with detailed lightboxes.
Skills Matrix: Visual representation of languages and frameworks.
Contact Form: Information for professional inquiries.
Development Workflow
1. Preparation
Ensure you have a code editor (like VS Code) and a local development server (like Live Server extension) to preview changes in real-time.

2. Modifying Content
Bio/Text: Edit text directly within the <section> tags in 
index.html
.
Experience/Education: Add new items by duplicating the col-md-12 icon-box div within the respective sections.
Skills: Update the skill icons in the skills section using SVG links or image paths.
3. Adding a New Project
Create Thumbnail: Save a 600x600px image in assets/img/project/.
Create Project Page: Create a new 
.html
 file in the projects/ directory (use 
projects/ml.html
 as a template).
Update Portfolio: In 
index.html
, add a new div in the portfolio-container section, linking to your new thumbnail and project page.
4. Custom Styling
Add or modify CSS in 
assets/css/style.css
 for any layout or color changes.

5. Deployment
The project is optimized for GitHub Pages. To deploy:

Push your changes to a GitHub repository.
Go to Repository Settings -> Pages.
Select the main branch and /root as the source.
Your site will be live at https://<username>.github.io/<repo-name>/.
Verification Plan
Automated Tests
N/A - This is a static site. No automated testing framework is currently integrated.

Manual Verification
Visual Check: Open 
index.html
 in a browser and verify all sections load correctly.
Responsiveness: Resize the browser window to ensure mobile and tablet layouts look good.
Link Testing: Click all social links, navigation menu items, and project "info" icons to ensure they lead to the correct destinations.
Console Check: Open Browser DevTools (F12) and ensure there are no JavaScript errors in the console.
