# Project Portfolio

A simple personal portfolio website for Peter Aronson, designed for GitHub Pages. The site provides a central place to introduce myself, share my résumé and LinkedIn profile, and showcase my projects.

**Status:** Initial implementation. Tweaking some styling choices and verbiage. Personal content and completed projects still need to be added.

## Project Goals

* Create a professional-grade portfolio to showcase my achievements, my resume, my direct LinkedIn page, and future features. 
* Establish a subpage for future projects and its relevant screenshots, documentation, and repository links. Essentially making it into a mini blog per project.

## Technologies

* **HTML5:** Page structure and content.
* **CSS3:** Theme, layout, responsive behavior, and visual effects.
* **Vanilla JavaScript:** Content switching, navigation state, and configurable links.
* No frameworks, external fonts, package installation, or build tools are required. JavaScript is included at the bottom of `index.html`.
* And of course, my beloved ChatGPT Astra 6.0 to guide me throughout this process, teaching me about creating a website.

## File Structure

|File|Purpose|
|-|-|
|`index.html`|Page content, inline icons, navigation logic, and link configuration.|
|`style.css`|Colors, typography, layouts, animations, and responsive styles.|
|`README.md`|Project overview, setup instructions, and development notes.|

A résumé PDF and project images can be added later.

## Features (Current and Planned)

### Navigation and Layout

* Persistent left sidebar on desktop with the name and “Project Portfolio” subtitle.
* About and Project Portfolio navigation links that change the main content pane.
* LinkedIn logo and a configurable profile link.
* Clicking the name returns to the welcome screen.
* Compact navigation above the content on smaller screens.

### Welcome Screen

* Large welcome heading and introductory text.
* Links to the project portfolio and About section.

### About Section

* Placeholder introduction for background, accomplishments, and career goals.
* Résumé area with a configurable PDF link.
* Separate placeholders for achievements and certificates.

### Project Portfolio

* Two square, clickable project tiles labeled “Coming soon.”
* A separate detail view for each future project.
* Placeholder areas for screenshots, documentation, and a GitHub repository link.

### Accessibility and Usability

* Semantic page sections and labeled navigation.
* Visible keyboard focus styles and a skip-to-content link.
* Active navigation indicators and heading focus when changing views.
* Reduced-motion support.
* A JavaScript-disabled fallback that displays all content sections.

## Future Planned Features

* Easter Egg! Click a certain place to start a minigame.

### Projects

Update each tile's title and description, then update its matching detail section. Add screenshots, documentation, and a repository link as each project becomes available.

The current views use these URL fragments:

|Fragment|View|
|-|-|
|`#welcome`|Welcome screen|
|`#about`|About section|
|`#projects`|Project portfolio|
|`#project-01`|First project detail view placeholder|
|`#project-02`|Second project detail view placeholder|

Project detail views are sections within `index.html`, not separate HTML files. Fragment-based navigation is designed to support direct links and browser back/forward navigation without server routing.

### Theme

Creating a sleek, clean, professional-grade purple/white/black gradient. Sets a cool ambiance, and accentuates who I am as a person well.

## Validation

The initial implementation passed structural checks for:

* Unique HTML element IDs.
* Matching destinations for all internal links.
* Two project tiles and five content views.
* Presence of the stylesheet.
* JavaScript syntax.

Browser rendering and interactive behavior were not verified because a browser could not be installed in the development environment. Desktop and mobile appearance, keyboard navigation, back/forward navigation, and configured external links still need manual browser testing.

## Current Limitations

* The biography, résumé, achievements, certificates, and LinkedIn URL require personalization.
* Both projects are placeholders; screenshots, documentation, and repository links have not been added.
* The site is static and has no backend, database, or content management system.

## Development Log

### Initial Implementation: September 26, 2026

* Created `index.html` and `style.css`.
* Implemented the dark gradient theme and responsive two-pane layout.
* Added the welcome screen, About section, and project portfolio.
* Created two placeholder project detail views.
* Included keyboard accessibility, reduced-motion styles, and a no-JavaScript fallback.
* Completed structural and JavaScript syntax checks.
* Packaged the initial website files and setup guide in a downloadable ZIP.
* Populating About section and LinkedIn hyperlink.

