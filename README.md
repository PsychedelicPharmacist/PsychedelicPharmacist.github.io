# HarmReductionAdvocate.com Website

This project is a comprehensive website for Mike Bonertz, a Harm Reduction Advocate and Psychedelic Pharmacist. The site showcases his educational resources, services, published articles, and information about the Sophrodelic Legal Magic Mushroom Retreat.

## Project Overview

The HarmReductionAdvocate.com website serves as a professional platform for Mike Bonertz, providing evidence-based information about psychedelic therapies and harm reduction approaches. The site is designed with a premium, modern aesthetic that incorporates psychedelic visual elements while maintaining professional credibility.

## Features

- **Responsive Design**: Fully responsive across desktop, tablet, and mobile devices
- **Premium Aesthetic**: Psychedelic gradients, SVG animations, and neural network visualizations
- **Educational Resources**: In-depth resources on psychedelic therapies for various conditions
- **Educational Events**: Separate section for psychedelic education events
- **Published Articles**: Collection of Mike's published works and resources
- **Sophrodelic Retreat**: Information about legal psilocybin retreats in Jamaica
- **Contact Information**: Easy way for visitors to connect with Mike via email and Instagram
- **Downloadable Resources**: Direct access to Word versions of educational materials

## Project Structure

```
/mike-website/
├── index.html                  # Homepage with site overview
├── about.html                  # About Mike Bonertz page
├── services.html               # Services and consultation information
├── contact.html                # Contact information page
├── educational-resources.html  # Main educational resources page
├── published-articles.html     # Published articles and external resources
├── retreat.html                # Sophrodelic retreat information
├── resources/                  # Detailed educational resource pages
│   ├── ptsd.html               # PTSD and psychedelic therapy
│   ├── end-of-life-distress.html # End of life care with psychedelics
│   └── substance-use-disorder.html # Addiction treatment with psychedelics
├── events/                     # Educational events pages
│   ├── introduction-new-era.html  # Introduction to psychedelic education
│   ├── spiritual-wellness.html    # Spiritual wellness event
│   ├── wellness-of-the-well.html  # Wellness of the well event
│   ├── wellness-of-the-planet.html # Wellness of the planet event
│   └── physical-well-being.html   # Physical well-being event
├── css/
│   ├── normalize.css           # CSS reset for consistent rendering
│   ├── style.css               # Main stylesheet
│   ├── hero-fallback.css       # Hero section styling
│   ├── premium-cards.css       # Premium card component styling
│   └── svg-effects.css         # SVG animation effects
├── js/
│   └── main.js                 # JavaScript functionality
├── images/                     # Site images
│   ├── hra-logo.png            # Site logo
│   ├── hero/                   # Hero background images
│   ├── about/                  # About page images
│   ├── resources/              # Resource page images
│   └── retreat/                # Retreat page images (including Sophrodelic logo)
├── svg/                        # SVG assets
│   ├── logo.svg                # Vector logo
│   ├── favicon.svg             # Favicon
│   └── neural-background.svg   # Neural network background
└── README.md                   # This documentation file
```

## Pages

1. **Homepage (index.html)**
   - Hero section with main messaging
   - Welcome section highlighting purpose
   - Services preview with key offerings
   - Educational preview and evidence

2. **About Page (about.html)**
   - Professional background
   - Expertise and qualifications
   - Philosophy and mission

3. **Services Page (services.html)**
   - Consultation services information
   - Donation-based pricing model
   - Target audiences (medical professionals, psychonauts, patients, etc.)
   - Retreat partnership information

4. **Educational Resources (educational-resources.html)**
   - Main page with introduction to educational content
   - Separate sections for "Educational Events" and "Resources"
   - Each event and resource should link to its own dedicated page
   - Research evidence on psychedelic therapies
   - Links to in-depth resources on specific conditions
   - Scientific references and citations

5. **Published Articles (published-articles.html)**
   - Mike's published works
   - External resources and collaborations
   - Links to industry organizations

6. **Retreat Page (retreat.html)**
   - Sophrodelic Legal Magic Mushroom Retreat information
   - What is sophrology and how it works
   - Retreat details and core values

7. **Resource Pages (in resources/ directory)**
   - In-depth pages on specific conditions treated with psychedelics
   - Research evidence and personal accounts
   - Comparison with conventional treatments
   - Links to downloadable resources

8. **Event Pages (in events/ directory)**
   - Dedicated pages for each educational event
   - Detailed information about event topics
   - Registration or participation information
   - Related educational materials

## Design Elements

- **Color Palette**: Purple, teal, and pink gradients on dark backgrounds
- **Typography**: 
  - Philosopher font for headings
  - Raleway for body text
- **Visual Elements**:
  - SVG animations
  - Neural network visualizations
  - Premium card components with hover effects
  - Psychedelic gradients for emphasis

## Technologies Used

- HTML5
- CSS3 (with custom properties/variables)
- JavaScript
- SVG animations
- Font Awesome icons
- Google Fonts

## Educational Resources

The site provides comprehensive educational resources on various applications of psychedelic therapy:

- PTSD and trauma healing
- End of life distress and terminal illness
- Substance use disorders and addiction
- Physical wellness
- Spiritual and environmental connection
- Neurodegenerative diseases

## Educational Resources Structure

The educational resources section is structured with clear separation between events and resources:

1. **Separate Categories**:
   - Educational Events and Resources are separated into distinct sections with visual separation
   - Each section has its own heading and styling to differentiate them
   - The Events section appears first, followed by Resources

2. **Individual Pages**:
   - Each event and resource links to its own dedicated page
   - Event links point to files in the `events/` directory
   - Resource links point to files in the `resources/` directory

3. **Navigation Structure**:
   - Each event page has a "Back to Educational Events" link at the top left
   - Each resource page has a "Back to Resource Pages" link at the top left
   - These back links use anchor IDs (#events-section and #resources-section) to return to the specific section

4. **Content Organization**:
   - Educational resources focus on condition-specific information (PTSD, substance use disorder, etc.)
   - Educational events focus on broader psychedelic education topics (spiritual wellness, wellness of the planet, etc.)
   - Each page maintains consistent styling with the main site

## Logo Information

The website's main logo (snake wrapped around a wooden staff) is used in the following files:

- **Main Logo**: `images/hra-logo.png` - Used throughout the site as the main logo
- **Apple Touch Icon**: `images/hra-logo-apple.png` - Used for iOS devices when saved to home screen

To update the logo:
1. Replace these files with your new logo design (ideally maintaining the same dimensions)
2. Ensure the new logo has a transparent background for proper display
3. Consider creating multiple sizes if needed for different display contexts

## Updating Contact Information

To update the website's contact information, you will need to modify the following files:

### 1. Contact Page Email Address

The primary contact email address appears in `contact.html`:

- **Location**: In the contact form and contact details section
- **Files to Edit**: `contact.html`
- **What to Update**:
  - Find the section with the email address display (typically inside a `<p>` tag)
  - Update the visible email text
  - Also update the `mailto:` link in the same section
  - Example: `<a href="mailto:mike@harmreductionadvocate.com">mike@harmreductionadvocate.com</a>`

### 2. Social Media Links

Instagram is the only social media platform used on the website:

- **Location**: In the `<header>` and `<footer>` sections of all HTML files
- **Files to Edit**: All HTML files (using search and replace is recommended)
- **What to Update**:
  - Find Instagram link elements: `<a href="#" class="social-link instagram"><i class="icon-instagram"></i></a>` or `<a href="#" class="social-link instagram"><i class="fab fa-instagram"></i></a>`
  - Replace the `#` placeholder with the actual Instagram profile URL
  - Example: `<a href="https://www.instagram.com/harmreductionadvocate" class="social-link instagram"><i class="fab fa-instagram"></i></a>`
  - Update all instances across all HTML files for consistency
  - Note: The site previously had LinkedIn and TikTok links which have been removed to focus only on Instagram

### 3. Footer Contact Information

Additional contact details may appear in the footer:

- **Location**: In the `<footer>` section, typically within the `.footer-contact` div
- **Files to Edit**: All HTML files with footers
- **What to Update**:
  - Find any additional contact details in the footer section
  - Update phone numbers, addresses, or other contact information as needed
  - Update any associated links (mailto:, tel:, etc.)

### 4. Contact Form Settings

If the contact form sends to a specific email address:

- **Location**: In the contact form's action attribute or in JavaScript that handles form submission
- **Files to Edit**: `contact.html` and possibly `js/main.js`
- **What to Update**:
  - Check the form's `action` attribute or any JavaScript that handles form submission
  - Update the destination email address if necessary

## Updating SEO Information

Search Engine Optimization (SEO) elements are crucial for visibility. Here's where to update them:

### 1. Page Titles

Each page has its own title that appears in search results and browser tabs:

- **Location**: In the `<head>` section of each HTML file
- **Files to Edit**: All HTML files, individually
- **What to Update**:
  - Find the `<title>` tag in each file
  - Update it with a descriptive, keyword-rich title (60 characters max recommended)
  - Format: "Primary Keyword - Secondary Keyword | Harm Reduction Advocate"

### 2. Meta Descriptions

Meta descriptions provide search result snippets:

- **Location**: In the `<head>` section of each HTML file
- **Files to Edit**: All HTML files, individually
- **What to Update**:
  - Find the `<meta name="description" content="...">` tag
  - Update with a compelling description (150-160 characters recommended)
  - Include relevant keywords naturally in the text

### 3. Resource Pages SEO

Resource pages have additional SEO elements for specific topics:

- **Location**: In the `<head>` section of resource HTML files
- **Files to Edit**: All files in the `resources/` directory
- **What to Update**:
  - More extensive meta tags including keywords
  - Open Graph and Twitter card information for social sharing
  - Structured data in JSON-LD format

### 4. Canonical URLs

When the site goes live, update canonical URLs:

- **Location**: In the `<head>` section
- **Files to Edit**: All HTML files
- **What to Update**:
  - Find `<link rel="canonical" href="...">` tags
  - Replace placeholder URLs with actual live site URLs
  - Example: `<link rel="canonical" href="https://www.harmreductionadvocate.com/resources/ptsd.html">`

### 5. Image Alt Text

Ensure all images have descriptive alt text:

- **Location**: Throughout the HTML files
- **Files to Edit**: All HTML files with images
- **What to Update**:
  - Find `<img>` tags
  - Ensure each has a descriptive `alt` attribute
  - Example: `<img src="images/hra-logo.png" alt="Harm Reduction Advocate Logo" ...>`

## Content Management Instructions

1. **Adding New Resources**:
   - Create a new HTML file in the `resources/` directory
   - Use existing resource files as templates
   - Add a link to the new resource in `educational-resources.html` under the "Resource Pages" section

2. **Adding New Events**:
   - Create a new HTML file in the `events/` directory
   - Use existing event files as templates
   - Add a link to the new event in `educational-resources.html` under the "Educational Events" section

3. **Updating Research Evidence**:
   - Edit the "Research Evidence" section in `educational-resources.html`
   - Follow the existing format for new evidence categories
   - Include proper citations and links to sources

4. **General Content Updates**:
   - Use consistent formatting throughout the site
   - Maintain the distinction between educational events and resource pages
   - Ensure all downloadable resources (Word docs) in the `zip/REL/` directory are up to date
