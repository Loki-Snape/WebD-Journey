# WebD-Journey

WebD-Journey is a browser-based collection of front-end web development exercises completed while working through **The Complete Full-Stack Web Development Bootcamp** by Angela Yu on Udemy. The repository records the progression from basic HTML documents to styled layouts, responsive page composition, Bootstrap components, and small JavaScript games.

The projects are intentionally kept as standalone files. There is no build system, package manager, backend, database, or application framework: each page can be opened directly in a browser and inspected as an individual lesson.

## Project Hub

Open [`index.html`](index.html) to use the themed project archive. It presents the projects as animated links and provides the main navigation entry point for the repository.

## Projects

### 1. Top 3 Movies

File: [`1. Top 3 Movies.html`](1.%20Top%203%20Movies.html)

A semantic HTML practice page presenting a personal top-three movie list. It uses heading hierarchy, horizontal rules, paragraphs, and line breaks to introduce *Munna Bhai*, *Conjuring 2*, and *The Mummy*.

### 2. Happy Birthday

File: [`2. Happy Birthday To Me.html`](2.%20Happy%20Birthday%20To%20Me.html)

An invitation-style page built with HTML content elements. It includes a birthday heading, date, remote cake image, a list of suggested gifts, and an external Google Maps link.

### 3. HTML Resume

File: [`3. HTML Only Resume.html`](3.%20HTML%20Only%20Resume.html)

A resume created without a stylesheet. It demonstrates document structure through headings, paragraphs, lists, an image, and a footer, with sections for summary, education, work experience, and skills.

### 4. Colour Translator

File: [`4. Colour Translater.html`](4.%20Colour%20Translater.html)

An introductory color-learning page that pairs English color names with Hindi translations and transliterations. Inline CSS supplies colored labels and matching color swatches for ten colors.

### 5. Stark Motivation

File: [`5. Stark Motivation.html`](5.%20Stark%20Motivation.html)

A simple poster exercise featuring a locally stored image and a Tony Stark quotation. Inline CSS establishes a black background, white border, image sizing, and typography.

### 6. Laos Flag

File: [`6. Laos.html`](6.%20Laos.html)

A CSS drawing of the Laos flag made from nested `div` elements. It demonstrates positioning, fixed dimensions, layered blocks, color fills, and a circular shape created with `border-radius`.

### 7. Avengers Agency

File: [`7. Avengers Agency.html`](7.%20Avengers%20Agency.html) with [`style7.css`](style7.css)

A creative agency landing page themed around the Avengers. The layout contains a logo, agency headline, Beauty and Construction service cards, responsive image behavior, and a footer. It demonstrates external CSS, floating desktop columns, a mobile breakpoint, Google Fonts, and remote image assets.

### 8. Price Table

File: [`8. Price Table.html`](8.%20Price%20Table.html)

A three-tier pricing component for Basic, Standard, and Premium plans. It uses Flexbox for alignment, CSS sizing and spacing, custom typography from Google Fonts, buttons, feature lists, and a media query that stacks the plans on narrower screens.

### 9. Mondrian Painting

File: [`9. Mondrian Painting.html`](9.%20Mondrian%20Painting.html)

A recreation of a Piet Mondrian-inspired composition using CSS Grid. Grid tracks, spans, gaps, and colored blocks create the red, blue, yellow, black, and off-white geometric layout.

### 10. TinDog

File: [`10. TinDog.html`](10.%20TinDog.html) with [`solution10.css`](solution10.css)

A multi-section, Bootstrap-based landing page for a fictional dog-matching service. It includes a hero section, download buttons, feature highlights, testimonial content, press logos, pricing cards, and a footer. Bootstrap 5 provides the responsive grid and component classes, while the local stylesheet adds the animated gradient background and profile styling.

### Capstone Resume

File: [`HTML CSS Resume Capstone 1.html`](HTML%20CSS%20Resume%20Capstone%201.html) with [`styleCP.css`](styleCP.css)

A styled personal portfolio and resume page. It includes sticky navigation, a hero profile section, resume details, project cards, an about section, external project links, contact details, and a contact form layout. The page uses CSS Flexbox/Grid patterns, responsive project cards, remote hero imagery, and a local profile image.

### 11. Dice Toss

File: [`11. Dice Toss.html`](11.%20Dice%20Toss.html), [`index11.js`](index11.js), and [`styles11.css`](styles11.css)

An interactive two-player dice game. Clicking **Roll Dice** generates two random values from 1 to 6, swaps the dice images in [`images11/`](images11/), and updates the heading to show Player 1, Player 2, or a draw. The visual design uses local CSS and the Indie Flower/Lobster Google Fonts.

### 12. Simon Says

File: [`12. Simon Says.html`](12.%20Simon%20Says.html), [`game.js`](game.js), and [`styles12.css`](styles12.css)

An interactive Simon memory game. A keypress starts a sequence; the player repeats the colored button pattern, with the sequence growing after each successful round. The game handles level updates, button animation, sound playback, incorrect-answer feedback, and restarting after game over. It uses jQuery for event handling, animation, and DOM updates, plus local sound files in [`sounds/`](sounds/).

## Technology Stack

### Core technologies

- **HTML5:** Page structure, semantic content, links, images, lists, forms, and sectioning.
- **CSS3:** Colors, typography, spacing, responsive media queries, Flexbox, CSS Grid, transitions, animations, positioning, and shape construction.
- **JavaScript:** Random number generation, DOM selection and mutation, event listeners, game state, timers, audio creation, and interaction logic.
- **jQuery 3.3.1:** Used by the Simon Says game for events, animations, selectors, and text updates.
- **Bootstrap 5.3.0-alpha3:** Used by TinDog for its responsive containers, grid, buttons, cards, and utility classes.

### External resources

- **Google Fonts:** Creepster, Special Elite, Poppins, Sono, Indie Flower, Lobster, and Press Start 2P.
- **Bootstrap CDN:** Loads Bootstrap CSS for TinDog.
- **Google Hosted Libraries CDN:** Loads jQuery for Simon Says.
- **Remote images:** Several exercises reference images hosted on GitHub, Unsplash, ModDB, Bing, or other external services.
- **Local assets:** The repository includes the resume/profile image, Stark poster image, six dice images, and five Simon Says sound effects.

## Running the Project

No installation or build step is required.

1. Clone or download the repository.
2. Open the project folder in a browser-friendly editor such as VS Code.
3. Open [`index.html`](index.html), or open any project HTML file directly.
4. For the most reliable local experience, serve the folder with a static HTTP server. For example, with Python installed:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000/`.

The pages depend on internet access for some fonts, CDN libraries, and remote images. Dice Toss and Simon Says require their local asset directories to remain beside the referenced files.

## Repository Structure

```text
WebD-Journey/
├── index.html                         # Project archive and navigation hub
├── 1. Top 3 Movies.html               # HTML movie ranking
├── 2. Happy Birthday To Me.html       # Birthday invitation
├── 3. HTML Only Resume.html           # HTML-only resume
├── 4. Colour Translater.html          # English/Hindi color lesson
├── 5. Stark Motivation.html           # Image and quote poster
├── 6. Laos.html                       # CSS flag composition
├── 7. Avengers Agency.html            # Agency landing page
├── 8. Price Table.html                # Flexbox pricing layout
├── 9. Mondrian Painting.html          # CSS Grid artwork
├── 10. TinDog.html                    # Bootstrap landing page
├── HTML CSS Resume Capstone 1.html    # Portfolio/resume capstone
├── 11. Dice Toss.html                 # Dice game interface
├── 12. Simon Says.html                # Simon game interface
├── style7.css                         # Avengers Agency styles
├── solution10.css                     # TinDog custom styles
├── styleCP.css                        # Capstone styles
├── styles11.css                       # Dice Toss styles
├── styles12.css                       # Simon Says styles
├── index11.js                         # Dice Toss logic
├── game.js                            # Simon Says logic
├── images11/                          # Dice images and an auxiliary HTML file
├── sounds/                             # Simon Says sound effects
├── IMG-20240417-WA0038.jpg            # Local profile image
└── OIP.webp                           # Local Stark poster image
```

## Learning Progression

The archive follows a practical progression:

1. Build pages with headings, paragraphs, lists, links, and images.
2. Add inline CSS and learn selectors, colors, sizing, and positioning.
3. Move styles into external stylesheets and introduce responsive layouts.
4. Practice Flexbox and CSS Grid with pricing and artwork compositions.
5. Assemble a larger landing page with Bootstrap utilities and components.
6. Build a personal portfolio/resume as a capstone page.
7. Add JavaScript behavior, randomization, event handling, state, animation, and audio through Dice Toss and Simon Says.

## Current Limitations

- Several pages depend on third-party URLs, so images, fonts, maps, and libraries can fail when offline or when a remote URL changes.
- TinDog references an `images/` directory for its phone, dog, and publication images; the current repository listing contains `images11/` for Dice Toss but no root-level `images/` directory. Those TinDog images may therefore need to be restored or updated before the page is fully self-contained.
- The repository has no automated tests, linting configuration, or build pipeline. Validation is currently performed by opening the pages and exercising the interactive games in a browser.
- Some pages are learning exercises rather than production-ready interfaces and may contain fixed dimensions, placeholder links, or intentionally simple markup.

## Credits

The exercises are part of Angela Yu's **The Complete Full-Stack Web Development Bootcamp** on Udemy. The personal content, styling changes, and project archive are maintained by Mridul Jha.