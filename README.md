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

## References and Attribution

- INFR3120 lecture materials: Weeks 1, 2, 2-b, 3, and 4.
- Portfolio content based on personal coursework and professional experience.
- README wording and earlier portfolio template development assisted by OpenAI ChatGPT (October 2026). Review and revise submitted code in line with the course's attribution and external-code rules.

## Author

**Thmisha Rasanathan**  
Bachelor of Information Technology — Networking and IT Security  
Ontario Tech University
