# nmc-website Documentation

## Project Overview
The `nmc-website` project is designed to serve as a comprehensive online platform for providing important information and resources related to the NMC. This website aims to streamline communication and improve accessibility for stakeholders, including students, faculty, and the public.

## HTML Structure
The HTML structure of the project follows a clean and organized format. The main sections include:
- Header: Contains the navigation bar.
- Hero Section: Highlights key information.
- About Section: Provides details about the NMC.
- Announcements: Displays important updates.
- News and Events: Lists upcoming events and news features.
- Quick Links: Offers easy access to vital resources.
- Departments: Showcases various departments available at the NMC.
- Footer: Includes contact information and additional resources.

## How to Modify Content
### Navbar Links
To modify the navbar links, locate the `navbar.html` file in the `partials` directory. Update the link URLs and text as needed:
```html
<a href="/new-link">New Link</a>
```

### Hero Section
The hero section can be updated in the `index.html` file. Look for the section with the class name `hero`. You can change the content or style:
```html
<section class="hero">
  <h1>New Hero Title</h1>
  <p>Updated descriptive text.</p>
</section>
```

### About Section
To modify the content in the About section, refer to the `about.html` file:
```html
<section class="about">
  <h2>About Us</h2>
  <p>Updated information about the NMC.</p>
</section>
```

### Announcements, News, and Events Sections
These sections are typically pulled from a CMS or can be manually updated in their respective files. Ensure to replace the content in the designated files for announcements or events:
```html
<section class="announcements">
  <h2>Latest Announcements</h2>
  <p>New announcement content here.</p>
</section>
```

### Quick Links
Quick links can be updated within the `index.html`, or the specific `quick-links.html` file. Ensure the links are relevant:
```html
<ul class="quick-links">
  <li><a href="/link1">Link 1</a></li>
</ul>
```

### Departments
Each department can have its own section in the `departments.html`. Update as necessary:
```html
<section class="departments">
  <h2>Departments</h2>
  <div class="department-item">Department Name</div>
</section>
```

## Styling System using Tailwind CSS
Tailwind CSS is used for styling. Ensure to check the `tailwind.config.js` file to add or modify styles. A standard setup will look like:
```javascript
module.exports = {
  theme: {
    extend: {},
  },
  variants: {},
  plugins: [],
}
```

## Image Asset Management
Images are managed within the `images` directory. Ensure images are optimized for web use. Place all image assets into this folder and reference them properly in your HTML files:
```html
<img src="images/sample-image.jpg" alt="Sample Image">
```

## SEO and Metadata
For SEO, update the metadata in the `head` section of HTML files. This may include title, description, and keywords:
```html
<meta name="description" content="Your site description here">
```

## Step-by-Step Instructions for Clients to Update Content
1. **Access the Repository:** Clone or pull the latest version of the project.
2. **Modify HTML Files:** Use a text editor to open and edit HTML files in accordance with the sections outlined above.
3. **Update Styles (if needed):** Modify the `tailwind.config.js` or apply additional classes in HTML files for styling changes.
4. **Manage Images:** Place new or updated images in the `images` directory and adjust corresponding file paths.
5. **Ensure Compliance with SEO Guidelines:** Update all SEO metadata as needed in each HTML file.
6. **Test Changes Locally:** Run a local server to preview changes before pushing updates.
7. **Commit and Push Changes:** Once satisfied, commit all changes and push to the repository.

By following this documentation, clients can easily maintain and update their website content efficiently.