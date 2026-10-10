# Thmisha Rasanathan — Personal Portfolio

A responsive four-page portfolio created for **INFR3120** at Ontario Tech University. The website introduces my background in Networking and IT Security and highlights my programming, networking, event coordination, and digital marketing experience.

## Website Pages

- **Home (`index.html`)** — Introduction, areas of interest, and links to other pages.
- **About (`about.html`)** — Education, technical skills, work experience, profile photo, and introduction video.
- **Projects (`projects.html`)** — Four projects from coursework and professional experience.
- **Contact (`contact.html`)** — Contact information and an HTML form with built-in browser validation. The form uses the visitor's email application rather than a backend service.

## Featured Projects

### 1. Student Grade Calculator
A beginner-friendly Python program that accepts three grades, calculates their arithmetic average, and uses `if`, `elif`, and `else` statements to assign a letter grade. It demonstrates user input, variables, arithmetic, and conditional logic.

### 2. ThreatIQ — PCI DSS Conference Coordination
Supported conference-related marketing and coordination, including promotional merchandise, social media posts, one-pagers, booth-location information, and LinkedIn content.

**Image:** `images/threatiq-conference.jpg` (landscape)

### 3. Advanced Networking — Network Design
An academic networking project focused on network design and applying networking concepts learned through coursework.

### 4. Rossland Landing Dental Care — Invisalign Event
Created promotional materials and supported event communications, including flyers, social media posts, emails and text messages, and promotional voucher coordination. Content was prepared for platforms such as Instagram and TikTok.

**Image:** `images/invisalign-event.jpg` (landscape)

## Technologies and Techniques

- **HTML5:** Semantic elements, navigation, images, native video, and forms.
- **CSS3:** External stylesheets, selectors, typography, colors, gradients, floats, responsive layouts, and hover transitions.
- **Python:** Basic programming concepts demonstrated in the Student Grade Calculator.
- **Responsive design:** Separate stylesheets for laptop, tablet, and mobile layouts; no Flexbox or CSS Grid.

## File Structure

```text
portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   ├── styles-laptop.css
│   ├── styles-tablet.css
│   └── styles-mobile.css
├── images/
│   ├── profile-photo.jpg
│   ├── video-poster.jpg
│   ├── introduction.mp4
│   ├── threatiq-conference.jpg
│   └── invisalign-event.jpg
└── README.md
```

The structure above shows the expected asset filenames; confirm that the corresponding files have been added before publishing. The Python calculator may be stored separately if it is not part of the website repository.

## Responsive Layout

The website uses CSS media queries to adapt to different screens:

- **Laptop/desktop:** Default styles in `css/styles-laptop.css`.
- **Tablet:** 601–1023 px, using `css/styles-tablet.css`.
- **Mobile:** Up to 600 px, using `css/styles-mobile.css`.

The conference and Invisalign photographs are landscape images and are displayed within responsive project-image containers.

## Color Palette

| Color | Hex Code |
| --- | --- |
| Ocean Blue | `#24558A` |
| Espresso Brown | `#3B2F2A` |
| Midnight Navy | `#17243A` |
| Mocha Brown | `#725747` |
| Warm Beige | `#D8CBBE` |
| Soft Ivory | `#F2EEE8` |

The website also uses CSS linear gradients for visual depth and contrast.

## How to View

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a browser (or use a local preview extension).
4. Navigate between Home, About, Projects, and Contact.

No website build step or framework installation is required.

## Before Submission

- Check that the profile photo, introduction video, poster image, and two landscape project photos load correctly.
- Confirm the Python project description matches the saved code and that project-specific materials accurately reflect completed work.
- Test navigation, video controls, responsive layouts, and the contact form.
- Validate HTML, CSS, accessibility, and links; do not report validation as passed until tested.
- Review the course's academic integrity and AI-use requirements, and document external assistance appropriately.
- Publish to GitHub Pages if required and verify the live site before submission.


## Lecture References and Code Implementation

This portfolio applies HTML5 and CSS3 concepts taught in
INFR3120. Comments are included in the source code to
identify the relevant lectures.

### Week 1 — Basics of HTML and CSS

Concepts covered:
- Basic HTML5 document structure
- Head and body elements
- Headings, paragraphs, lists, and links
- External CSS stylesheets
- CSS selectors, classes, and IDs
- Floated elements for page layouts

Where used:
- All four HTML files use the HTML5 document structure.
- All pages link to external CSS files.
- styles-laptop.css defines the website's typography,
  colors, spacing, and floated elements.
- The navigation menu and home page cards use CSS styling.

Example:
    .tile {
        float: left;
        width: 31.33%;
    }

The float property positions the three cards beside
each other without using Flexbox.

### Week 2 — Embedding Native Video

Concepts covered:
- HTML5 video element
- Video source and file formats
- Video controls
- Poster image

Where used:
- about.html

Example:
    <video controls poster="images/video-poster.jpg">
        <source src="images/introduction.mp4"
                type="video/mp4">
    </video>

The video element displays my introductory video.
The controls attribute provides playback options,
and the poster displays an image before playback.

### Week 2-b — HTML5 Semantic Markup

Concepts covered:
- Header and navigation elements
- Articles and sections
- Aside elements
- Footer elements

Where used:
- All four HTML files use header, nav, main, and footer.
- index.html uses articles for the three introductory cards.
- projects.html uses articles for each project.
- about.html uses an aside for the profile photograph.
- contact.html uses an aside for contact information.

These elements organize page content according to
its purpose rather than relying only on div elements.

### Week 3 — Responsive Design

Concepts covered:
- Fluid layouts using percentages
- Media queries
- Different layouts for desktop, tablet, and mobile
- Responsive navigation and content

Where used:
- css/styles-laptop.css
- css/styles-tablet.css
- css/styles-mobile.css

Viewport sizes:
- Mobile: 600px and below
- Tablet: 601px to 1023px
- Laptop/Desktop: 1024px and above

The laptop stylesheet contains the shared styling
and default layout. The tablet and mobile stylesheets
override selected properties for smaller screens.

I selected these breakpoints so the website can display
three-column content on larger screens and reduce
the number of columns on smaller devices.

The website uses percentage widths and floats rather
than Flexbox or CSS Grid.

### Week 4 — Interactive CSS Transforms

Concepts covered:
- CSS transforms
- Translation and scaling
- Hover-based interaction

Where used:
- css/styles-laptop.css

Example:
    .button:hover {
        transform: translateY(-2px);
        background: var(--mocha);
    }

The translateY property moves a button slightly upward
when hovered over, providing visual feedback.

### Gradients and Color Scheme

The website uses CSS linear gradients in
css/styles-laptop.css.

Angled gradient:
    .hero {
        background: linear-gradient(
            115deg,
            var(--navy) 0%,
            var(--blue) 65%,
            var(--mocha) 100%
        );
    }

Horizontal gradient:
    .soft-panel {
        background: linear-gradient(
            to right,
            var(--beige),
            var(--ivory)
        );
    }

The angled gradient is used on the home page's
introductory banner, while the horizontal gradient
is used in the supporting information panel.

The six-color palette combines blue and brown tones
with neutral backgrounds for a professional appearance.

Palette:
- Ocean Blue: #24558A
- Espresso Brown: #3B2F2A
- Midnight Navy: #17243A
- Mocha Brown: #725747
- Warm Beige: #D8CBBE
- Soft Ivory: #F2EEE8

## References and Attribution

**Course Materials**

- INFR3120 Week 1 — Basics of HTML and CSS
- INFR3120 Week 2 — Embedding Native Video
- INFR3120 Week 2-b — Structuring Pages with HTML5 Semantic Markup
- INFR3120 Week 3 — Responsive Design
- INFR3120 Week 4 — Interactive Transforms with CSS

The course lectures provided examples and explanations of HTML5 page structure, semantic elements, native video, external stylesheets, floated layouts, responsive design, and CSS transforms.

**Personal Content**

Project descriptions and professional experience are based on my academic work and employment at ThreatIQ and Rossland Landing Dental Care. Photographs and other project materials are included as supporting examples of my work.

## Author

**Thmisha Rasanathan**  
Bachelor of Information Technology — Networking and IT Security  
Ontario Tech University
