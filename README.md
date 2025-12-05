🌤️ Kwik Shadez — Custom WordPress Theme

Live Website: https://kwikshadez.com/

Kwik Shadez is a custom WordPress theme built for a modern, responsive, and content-driven business website.
This repository contains only the theme files and ACF field configurations, making it suitable for development, version control, and deployment.

⭐ Features

Fully Responsive Design (mobile-first layout)

Custom ACF Integration for easy content management

Clean and semantic HTML structure optimized for SEO

Custom templates for pages, sections, and reusable components

Modular assets (CSS, JS, Fonts, Images)

Fast-loading & lightweight theme structure

📁 Folder Structure

kwik-shadez/
 ├── style.css                ← Theme metadata + main stylesheet
 ├── functions.php            ← Theme setup, scripts, menus, ACF support
 ├── header.php               ← Global header template
 ├── footer.php               ← Global footer template
 ├── index.php                ← Default template
 ├── page.php                 ← Page template
 ├── single.php               ← Post template
 ├── template-parts/          ← Reusable UI sections
 ├── assets/
 │    ├── css/                ← Stylesheets
 │    ├── js/                 ← JavaScript files
 │    ├── images/             ← Theme images/icons
 │    └── fonts/              ← Web fonts
 ├── acf-json/                ← ACF field groups (auto-loaded)
 └── README.md                ← Documentation

Why acf-json/ is included

WordPress automatically loads ACF field groups from this folder, which makes:

Version control easy

Cloning and redeploying identical ACF settings possible

No manual export/import required

🚀 Installation

Download or clone this repository.

Upload the theme folder into:
/wp-content/themes/

Log in to WordPress Admin → Appearance → Themes

Activate the Kwik Shadez theme.

Make sure Advanced Custom Fields (ACF) plugin is installed.
The theme will automatically load ACF field groups from /acf-json/.

🔧 Development Notes

WordPress core files are not included.

User-uploaded media (/uploads/) is not included.

Database is not included — export it manually via phpMyAdmin or hosting panel.

When modifying assets (CSS/JS), use versioning to avoid browser cache issues.

🛡️ Security Recommendations

Disable WordPress file editor in production (define('DISALLOW_FILE_EDIT', true);)

Limit write permissions on theme files

Use caching + optimization plugin if needed

📌 About

Author: Rong Liu

Project: Custom WordPress theme for Kwik Shadez

Tech stack: WordPress, PHP, ACF, HTML, CSS, JavaScript
